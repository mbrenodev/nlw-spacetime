<h1 align="center">
   <img src="./.github/logo-nlw-spacetime.png" alt="NLW Spacetime" width="300"/>
</h1>
<h1 align="center">
   NLW Spacetime - Cápsula do Tempo
</h1>

<p align="center">
  <img alt="Last commit on GitHub" src="https://img.shields.io/github/last-commit/mbrenodev/nlw-spacetime?color=6c4ad0">
  <img alt="Made by Márcio Breno" src="https://img.shields.io/badge/made%20by-Márcio Breno-%20?color=6c4ad0">
  <img alt="Project top programing language" src="https://img.shields.io/github/languages/top/mbrenodev/nlw-spacetime?color=6c4ad0">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/mbrenodev/nlw-spacetime?color=6c4ad0">
  <img alt="GitHub license" src="https://img.shields.io/github/license/mbrenodev/nlw-spacetime?color=6c4ad0">
</p>

<p align="center">
  <a href="#information_source-como-executar">ℹ️ Como Executar?</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias">🚀 Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-autores">💻 Autores</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">📝 Licença</a>
</p>

<p align="center">
  O <b>NLW Spacetime - Cápsula do Tempo</b> é o projeto desenvolvido durante a <b>NLW Spacetime da Rocketseat</b>, utilizando <b>NodeJS</b> com <b>Fastify</b> e <b>React</b> com <b>NextJS 13</b>.
</p>


<p align="center">
  <img alt="Demonstration" src="./.github/NLW-Spacetime2.gif" />
</p>


---

> 🧪 Essa aplicação não possuirá **Testes Unitários**, **Integração** e **E2E** por não ser o foco do estudo, mas está pronta para ser executada. 🧪


# :information_source: Como Executar?

> Clone o Repositório:

```bash
git clone https://github.com/mbrenodev/nlw-spacetime
```

## Server

> Acesse o Server

```bash
cd server
```

> Instale as dependências:

```bash
pnpm install
```

> Informe as variáveis de ambiente
```bash
.env
```

```bash
DATABASE_URL="file:./dev.db"

GITHUB_CLIENT_ID=""
GITHUB_CLIENT_SECRET=""
```

> Execute o Prisma para criar as tabelas

```bash
npx prisma migrate dev
```

> Inicie o Serviço:

```bash
pnpm dev
```

## Web

> Com o Server Iniciado, acesse o projeto Web:

```bash
cd .. && cd web
```

> Instale as dependências:

```bash
pnpm install
```

> Informe a variável de ambiente
```bash
.env.local
```

```bash
NEXT_PUBLIC_GITHUB_CLIENT_ID=
```

> Inicie o Projeto:

```bash
pnpm dev
```

> ➡️ Acesse [http://localhost:3000](http://localhost:3000) para acessar a aplicação web.


# :rocket: Tecnologias

- [React](https://reactjs.org/)
- [NodeJS](https://nodejs.org/en/)
- [Typescript](https://www.typescriptlang.org/)
- [Axios](https://axios-http.com/ptbr/docs/intro)
- [Fastify](https://www.fastify.io/)
- [Prisma](https://www.prisma.io/)
- [Zod](https://zod.dev/)
- [NextJS](https://nextjs.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [DayJS](https://day.js.org/)
- [JS Cookie](https://github.com/js-cookie/js-cookie)
- [JWT Decode](https://github.com/auth0/jwt-decode#readme)

# :computer: Autores

<table>
  <tr>
    <td align="center">
      <a href="http://github.com/mbrenodev/">
        <img src="https://github.com/mbrenodev.png?v=4" width="100px;" alt="Márcio Breno"/>
        <br />
        <sub>
          <b>Márcio Breno</b>
        </sub>
       </a>
       <br />
       <a href="https://www.linkedin.com/in/mbrenodev/" title="Linkedin">@mbrenodev</a>
       <br />
       <a href="https://github.com/mbrenodev/go-barber-web-ts/commits?author=mbrenodev" title="Code">💻</a>
    </td>
    <td align="center">
      <a href="http://github.com/rocketseat/">
        <img src="https://avatars.githubusercontent.com/u/28929274?s=200&v=4" width="100px;" alt="Logo da Rocketseat"/>
        <br />
        <sub>
          <b>Rocketseat</b>
        </sub>
       </a>
       <br />
       <a href="http://github.com/rocketseat/" title="Linkedin">@rocketseat</a>
       <br />
       <a href="https://github.com/tavareshenrique/go-barber-web-ts/commits?author=tavareshenrique" title="Education Platform">🚀</a>
    </td>
  </tr>
</table>

# :memo: Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo de [licença](./LICENSE) para mais detalhes.