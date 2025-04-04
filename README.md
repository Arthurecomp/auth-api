# Authetication API

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-005EB8?style=for-the-badge&logo=flyway&logoColor=white)

---
#### Este projeto foi desenvolvido com o objetivo de proporcionar um aprendizado prático sobre a configuração e utilização de tokens JWT (JSON Web Tokens) para controle de autenticação em aplicações.

Utilizada as seguintes tecnologias:

* MySQL: Sistema de gerenciamento de banco de dados relacional para armazenar dados de forma estruturada.
* Flyway: Ferramenta de migração de banco de dados que facilita o versionamento e a aplicação de alterações no esquema do banco.
* Java: Linguagem de programação utilizada para desenvolver a lógica do aplicativo.
* Spring Boot: Framework que simplifica o desenvolvimento de aplicações Java, permitindo a criação de serviços web de forma ágil e eficiente.
* Spring Security: Módulo do Spring que fornece funcionalidades de segurança, incluindo autenticação e autorização.
Este projeto visa não apenas a prática técnica, mas também a compreensão dos princípios fundamentais de segurança em aplicações web. 


---
## Endpoints da API
```
GET /product - Retrieve a list of all products. (all authenticated users)

POST /product - Register a new product (ADMIN access required).

POST /auth/login - Login into the App

POST /auth/register - Register a new user into the App
```

---
## Autenticação

```
USER -> apel de usuário padrão para usuários logados.
ADMIN -> Papel de administrador para gerenciar parceiros (registrar novos produtos).
```
