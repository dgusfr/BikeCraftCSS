# BikeShop Web Store

Este é um projeto de uma loja web de bicicletas, onde os usuários podem navegar e comprar diferentes tipos de bicicletas.

## Interface

<div align="center">
  <img src="img/logo.png" alt="Imagem do Projeto" width="900">
</div>

## Sumário

- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Status](#status)
- [Descrição](#descrição)
- [Funcionalidades](#funcionalidades)
- [Explicação](#explicação)
- [Como Usar](#como-usar)
- [Autor](#autor)

## Tecnologias Utilizadas

<div style="display: flex; flex-direction: row;">
  <div style="margin-right: 20px; display: flex; justify-content: flex-start;">
    <img src="img/js.png" alt="Logo Linguagem" width="100"/>
  </div>
  <div style="margin-right: 20px; display: flex; justify-content: flex-start;">
    <img src="img/html.png" alt="Logo Linguagem" width="100"/>
  </div>
  <div style="margin-right: 20px; display: flex; justify-content: flex-start;">
    <img src="img/css.png" alt="Logo Linguagem" width="100"/>
  </div>
</div>

## Status

![Concluído](http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge)

<!-- -->

## Descrição

Este projeto consiste em uma loja online de bicicletas, onde os usuários podem visualizar uma variedade de modelos, adicionar produtos ao carrinho e finalizar a compra.

## Funcionalidades

- Exibição de bicicletas disponíveis para venda
- Adicionar bicicletas ao carrinho de compras
- Remover bicicletas do carrinho de compras
- Finalizar a compra com um resumo do pedido

## Explicação

```javascript
// Exemplo de código de listagem de produtos
const products = [
  { id: 1, name: 'Mountain Bike', price: 1200 },
  { id: 2, name: 'Road Bike', price: 1500 },
  { id: 3, name: 'Electric Bike', price: 3000 }
];

function displayProducts() {
  products.forEach(product => {
    console.log(`Product: ${product.name}, Price: ${product.price}`);
  });
}

displayProducts();
``` 

## Como Usar

`1.` Clone o repositório para sua máquina local.

`2.` Abra o arquivo index.html em seu navegador.

`3.` Navegue pela loja, adicione produtos ao carrinho e finalize a compra.

## Autor
Desenvolvido no curso de CSS da Origamid®