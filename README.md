<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />

<h3 align="center">
  Desafio 04: Conceitos do React Native
</h3>

## O desafio 

O desafio pede para criar uma aplicação que irá listar todos os repositórios e permitir que recebam likes.

São 2 funcionalidades propostas: 

- [x] 1. Listar os repositórios da api

A funcionalidade deve pegar todos os reposiórios contidos na api e listá-los.

- [x] 2. Dar like em um repositório

Devará ser capaz de dar like em um repositório da api.

## Solução

1. Com o ```ùseEffect``` do React deverá fazer uma requisição do tipo ```[GET]``` para o backend e setar estes valores em um ```state```.

2. Com uma função nomeada ```handleLikeRepository``` é feito uma requisição ```[POST]``` com um id específico de um repositório. E com o retorno dessa função devo setar em meu ```state``` o repositório atualizado.

### Para instalar e usar esta aplicação sigas os passos abaixo.

1. Faça um ```git clone``` do projeto.

2. Instale as dependências do projeto utilizando ```npm install``` ou ```yarn add```.

3. Inicie o projeto com ```yarn dev```.
