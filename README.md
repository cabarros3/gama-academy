# Desafio Final - Grupo 6 - CoreBiz

Este é o desafio final do Grupo 6 do Hiring Coders #2. O desafio consistem em desenvolver uma loja Vtex com consumo de API's com o front-end baseado na temática da parceira e patrocinadora corebiz.

O contexto completo do desafio está [aqui](https://drive.google.com/file/d/1cjX4W7MmtVMAX0HBbl17eaJcD1N-B223/view).

## Preview

![](https://github.com/cabarros3/gama-academy/blob/main/header.png)

## Estruturação da loja

A loja foi pensada para ser composta por 5 páginas:

	* Home
	* Sobre
	* Produtos
	* Contato
	* Blog

As página "Home" e "Sobre" seguem os mesmos padrões da corebiz com as informações e caracteríticas principais da marca. As páginas "produtos" e "contato" são as que, conforme solicitado no desafio, entregam o consumo da API vtex e AWS, nelas podemos verirficar os produtos, fazer a compra desses produtos e observar a lista de clientes. O link do header denominado "blog" redireciona para um link externo mantido pela corebiz.

### Dependências
- [Store](https://github.com/vtex-apps/store/blob/master/README.md)
- [Store GraphQL](https://github.com/vtex-apps/store-graphql/blob/master/docs/README.md)
- [Add to Cart Button](https://vtex.io/docs/components/all/vtex.add-to-cart-button@0.26.12/)
- [Breadcrumb](https://vtex.io/docs/components/all/vtex.breadcrumb/)
- [Carousel](https://vtex.io/docs/releases/2019-week-43-44/carousel)
- [Category Menu](https://vtex.io/docs/components/all/vtex.category-menu@2.16.0/)
- [Checkout Summary](https://vtex.io/docs/app/vtex.checkout-summary@0.18.0/)
- [Condition Layout](https://developers.vtex.com/vtex-developer-docs/docs/vtex-condition-layout)
- [CSS Handles](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-using-css-handles-for-store-customization)
- [Disclosure Layout](https://developers.vtex.com/vtex-developer-docs/docs/vtex-disclosure-layout)
- [Flex Layout](https://vtex.io/docs/components/all/vtex.flex-layout/)
- [Footer](https://vtex.io/docs/components/all/vtex.store-footer/)
- [Header](https://vtex.io/docs/components/all/vtex.store-header@2.26.0/)
- [Icons](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-icons#icons)
- [Image](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-components-image)
- [Link](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-link)
- [Locale Switcher](https://developers.vtex.com/vtex-developer-docs/docs/vtex-locale-switcher)
- [Login](https://vtex.io/docs/app/vtex.login@2.45.5/)
- [Logo](https://vtex.io/docs/components/all/vtex.store-components@3.151.2/logo/)
- [Minicart](https://vtex.io/docs/components/all/vtex.minicart/)
- [Modal layout](https://developers.vtex.com/vtex-developer-docs/docs/vtex-modal-layout)
- [Menu](https://developers.vtex.com/vtex-developer-docs/docs/vtex-menu)
- [My Account](https://developers.vtex.com/vtex-developer-docs/docs/my-account)
- [Order Placed](https://vtex.io/docs/components/content-blocks/vtex.order-placed/readme)
- [Product Bookmark Interface](https://github.com/vtex-apps/product-bookmark-interfaces)
- [Product Customizer](https://vtex.io/docs/components/all/vtex.product-customizer@2.11.0/)
- [Product Details](https://vtex.io/docs/components/all/vtex.product-details@1.20.0/)
- [Product Gifs](https://developers.vtex.com/vtex-developer-docs/docs/vtex-product-gifts)
- [Product Highlights](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-components-producthighlights)
- [Product Identifier](https://vtex.io/docs/components/all/vtex.product-identifier/)
- [Product Kit](https://developers.vtex.com/vtex-developer-docs/docs/vtex-product-kit)
- [Product Price](https://developers.vtex.com/vtex-developer-docs/docs/vtex-product-price)
- [Product Quantity](https://developers.vtex.com/vtex-developer-docs/docs/vtex-product-quantity)
- [Product Review Interfaces](https://vtex.io/docs/components/all/vtex.product-review-interfaces@1.0.2/)
- [Product Specification](https://vtex.io/docs/app/vtex.product-specification-badges@0.4.0/)
- [Product Specifications](https://developers.vtex.com/vtex-developer-docs/docs/vtex_store-components_productspecifications)
- [Product Summary](https://vtex.io/docs/app/vtex.product-summary)
- [Product Summary List](https://vtex.io/docs/components/all/vtex.product-summary/product-summary-list)
- [Responsive Layout](https://developers.vtex.com/vtex-developer-docs/docs/vtex-responsive-layout)
- [Review and Ratings](https://developers.vtex.com/vtex-developer-docs/docs/vtex-reviews-and-ratings)
- [Rich Text](https://developers.vtex.com/vtex-developer-docs/docs/vtex-rich-text)
- [Shelf](https://vtex.io/docs/components/all/vtex.shelf/)
- [Slider Layout](https://vtex.io/docs/app/vtex.slider-layout@0.19.2)
- [Slider](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-components-slider)
- [Styleguide]([https://styleguide.vtex.com/#/Styles](https://styleguide.vtex.com/#/Styles))
- [Stack Layout](https://vtex.io/docs/components/all/vtex.stack-layout@0.1.0/)
- [Sticky Layout](https://vtex.io/docs/components/all/vtex.sticky-layout/)
- [Store Drawer](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-drawer)
- [Search Result](https://vtex.io/docs/components/all/vtex.search-result@3.108.0)
- [Store Components](https://vtex.io/docs/components/all/vtex.store-components@3.151.2/)
- [Store Form](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-form)
- [Tab Layout](https://developers.vtex.com/vtex-developer-docs/docs/vtex-tab-layout)
- [Telemarketing](https://vtex.io/docs/components/all/vtex.telemarketing@2.10.2/)
- [Video](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-video)

### Aplicativos Vtex usados
- [Checkout Custom](https://apps.vtex.com/vtex-checkout-ui-custom/p)
- [Customer Credit](https://apps.vtex.com/vtex-customer-credit/p)

## Componentes

Os componentes da loja elaborados para o desafio foram:

* [Api Vtex IO]()
* [Api AWS]()
* [Header]()
* [Footer]()
* [Home]()
* [Sobre]()
* [Produtos]()
* [Contato]()

Abaixo você pode conferir como realizamos a construção de cada um destes compenentes.

### API VTEX IO

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque elementum nisi vel metus ultricies congue. Praesent tempus dignissim placerat. Morbi viverra, velit vitae imperdiet facilisis, tellus eros sodales felis, id aliquet eros ipsum eu nisl. Curabitur ac ante vitae lectus cursus porttitor id vel enim. Nullam placerat ac augue ut auctor. Fusce mattis sit amet nisi at ultricies. Nunc iaculis finibus lectus, sit amet mollis lectus suscipit in. Integer volutpat tellus at congue congue.

### API AWS

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque elementum nisi vel metus ultricies congue. Praesent tempus dignissim placerat. Morbi viverra, velit vitae imperdiet facilisis, tellus eros sodales felis, id aliquet eros ipsum eu nisl. Curabitur ac ante vitae lectus cursus porttitor id vel enim. Nullam placerat ac augue ut auctor. Fusce mattis sit amet nisi at ultricies. Nunc iaculis finibus lectus, sit amet mollis lectus suscipit in. Integer volutpat tellus at congue congue.

### Header

![](https://github.com/cabarros3/gama-academy/blob/main/headerv.gif)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque elementum nisi vel metus ultricies congue. Praesent tempus dignissim placerat. Morbi viverra, velit vitae imperdiet facilisis, tellus eros sodales felis, id aliquet eros ipsum eu nisl. Curabitur ac ante vitae lectus cursus porttitor id vel enim. Nullam placerat ac augue ut auctor. Fusce mattis sit amet nisi at ultricies. Nunc iaculis finibus lectus, sit amet mollis lectus suscipit in. Integer volutpat tellus at congue congue.

### Footer

![](https://github.com/cabarros3/gama-academy/blob/main/footer.png)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque elementum nisi vel metus ultricies congue. Praesent tempus dignissim placerat. Morbi viverra, velit vitae imperdiet facilisis, tellus eros sodales felis, id aliquet eros ipsum eu nisl. Curabitur ac ante vitae lectus cursus porttitor id vel enim. Nullam placerat ac augue ut auctor. Fusce mattis sit amet nisi at ultricies. Nunc iaculis finibus lectus, sit amet mollis lectus suscipit in. Integer volutpat tellus at congue congue.

### Home

![Imagem do elemento](https://images.unsplash.com/photo-1522252234503-e356532cafd5?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=625&q=80)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque elementum nisi vel metus ultricies congue. Praesent tempus dignissim placerat. Morbi viverra, velit vitae imperdiet facilisis, tellus eros sodales felis, id aliquet eros ipsum eu nisl. Curabitur ac ante vitae lectus cursus porttitor id vel enim. Nullam placerat ac augue ut auctor. Fusce mattis sit amet nisi at ultricies. Nunc iaculis finibus lectus, sit amet mollis lectus suscipit in. Integer volutpat tellus at congue congue.

### Sobre

![](https://github.com/cabarros3/gama-academy/blob/main/sobre.png)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque elementum nisi vel metus ultricies congue. Praesent tempus dignissim placerat. Morbi viverra, velit vitae imperdiet facilisis, tellus eros sodales felis, id aliquet eros ipsum eu nisl. Curabitur ac ante vitae lectus cursus porttitor id vel enim. Nullam placerat ac augue ut auctor. Fusce mattis sit amet nisi at ultricies. Nunc iaculis finibus lectus, sit amet mollis lectus suscipit in. Integer volutpat tellus at congue congue.

### Produtos

![](https://github.com/cabarros3/gama-academy/blob/main/produtos.png)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque elementum nisi vel metus ultricies congue. Praesent tempus dignissim placerat. Morbi viverra, velit vitae imperdiet facilisis, tellus eros sodales felis, id aliquet eros ipsum eu nisl. Curabitur ac ante vitae lectus cursus porttitor id vel enim. Nullam placerat ac augue ut auctor. Fusce mattis sit amet nisi at ultricies. Nunc iaculis finibus lectus, sit amet mollis lectus suscipit in. Integer volutpat tellus at congue congue.

### Contato

![Imagem do elemento](https://github.com/cabarros3/gama-academy/blob/main/contactv.gif)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque elementum nisi vel metus ultricies congue. Praesent tempus dignissim placerat. Morbi viverra, velit vitae imperdiet facilisis, tellus eros sodales felis, id aliquet eros ipsum eu nisl. Curabitur ac ante vitae lectus cursus porttitor id vel enim. Nullam placerat ac augue ut auctor. Fusce mattis sit amet nisi at ultricies. Nunc iaculis finibus lectus, sit amet mollis lectus suscipit in. Integer volutpat tellus at congue congue.

## Sobre o grupo :sparkles:

Ao todo o nosso grupo é composto de 10 integrantes. Nos dividimos em back-end e front-end para elaborar desafio. Utilizamos a metodologia Kanban e a ferramenta Trello para nos organizar e ter ciência das atividades a fazer, em andamento e controle do que já foi concluído. Também elaboramos um fluxograma das atividades que você pode conferir [aqui](https://whimsical.com/grupo-6-corebiz-5vTgcgdSLVoBVeyzVwHgSK).

Camilla        | Alberto        | Lucas Ramos    |Jefferson       | 
-------------- | -------------- | -------------- | -------------- |
<a href="https://www.linkedin.com/in/camillabarros/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| <a href="https://www.linkedin.com/in/albertohfernandes/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| <a href="https://www.linkedin.com/in/lucas-ramos-gmp/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| 

Lucas Vihuchi  | Laura          | Guilhermano    | Evelyn         | 
-------------- | -------------- | -------------- | -------------- |
<a href="https://www.linkedin.com/in/lucasvihuchibraga/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| <a href="https://www.linkedin.com/in/laurapelaezmuller/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| <a href="https://www.linkedin.com/in/guilhermanosilva/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| |

Breno          | Victor         |
-------------- | -------------- |  


