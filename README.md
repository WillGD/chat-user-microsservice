# 🎮 Chat-User-Microservice Application 🚀

Bem-vindo ao projeto **Chat-User-Microservice**! 🎉

Esta aplicação é um sistema baseado em **microsserviços** utilizando **Java Spring Boot** com **WebSockets** para comunicação em tempo real (chat), **JWT** para autenticação e autorização, e **Docker** para facilitar a construção e deploy da aplicação. A aplicação é dividida em dois microsserviços principais: **User** e **Chat**, com diferentes bancos de dados (MySQL para o serviço de usuário e PostgreSQL para o serviço de chat).

## 🚀 Funcionalidades

- **Autenticação com JWT**: O microsserviço de **usuário** permite a criação e autenticação de usuários utilizando **JSON Web Tokens (JWT)** para garantir que apenas usuários autenticados possam interagir com o sistema.
- **Chat em Tempo Real**: O microsserviço de **chat** utiliza **WebSockets** para permitir uma comunicação em tempo real entre usuários.
- **Bancos de Dados**:
  - **MySQL** para o serviço de **usuário**.
  - **PostgreSQL** para o serviço de **chat**.
- **Docker**: Utilização de **Docker** para containerizar ambos os microsserviços e facilitar o desenvolvimento, testes e deploy.

---

## 📦 Tecnologias Usadas

- **Java 17+**
- **Spring Boot 3.x**
- **WebSockets**
- **JWT (JSON Web Tokens)**
- **MySQL** (para o microsserviço de **usuário**)
- **PostgreSQL** (para o microsserviço de **chat**)
- **Docker** para containerização
- **Spring Data JPA** para persistência de dados
- **Docker Compose** para orquestrar os containers

---

## 🔧 Pré-requisitos

Antes de executar a aplicação, certifique-se de ter os seguintes pré-requisitos instalados em sua máquina:

- **Java 17**
- **Docker** e **Docker Compose**
- **Maven** 
- **IDE** (como IntelliJ IDEA & VSCode.)

---

## 🚀 Como Rodar a Aplicação

### Passo 1: Clonar o Repositório

Clone o repositório do projeto:

```bash
git clone [https://github.com/seu-usuario/chat-user-microservice.git](https://github.com/WillGD/chat-user-microsservice/edit/main/README.md)
