# Sobre o Projeto

O projeto consiste em um sistema distribuído que visa fornecer funcionalidades de login, autenticação de usuários e gerenciamento de tarefas. Ele é composto por dois principais microserviços:

## Microserviço de Autenticação de Usuários

Este microserviço é responsável por gerenciar os usuários e conta com o processo de autenticação. 

## Microserviço de Gerenciamento de Tarefas

O segundo microserviço se trata do gerenciamento de tarefas atribuídas aos usuários autenticados. Ele oferece funcionalidades para criar, visualizar, atualizar e excluir tarefas.

## Tecnologias Utilizadas

- Bun.JS
- Elysia.JS
- Prisma
- TypeScript

## Execute o projeto

- Clone esse repositório em sua máquina
- No terminal do dentro da pasta app, instale as dependências usadas no projeto:
  - ```bun run setup```
- Ainda no terminal, entre na pasta referente ao microserviço que deseja executar e digite:
  - ```bun run dev```
- No navegador, entre na url:
  - Para user: http://localhost:3001
  - Para task: http://localhost:3001

# Como criar um projeto Elysia usando Bun

## Instalação:

- Instale o Bun.JS  
  - ```bash bun create elysia ./elysia-example ```
- Cheque sua instalação
  - ```bun --version```

## Criação do projeto:

- Crie um projeto com Elysia
-  ```bash bun create elysia app```

# Arquitetura

## Arquitetura de Sistema

Este projeto segue uma arquitetura de microserviços, uma abordagem de desenvolvimento de software que organiza uma aplicação como um conjunto de serviços independentes, cada um representando uma funcionalidade específica. Cada microserviço opera de forma autônoma, com sua própria base de código, banco de dados e lógica de negócios.

## Arquitetura de Software

### Sobre a organização das pastas, o projeto foi dividido em:

- App
- 
  - task_microservice
    - node_modules
    - prisma
    - src
      - controllers
      - dtos
      - repositories
      - services
        
  - user_microservice
    - node_modules
    - prisma
    - src
      - controllers
      - dtos
      - repositories
      - services

