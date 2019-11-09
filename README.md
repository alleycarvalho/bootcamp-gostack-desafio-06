<h1 align="center">
    <img src=".github/gostack-logo.png" width="200px" alt="GoStack" />
</h1>

<h3 align="center">
  Desafio 6: Primeiro projeto com React Native
</h3>

<blockquote align="center">“Só deseje as coisas as quais você está disposto a lutar!”</blockquote>

<p align="center">
  <img src="https://img.shields.io/github/languages/count/alleycarvalho/bootcamp-gostack-desafio-06?color=%2304D361" alt="GitHub language count">

  <img src="https://img.shields.io/badge/license-MIT-%2304D361" alt="License">

  <a href="https://github.com/alleycarvalho/bootcamp-gostack-desafio-06/stargazers">
    <img src="https://img.shields.io/github/stars/alleycarvalho/bootcamp-gostack-desafio-06?style=social" alt="Stargazers">
  </a>
</p>

## :rocket: Sobre o projeto

- Uma aplicação criada do zero utilizando [React Native](https://facebook.github.io/react-native/).

- A aplicação permite adicionar `usuários do Github` em uma lista gravada no `Storage` do celular.

- Em uma página específica, nos `Detalhes` de cada usuário, será listado os `repositórios favoritos` do usuário específico.

## :mortar_board: Bootcamp - Desafio 6

### Funcionalidades

###### 1. Loading de repositórios

- [x] Adicionar um indicator de `loading`, utilizando `<ActivityIndicator />` antes de carregar a lista de repositórios favoritados na tela de `detalhes do Usuário`.

###### 2. Scroll infinito

- [x] Adicionar uma funcionalidade de `scroll infinito` na lista de repositórios favoritados. Assim que o usuário chegar nos **20% do final de lista**, busque pelos items na próxima página e adicione na lista.

- [x] Para requisitar uma nova página no Github utilize um parâmetro `page` no fim da URL.

###### 3. Pull to Refresh

- [x] Adicionar uma funcionalidade para quando o usuário arrastar a listagem de repositórios favoritados pra baixo atualize a lista resetando o estado, ou seja, volte o estado da paginação para a página 1 exibindo apenas os 30 primeiros itens.

A funcionalidade `Pull to Refresh` existe por padrão na **FlatList**.

###### 4. WebView

- [x] Criar uma nova página na aplicação que vai ser acessada quando o usuário clicar em um repositório favoritado, essa página deve conter apenas o `Header` da aplicação.

- [x] O conteúdo da página será uma **WebView**, ou seja, um browser integrado que exibe o atributo `html_url` presente no objeto do repositório que vem da API do Github.

Documentação de utilização da [WebView](https://github.com/react-native-community/react-native-webview/blob/master/docs/Getting-Started.md).

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

Desafio realizado por Alley M. Carvalho
