# ✅ API de Gerenciamento de Tarefas

API REST desenvolvida em **ASP.NET Core (.NET 9)** para gerenciamento de tarefas com autenticação baseada em **JSON Web Token (JWT)**.

O projeto foi desenvolvido seguindo uma arquitetura em camadas, utilizando **Entity Framework Core**, **SQL Server** e autenticação segura com **JWT** e **BCrypt**, demonstrando boas práticas de desenvolvimento back-end.

---

## 🚀 Funcionalidades

- 👤 Cadastro de usuários
- 🔐 Login com autenticação JWT
- 📝 CRUD completo de tarefas
- 🔒 Rotas protegidas por autenticação
- 🔑 Hash seguro de senhas com BCrypt
- 💾 Persistência de dados em SQL Server
- 📖 Documentação da API com Scalar/OpenAPI

---

## 🛠 Tecnologias Utilizadas

- C#
- ASP.NET Core (.NET 9)
- Entity Framework Core
- SQL Server
- JWT Authentication
- BCrypt
- Scalar (OpenAPI)

---

## 📂 Estrutura do Projeto

```text
TarefasAPI
│
├── Controllers
│   ├── AuthController.cs
│   └── TarefasController.cs
│
├── Data
│   └── AppDbContext.cs
│
├── Models
│
├── Repositories
│
├── Services
│
├── Migrations
│
├── Program.cs
├── appsettings.json
└── appsettings.Development.json
```

---

## 🏗 Arquitetura

```text
Cliente
    │
    ▼
Controllers
    │
    ▼
Services
    │
    ▼
Repositories
    │
    ▼
Entity Framework Core
    │
    ▼
SQL Server
```

---

## 🔐 Segurança

A API implementa mecanismos de segurança para proteger os recursos da aplicação.

- Autenticação utilizando JWT
- Autorização por token
- Senhas armazenadas utilizando BCrypt
- Endpoints protegidos contra acesso não autorizado

---

## ▶️ Como executar

### Clone o repositório

```bash
git clone https://github.com/Rester-fullstack/aspnetcore-task-api.git
```

Entre na pasta do projeto

```bash
cd tarefas-api-dotnet
```

Restaure os pacotes

```bash
dotnet restore
```

Execute a aplicação

```bash
dotnet run
```

---

## 📄 Documentação da API

Após iniciar a aplicação, acesse:

```text
http://localhost:5168/scalar/v1
```

A documentação permite testar todos os endpoints diretamente pelo navegador.

---

## 📸 Screenshots

Adicione imagens da aplicação, por exemplo:

- Tela do Scalar
- Login
- Cadastro
- Endpoints protegidos
- CRUD de tarefas

---

## 📚 Objetivos do Projeto

Este projeto foi desenvolvido para praticar conceitos fundamentais do desenvolvimento back-end com .NET, incluindo:

- Desenvolvimento de APIs REST
- ASP.NET Core
- Entity Framework Core
- SQL Server
- JWT Authentication
- BCrypt
- Repository Pattern
- Arquitetura em camadas
- Organização de projetos
- Boas práticas de desenvolvimento

---

## 👩‍💻 Desenvolvedora

**Ester da Costa Batista**

Desenvolvedora Full Stack

### Tecnologias

- C#
- .NET
- React
- SQL Server
- APIs REST
- Entity Framework Core

GitHub:

https://github.com/Rester-fullstack

---

## 📄 Licença

Este projeto foi desenvolvido para fins de estudo e portfólio.
