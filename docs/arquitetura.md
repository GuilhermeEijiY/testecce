# 🏗️ Arquitetura do Sistema — CasaCerta

## 1. Visão Geral

O sistema segue uma arquitetura em camadas:

- Frontend (React)
- Backend (Node.js + Express)
- Banco de Dados (PostgreSQL)

---

## 2. Camadas

### 2.1 Frontend
Responsável por:
- Interface do usuário
- Captura de dados
- Exibição de resultados

**Tecnologias:**
- React
- CSS Modules
- Axios

---

### 2.2 Backend
Responsável por:
- Regras de negócio
- Processamento das simulações
- Autenticação

**Tecnologias:**
- Node.js
- Express
- JWT

---

### 2.3 Banco de Dados
Responsável por:
- Persistência de dados
- Histórico de simulações
- Usuários

**Tecnologias:**
- PostgreSQL
- Prisma ORM

---

## 3. Fluxo de Dados
Usuário → Frontend → Backend → Banco de Dados → Backend → Frontend
