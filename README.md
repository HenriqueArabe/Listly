# Listly

**Listly** é uma aplicação web desenvolvida para auxiliar usuários na organização de compras, permitindo criar e gerenciar listas de produtos de forma prática e personalizada. O projeto foi construído como parte da disciplina de Engenharia de Software da Universidade Presbiteriana Mackenzie.

## 📋 Funcionalidades

- Cadastro e login de usuários
- Criação, edição, exclusão e visualização de listas
- Adição de produtos com nome, descrição, preço, categoria, prioridade e link
- Organização dos itens por critérios definidos pelo usuário
- Edição e remoção de produtos
- Visualização e edição de perfil do usuário
- Interface intuitiva e responsiva

## 🧰 Tecnologias Utilizadas

### Frontend
- [ReactJS](https://reactjs.org/)
- HTML5, CSS3, JavaScript

### Backend
- [Java 21](https://www.oracle.com/br/java/)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [SQLite](https://www.sqlite.org/index.html)

### DevOps
- [Swagger](https://swagger.io/) (documentação de API)
- [Jenkins](https://www.jenkins.io/) (integração contínua)
- [AWS EC2](https://aws.amazon.com/ec2/) (implantação da API)

## 📦 Arquitetura

O sistema segue uma arquitetura em camadas:

- Interface (React)
- Controladores (Spring Boot)
- Camada de Domínio
- Camada de Persistência (SQLite)

## 🚀 Como Rodar o Projeto

### Pré-requisitos

- Java 21
- Node.js e npm
- Docker (opcional para rodar a API)
- Jenkins (opcional para CI/CD)

### Backend

```bash
cd backend
./mvnw spring-boot:run

Frontend
bash
Copy
Edit
cd frontend
npm install
npm start
Acesse em: http://localhost:3000

🛠️ Contribuições
Este projeto foi desenvolvido em ambiente acadêmico e não está aberto a contribuições externas, mas forks são bem-vindos para fins de aprendizado e portfólio.

👨‍💻 Autores
Antonio Carlos Sciamarelli Neto

Henrique Árabe Neres de Farias

Joaquim Rafael Mariano Prieto Pereira

🔗 Links
🔗 Repositório original

🌐 Deploy Frontend (Vercel)

▶️ Vídeo demonstrativo
