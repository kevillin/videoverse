# VideoVerse

Esse projeto é baseado em streamings de vídeo. Aqui, utilizamos até agora: React, Typescript, Eslint, Vite como Bundle.
Além disso, vamos criar testes e a arquitetura MSC (model, service e controller) para melhor organização das camadas de Back-End.
Para o Back-End, vamos usar o Node e fazer as requisições HTTP pelo ThunderClient.
E, como banco de dados, optamos por um banco de dados noSQL (MongoDB).
Vamos utilizar o Docker para conteinerização.

# Equipe

  - [Carlos Augusto](https://github.com/carlos-aug)
  - [Pedro Gonçalves](https://github.com/pllsg96)
  - [Isaque Almeida](https://github.com/isaquealmeida)
  - [Kevillin Santos](https://github.com/kevillin)

## Como rodar esse projeto no seu VSCode

Para usar esse projeto no seu VSCode, basta seguir esse passos:

```bash
  cd backend/
  npm install
```

```bash
  cd frontend/
  npm install
```
Depois de instalar todas as dependencias do projeto, você pode dar o seguinte comando que já abrirá uma aba no seu navegador automaticamente:

```bash
  npm run dev
```

Para rodar o Linter, dê o seguinte comando:

```bash
  npm run lint
```

Para rodar o Docker, vá para o diretório raiz e dê o seguinte comando:

```bash
  docker-compose up -d
```

## Referências

 - [React](https://react.dev/)
 - [Vite](https://vitejs.dev/)
 - [Eslint](https://eslint.org/)
 - [Typescript](https://www.typescriptlang.org/)
 - [MongoDB](https://www.mongodb.com/)
 - [ThunderClient](https://www.thunderclient.com/)
 - [Arquitetura MSC, o que é e por que usar? - Mariana Mohr](https://medium.com/@marianamohr/arquitetura-msc-o-que-%C3%A9-e-por-que-usar-42ad4cf19583)
 - [Docker](https://docs.docker.com/)
 - [Nodemon](https://github.com/remy/nodemon)