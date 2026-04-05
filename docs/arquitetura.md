# 🏗️ Arquitetura do Sistema - CasaCerta

## 📌 1. Visão Geral
O sistema utiliza arquitetura em camadas, separando responsabilidades.

---

## 🧱 2. Camadas

### 🎨 Frontend (Apresentação)
- React.js
- Responsável pela interface do usuário
- Comunicação com backend via API

---

### ⚙️ Backend (Aplicação)
- Node.js + Express
- Responsável pelas regras de negócio
- Processamento das simulações

---

### 🗄️ Banco de Dados
- PostgreSQL
- Prisma ORM
- Armazenamento de dados do usuário e simulações

---

## 🔄 3. Fluxo de Dados

Usuário → Frontend → Backend → Banco de Dados → Backend → Frontend

---

## 📦 4. Estrutura do Projeto
casacerta/
├── frontend/
├── backend/
├── database/
├── docs/

---

## 🔌 5. Comunicação

- Protocolo: HTTP
- Formato: JSON
- Biblioteca: Axios

---

## 🔐 6. Autenticação

- JWT (JSON Web Token)
- Proteção de rotas

---

## 🚀 7. Escalabilidade

- Separação de responsabilidades
- Possibilidade de integração com APIs externas no futuro
