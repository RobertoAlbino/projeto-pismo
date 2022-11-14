# Projeto pismo

## 💻 Tecnologias utilizadas na construção

* Linux
* Docker
* Docker Compose
* Spring boot + Java 11 para construção dos micro serviços
* PostgreSQL para o banco de dados
* FlyWay para a migração de banco de dados
* Git + GitHub + GitHub Actions para CI/CD

## 📝 Desenho da arquitetura

![arquitetura](desenho.jpg)

## 💻 Componentes da arquitetura

### Transactions Api

* Micro serviço Spring responsável por criar as transações do sistema
* Repositório: https://github.com/RobertoAlbino/transactions_api

### Transactions Database

* Banco de dados PostgreSQL que armazena os dados de transação
* Repositório: https://github.com/RobertoAlbino/transactions_api

### Transactions Api

* Micro serviço Spring responsável pelas transações do sistema
* Repositório: https://github.com/RobertoAlbino/transactions_api

### Transactions Database

* Banco de dados PostgreSQL que armazena os dados de transação
* Repositório: https://github.com/RobertoAlbino/transactions_database

### Clients Api

* Micro serviço Spring responsável pelos dados de cliente e contas
* Repositório: https://github.com/RobertoAlbino/clients_api

### Clients Database

* Banco de dados PostgreSQL que armazena os dados de cliente e contas
* Repositório: https://github.com/RobertoAlbino/clients_database

### Pismo Infra

* Esse projeto no momento tem apenas a responsabilidade de criar a network docker para os outros micro serviços utilizarem
* Repositório: https://github.com/RobertoAlbino/pismo-infra


