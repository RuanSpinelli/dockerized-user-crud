# dockerized-user-crud
# CRUD de Usuários com Docker, PHP e PostgreSQL

Projeto desenvolvido para praticar Docker Compose, Apache, PHP e PostgreSQL.

## Tecnologias utilizadas

* Docker
* Docker Compose
* Apache
* PHP 8.3
* PostgreSQL 17
* Adminer

## Funcionalidades

* Criar usuários
* Listar usuários
* Editar usuários
* Excluir usuários
* Marcar usuários como favoritos

## Como executar

Clone o repositório:

```bash
git clone URL_DO_REPOSITORIO
```

Entre na pasta:

```bash
cd desafio-docker-crud
```

Suba os containers:

```bash
docker compose up -d
```

Acesse:

Aplicação:
http://localhost:8080

Adminer:
http://localhost:8081

## Banco de dados

* Banco: cruddb
* Usuário: admin
* Senha: admin123

## Estrutura

* Apache + PHP em container
* PostgreSQL em container
* Persistência de dados com Docker Volume
* Administração do banco via Adminer
