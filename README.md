# 🚀 Projeto NodeJS com Express, Handlebars, Docker e MySQL

Este projeto é uma aplicação NodeJS que utiliza **Express** como framework, **Handlebars** como template engine e **MySQL** como banco de dados, com suporte a **Docker** para facilitar a configuração do ambiente.  

## 🛠 Tecnologias Utilizadas
- **NodeJS**
- **Express**
- **Handlebars**
- **MySQL** (via Docker)
- **phpMyAdmin** (para gerenciar o banco via interface web)
- **Docker / Docker Compose**

---

## ⚙️ Como Rodar o Projeto

### 1. Subir os containers com Docker
No diretório raiz do projeto, execute:  

```bash
docker compose up -d
```

Isso irá criar:

* Uma instância do MySQL
* Uma instância do phpMyAdmin, acessível em: http://localhost:8080

### 2. Rodar a aplicação NodeJS
Após o banco estar rodando, instale as dependências (se ainda não fez):

```bash
npm install
```

E execute o projeto em modo desenvolvimento:
```bash
npm run dev
```
A aplicação estará disponível em: http://localhost:3000

## 🖥 Acessos
Aplicação NodeJS → http://localhost:3000
phpMyAdmin → http://localhost:8080