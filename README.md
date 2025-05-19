# 🍕 Mini E-commerce - Pizza & Refrigerante 🥤

Sistema web completo desenvolvido como avaliação de disciplina acadêmica.  
Permite a visualização, seleção e compra simulada de produtos como pizzas e refrigerantes.

---

## Tecnologias Utilizadas

### Frontend:
- React.js + Vite
- Tailwind CSS

### Backend:
- Node.js + Express.js
- Prisma ORM
- SQLite (banco leve e embutido)

---

## 📂 Estrutura do Projeto

---

## 🚀 Como Rodar o Projeto Localmente

### 🔁 Clonar o repositório

```bash
git clone https://github.com/kellyvieira2021/piy-solucao-final
cd ecommerce-pizza

cd backend
npm install
npx prisma init

DATABASE_URL="file:./dev.db"

npx prisma migrate dev --name init
node seed.js

node src/server.js

cd ../frontend
npm install
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"]
@tailwind base;
@tailwind components;
@tailwind utilities;
npm run dev




