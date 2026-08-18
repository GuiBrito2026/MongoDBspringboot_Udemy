# Blog API

API RESTful para gerenciamento de posts de um blog, desenvolvida durante meus estudos de **Java e Spring Boot**, com base no curso do **Nelio Alves**.

O projeto teve como objetivo aprofundar os conhecimentos em desenvolvimento backend e explorar a utilização do **MongoDB** como banco de dados NoSQL.

## 🎯 Objetivos

- Desenvolver uma API RESTful com Spring Boot
- Trabalhar com MongoDB e persistência de dados
- Implementar operações CRUD
- Trabalhar com tratamento de exceções
- Aprender a interpretar mensagens de erro e realizar debugging
- Aprofundar os conhecimentos sobre o funcionamento do Spring Boot

## 🛠️ Tecnologias utilizadas

- **Java**
- **Spring Boot**
- **Spring Data MongoDB**
- **MongoDB**
- **Maven**
- **Postman**

## 🏗️ Arquitetura

A aplicação utiliza uma arquitetura em camadas para separar as responsabilidades:

```text
src
└── main
    └── java
        └── com.example.workshopmongo
            ├── config
            ├── resources
            ├── domain
            │   ├── entities
            │   └── repositories
            └── services
