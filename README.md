<h1 align="center">

<img src="https://raw.githubusercontent.com/khalleb/ignews/main/public/images/avatar.svg" alt="rocketshoes" width="100px"/>

</h1>

<p align="center">
  IGNEWS - Portal de notícias 📰🚀
  <br>
  
  <img alt="Language count" src="https://img.shields.io/github/repo-size/shateixeira/ignews"/>
  <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1">
  <a href="https://www.linkedin.com/in/shayane-teixeira-4520b2196/">
    <img alt="Made by Shayane" src="https://img.shields.io/badge/made%20by-ShayTeixeira-%237519C1">
  </a>
  <a href="https://github.com/shateixeira/ignews/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/shateixeira/ignews">
  </a>
  <img alt="License" src="https://img.shields.io/github/license/shateixeira/ignews">
</p>

---

<p align="center">
  <a href="#dart-sobre">Sobre</a> | 
  <a href="#rocket-tecnologias">Tecnologias</a>  |
  <a href="#white_check_mark-requerimentos">Requerimentos</a> | 
  <a href="#checkered_flag-começando">Começando</a> 
</p>

<br>

## :dart: Sobre ##

O projeto ig.news é um blog onde os usuários podem ter acesso ao conteúdo de cada postagem de acordo com o status de sua assinatura.<br>
O blog possui um sistema de compra integrado com o STRIPE, e após o usuário realizar o pagamento, sua inscrição estará ativa e pronta para visualizar o conteúdo completo
de todo o blog. Caso o usuário não deseje optar pela assinatura, ele terá acesso limitado ao conteúdo das postagens. E todos os dados necessários para se fazer verificações
de assinaturas ou dados dos usuários, estão salvos no banco de dados FaunaDB.
<br>
<br>
Essa é uma aplicação Serverless, ou seja, todo o processo que dependeria de um backend foi integrado dentro do front e seguindo o padrão da JAMStack.
<br>
As postagens são feitas pelo painel do Prismic CMS e integradas diretamente pelo front.


## :rocket: Tecnologias ##

As seguintes tecnologias foram utilizadas no projeto:

- [Next.js](https://nextjs.org/)
- [Prismic CMS](https://prismic.io/)
- [Stripe](https://stripe.com/)
- [FaunaDB](https://fauna.com/)

## :white_check_mark: Requerimentos ##

- [Node](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/lang/en/)

## :checkered_flag: Começando ##

```bash
# Clone this project
$ git clone https://github.com/ShaTeixeira/ignews

# Access
$ cd ignews

# Install dependencies
$ yarn install

# Run the project
$ yarn dev

# The server will initialize in the <http://localhost:3000>
```



