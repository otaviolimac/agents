# 🧠 Agents

Um sistema de perguntas e respostas em tempo real com gravação de áudio e IA.

# 🚀 NLW IA Rocketseat

Projeto desenvolvido durante o evento NLW IA da Rocketseat, que consiste em um sistema de perguntas e respostas em tempo real com gravação de áudio e inteligência artificial integrada.

## Funcionalidades principais:

- Gravação de áudio direto pelo navegador
- Transcrição e análise semântica usando API Gemini
- Backend com Fastify e banco PostgreSQL via Drizzle ORM
- Frontend responsivo com React, Vite e ShadCN UI

## Objetivo

Aprender e aplicar conceitos de IA, desenvolvimento fullstack e integração com APIs modernas em um projeto prático.

## 📦 Tecnologias

### Backend
- TypeScript
- Node.js
- Fastify
- Zod
- Drizzle ORM + PostgreSQL
- Gemini API

### Frontend
- React
- Vite
- Lucide Icons
- ShadCN UI

## 🚀 Como rodar

## Back
```bash
cd server
npm install
docker compose up -d
npm run dev
```

## Front

```bash
cd web
npm install
npm run dev
```


## 🔊 Gravação de Áudio

O navegador precisa suportar o MediaRecorder. Funciona em Chrome, Edge e Firefox.

## 📂 Estrutura do projeto

server/
├── docker/
├── src/
│   ├── db/
│   │   ├── migrations/
│   │   ├── schema/
│   │   ├── connection.ts
│   │   └── seed.ts
│   ├── http/
│   │   └── routes/
│   ├── services/
│   ├── env.ts
│   └── server.ts
web/
├── public/
├── src/
│   ├── components/
│   ├── http/
│   ├── lib/
│   ├── pages/
│   └── app.tsx