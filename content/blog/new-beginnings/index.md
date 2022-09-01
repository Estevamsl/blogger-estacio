---
title: node para iniciantes
date: "2022-08-31T22:12:03.284Z"
description: "Nodejs para iniciantes, um runtime para javascript"
---

<!-- buscando uma imagem do Nodejs -->

![Nodejs](https://nodejs.org/static/images/logo.svg)


# Nodejs

Nodejs é um runtime para javascript, ou seja, ele executa javascript fora do navegador. Ele é baseado no motor V8 do Google Chrome, que é um interpretador de javascript.

## Instalação

```bash

# Ubuntu

curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash -

sudo apt-get install -y nodejs

# Windows

https://nodejs.org/en/download/

```

## Criando um projeto

```bash

npm init -y

```

## Instalando dependências

```bash

npm i express

```

## Criando um servidor

```bash

# index.js

const express = require('express')

const app = express()

app.get('/', (req, res) => {

res.send('Hello World!')

})

app.listen(3000, () => {

console.log('Example app listening at http://localhost:3000')

})

```

<!-- Vantagens de usar o node -->

## Vantagens de usar o node

- Nodejs é assíncrono, ou seja, ele não bloqueia o código enquanto aguarda uma resposta de uma requisição, ele continua executando o código enquanto aguarda a resposta.
- Nodejs é single-threaded, ou seja, ele usa apenas uma thread para executar o código, mas ele usa o conceito de event loop para executar o código de forma assíncrona.
- Nodejs é baseado no motor V8 do Google Chrome, que é um interpretador de javascript.
- Nodejs é open-source.
- Nodejs é multiplataforma.
- Nodejs é rápido.
- Nodejs é leve.
- Nodejs é escalável.
- Nodejs é fácil de aprender.
- Nodejs é fácil de usar.
- Nodejs é fácil de manter.
- Nodejs é fácil de depurar.
- Nodejs é fácil de testar.
- Nodejs é fácil de documentar.

