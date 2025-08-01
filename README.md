<h1 align="center">Bookrate</h1>

![GitHub Org's stars](https://img.shields.io/github/license/Artur-Neves/Gerenciamento-escolar_java)
&nbsp;
![Badge Finalizado](http://img.shields.io/static/v1?label=STATUS&message=finalizado)

Este é um projeto com fins acadêmicos, desenvolvido para praticar conceitos de arquitetura de microsserviços utilizando **Java**, **Spring Boot** e tecnologias modernas como **Docker**, **GitHub Actions** e **API Gateway**. O projeto simula um sistema de gerenciamento de livros, onde diversos microsserviços se comunicam entre si.

O repositório principal contém os seguintes serviços:

- [`api-gateway`](https://github.com/Artur-Neves/bookrate-api-gatewa)
- [`eureka-server`](https://github.com/Artur-Neves/bookrate-eureka-server)
- [`book-service`](https://github.com/Artur-Neves/book-service)
- [`exchange-service`](https://github.com/Artur-Neves/exchange-service)

<br>

## 🧱 Arquitetura do Projeto

O projeto segue a arquitetura de microsserviços, com os seguintes papéis definidos:

- `api-gateway`: Centraliza todas as requisições externas.
- `eureka-server`: Registro e descoberta de serviços.
- `book-service`: Gerencia o catálogo e avaliações de livros.
- `exchange-service`: Responsável por conversões ou dados auxiliares externos.

Todos os serviços são **containerizados com Docker** e orquestrados localmente para fins de desenvolvimento.

<br>

## 🚀 Tecnologias principais
<div align="center">

| Categoria          | Tecnologias Utilizadas                       |
|--------------------|-----------------------------------------------|
| Linguagem          | Java 17                                       |
| Framework          | Spring Boot, Spring Cloud                    |
| Comunicação        | REST API, API Gateway, Eureka Discovery      |
| Documentação       | Swagger / Springdoc OpenAPI                  |
| Containerização    | Docker                                        |
| Logs               | Resilience4j, Zipkin                          |
| CI/CD              | GitHub Actions                                |
| Versionamento      | Git + GitHub                                  |

</div>

