# RH Queens - Frontend

![Badge](https://img.shields.io/badge/react-18.2.0-blue)
![Badge](https://img.shields.io/badge/api-integrada-success)

Este é o repositório **frontend** do projeto **RH Queens**, uma plataforma para gestão de talentos e profissionais com foco em diversidade, inclusão e equidade. Desenvolvido com **React** e integrado ao backend Java/Spring Boot disponível neste repositório: [RH Queens - Backend](https://github.com/Isabela-prog/rh-queens).

## 🚀 Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Axios](https://axios-http.com/)
- [React Router DOM](https://reactrouter.com/)
- [Tailwind CSS](https://tailwindcss.com/) (se aplicável)
- Integração com API RESTful (Spring Boot)

## ⚙️ Funcionalidades

- Autenticação de usuários (login e cadastro)
- Visualização de funcionários
- Filtro por categoria (tema)
- Integração completa com o backend via API

## 📦 Como rodar o projeto localmente

### Pré-requisitos

- Node.js (versão 18 ou superior)
- Gerenciador de pacotes (npm ou yarn)
- Backend em execução ([veja aqui como rodar](https://github.com/Isabela-prog/rh-queens))

### Passos

```bash
# Clone o repositório
git clone https://github.com/Isabela-prog/projeto_integrador_rh_queens_-front.git

# Acesse a pasta do projeto
cd projeto_integrador_rh_queens_-front

# Instale as dependências
yarn install

# Inicie o projeto
yarn dev
```

A aplicação será iniciada em `http://localhost:5173`.

⚠️ **Importante:** Certifique-se de que o backend esteja rodando em `http://localhost:8080` ou ajuste a baseURL em `services/Service.ts`.

## 🧩 Estrutura do Projeto

```bash
📁 src
 ┣ 📁 assets        # Imagens e ícones
 ┣ 📁 components    # Componentes reutilizáveis (Navbar, Footer, etc.)
 ┣ 📁 pages         # Páginas principais (Home, Login, Cadastro, etc.)
 ┣ 📁 services      # Integração com API (funções com Axios)
 ┣ 📁 types         # Tipagens TypeScript
 ┣ App.tsx
 ┗ main.tsx
```

## 👩‍💻 Desenvolvedora

- [@Isabela-prog](https://github.com/Isabela-prog)
- [@EvelynSantos6](https://github.com/EvelynSantos6)
- [@maytearaujo](https://github.com/maytearaujo)
- [@ThainaraCruz](https://github.com/ThainaraCruz)
- [@Abilafora](https://github.com/Abilafora)
- [@hellengleice](https://github.com/hellengleice)
