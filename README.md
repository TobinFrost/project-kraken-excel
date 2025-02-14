# Project Kraken excel

## 📂 Structure du projet

```
/project-kraken-excel
│── kraken-excel-front/ # Projet Angular
│── kraken-excel-backend/ # Projet NestJS
│── README.md
```

## 🚀 Prérequis

- Node.js (22.13.1)
- npm
- MongoDB (doit être installer et en cours d'installation)
- Docker (optionel)

## ⚙️ Installation

### 1️⃣ Cloner le repo

```bash
git clone https://github.com/TobinFrost/project-kraken-excel.git
cd project-kraken-excel
git submodule update --init --recursive
git submodule update --remote --merge
```

### 2️⃣ Installation des dépendances

Frontend (Angular)

```bash
cd kraken-excel-front
npm install
```

Backend (NestJS)

```bash
cd kraken-excel-backend
npm install
```

## 🏃 Lancer les projets

### Assurer que MongoDB est démarré

Si MongoDB est installé localement, démarre-le avec :

```bash
mongod
```

### Frontend(Angular)

Dans le dossier kraken-excel-front, exécuter :

```bash
npm run start
```

L'application sera accessible sur : http://localhost:4200

### Backend(NestJS)

Dans le dossier kraken-excel-backend, exécuter :

```bash
npm run start:dev
```

L'application sera accessible sur : http://localhost:3000
