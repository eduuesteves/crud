# Microsserviço

## Neste projeto vamos usar:

    - Framework - Reactjs
    - Banco de cados - Mysql

## Serão duas pastas:

    - Client - para o front-end
    - Server - para o back-end
  
## Rotas

    - get('/users') - para acessar todos os usuários
    - get('/users/:id') - para acessar usuário específico
    - post('/new-users') - para cadastrar novo usuários
    - put('/users/change/:id') - para alterar usuário
    - delete('/users/delete/:id') - para deletar usuário
    - get('/create-table') - para criar a tabela
  
## Código

### Iniciar o projeto Back-End

    cd server >
    |
    yarn init
    |
    yarn
    |

### Bibliotecas Back-End

Cors - compartilhamento de recursos com origens diferentes - usa cabeçalhos adicionais HTTP para informar a um navegador que permita que um aplicativo Web seja executado em uma origem (domínio) com permissão para acessar recursos selecionados de um servidor em uma origem distinta.

    yarn add cors

Express - para acessar rotas

    yarn add express

Mysql - para conectar o banco de dados mysql ao projeto

    yarn add mysql

Nodemon - para que quando houver alteração no código, não precise reiniciar o servidor

    yarn add Nodemon


Middleware - são funções que processam a solicitação e envia a resposta. Não é necessário para solicitações GET e DELETE, mas sim para POST e PUT, porque ambas enviam dados para o servidor e solicita ao servidor que aceite ou armazene esse dados, que está incluído em um corpo (req.body)

### Iniciar o projeto Front-End

    yarn create react-app client

### Bibliotecas Front-End

Sass - pré processador css

    yarn add sass

React Router Dom - para criar rotas no site

    yarn add react-router-dom

Axios - para acessar API

    yarn add axios

Formik - para criar formulário

    yarn add formik

Yup - para exibir mensagens no formulário, caso o usuário não faço o que é esperado

    yarn add yup