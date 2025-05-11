# API de Produtos

Uma aplicação **Spring Boot** para gerenciamento de produtos, desenvolvida com **Java 17** e **Maven**. Esta API fornece endpoints para criar e listar produtos, com integração a um banco de dados PostgreSQL.

---

## 📋 Funcionalidades

- **API RESTful**: Endpoints para gerenciamento de produtos.
- **Integração com Banco de Dados**: Utiliza PostgreSQL para persistência de dados.
- **Spring Data JPA**: Simplifica as operações com o banco de dados.
- **Lombok**: Reduz o código boilerplate.
- **Spring Boot Actuator**: Fornece endpoints para monitoramento e gerenciamento.
- **DevTools**: Permite hot-reloading durante o desenvolvimento.

---

## 🛠️ Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 3.1.4**
- **Maven**
- **PostgreSQL**
- **Lombok**

---

## 📂 Estrutura do Projeto

```plaintext
src/main/java/com/exemplo/produto
├── controller
│   └── ProdutoController.java   # Gerencia as requisições HTTP
├── entity
│   └── Produto.java             # Representa a entidade Produto
├── repository
│   └── ProdutoRepository.java   # Repositório JPA para operações no banco de dados
└── ProdutoApplication.java      # Classe principal da aplicação

