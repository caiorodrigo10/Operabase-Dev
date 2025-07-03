# Operabase Dev

Sistema completo de gestão para clínicas médicas.

## 🚀 Setup Local

1. Clone o repositório
   ```bash
   git clone https://github.com/SEU_USUARIO/Operabase-Dev.git
   cd Operabase-Dev
   ```

2. Configure as variáveis de ambiente
   ```bash
   cp .env.example .env
   # Edite o arquivo .env com suas configurações
   ```

3. Instale as dependências
   ```bash
   npm install
   ```

4. Execute o projeto
   ```bash
   npm run dev
   ```

## 📦 Scripts Disponíveis

- `npm run dev` - Executa o servidor em modo desenvolvimento
- `npm run build` - Build do frontend (Vite)
- `npm run build:full` - Build completo (frontend + backend)
- `npm run start` - Executa o servidor em produção
- `npm run check` - Verifica tipos TypeScript
- `npm run db:push` - Aplica migrations do banco de dados

## 🛠️ Stack Tecnológica

- **Frontend**: React + Vite + TypeScript
- **Backend**: Express + TypeScript
- **Database**: PostgreSQL + Drizzle ORM
- **Styling**: Tailwind CSS + Shadcn UI
- **State Management**: TanStack Query
- **Authentication**: Passport.js
- **AI Integration**: OpenAI + Anthropic

## 🚀 Deploy

O frontend é deployado automaticamente no Netlify ao fazer push para main.

## 📝 Licença

MIT
