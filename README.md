# API REST - Desafio DIO

## Descrição
Este projeto é um exemplo de padrões de projeto utilizando Spring Boot, desenvolvido como parte de um desafio da Digital Innovation One (DIO). O objetivo é demonstrar boas práticas no desenvolvimento de APIs REST.

## Tecnologias Utilizadas
- **Java 21**
- **Spring Boot 3.4.4**
- **Banco de Dados H2**
- **Swagger para Documentação da API**

## Configuração do Ambiente

### Pré-requisitos
Antes de iniciar, certifique-se de ter instalado:
- Java 21

### Clonando o Repositório
```sh
git clone https://github.com/Rafael-Feitosa-santos/desafio-DIO---API-REST---Design-Patterns.git
cd desafio-DIO-API-rest
```

## Testando a API com Swagger
A documentação interativa da API pode ser acessada via Swagger:

- URL: `http://localhost:8080/swagger-ui.html`

## Endpoints Principais
A API expõe alguns endpoints REST. Para testar, utilize o Swagger, Postman ou Curl.

- `GET /api/exemplo` - Retorna uma lista de exemplos.
- `POST /api/exemplo` - Cria um novo exemplo.
- `PUT /api/exemplo/{id}` - Atualiza um exemplo existente.
- `DELETE /api/exemplo/{id}` - Remove um exemplo.

