# 🚀 Web services project

O projeto "workshop-springboot3-jpa" é uma aplicação desenvolvida em Java utilizando o framework Spring Boot 3 e JPA/Hibernate. Seu objetivo é gerenciar entidades como produtos, pedidos e pagamentos, implementando operações CRUD (Criar, Ler, Atualizar e Deletar) 
e estabelecendo relacionamentos entre essas entidades. Para o ambiente de desenvolvimento, é utilizado o banco de dados em memória H2, enquanto para produção, o PostgreSQL é configurado. 
O projeto segue uma arquitetura em camadas, incluindo recursos RESTful, serviços e repositórios, promovendo uma separação clara de responsabilidades e facilitando a manutenção e escalabilidade da aplicação.

## 📌 Tecnologias Utilizadas

- Java
- Spring Boot
- PostgreSQL
- JPA/Hibernate
- Maven

## 🛠️Funcionalidades principais:

**Operações da APIREST **: O sistema permite operações CRUD. Por meio de endpoints da API o usuário consegue realizar operações como criação, leitura, atualização e exclusão. Sendo essas operações aplicadas as entidades como pedidos, usuários e produtos.

## ⚙️ Como Rodar o Projeto
### 🔧 Pré-requisitos
- Ter o **Java 17** ou superior instalado.
- Ter o **Maven** configurado.
- Ter um banco de dados PostgreSQL rodando.
- Ter o **Git** instalado para clonar o repositório.

### 🚀 Passos para rodar
1. Clone o repositório:
- https://github.com/Felipeleres/workshop-springboot3-jpa.git
   cd workshop-springboot3-jpa
   
2. Configure o banco de dados no application.properties:

- spring.datasource.url=jdbc:postgresql://localhost:5432/seu_banco
- spring.datasource.username=seu_usuario
- spring.datasource.password=sua_senha
- spring.datasource.driver-class-name=org.postgresql.Driver
- spring.jpa.database-platform=org.hibernate.dialect.PostgreSQLDialect
- spring.jpa.hibernate.ddl-auto=update

3. Execute o projeto com:
- mvn spring-boot:run
4. Acesse a API no navegador ou via Postman:
- http://localhost:8080



 
