# Projeto Olá Mundo

Este é um projeto básico de front-end que exibe uma página com a mensagem "Olá Mundo", utilizando HTML e CSS para estilização.

## Funcionalidades

- Exibe uma mensagem de "Olá Mundo" centralizada na tela.
- Estilização simples com fundo claro, texto azul e um contêiner centralizado com sombra.

## Tecnologias Utilizadas

- HTML5
- CSS3

## Estrutura do Projeto
- index.html
- style.css  

## Como Executar o Projeto

1. Copie o código abaixo e cole no seu arquivo `Olamundo.html` no VS Code:
///<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Olá Mundo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <p>Olá Mundo!</p>
    </div>
</body>
</html>\\\

2. Copie o código abaixo e cole no seu arquivo `style.css` no VS Code:
\\\* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f0f0f0;
}

.container {
    text-align: center;
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

p {
    font-size: 3rem;
    color: blue;
}\\\

Dessa forma, qualquer pessoa pode facilmente copiar e colar o código no VS Code e rodar o projeto localmente.
