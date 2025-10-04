# ToDo List API - Gerenciamento de Tarefas

## 🚀 Sobre o Projeto

Este é um projeto realizado durante um mini curso de Java da Rockeseat, onde foi realizada uma API RESTful construído com **Spring Boot** para gerenciar tarefas (To-Do List), com foco na autenticação de usuários e persistência de dados. A API permite a criação de usuários e a gestão de tarefas vinculadas a esses usuários.

### Funcionalidades Implementadas

- **Autenticação:** Uso do filtro customizado para autenticação **Basic Auth** nas rotas de tarefa.
- **Segurança:** Criptografia de senhas utilizando **BCrypt** (at.favre.lib) para armazenamento seguro.
- **CRUD (Create):** Criação de usuários e tarefas.
- **Listagem:** Listagem de tarefas por usuário autenticado.
---
## 🛠️ Tecnologias Utilizadas

As seguintes ferramentas e tecnologias foram usadas na construção do projeto:

**Java** - Linguagem principal do projeto
**Spring Boot** - Framework principal para construção da API
**Spring DataJPA** - Facilita a interação com o banco de dados
**Hibernate** - Implementação de JPA
**H2 DataBase** - Banco de dados em memória para desenvolvimento e testes
**Lombok** - Simplifica o código com anotações
**BCrypt Lib** - Biblioteca para hash de senhas

---

