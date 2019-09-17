# Teste - Criação de API

O teste consiste no desenvolvimento de um catálogo de usuários.

Para isso, você deverá criar uma aplicação que:

1. Importe usuários e posts de uma API e guarde em um banco de dados não relacional (ex: mongodb)
1. Possua uma tela para listar os usuários, com ações de adicionar, editar e excluir
1. Também é necessário ter uma tela de detalhes de usuário, para listar os posts de cada um deles
1. Tenha APIs que retornem os dados do banco de dados no formato JSON
   * Todos os usuários: **/users**
   * Usuário específico: **/users/:id**
   * Posts de um usuário: **/users/:id/posts**

O backend da aplicação pode ser feito utilizando um web framework como Express/Restify.

O frontend da aplicação pode ser feito em VueJs/React.

## Fonte dos dados - APIs

**Usuários:**
http://jsonplaceholder.typicode.com/users

**Posts:**
http://jsonplaceholder.typicode.com/posts

## Entrega

O código do projeto deve ser disponibilizado em um repositório no GitHub ou Bitbucket e ser enviado apenas o link do mesmo.

### Muita atenção

Incluir também no repositório um arquivo **README** com instruções para rodar o projeto. É muito importante que funcione.
