# ⚽🏆 KoraLive - Suivez vos matchs en direct ! 🏟️📺

Bienvenue sur **KoraLive**, votre plateforme en ligne pour **suivre les scores en direct** et **regarder vos matchs préférés en streaming**. Notre site web est conçu pour les fans de sport qui veulent rester connectés avec l'action à tout moment !  

**Siteweb** : https://koralive.vercel.app

---

## 🚀 Fonctionnalités Principales

### 🔹 Scores en Direct
- Affichage des scores en temps réel pour tous les matchs majeurs ⚡
- Informations détaillées : équipes, logo, score, minute actuelle ⏱️
- Classement et statistiques des équipes  

### 🔹 Streaming des Matchs
- Regarder les matchs en direct directement depuis le site 📺
- Choix de différents serveurs pour un streaming fluide 🌐
- Interface intuitive et responsive pour tous les appareils 📱💻  

### 🔹 Historique et Résultats
- Consulter les résultats des matchs passés 📝
- Revoir les highlights et moments clés ⚡  

### 🔹 Notifications & Alertes
- Recevez des notifications pour vos matchs favoris 🔔
- Suivi des scores en temps réel sans rafraîchir la page ⏱️  

---

## 🖌️ Design et Technologie

### 🎨 UI/UX
- Interface moderne, fluide et responsive 🌈
- Thème dynamique inspiré des stades et des équipes de foot ⚽
- Animations et transitions stylées pour une expérience immersive ✨

### 💻 Stack Technique
- **Frontend** : Next.js, Tailwind CSS pour un design rapide et moderne 🖥️
- **Backend** : API Next.js + Puppeteer pour scraper les scores et vidéos en direct ⚡
- **Base de données** : MySQL ou PostgreSQL pour stocker les utilisateurs et les favoris 🗄️
- **Librairies & Outils** :
  - `lucide-react` pour les icônes 🖼️
  - `GSAP` pour les animations ⚡
  - `react-player` pour le streaming des vidéos 🎬  

---

## 📂 Structure du Projet

```text
KoraLive/
├─ pages/
│  ├─ index.jsx         # Page d'accueil avec liste des matchs
│  ├─ match.jsx         # Page pour regarder un match spécifique
│  ├─ api/
│  │  ├─ home.js        # API pour récupérer les scores et les horaires des matches
│  │  ├─ match.js       # API pour récupérer le streaming du match
├─ public/
│  ├─ images/           # Logos et images des équipes
├─ styles/
│  ├─ globals.css       # Styles globaux
├─ package.json
├─ README.md
