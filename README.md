# Spring Boot CRUD Study Repository
This repository was created to store my learning while developing a CRUD (Create, Read, Update, Delete) application using the Spring Boot framework. The objective is to understand the basic concepts of Spring Boot and how to implement CRUD operations efficiently.

# Prerequisites
Make sure you have the following software installed on your machine before you begin:
* Java JDK 17 or higher
* Spring Boot 3.2.1 or higher
*Maven
* IDE of your choice (recommended: IntelliJ IDEA or Eclipse)

# Dependencies Used
If you don't use intellij idea, install the dependencies using Spring Initializr
*SpringWeb
* Spring HATEAOS
* Spring Data JPA
* Database of your choice (recommended for studying H2 DataBase or PostgreSQL Driver)
* Validation
* Lombok

# Project Structure
The project is structured as follows:
* controller: Contains classes responsible for handling HTTP requests.
* model: Defines the system entities.
* repository: Provides access to data through CRUD operations.
* service: Contains the application's business logic.
* CrudApplication.java: Spring Boot application main class.
* application.properties: Spring Boot configuration file.

# Database Configuration
Update the database settings in the 'application.properties' file with information specific to your environment.

--spring.datasource.url=jdbc":mysql:"(database ex: h2 or postgreSQl)//localhost:3306/seu_banco_de_dados--

--spring.datasource.username=your_username--

--spring.datasource.password=your_password--

# Endpoints
GET /api/entities: Returns all entities.

GET /api/entities/{id}: Returns a specific entity by ID.

POST /api/entities: Creates a new entity.

PUT /api/entities/{id}: Updates an existing entity by ID.

DELETE /api/entities/{id}: Deletes an entity by ID.

# CRUD
Study and implementation of a CRUD

C: Create - create a new record

A: Read - read/display information from a record

U: Update - update registry data

D: Delete - deletes a record

# Running the Application
Clone this repository: git clone https://github.com/seu-usuario/spring-boot-crud-study.git

Navigate to the project directory: cd spring-boot-crud-study

Run the application: mvn spring-boot:run

The application will be available at http://localhost:8080.
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
# Spring Boot CRUD Study Repository
Este repositório foi criado para armazenar meu aprendizado ao desenvolver um aplicativo CRUD (Create, Read, Update, Delete) usando o framework Spring Boot. O objetivo é entender os conceitos básicos do Spring Boot e como implementação das operações CRUD de forma eficiente.

# Pré-requisitos
Certifique-se de ter os seguintes softwares instalados em sua máquina antes de começar:
* Java JDK 17 ou superior
* Spring Boot 3.2.1 ou superior
* Maven
* IDE de sua escolha (recomendado: IntelliJ IDEA ou Eclipse)

# Dependencias Utilizadas
Caso não use o intellij idea, instale as dependencias pelo Spring Initializr
* Spring Web
* Spring HATEAOS
* Spring Data JPA
* Banco de dados da sua preferência (recomendado para estudo H2 DataBase ou PostgreSQL Driver)
* Validation
* Lombok

# Estrutura do Projeto
O projeto está estruturado da seguinte forma:
* controller: Contém classes responsáveis por lidar com as requisições HTTP.
* model: Define as entidades do sistema.
* repository: Fornece acesso a dados por meio de operações CRUD.
* service: Contém a lógica de negócios da aplicação.
* CrudApplication.java: Classe principal do aplicativo Spring Boot.
* application.properties: Arquivo de configuração do Spring Boot.

# Configuração do Banco de Dados
Atualize as configurações do banco de dados no arquivo 'application.properties' com as informações específicas do seu ambiente.

--spring.datasource.url=jdbc":mysql:"(banco de dados ex: h2 ou postgreSQl)//localhost:3306/seu_banco_de_dados--

--spring.datasource.username=seu_usuario--

--spring.datasource.password=sua_senha--

# Endpoints
GET /api/entities: Retorna todas as entidades.

GET /api/entities/{id}: Retorna uma entidade específica por ID.

POST /api/entities: Cria uma nova entidade.

PUT /api/entities/{id}: Atualiza uma entidade existente por ID.

DELETE /api/entities/{id}: Exclui uma entidade por ID.

# CRUD
Estudo e implementação de um CRUD 

C: Create (criar) - criar um novo registro

R: Read (ler) - ler /exibir as informações de um registro

U: Update (atualizar) - atualizar os dados do registro

D: Delete (apagar) - apaga um registro 

# Executando a Aplicação
Clone este repositório: git clone https://github.com/seu-usuario/spring-boot-crud-study.git

Navegue até o diretório do projeto: cd spring-boot-crud-study

Execute o aplicativo: mvn spring-boot:run

A aplicação estará disponível em http://localhost:8080.
  
