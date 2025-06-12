# 🛍️ Boutique en ligne de chaussures

Ce projet est une **application web complète** dédiée à la vente de chaussures.  
Il se compose d’un **frontend en React.js** et d’un **backend en Node.js/Express**, avec une base de données relationnelle gérée par **MySQL via Sequelize**.

---

## 📝 Présentation

Cette plateforme e-commerce permet aux utilisateurs de :

- 🛒 Parcourir un catalogue de chaussures
- ➕ Ajouter des articles à leur panier
- 📦 Passer commande
- 📈 Gérer les stocks (côté administrateur)

Le projet a été développé dans un **cadre pédagogique**, avec pour objectif d’apprendre à construire une application web **fullstack**, de l’interface utilisateur jusqu’à la gestion des données.

---

## 🔧 Stack technique

### 🖥️ Frontend

- ⚛️ [React.js](https://react.dev/) – Librairie JavaScript pour créer des interfaces modernes et dynamiques
- 🌐 [React Router](https://reactrouter.com/) – Système de routage pour la navigation entre les pages
- 📡 [Axios](https://axios-http.com/) – Librairie HTTP pour les appels à l’API
- 🎨 [CSS3](https://developer.mozilla.org/fr/docs/Web/CSS) – Mise en forme et styles

### 🛠️ Backend

- 🟢 [Node.js](https://nodejs.org/) – Environnement d’exécution JavaScript côté serveur
- 🚂 [Express.js](https://expressjs.com/) – Framework minimaliste pour construire des API REST
- 🧩 [Sequelize](https://sequelize.org/) – ORM pour la gestion des modèles et des requêtes SQL
- 🗄️ [MySQL](https://www.mysql.com/) – Système de gestion de base de données relationnelle

---

## 📚 Documentation API – Swagger

Une documentation interactive de l’API est générée automatiquement avec Swagger.  
👉 Elle est accessible à l’adresse suivante, une fois le backend démarré :  
**http://localhost:3000/api-docs**

---

## 🚀 Installation du projet

### 1️⃣ Cloner le dépôt Git

```bash
git clone -b master https://github.com/KoolHenikaja/techweb.git


### Installation du frontend
cd app/
npm install
npm run dev


### Installation du backend
cd api/
npm install
npm run dev

### structure du projet
techweb/
├── app/         # Frontend React
│   ├── public/
│   ├── src/
│   └── ...
├── api/         # Backend Node.js/Express
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── ...
├── README.md
└── ...
