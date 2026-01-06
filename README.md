# SiteChris07 – Portfolio Angular

![CI](https://github.com/Clinter77/sitechris07/actions/workflows/angular-ci.yml/badge.svg)

Portfolio personnel développé avec **Angular**, mettant en avant mes projets, mes compétences techniques et mes pratiques modernes de développement frontend (CI/CD, qualité de code, sécurité).

Le site est conçu pour être :
- ⚡ Rapide
- 📱 Responsive
- 🌙 Compatible Dark / Light mode
- 🔒 Maintenable et sécurisé
- 🚀 Déployé automatiquement

---

## 🌐 Démo en ligne

👉 https://sitechris07.vercel.app  
*(déploiement automatique via Vercel)*

---

## ✨ Fonctionnalités principales

- 🏠 **Page d’accueil**
  - Carrousel de projets (Swiper)
  - Navigation fluide vers les détails

- 📁 **Projets**
  - Liste complète des projets
  - Page de détails par projet
  - Navigation précédent / suivant

- 📬 **Contact**
  - Email direct
  - Lien LinkedIn

- 🎨 **UI / UX**
  - Angular Material
  - Dark / Light theme persistant
  - Responsive mobile / desktop

---

## 🧰 Stack technique

### Frontend
- **Angular 20**
- **TypeScript**
- **Angular Material**
- **Swiper (Web Components)**
- **RxJS**

### Qualité & Outillage
- Standalone Components
- Architecture DRY (source de données unique)
- Routing Angular
- Lazy loading (prévu)
- Thème stocké côté client (RGPD friendly)

---

## 🔁 CI / CD

### GitHub Actions
Pipeline automatique déclenché sur :
- `push`
- `pull_request`

Étapes du pipeline :
1. 📦 Installation des dépendances
2. 🔍 Lint (Angular / ESLint-ready)
3. 🧪 Tests unitaires (ChromeHeadless)
4. 🏗 Build de production

👉 Le badge CI ci-dessus reflète l’état du pipeline.

### Dependabot
- Surveillance automatique des dépendances
- PR de mise à jour sécurisées
- Prévention des vulnérabilités connues (CVE)

---

## 🚀 Déploiement

- **Vercel**
- Déploiement automatique après build réussi
- Optimisé pour Angular SPA

---

## 🛠️ Installation locale

### Prérequis
- Node.js ≥ 20
- Angular CLI ≥ 20

### Installation
```bash
npm install
