# 🚀 Curso Completo de Web APIs com ASP.NET Core

![.NET Core](https://img.shields.io/badge/.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![EF Core](https://img.shields.io/badge/Entity%20Framework-512BD4?style=for-the-badge&logo=.net&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)

## 📖 Sobre o Projeto

Este repositório contém o código-fonte desenvolvido ao longo do curso de **Criação de APIs REST com ASP.NET Core**. O projeto ("ApiCatalogo") tem como objetivo ensinar desde os fundamentos do protocolo HTTP até a implementação de uma arquitetura robusta, segura e escalável utilizando o ecossistema .NET.

O foco não é apenas a criação da API, mas também a implementação de boas práticas de design de software e o consumo destes dados em diferentes plataformas.

## 🛠️ Tópicos Abordados

### Fundamentos & Core
- Conceitos de REST, JSON e Verbos HTTP.
- Criação e configuração de Web APIs no Visual Studio.
- Roteamento, Action Filters e Métodos Assíncronos (Async/Await).
- Logging e Tratamento Global de Erros.

### Persistência de Dados
- **Entity Framework Core**: Abordagem Code-First.
- **Migrations**: Versionamento do esquema de banco de dados.
- Paginação de dados eficiente.

### Arquitetura & Design Patterns
- **Repository Pattern**: Abstração da camada de acesso a dados.
- **Unit of Work**: Gerenciamento de transações.
- **AutoMapper**: Mapeamento objeto-objeto (Domain to DTO).

### Segurança & Produção
- **JWT (JSON Web Token)**: Autenticação e Autorização (Login/Registro).
- **CORS**: Habilitação de requisições Cross-Origin.
- **Swagger/OpenAPI**: Documentação e teste da API.
- Versionamento de API.

## 🔌 Consumo da API (Clientes)

O projeto demonstra a versatilidade da API consumindo-a através de diferentes tecnologias:

1.  **Angular**: Aplicação Single Page Application (SPA).
2.  **Windows Forms**: Aplicação Desktop clássica.
3.  **Integrações Avançadas**: Implementação com **OData** e **GraphQL**.

## 🚀 Como Executar

### Pré-requisitos
* [.NET SDK](https://dotnet.microsoft.com/download) instalado.
* SQL Server (ou LocalDB).
* Visual Studio 2022 ou VS Code.

### Passos para rodar
1.  Clone o repositório:
    ```bash
    git clone [https://github.com/raphael-aciardi/ApiCatalogo.git](https://github.com/raphael-aciardi/ApiCatalogo.git)
    ```
2.  Navegue até a pasta do projeto e configure a string de conexão no arquivo `appsettings.json`.
3.  Execute as migrações para criar o banco de dados:
    ```bash
    dotnet ef database update
    ```
4.  Execute a aplicação:
    ```bash
    dotnet run
    ```

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais.
