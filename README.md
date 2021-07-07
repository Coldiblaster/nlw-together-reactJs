<h1 align="center">
    Letmeask - Toda pergunta tem uma resposta.
    <h5 align="center">
      Projeto construído durante o Next Level Week Together
    </h5>
</h1>

<h1 align="center">
  <img src="https://i.ibb.co/R4tPT8p/1-NLW-05-1920x1080.png" alt="1-NLW-05-1920x1080" border="0" />
</h1>


## 📚 Índice

<p align="center">
  <a href="#thought_balloon-introdução">:small_blue_diamond: Introdução</a>
  <a href="#warning-pré-requisitos">:small_blue_diamond: Pré-requisitos</a>
  <a href="#arrow_forward-como-rodar-a-aplicação">:small_blue_diamond: Como rodar a aplicação</a>
  <a href="#rocket-deploy">:small_blue_diamond: Deploy</a>
  <a href="#open_file_folder-linguagens-e-dependencias-utilizadas">:small_blue_diamond: Linguagens e dependencias utilizadas</a>
</p>


## :thought_balloon: Introdução
Projeto realizado com o objetivo de compartilhar o conhecimento ou dúvidas com outras pessoas de qualquer lugar do país.
Para utilizar o Letmeask é bem simples, é preciso realizar o login via google, para efetuar criação de sala ou realizar uma pergunta em alguma sala existente.

## :warning: Pré-requisitos 

- [x] [Node.js](https://nodejs.org/en/download)
- [x] [Git](https://git-scm.com)
- [x] [Yarn](https://yarnpkg.com/)
- [x] [Firebase](https://firebase.google.com/?hl=pt)

## :arrow_forward: Como rodar a aplicação 

```bash
# Clone o repositório
$ git clone https://github.com/Coldiblaster/go-barber-back-end.git
# Entre na pasta
$ cd go-barber-back-end
# Instale as dependências
$ yarn
# Crie o Banco de Dados relacional
$ docker run --name gostack_gobarber -e POSTGRES_PASSWORD=123456 -p 5432:5432 -d postgres
# Crie o Banco de Dados não relacional
$ docker run --name mongodb -p 27017:27017 -d -t mongo
# Crie o Banco de Dados para cache
$ docker run --name redis -p 6379:6379 -d -t redis:alpine
# Rode as migrations
$ yarn typeorm migration:run
# Inicie o Projeto
$ yarn dev:serv
```

## :rocket: Deploy 

Passo a passo para executar o Deploy

## :open_file_folder: Linguagens e dependencias utilizadas
