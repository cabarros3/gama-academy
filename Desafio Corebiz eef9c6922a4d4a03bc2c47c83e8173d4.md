# **Desafio Final - Grupo 6 - CoreBiz**

Este é o desafio final do Grupo 6 do Hiring Coders #2. O desafio consiste em desenvolver uma loja Vtex com consumo de API's com o front-end baseado na temática da parceira e patrocinadora corebiz.

O contexto completo do desafio está [aqui](https://drive.google.com/file/d/1cjX4W7MmtVMAX0HBbl17eaJcD1N-B223/view).

## **Preview**

![https://github.com/cabarros3/gama-academy/raw/main/header.png](https://github.com/cabarros3/gama-academy/raw/main/header.png)

## **Estruturação da loja**

A loja foi pensada para ser composta por 5 páginas:

- `Home`
- `Sobre`
- `Produtos`
- `Contato`
- `Blog`

As página "Home" e "Sobre" seguem os mesmos padrões da corebiz com as informações e caracteríticas principais da marca. As páginas "produtos" e "contato" são as que, conforme solicitado no desafio, entregam o consumo da API vtex e AWS, nelas podemos verirficar os produtos, fazer a compra desses produtos e observar a lista de clientes. O link do header denominado "blog" redireciona para um link externo mantido pela corebiz.

## **Componentes**

Os componentes da loja elaborados para o desafio foram:

- [Api Vtex IO](https://github.com/cabarros3/gama-academy/blob/main)
- [Api AWS](https://github.com/cabarros3/gama-academy/blob/main)
- [Header](https://github.com/cabarros3/gama-academy/blob/main)
- [Footer](https://github.com/cabarros3/gama-academy/blob/main)
- [Home](https://github.com/cabarros3/gama-academy/blob/main)
- [Sobre](https://github.com/cabarros3/gama-academy/blob/main)
- [Produtos](https://github.com/cabarros3/gama-academy/blob/main)
- [Contato](https://github.com/cabarros3/gama-academy/blob/main)

Abaixo você pode conferir como realizamos a construção de cada um destes compenentes.

### **API VTEX IO**

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque elementum nisi vel metus ultricies congue. Praesent tempus dignissim placerat. Morbi viverra, velit vitae imperdiet facilisis, tellus eros sodales felis, id aliquet eros ipsum eu nisl. Curabitur ac ante vitae lectus cursus porttitor id vel enim. Nullam placerat ac augue ut auctor. Fusce mattis sit amet nisi at ultricies. Nunc iaculis finibus lectus, sit amet mollis lectus suscipit in. Integer volutpat tellus at congue congue.

### **API AWS**

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque elementum nisi vel metus ultricies congue. Praesent tempus dignissim placerat. Morbi viverra, velit vitae imperdiet facilisis, tellus eros sodales felis, id aliquet eros ipsum eu nisl. Curabitur ac ante vitae lectus cursus porttitor id vel enim. Nullam placerat ac augue ut auctor. Fusce mattis sit amet nisi at ultricies. Nunc iaculis finibus lectus, sit amet mollis lectus suscipit in. Integer volutpat tellus at congue congue.

### **Header**

![https://github.com/cabarros3/gama-academy/raw/main/headerv.gif](https://github.com/cabarros3/gama-academy/raw/main/headerv.gif)

O Header responsivo foi desenvolvido através dos blocos "header-layout.desktop" e "header-layout.mobile". O layout desktop conta com o logo, um menu de navegação e um minicart, organizados em um "flex-layout". Já o layout mobile, mantém o logo e minicart, e a navegação é condensada em um menu gaveta.

### **Footer**

![https://github.com/cabarros3/gama-academy/raw/main/footer.png](https://github.com/cabarros3/gama-academy/raw/main/footer.png)

O footer responsivo com os blocos "footer-layout.desktop" e "footer-layout.mobile" também utiliza o flex layout para organizar o logo, os endereços da corebiz em cada país, as redes sociais, o copyright e um botão que leva ao topo da página.

### **Home**

[https://camo.githubusercontent.com/7b4d6a54cd70e67af0747607397de94a47b7b7076a74fc32a1065fcf4f34321b/68747470733a2f2f696d616765732e756e73706c6173682e636f6d2f70686f746f2d313532323235323233343530332d6533353635333263616664353f697869643d4d6e77784d6a4133664442384d48787761473930627931775957646c664878386647567566444238664878382669786c69623d72622d312e322e31266175746f3d666f726d6174266669743d63726f7026773d36323526713d3830](https://camo.githubusercontent.com/7b4d6a54cd70e67af0747607397de94a47b7b7076a74fc32a1065fcf4f34321b/68747470733a2f2f696d616765732e756e73706c6173682e636f6d2f70686f746f2d313532323235323233343530332d6533353635333263616664353f697869643d4d6e77784d6a4133664442384d48787761473930627931775957646c664878386647567566444238664878382669786c69623d72622d312e322e31266175746f3d666f726d6174266669743d63726f7026773d36323526713d3830)

O store.home, baseado na aparência do site original, tem como objetivo trazer de mensagem inicial a presença global da corebiz. Desta forma, há uma imagem de fundo com o mapa de presença, mais um "stack-layout" estilizado com blocos "rich-text" para o título, subtítulo e estatísticas.

### **Sobre**

![https://github.com/cabarros3/gama-academy/raw/main/sobre.png](https://github.com/cabarros3/gama-academy/raw/main/sobre.png)

A página about-us traz a missão e valores que são a base da corebiz. Foi utilizado "flex-layout" para compor o design das imagens com os textos e foi inserido um "tab-layout" estilizado para descrever o framework de transformação digital da empresa, separando os seguimentos canal de vendas, taxa de conversão, marketing de performance e projetos ominichannel.

### **Produtos**

![https://github.com/cabarros3/gama-academy/raw/main/produtos.png](https://github.com/cabarros3/gama-academy/raw/main/produtos.png)

Após cadastrar e ativar as marcas, categorias e produtos através do Admin, a página de produtos foi criada através de um bloco customizado "store.custom#products" com um "search-result-layout", filtrando apenas os óculos e estabelecendo um máximo de 8 produtos por página. Possui a opção de visualização em grid ou lista e customização dos filtros de busca.

### **Contato**

![https://github.com/cabarros3/gama-academy/raw/main/contactv.gif](https://github.com/cabarros3/gama-academy/raw/main/contactv.gif)

A área de contato do site abre um modal para cadastro de leads de clientes que se conecta a API AWS. Foi utilizado um Componente VTEX com um formulário de cadastro contendo os campos nome, email, telefone, e um registro automático de prospect para possivelmente ser transformado em cliente caso o usuário finalize alguma compra na loja. Mais detalhes [aqui](https://github.com/guilhermanosilva/form-lead-component-vtex).