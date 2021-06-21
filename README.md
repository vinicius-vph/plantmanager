<h1 align="center">
  <img alt="Plant Manager" title="Plant Manager" src=".github/logo.png" />
</h1>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=32B768&labelColor=000000">

 <img src="https://img.shields.io/static/v1?label=NLW&message=05&color=32B768&labelColor=000000" alt="NLW 05" />
</p>

<br>

## ✨ Tecnologias
Esse projeto foi desenvolvido durante a **NLW 5** da <a href="https://rocketseat.com.br/">Rocketseat</a> com as seguintes tecnologias:

- [React Native](https://reactnative.dev/)
- [Typescript](https://www.typescriptlang.org/)
- [Expo](https://expo.io/)

<br>

## 💻 Projeto

Plantmanager é um aplicativo para lhe ajudar a lembrar de cuidar de suas plantas de forma fácil de acordo com cada tipo de planta.

## 🔖 Layout

Você pode visualizar todas as telas do app a seguir:

<div align="center">
  <img alt="Tela de Bem-vindo" src=".github/screen-welcome.png" width="30%">
  <img alt="Tela de inicio" src=".github/screen-start.png" width="30%">
  <img alt="Tela Minhas Plantas" src=".github/screen-my-plants.png" width="30%">
</div>
<div align="center">
  <img alt="Tela Principal parte 1" src=".github/screen-dashboard-full1.png" width="30%">
  <img alt="Tela Principal parte 2" src=".github/screen-dashboard-full2.png" width="30%">
  <img alt="Tela Principal filtrada" src=".github/screen-dashboard-filter.png" width="30%">
</div>
<br>


## 🚀 Para rodar o projeto você vai precisar:
- Ter uma chave ssh configurada, você pode ver mais <a href="https://docs.github.com/pt/github/authenticating-to-github/connecting-to-github-with-ssh">Aqui</a>
- Clonar o repositório
```

$ git clone git@github.com:vinicius-vph/plantmanager.git

``` 
<h3>Após o passo anterior</h3>

- Instale as dependências do projeto com o comando
```
$ yarn
```
- Inicie seu app com 
```
$ expo start
```
- Inicie a fake api com 
```
$ json-server ./src/services server.json --host 192.168.0.2 --port 3333 --delay 700
```
caso não funcione com o comando acima utilize
```
$ yarn json-server ./src/services/server.json --host 192.168.0.2 --port 3333 --delay 700
```
Substitua o host pelo seu endereço IP local. Faça o mesmo no arquivo API dentro de services.

## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

