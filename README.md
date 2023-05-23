<p align="center">
   <a href="https://www.linkedin.com/in/filipefmotta/">
      <img alt="filipe Motta" src="https://img.shields.io/badge/-Filipe%20Motta-4e5acf?style=flat&logo=Linkedin&logoColor=white" />
   </a>

  <a aria-label="Last Commit" href="https://github.com/filipefdm/nlw-spacetime/commits/master">
    <img alt="Last commit on GitHub" src="https://img.shields.io/github/last-commit/filipefdm/nlw-spacetime?color=4e5acf">
  </a>
</p>

<p align="center">
   <img src=".github/spacetime-cover.png"/>
</p>

# Temas

- [O que é o Spacetime?](#o-que-é-o-spacetime)
- [Tecnologias](#tecnologias)
- [Como executar?](#como-executar)

## O que é o Spacetime?

Este é um repositório que contém uma aplicação de cápsula do tempo, onde você pode armazenar e preservar suas memórias passadas. Com esta aplicação, você poderá criar registros de momentos especiais, como fotos e mensagens.

A aplicação permite que você defina uma data de abertura da cápsula, para que suas memórias fiquem guardadas e só possam ser acessadas posteriormente, trazendo uma sensação de surpresa e nostalgia quando o momento chegar.

O objetivo deste repositório é fornecer uma solução completa e amigável para que você possa criar suas próprias cápsulas do tempo e manter suas memórias vivas ao longo do tempo. Sinta-se à vontade para explorar o código-fonte, contribuir com melhorias e personalizar a aplicação de acordo com suas necessidades e preferências.

Compartilhe suas memórias e crie momentos especiais que serão apreciados no futuro com a aplicação de cápsula do tempo.

## Tecnologias

Foram utilizadas as seguintes tecnologias e ferramentas:

- [NodeJS](https://nodejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Fastify](https://www.fastify.io/)
- [Prisma](https://www.prisma.io/)
- [NextJS](https://nextjs.org)
- [ReactJS](https://reactjs.org/)
- [TailwindCSS](https://tailwindcss.com/)

## Como executar?

### Server

```bash
# Install the server dependencies
$ cd server
$ npm install

# Start the server project
$ npx prisma migrate deploy
$ npm run dev
```

### Web

```bash
# Install the web dependencies
$ cd web
$ npm install

# Start the web project
$ npm run dev
```

Acesse <http://localhost:3000> no navegador para ver o resultado!

---

Feito com 💜 por [Filipe Motta](https://github.com/filipefdm) 😊
