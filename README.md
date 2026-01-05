# 🚀 CV Analyzer Pro

Plateforme SaaS d'analyse automatique de CV avec IA.

## 📋 Prérequis

- Node.js 18+
- npm ou yarn
- Compte MongoDB Atlas
- Compte OpenAI
- Compte Stripe

## 🛠️ Installation

### 1. Cloner le projet
\`\`\`bash
git clone [votre-repo]
cd cv-analyzer-pro
\`\`\`

### 2. Installer les dépendances

**Backend :**
\`\`\`bash
cd backend
npm install
\`\`\`

**Frontend :**
\`\`\`bash
cd frontend
npm install
\`\`\`

### 3. Configuration

**Backend** : Créez `backend/.env`
\`\`\`env
PORT=5000
MONGODB_URI=mongodb+srv://...
JWT_SECRET=votre-cle-secrete
OPENAI_API_KEY=sk-proj-...
STRIPE_SECRET_KEY=sk_test_...
STRIPE_WEBHOOK_SECRET=whsec_...
FRONTEND_URL=http://localhost:3000
NODE_ENV=development
\`\`\`

**Frontend** : Créez `frontend/.env.local`
\`\`\`env
NEXT_PUBLIC_API_URL=http://localhost:5000/api
NEXT_PUBLIC_STRIPE_PUBLIC_KEY=pk_test_...
\`\`\`

## 🚀 Lancement

**Backend :**
\`\`\`bash
cd backend
npm run dev
\`\`\`
Accessible sur : http://localhost:5000

**Frontend :**
\`\`\`bash
cd frontend
npm run dev
\`\`\`
Accessible sur : http://localhost:3000

## 📦 Structure

\`\`\`
cv-analyzer-pro/
├── backend/          # API Node.js + Express
├── frontend/         # Application Next.js
└── README.md         # Ce fichier
\`\`\`

## 🌐 Déploiement

- Frontend : Vercel
- Backend : Render.com
- Database : MongoDB Atlas

Voir le guide complet dans le document principal.

## 📄 Licence

MIT