<h1 align="center">
    <img alt="NextLevelWeek" title="#NextLevelWeek" src=".github/logo.png" />
</h1>

<h4 align="center"> 
	🚀 NextLevelWeek 1.0 🚀
</h4>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/styllth/Ecoleta-NLW?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/styllth/Ecoleta-NLW">

  <a href="https://www.linkedin.com/in/styllth/">
    <img alt="Made by Styllth" src="https://img.shields.io/badge/made%20by-Styllth-%2304D361">
  </a>
  
  <a href="https://github.com/styllth/Ecoleta-NLW/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/styllth/Ecoleta-NLW">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">

  <a href="https://github.com/styllth/Ecoleta-NLW/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/styllth/Ecoleta-NLW?style=social">
  </a>
</p>

# Índice

<p align="center">

[NLW](#nlw) -
[Sobre](#sobre) -
[Layout](#layout) -
[Documentação](#documentacao) -
[Tecnologias Utilizadas](#tecnologias-utilizadas) -
[Como rodar este projeto](#como-rodar) -
[Como Contribuir](#como-contribuir) -
[Licença](#licenca)

</p>

<a id="nlw"></a>

## :information_source: O que é o Next Level Week?

O NLW é uma experiência online com muito conteúdo prático, desafios e hacks que vão te ajudar a avançar para o próximo nível.

<a id="sobre"></a>

## :bookmark: Sobre o projeto ♻️

Este projeto foi desenvolvido na Trilha **Booster** durante a **Next Level Week** distribuída pela [Rocketseat](https://rocketseat.com.br/).

O **Ecoleta** é uma aplicação Web e Mobile cujo objetivo é conectar empresas ou entidades de coleta de resíduos à pessoas que precisam descartar seus resíduos de maneira ecológica.

As empresas ou entidades poderão se cadastrar na plataforma web e as pessoas terão acesso ao aplicativo móvel, onde poderão navegar pelo mapa para ver as instituições cadastradas e encontrar um ponto de coleta mais próximo.

<a id="layout"></a>

## :art: Layout

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/Ecoleta?node-id=136%3A546">
  <img alt="Layout figma" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>

### :iphone: Mobile

<p align="center">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src=".github/home-mobile.png" width="200px">

  <img alt="NextLevelWeek" title="#NextLevelWeek" src=".github/detalhes-mobile.svg" width="200px">
</p>

### :desktop_computer: Web

<p align="center">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src=".github/web.svg" width="400px">
</p>

<a id="documentacao"></a>

## :books: Documentação

Para reforçar alguns conceitos e registrar comandos que são difíceis de se lembrar existe uma pequena **[DOCUMENTAÇÃO](DOCUMENTATION.md)** para ajudar quem esta iniciando com **TypeScript**, **Node**, **ReactJS** e **React Native**.

<a id="tecnologias-utilizadas"></a>

## :rocket: Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias

- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)

<a id="como-rodar"></a>

## :rocket: Como rodar este projeto

Podemos considerar este projeto como sendo divido em três partes:

1. Back End (pasta server)
2. Front End (pasta web)
3. Mobile (pasta mobile)

:bulb: Tanto o Front End quanto o Mobile precisam que o Back End esteja sendo executado para funcionar.

- ### **Pré-requisitos**

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
**[Git](https://git-scm.com)**
**[Node.js](https://nodejs.org/en/)**
**[Expo](https://expo.io/)**

Além disto é bom ter um editor para trabalhar com o código. Neste projeto foi usado o [VSCode](https://code.visualstudio.com/)

- ### Baixando o projeto

```bash
# Clone este repositório
$ git clone https://github.com/styllth/Ecoleta-NLW.git

```

- ### :gear: Rodando o Back End (servidor)

```bash
# Acesse a pasta do projeto no terminal
$ cd Ecoleta-NLW

# Vá para a pasta server
$ cd server

# Instale as dependências
$ npm install

# Crie o banco de dados
$ npm run knex:migrate
$ npm run knex:seed

# Execute a aplicação em modo de desenvolvimento
$ npm run dev

# O servidor inciará na porta:3333 - acesse http://localhost:3333
```

- ### :world_map: Rodando a aplicação web (Front End)

```bash
# Acesse a pasta do projeto no seu terminal
$ cd Ecoleta-NLW

# Vá para a pasta da aplicação Front End
$ cd web

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```

- ### :iphone: Rodando a aplicação mobile

```bash
# Acesse a pasta do projeto no seu terminal
$ cd Ecoleta-NLW

# Vá para a pasta da aplicação Front End
$ cd mobile

# Instale as dependências
$ npm install
```

<a id="como-contribuir"></a>

## :smirk: Como contribuir para o projeto

- Faça um Fork desse repositório,
- Crie uma branch com as suas alterações: `git checkout -b my-feature`
- Commit suas mudanças contando o que você fez: `git commit -m "feature: My new feature"`
- Envie as suas alterações: `git push origin my-feature`

> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions)

<a id="licenca"></a>

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

<h4 align="center">
    Feito com ❤️ by <a href="https://www.linkedin.com/in/styllth/" target="_blank">Styllth</a>
</h4>
