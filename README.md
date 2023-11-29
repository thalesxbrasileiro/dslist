# Projeto de Listagem de Jogos em Java com Spring Boot

Este projeto é um backend desenvolvido em Java com Spring Boot, destinado à listagem de jogos com a capacidade de reordená-los conforme desejado. O projeto abrange diversos aspectos fundamentais do desenvolvimento de software, incluindo arquitetura em camadas, persistência de dados, lógica de negócios e boas práticas de programação.

## Modelo conceitual
![dslist-model](https://github.com/thalesxbrasileiro/dslist/assets/71534326/f56108ae-da3d-4137-ac2e-6d2b59b2abca)

# Tecnologias e técnicas utilizadas

## Backend
- Java
- Spring Boot
- Maven
- JPA / Hibernate
- API RESTful
- Padrão em Camadas
- Modelo de Domínio
- Banco de dados:
  - H2 (testes)
  - Postgres (homologação e produção)
  
## Implantação em produção
- Backend: Railway
- Banco de dados: Postgresql

## Como Executar o Projeto 
- **Localmente:** `http://localhost:8080/h2-console`
- **Homologação:** `http://localhost:5050/`
- **Produção:** Endereço da plataforma em nuvem utilizado.

### Script Docker Compose
https://gist.github.com/thalesxbrasileiro/759617b373719132ffbec7d62007d08d.js
