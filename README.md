<h1 align="center">Bookrate - Versão Kubernetes</h1>

![GitHub Org's stars](https://img.shields.io/github/license/Artur-Neves/Gerenciamento-escolar_java)
&nbsp;
![Badge Finalizado](http://img.shields.io/static/v1?label=STATUS&message=finalizado)

Este é um projeto acadêmico que demonstra uma arquitetura de microsserviços em **Java** e **Spring Boot**, agora orquestrada em **Kubernetes**. Nessa versão, **API Gateway** e **Eureka Server** não são mais necessários, pois o próprio Kubernetes fornece service discovery e balanceamento de carga.

---

## 🎯 Visão Geral

O Bookrate simula um sistema de gerenciamento de livros com conversão de preços em diferentes moedas.  
Os microsserviços restantes — agora executados em Pods no cluster Kubernetes — são:

- [`book-service`](https://github.com/Artur-Neves/book-service/tree/branch-update-config-with-kubernetes)  
- [`exchange-service`](https://github.com/Artur-Neves/exchange-service/tree/branch-update-config-with-kubernetes)  

Cada serviço contém um diretório `k8s/` com manifestos YAML para Deployments, Services, ConfigMaps, Secrets e volumes persistentes (quando aplicável).
<br>

## 🚀 Tecnologias principais
<div align="center">

<p align="center"> 
  <table> 
      <thead> 
        <tr> <th>Categoria</th> <th>Tecnologias Utilizadas</th> </tr> 
      </thead> 
    <tbody> 
      <tr> <td>Linguagem</td> <td>Java 17</td> </tr> 
      <tr> <td>Framework</td> <td>Spring Boot 3.5.3</td> </tr> 
      <tr> <td>Banco de Dados</td> <td>MySQL + Flyway</td> 
      </tr> <tr> <td>Persistência</td> <td>Spring Data JPA</td> 
      </tr> <tr> <td>Containerização</td> <td>Docker</td> </tr> 
      <tr> <td>Orquestração</td> <td>Kubernetes (Deployments, Services, ConfigMap, Secret, PersistentVolume)</td> 
      </tr> <tr> <td>Configuração</td> <td>ConfigMap & Secret</td> </tr> 
      <tr> <td>Observabilidade</td> <td>Spring Boot Actuator</td> </tr> 
      <tr> <td>Documentação</td> <td>Springdoc OpenAPI (Swagger UI)</td> </tr> 
      <tr> <td>CI/CD</td> <td>GitHub Actions</td> </tr> 
      <tr> <td>Versionamento</td> <td>Git + GitHub</td> </tr> 
    </tbody> 
  </table> 
  </p>

</div>

