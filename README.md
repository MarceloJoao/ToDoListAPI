# ToDo List API - Gerenciamento de Tarefas

## 🚀 Sobre o Projeto

Este é um projeto de API RESTful construído com **Spring Boot** para gerenciar tarefas (To-Do List), com foco na autenticação de usuários e persistência de dados. A API permite a criação de usuários e a gestão de tarefas vinculadas a esses usuários.

### Funcionalidades Implementadas

- **Autenticação:** Uso do filtro customizado para autenticação **Basic Auth** nas rotas de tarefa.
- **Segurança:** Criptografia de senhas utilizando **BCrypt** (at.favre.lib) para armazenamento seguro.
- **CRUD (Create):** Criação de usuários e tarefas.
- **Listagem:** Listagem de tarefas por usuário autenticado.
---
## 🛠️ Tecnologias Utilizadas

As seguintes ferramentas e tecnologias foram usadas na construção do projeto:

| **Java** | 21 (LTS) | Linguagem principal do projeto. |
| **Spring Boot** | 3.x | Framework principal para construção da API. |
| **Spring Data JPA** | 3.x | Facilita a interação com o banco de dados. |
| **Hibernate** | 6.x | Implementação de JPA. |
| **H2 Database** | Embedded | Banco de dados em memória para desenvolvimento e testes. |
| **Lombok** | 1.18.x | Simplifica o código com anotações (Getters/Setters). |
| **BCrypt Lib** | 0.10.x | Biblioteca para hash de senhas. |

---

