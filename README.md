![Aurora Project](https://repository-images.githubusercontent.com/128673011/f6ebdd80-b6da-11ea-94bb-9d141944b257)

# O que é o projeto Aurora?
É um projeto de código aberto, escrito em .NET Core, atualmente na versão 3.1.

O objetivo do projeto é mostrar que é possível criar uma arquitetura mais simples do que outras e utilizando alguns conceitos como DDD (Design Driven Design).

## Proposta de negócio:
Este projeto é uma gestão simples de EPI (Equipamentos de Proteção Individual). A ideia principal é cadastrar trabalhadores e EPIs e, com esses dados, permitir a transferência de EPIs para um trabalhador. Além disso, este sistema permite que você veja todos os EPIs e quem possui um EPI e avise se o EPI está prestes a expirar.



## Como usar:
Clone este projeto em sua máquina
Use a string de conexão padrão ou: 2.1. Instale e configure o MySql , se desejar. 
2.2. Informe a string de conexão em [Mysql](Aroura.Infra.Data/Context/MySqlContext.cs), se necessário
Coloque o nome do servidor na tag [SERVER]
Coloque o número da porta na tag [PORT]
Coloque o banco de dados de nome de usuário na tag [USER]
Coloque o banco de dados de senha na tag [PASSWORD]
Por fim, crie e execute o aplicativo

## Migrações do MySql:
Abra o console do gerenciador de pacotes
Altere o projeto padrão para Aurora.Infra.Data
Execute o comando "Add-Migration [NAME OF YOUR MIGRATION]"
Execute o comando "Update-Database"
Para obter mais informações sobre este projeto, consulte este artigo . [artigo](https://medium.com/@alexalves_85598/criando-uma-api-em-net-core-baseado-na-arquitetura-ddd-2c6a409c686).

## Tecnologias implementadas:
* ASP.NET Core 3.1 (com .NET Core 3.1)
* Entity Framework Core 3.1.5
* Validação Flunt 1.0.5
* Swagger UI 5.5.0
* Conexão de banco de dados MySql
* .NET Core Native DI
* SpecFlow para BDD
* Ações GitHub

## Architecture:
* Layer architecture
* S.O.L.I.D. principles
* Clean Code
* Domain Validations
* Domain Notifications
* Domain Driven Design
* Repository Pattern
* Notification Pattern
* Mapper by Extension Methods
* Value Types
* BDD (Behavior Driven Development)

![Architecture](https://miro.medium.com/max/962/1*qpHCIA7RDfW89KtSUXGJog.png)

## News:
**v1.4 --- 2020-09-28**
* CI/CD by GitHub Actions
* Include integration tests using BDD with SpecFlow
    * scenario of register a worker
    * scenario of update a worker
* Bug corrections

**v1.3 --- 2020-07-30**
* Changed some Primitive Types to Value Types
* Changed the business idea principle

**v1.2 --- 2020-06-30**
* Implemented Notification Pattern
* Implemented Domain Validations and Notifications
* Using some concepts of Clean Architecture
    * Entities
    * Interface Adapters
* Changed the framework validations to Flunt
* Using mapper by extension methods

**v1.1 --- 2020-06-24**
* Updated the project name
* Updated the project's SDK to .NET Core 3.1 version
* Added the Swagger framework to document the API
* Corrections to end-points
* Published in [Azure](http://aurora-project.azurewebsites.net/swagger/index.html)

**v1.0 --- 2018-06-09**
* Create the project in .NET Core 2.0 version
* Structured the project on layer architecture 
* Used the Service layer to business rules
* Used the FluentValidation library
* Configured the connection to MySql database
* Used EntityFramework

## Why Aurora?
The name Aurora came from the natural event called Aurora Borealis. It is a scientific event described by the interaction between the earth's magnetic layer and energized particles from the solar wind.

A curiosity about such an event is that what we see in photographs is not always the same image that is seen live.

For more information, look this [link](https://www.hipercultura.com/fenomenos-naturais/).

## We're online!
See the project in [Azure](http://aurora-project.azurewebsites.net/swagger/index.html).


