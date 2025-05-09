# Tela de Login e Cadastro

Este projeto consiste em telas de login e cadastro desenvolvidas utilizando HTML e CSS básicos.

## Como a tela de login e cadastro foram criadas?

A tela de login foi estruturada utilizando HTML básico, com os seguintes elementos principais:

-   Um `<div>` com o id `login` para envolver todo o formulário e centralizar o conteúdo.
-   Outro `<div>` com a classe `caixa` para agrupar os elementos internos do formulário, como a logo, o título e os campos de entrada.
-   Uma tag `<img>` para exibir a logo.
-   Um `<h1>` para o título "LOGIN".
-   `<div>`s com as classes `email` e `senha` contendo os respectivos campos de entrada (`<input type="email">` e `<input type="password">`) com placeholders para guiar o usuário.
-   Um `<div>` com a classe `entrar` contendo uma mensagem com um link para a tela de cadastro (`<a href="./cadastro.html">Crie uma.</a>`) e um botão de envio do formulário (`<input type="submit" value="Entrar">`).

A tela de cadastro segue uma estrutura similar, com os campos adicionais para nome e confirmação de senha.

O estilo visual de ambas as telas foi definido em arquivos CSS separados (`./css/style.css` para login e `./css/cadastro.css` para cadastro). O CSS foi utilizado para controlar o layout, cores, tipografia, espaçamento e outros aspectos visuais, buscando uma interface amigável e consistente. Foi utilizada a fonte 'Roboto' do Google Fonts, importada através da tag `<link>` no `<head>` dos arquivos HTML.

## Comandos Git utilizados para criar e publicar o repositório no GitHub:

Os seguintes comandos Git foram utilizados para inicializar o repositório local, adicionar os arquivos, realizar o primeiro commit, criar o branch `main`, adicionar o repositório remoto no GitHub e enviar o código:

```bash
git init
git add NOME_DO_ARQUIVO
git commit -m "COMENTE O QUE FOI FEITO..."
git branch -M main
git remote add origin URL_DO_SEU_GITHUB
git push -u origin main
````

## Importante:

Atenção aluno, configure seu usuário e email no git para conseguir efetivar o envio dos conteúdos para o seu repositório local. Siga as instruções:

```bash
# Verificação de USER
- git config --list

# Cadastrar USERS
-  git config --global user.name "SEUNOME"
-  git config --global user.email "SEUNOME@EMAIL.COM"
````
