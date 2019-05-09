# Advise - Teste prático para back-end nodejs

API REST para gerenciar produtos e categorias de produtos. 

## Tecnologias utilizadas
Nodej, Express, Sequelize

## Como rodar o projeto
### criar um banco
create database adviseapi
### Instalar depencias

    Yarn install

Crinado as tabelas no banco

    yarn sequelize db:migrate

Rodar api

    yarn dev

Rodar testes

    yarn test
    
## Detalhes

Rota para acessar a documentação localhost:http://localhost:3000/api-docs/

- [x] TDD Desenvolvimento orientado a teste
- [x] Uso de validadores na rota.
- [ ] Testes unitários.
- [ ] Testes de integração.
- [x] Documentação.
 
## Rotas

### Produto
CRUD Produto
- [x] create
- [x] read
- [x] update
- [x] delete

### Categoria
Crud Categoria
- [x] create
- [x] read
- [x] update
- [x] delete

### Documentação
- [x] Rota para documentação
### Parcelas 
- [ ] Rota para calcular o valor das parcelas do produto.
