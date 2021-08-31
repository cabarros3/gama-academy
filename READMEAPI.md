<a name="ancora"></a>
# API's - GRUPO 6

Usamos duas API's para compor o projeto

* [API Vtex IO](#ancora1)
* [API AWS](#ancora2)

<a id="ancora1"></a>
## Api de Resposta VtexIO

Um aplicativo de referência implementando um serviço VTEX IO com manipuladores de rotas HTTP.

![](https://github.com/cabarros3/gama-academy/blob/main/77381360-72489680-6d5c-11ea-9da8-f4f03b6c5f4c.jpg)

 - Comece e acompanhe os comentários e importações :) node/index.ts

### efinindo rotas em service.json

```jsx
{
  "memory": 256,
  "ttl": 10,
  "timeout": 2,
  "minReplicas": 2,
  "maxReplicas": 4,
  "workers": 1,
  "routes": {
    "hook": {
      "path": "/_v/status/",
      "public": true
    }
  }
}
```

O arquivo que fica na raiz da pasta contém informações sobre este serviço, como o tempo limite máximo e o número de réplicas, o que pode ser descontinuado no futuro, mas também define suas rotas.service.jsonnode

### **Controle de acesso**

Você também pode fornecer uma opção para cada rota. Se , esse recurso será acessível para todos na internet. Se, credenciais VTEX também serão solicitadas.`publictruefalse`

Outra maneira de controlar o acesso a rotas específicas é o uso de **ReBACs (acesso baseado em recursos),**que suporta configuração mais robusta. Você pode ler mais [neste documento](https://docs.google.com/document/d/1ZxNHMFIXfXz3BgTN9xyrHL3V5dYz14wivYgQjRBZ6J8/edit#heading=h.z7pad3qd2qw7) (somente VTEX).

### **Sequência de consulta**

Para , você **não precisa declarar nada**, como qualquer consulta fornecida à URL já estará disponível para você usar no código como , já analisado como um objeto, ou , tirado diretamente da URL como uma sequência.`?accepting=query-stringctx.queryctx.queryString`

### **Rota Params**

Route Params estará disponível para você usar no código como , já analisado como um objeto. Para um caminho como , se você receber a solicitação , retornará `ctx.vtex.params/_v/status/:code/_v/status/200ctx.vtex.params{ code: '200' }`

### Métodos HTTP

```jsx
{ clients: { implementation: Clients, options: { default: { retries: 2, timeout: 10000, }, }, },
   routes: { hook: method({ POST: [oms], GET: oms }), }, })
```

### **Lendo um corpo JSON**

Ao escrever manipuladores POST ou PUT, por exemplo, muitas vezes você precisa ter acesso ao **órgão de solicitação** que vem como um formato JSON, que não é fornecido diretamente pela função manipuladora.

Para isso, você tem que usar o pacote [co-body](https://www.npmjs.com/package/co-body) que analisará a solicitação em um objeto JSON legível, usado como abaixo:

```
import { json } from 'co-body'
export async function method(ctx: Context, next: () => Promise<any>) {
    const body = await json(ctx.req)
```

### Capturando Informações MasterClient

```jsx
const { OrderId } = await json(ctx.req)

  const {clientProfileData: { email: userId }} = await ctx.clients.oms.order(OrderId)
  const data:any = await ctx.clients.masterdata.searchDocuments({
    dataEntity:'CL',
    where:`email=${userId}`,
    fields:['email','firstName','lastName','phone'],
    pagination:{
      pageSize:1,
      page:1
    }
  })

```

### Métodos Usados @Vtex/api

```jsx
import { Service, ServiceContext, ParamsContext, RecorderState, method, } from '@vtex/api'
```

### Métodos Usados @Vtex/Clients
```
import {OMS} from '@vtex/clients'

```

<a id="ancora2"></a>
## API AWS



## Sobre o grupo 6 ✨

Você pode conferir a nossa documentação completa sobre a estrutura da loja e front-end [aqui](https://github.com/LucasVihuchi/desafio-final-corebiz-hiring-coders#readme).

🔝 [Topo](#ancora)
