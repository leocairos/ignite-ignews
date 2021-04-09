<h1 align="center">
    <img alt="Ignite React JS" title="Ignite React JS" src="./.github/ignite.png" />
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/leocairos/ignite-ignews?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/leocairos/ignite-ignews">

  <a href="https://github.com//leocairos/ignite-ignews/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/leocairos/ignite-ignews">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/leocairos/ignite-ignews/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/leocairos/ignite-ignews?style=social">
  </a>

  <a href="https://www.linkedin.com/in/leonardo-sampaio-cairo-54a74756/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&labelColor=blue">
  </a>
</p>

# 🚀 Sobre

O Ignite é um programa de aceleração para devs desenvolvido pela [Rocketseat](https://rocketseat.com.br/).


## 💻 Sobre o Rentx

Trata-se de app para assinatura de conteudos (texto).

<h1 align="center">
    <img alt="Diagrama" title="Diagrama" src="./.github/Home.png" />
</h1>

[Oficial Figma](https://www.figma.com/file/gl0fHkQgvaUfXNjuwGtDDs/ig.news?node-id=1%3A2) |
[Copy of Oficial Figma](https://www.figma.com/file/HTnWm1Z088nZp9S0fqvnM1/ig.news-Copy?node-id=1%3A2)

### Diagrama de fluxo do APP

<h1 align="center">
    <img alt="Diagrama de fluxo do APP" title="Diagrama de fluxo do APP" src="./.github/fluxo-ig-news.png" />
</h1>

### APP model SPA (Single Page Application) vs SSR (Server Side Rendering)

<h1 align="center">
    <img alt="Diagrama APP model SPA vs SSR" title="APP model SPA vs SSR" src="./.github/SPAvsSSR.png" />
</h1>

### SSG (Static Site Generation)

<h1 align="center">
    <img alt="Diagrama SSG" title="Diagrama SSG" src="./.github/SSG.png" />
</h1>

### When use SPA, SSR and SSG

- SPA (client-side) dynamic information not recomended for informatin indexation on searchs
  * by useEfect
- SSR (server-side) dynamic information, especific information for a especific user
  * by GetServerSideProps
- SSG (static) static information, generic information for all users.
  * by GetStaticProps

### Execute

```bash
git clone
cd ignite-ignews
```

## Plugins - Dev

* VSCode CSS Modules
  - Extension for CSS Modules, which supports:
    * autocomplete
    * go to definition


## [Stripe](www.stripe.com)

* Create free login account
* Verify e-mail
* Create a Business Account
* Add a new product

* Developers >> API keys
  * Get a "Secret Key"
  * Create a .env.local file in root project path
  * Insert a propertie STRIPE_API_KEY with Secret Key value copied

* Optimal
  * Settings >> Branding:
    * Brand color
    * Accent color
    * Icon
    * Logo

## [FaunaDB](https://fauna.com/) Database for App serverless

* SignUp (Free account)
* Create Database
* Create New Key (in security)
* Create a New Collection (users)
* Create a Index for search
  * Source colletion: users
  * index name: user_by_email
  * terms: data.email
  * unique: true
  * serialized: true

*FaunaDB has a docker image for local use in dev mode.*

## Tips/Notes

* Set public e-mail on your github account

## 📝 Licença

Este projeto esta sob a licença MIT.

Feito com ❤️ por [Leonardo Cairo](https://www.linkedin.com/in/leonardo-sampaio-cairo-54a74756/)!
