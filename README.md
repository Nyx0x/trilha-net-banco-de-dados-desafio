# 🚀 Desafio: Sistema Gerenciador de Tarefas com API e EF Core

## 📝 Descrição
Este projeto faz parte do desafio do módulo de **API e Entity Framework** da **Trilha .NET** da [DIO](https://www.dio.me/).
O objetivo foi construir um CRUD completo para um sistema de gerenciamento de tarefas (Tasks), aplicando os conceitos de rotas, verbos HTTP e persistência de dados utilizando ORM.

## 🛠️ Tecnologias Utilizadas
* **C# / .NET 8**
* **Entity Framework Core** (ORM)
* **SQL Server** (Banco de Dados em Docker)
* **Swagger** (Documentação e Testes de API)

## ⚙️ Funcionalidades (Endpoints)
A API permite o gerenciamento completo de tarefas com os seguintes endpoints:
- `POST /Tarefa` - Cria uma nova tarefa.
- `GET /Tarefa/{id}` - Busca uma tarefa pelo ID.
- `GET /Tarefa/ObterTodos` - Lista todas as tarefas cadastradas.
- `GET /Tarefa/ObterPorTitulo` - Busca tarefas por palavra-chave no título.
- `GET /Tarefa/ObterPorData` - Busca tarefas pela data exata.
- `GET /Tarefa/ObterPorStatus` - Filtra tarefas por status (Pendente ou Finalizada).
- `PUT /Tarefa/{id}` - Atualiza os dados de uma tarefa existente.
- `DELETE /Tarefa/{id}` - Exclui uma tarefa do banco de dados.

## 🚀 Como Executar
1. Tenha o SDK do .NET 8 e o SQL Server instalados.
2. Clone este repositório.
3. Altere a `ConnectionStrings` no arquivo `appsettings.json` para o seu banco local.
4. Rode as migrations com `dotnet ef database update`.
5. Inicie a API com `dotnet run` e acesse a interface do Swagger no navegador.

---
<p align="center">
  Feito com 💀 e C# por <a href="https://github.com/Nyx0x">Nyx</a>
</p>
