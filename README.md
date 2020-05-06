# gostack-desafio-fundamentos-react-native
Código para o desafio de fundamentos de react-native do curso da Rocketseat.

<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 08: Fundamentos do React Native
</h3>

<p align="center">
  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

### Funcionalidades da aplicação

- **`Listar os produtos da fake API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem através de uma tabela, com o campo `title`, `image_url` e `price`.

- **`Adicionar itens ao carrinho`**: Em toda sua aplicação, você deve utilizar o Contexto chamado `cart` que deixamos disponível. Você vai precisar completar as funcionalidades dentro de `hooks/cart.tsx` para que você consiga adicionar itens ao carrinho.

- **`Exibir itens do carrinho`**: Na página `Cart` você deve exibir todos os itens do carrinho, junto com a quantidade, valor único, valor subtotal dos itens e total de todos os items.

- **`Aumentar quantidade de itens do carrinho`**: Na página `Cart` você deve permitir que o usuário aumente a quantidade de itens do mesmo produto, para isso você pode utilizar a função `increment` dentro do seu contexto em `/src/hooks/cart.tsx`.

- **`Diminuir quantidade de um item do carrinho`**: Na página `Cart` você deve permitir que o usuário decremente a quantidade de itens do mesmo produto, para isso você pode utilizar a função `decrement` dentro do seu contexto em `/src/hooks/cart.tsx`.

- **`Exibir valor total dos itens no carrinho`**: Tanto na página `Dashboard`, tanto na página `Cart` você deve exibir o valor total de todos os itens que estão no seu carrinho.
