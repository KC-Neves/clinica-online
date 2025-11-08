# 🏥 Clínica Online — Sistema Completo de Agendamento e Gestão de Pacientes

**Clínica Online** é uma aplicação **Fullstack** desenvolvida para gerenciar pacientes, médicos e agendamentos de consultas.  
O sistema combina **React + Node.js + MongoDB** em um ambiente moderno, seguro e escalável.

---

## 🌐 Visão Geral

A aplicação permite:

- 👩‍⚕️ Cadastro e listagem de pacientes  
- 🧑‍⚕️ Cadastro de médicos  
- 📅 Agendamento e cancelamento de consultas  
- 🔐 Autenticação com login seguro (JWT)  
- 📊 Dashboard interativo com informações de consultas  

---

## ⚙️ Tecnologias Utilizadas

### 🖥️ Frontend
- React + Vite  
- TailwindCSS  
- Chart.js  
- JWT via LocalStorage  
- Deploy: **Vercel**

### ⚙️ Backend
- Node.js + Express  
- MongoDB Atlas  
- JWT (Json Web Token)  
- bcrypt.js  
- Mongoose  
- Deploy: **Render**

---

## 🧩 Estrutura do Projeto

clinica-online/
├── frontend/ → Interface web (React + Tailwind + Vite)
│ ├── src/
│ ├── public/
│ └── package.json
│
├── backend/ → API REST (Node.js + Express + MongoDB)
│ ├── src/
│ ├── package.json
│ └── .env
│
└── README.md → Este arquivo (documentação principal)


---

## 🚀 Deploys

Frontend (Vercel):  
🔗 https://saude-dashboard-wine.vercel.app  

Backend (Render):  
🔗 https://api-pacientes-vh6j.onrender.com  

---

## 🔐 Login de Acesso

E-mail: `kelly@email.com`  
Senha: `001010`

---

## 🧪 Testes da API

### ➕ Criar paciente
**POST** `https://api-pacientes-vh6j.onrender.com/api/pacientes`
```json
{
  "nome": "Ana Souza",
  "idade": 30,
  "peso": 65,
  "altura": 1.68,
  "pressao": "120/80",
  "glicemia": 95
}

---

📋 Listar pacientes

GET https://api-pacientes-vh6j.onrender.com/api/pacientes

🧠 Próximas Funcionalidades

🕒 Sistema de agendamento de consultas

💬 Notificações automáticas de lembrete

👨‍⚕️ Cadastro e login de médicos

📈 Dashboard de consultas por período

---

👩‍💻 Desenvolvido por

Kelly Neves
💼 GitHub: KC-Neves