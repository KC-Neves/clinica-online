# 🏥 Clínica Online — Sistema Completo de Gestão de Consultas 

Um sistema **Fullstack completo** desenvolvido para o **agendamento, acompanhamento e visualização de consultas médicas**.  
Conta com **frontend moderno em React + TailwindCSS** e **backend seguro com Node.js, Express e MongoDB Atlas**.

---

## 🌟 Visão Geral

A **Clínica Online** permite que pacientes e profissionais de saúde interajam de forma simples e eficiente.  
O sistema inclui **autenticação JWT**, **cadastro de pacientes**, **agendamento de consultas**,  
e um **dashboard interativo** para análise e gestão.

---

## ⚙️ Tecnologias Utilizadas

### 💻 Frontend (`/frontend`)
- React + Vite  
- TailwindCSS  
- Chart.js  
- Autenticação JWT via API  
- Consumo de API com Fetch  
- Modo Claro/Escuro  
- Dashboard dinâmico e responsivo  

### 🧠 Backend (`/backend`)
- Node.js + Express  
- MongoDB Atlas (via Mongoose)  
- Autenticação com JWT  
- Criptografia com bcrypt.js  
- Dotenv para variáveis de ambiente  
- Estrutura modular (Models, Routes, Controllers)

---

## 📁 Estrutura do Projeto
```
clinica-online/
├── frontend/ → Interface React (Saúde+ Dashboard)
│ ├── src/
│ ├── public/
│ ├── package.json
│ └── vite.config.js
│
├── backend/ → API Node.js/Express (Pacientes e Consultas)
│ ├── src/
│ │ ├── models/
│ │ ├── routes/
│ │ ├── controllers/
│ │ └── server.js
│ ├── package.json
│ └── .env
│
└── README.md
```

---

## 🔐 Funcionalidades Principais

✅ Login com autenticação JWT  
✅ Cadastro e listagem de pacientes  
✅ Agendamento e cancelamento de consultas  
✅ Dashboard interativo com gráficos  
✅ Filtro de pacientes e modo escuro  
✅ Deploy completo (frontend + backend)

---

## 🚀 Deploys

- **Frontend (Vercel):** [saude-dashboard-wine.vercel.app](https://saude-dashboard-wine.vercel.app)  
- **Backend (Render):** [api-pacientes-vh6j.onrender.com](https://api-pacientes-vh6j.onrender.com)

---

## 🧪 Testes de API (Thunder Client / Postman)

### ➕ Criar Paciente (POST)


POST https://api-pacientes-vh6j.onrender.com/api/pacientes

Body (JSON):
```json
{
  "nome": "Ana Souza",
  "idade": 30,
  "peso": 65,
  "altura": 1.68,
  "pressao": "120/80",
  "glicemia": 95
}
```

---

## 📋 Listar Pacientes (GET)

GET https://api-pacientes-vh6j.onrender.com/api/pacientes

🔐 Login (POST)

POST https://api-pacientes-vh6j.onrender.com/api/auth/login

Body (JSON):
```json

{
  "email": "kelly@email.com",
  "senha": "001010"
}
```
🧭 Como Executar Localmente

### 1️⃣ Clone o repositório
```bash

git clone https://github.com/KC-Neves/clinica-online.git
cd clinica-online

2️⃣ Instale as dependências

cd backend
npm install
cd ../frontend
npm install

3️⃣ Crie o arquivo .env no backend

PORT=5000
MONGO_URI=sua_string_de_conexao
JWT_SECRET=minha_chave_supersegura

4️⃣ Rode o backend

cd backend
npm run dev

5️⃣ Rode o frontend

cd frontend
npm run dev

Acesse no navegador:
👉 http://localhost:5173
```

---

## 🧠 Próximas Funcionalidades 

🕒 Sistema de agendamento de consultas

💬 Notificações automáticas de lembrete

👨‍⚕️ Cadastro e login de médicos

📈 Dashboard de consultas por período

---

## 👩‍💻 Desenvolvido por:

Kelly Cristina Neves
💼 GitHub: KC-Neves