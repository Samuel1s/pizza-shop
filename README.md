<p align="center">
  <h1 align="center"><a href="https://github.com/Samuel1s/pizza-shop">Pizza Shop :rocket: </a></h1>
</p>

<p align="center" margin-top="25px" >
  <img alt="GitHub Language Count" src="https://img.shields.io/github/languages/count/Samuel1s/pizza-shop" />

  <img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/Samuel1s/pizza-shop" />
</p>

Este é o resultado de um estudo aprofundado de React.js, realizado no treinamento Ignite, da Rocketseat.

---

## 💻 Sobre

O Pizza Shop é uma aplicação para lojistas visualizarem e acompanharem métricas do seu restaurante que utiliza
alguma integração com aplicativos de delivery como por exemplo o IFood.

O projeto foi criado utilizando o Vite.js, e seu foco é na renderização pelo lado do cliente (SPA), aumentando a performance com um carregamento (cacheado) dos dados da API usando o React query e HTTP state. O projeto também utiliza Tailwind e Shadcnui(components) na camada do cliente para o design e também utiliza frameworks de teste que validam o funcionamendo da aplicação como o Vitest para testes unitários, a biblioteca MSW (Mock Service Worker) para mockar e interceptar a API consumida no FrontEnd com dados fictícios e o PlayWright para testes E2E.

---

## 🎨 Layout

A página em formato desktop é vista na imagem abaixo:

![PizzaShop Dashboard](https://github.com/Samuel1s/pizza-shop/assets/dashboard.png)

---

## 🛠 Tecnologias

As seguintes tecnologias foram empregadas na criação deste projeto:

- [ReactJs](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org/)
- [TailwindCss](https://tailwindcss.com/docs/installation)
- [Shadcn/ui](https://ui.shadcn.com/docs/installation/vite)
- [Axios](https://axios-http.com/ptbr/docs/intro)
- [ESLint](https://eslint.org/)
- [ReactQuery](https://tanstack.com/query/latest/docs/framework/react/overview)
- [ReactHookForm](https://www.react-hook-form.com/)
- [ReactRouterDom](https://reactrouter.com/en/main/start/overview)
- [DateFNS](https://date-fns.org/)
- [HelmetSEO](https://www.fullstacklabs.co/blog/improving-seo-in-react-apps-with-react-helmet)
- [Vitest](https://vitest.dev/guide/)
- [MockServiceWorker](https://mswjs.io/docs/getting-started)
- [PlayWright](https://playwright.dev/docs/intro)

---

## 🚀 Como utilizar

Clone o projeto para o local desejado em seu computador.

```bash
$ git clone git@github.com:Samuel1s/pizza-shop.git
```

---

#### 🚧 Executando o Projeto

```bash

# Navegue até o diretório
$ cd pizza-shop/app

# Instale as dependências necessárias
$ pnpm install

# Renomeie o arquivo .env.example para .env e adicione as informações necessárias nele
# OBS: Necessário possuir o backend "Teste" clonado e executando em outro diretorio.
$ git clone git@github.com:rocketseat-education/pizzashop-api.git

# Agora inicie o servidor do FrontEnd
$ pnpm run dev

# O terminal irá exibir o endereço local onde a aplicação está sendo executada:

  http://localhost:5173/

# Também pode-se iniciar o servidor em modo Teste com a API do Backend mockada.
$ pnpm run dev:test

# O terminal irá exibir o endereço local onde a aplicação está sendo executada:

  http://localhost:5174/

```

---

## Made with ❤️ by Samuel Santos 👋🏽 [Get in Touch!](https://www.linkedin.com/in/samuel-santos-29863113b/)
