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
* Coloque o nome do servidor na tag [SERVER]
* Coloque o número da porta na tag [PORT]
* Coloque o banco de dados de nome de usuário na tag [USER]
* Coloque o banco de dados de senha na tag [PASSWORD]
* Por fim, crie e execute o aplicativo

## Migrações do MySql:
* Abra o console do gerenciador de pacotes
* Altere o projeto padrão para Aurora.Infra.Data
* Execute o comando "Add-Migration [NAME OF YOUR MIGRATION]"
* Execute o comando "Update-Database"
* Para obter mais informações sobre este projeto, consulte este artigo . [artigo](https://medium.com/@alexalves_85598/criando-uma-api-em-net-core-baseado-na-arquitetura-ddd-2c6a409c686).

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




