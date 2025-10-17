# sistema-gestao-tarefas
Um sistema web completo para gerenciamento de tarefas, com funcionalidades de cadastro de usuários, criação de tarefas, atribuição de prazos, filtros por status e relatórios. Ideal para equipes pequenas ou uso pessoal.
## 🚀 Tecnologias Utilizadas
- **Backend:** Node.js + Express
- **Frontend:** React.js + Tailwind CSS
- **Banco de Dados:** PostgreSQL
- **Autenticação:** JWT
- **ORM:** Prisma

## 📦 Como Rodar Localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/sistema-gestao-tarefas.git

# Backend
cd backend
npm install
npx prisma migrate dev
npm run dev

# Frontend
cd ../frontend
npm install
npm start
