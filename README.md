# Projeto-gerenciamento-contatos-api
API RESTful para gerenciamento de contatos, desenvolvida em Java com Spring Boot e PostgreSQL. Permite criar, atualizar, listar e excluir contatos, com hospedagem no Railway.

## 🔧 Tecnologias

- Java 17
- Spring Boot
- JPA
- PostgreSQL
- Swagger
- Deploy: Visual Studio Code + Railway

## 📌 Endpoints

- `GET /contato` — Listar todos os contatos
- `POST /contato` — Cadastrar novo contato
- `PUT /contato/{id}` — Atualizar contato completo
- `PATCH /contato/{id}` — Atualizar contato parcialmente
- `DELETE /contato/{id}` — Excluir contato

## 🗄️ Configuração do Banco de Dados
Crie um banco no PostgreSQL e ajuste o arquivo `src/main/resources/application.properties`:

```properties
spring.datasource.url=
spring.datasource.username=
spring.datasource.password=
```

## 📍 Como Rodar

```bash

# Clone o repositório
git clone https://github.com/GuilhermeLucera/projeto-gerenciamento-contatos-api

# Entre no diretório
cd projeto-gerenciamento-contatos-api

# Instale as dependências e compile
mvn clean install

# Executar localmente
mvn spring-boot:run
```

## 🌐 Acesso após rodar
Após iniciar a aplicação, você poderá acessar:

- **Swagger (documentação):** [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)

[Guilherme Lucera / [LinkedIn](https://www.linkedin.com/in/guilherme-lucera-49997b213/)]
