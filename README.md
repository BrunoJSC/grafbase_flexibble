# dribbble-clone

**Versão:** 0.1.0  
**Privado:** true  

Este repositório contém o código para um projeto chamado "dribbble-clone". O projeto tem como objetivo replicar algumas funcionalidades da popular plataforma de design Dribbble. Ele utiliza tecnologias e bibliotecas modernas de desenvolvimento web para criar uma experiência de usuário visualmente atraente e interativa. Abaixo, você encontrará informações importantes sobre como configurar e executar o projeto.

## Tabela de Conteúdos

- [Visão Geral do Projeto](#visão-geral-do-projeto)
- [Começando](#começando)
  - [Instalação](#instalação)
  - [Scripts Disponíveis](#scripts-disponíveis)
- [Dependências](#dependências)
- [Dependências de Desenvolvimento](#dependências-de-desenvolvimento)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Visão Geral do Projeto

O projeto "dribbble-clone" é construído usando [Next.js](https://nextjs.org/), um framework React que permite renderização no lado do servidor e navegação eficiente no lado do cliente. Ele também utiliza [Tailwind CSS](https://tailwindcss.com/) para estilização, fornecendo uma abordagem de utilitários para construir interfaces de usuário. O projeto inclui capacidades de autenticação alimentadas pelo [NextAuth.js](https://next-auth.js.org/) e interage com o serviço [Cloudinary](https://cloudinary.com/) para gerenciamento de imagens. Além disso, consultas [GraphQL](https://graphql.org/) são feitas usando a biblioteca [graphql-request](https://github.com/prisma-labs/graphql-request).

## Começando

### Instalação

Para configurar e executar o projeto localmente, siga estes passos:

1. Clone este repositório para a sua máquina local.
2. Navegue até o diretório do projeto:
   ```bash
   cd dribbble-clone
   ```
3. Instale as dependências necessárias:
   ```bash
   npm install
   ```
4. Crie um arquivo `.env.local` na raiz do diretório do projeto e forneça as variáveis de ambiente necessárias. Consulte o arquivo `.env.example` para as variáveis obrigatórias.

### Scripts Disponíveis

No diretório do projeto, você pode executar os seguintes scripts:

- `npm run dev`: Inicia o servidor de desenvolvimento.
- `npm run build`: Compila a aplicação para produção.
- `npm run start`: Inicia o servidor de produção.
- `npm run lint`: Executa verificações de linting.

## Dependências

O projeto depende das seguintes bibliotecas principais:

- `@headlessui/react`
- `@types/jsonwebtoken`
- `@types/node`
- `@types/react`
- `@types/react-dom`
- `autoprefixer`
- `cloudinary`
- `graphql-request`
- `jsonwebtoken`
- `next`
- `next-auth`
- `postcss`
- `react`
- `react-dom`
- `tailwindcss`
- `typescript`

Consulte o arquivo [`package.json`](./package.json) para detalhes das versões.

## Dependências de Desenvolvimento

- `@grafbase/sdk`

## Contribuição

Contribuições para este projeto são bem-vindas. Se encontrar problemas ou tiver sugestões, sinta-se à vontade para abrir pull requests ou enviar problemas no [repositório](https://github.com/seu-nome-de-usuário/dribbble-clone).

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
