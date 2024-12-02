# CRUD-DripStore
O CRUD - DripStore é um projeto desenvolvido para gerenciar informações de uma loja online. Ele implementa as operações fundamentais de um CRUD (Create, Read, Update, Delete), permitindo a manipulação de dados de produtos, clientes ou outras entidades relacionadas a um sistema de e-commerce.

Esta documentação apresenta uma visão geral do projeto, como instalá-lo, utilizá-lo e contribuir para sua manutenção.
## Autores:
- Thiago Arruda
- Cleber França
- Icaro Pereira
### Tecnologias utilizadas
-JavaScript e Node.js
### Banco de dados utilizad
-mySQL
### Bibliotecas utilizadas
- Express.js
- dotenv
- nodemon
- sequelize
- JWT
- JEST

#### instalação
- Primeiro clone o repositório
- Crie um banco de dados no MySQL chamado digital ou configure o nome no arquivo de configuração.
- Atualize as credenciais do banco no arquivo .env (ou onde está configurado no projeto):


DB_DRIVER='mysql'

DB_NAME='digital'

DB_HOST='localhost'

DB_PORT=''

DB_USER='root'

DB_PASSWORD='sua senha'

## Para o cadastro de usuarios, produtos e categorias, use respectivamente:
### Usuarios:
- firstname:
- surname:
- email:
- password:

### produtos:

- enabled:
- name:
- slug:
- useInMenu:
- stock:
- description:
- price:
- priceWithDiscout:

### Categorias:
- name:
- slug:

## Para ter acesso as rotas entre em:
- /Users: Para CRUD de usuarios
- /Products: Para o CRUD de produtos
- /Category: Para o CRUD de Categorias

## Plataforma de testes sugerida:
- Insomnia







