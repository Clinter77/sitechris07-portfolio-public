# SiteChris07 – Portfolio Fullstack Angular 22 & DevSecOps **v2.0.0** 🔒 (sécurisé)

![CI/CD DevSecOps](https://github.com/Clinter77/sitechris07/actions/workflows/angular-ci.yml/badge.svg)
![Dependabot](https://img.shields.io/badge/Dependabot-enabled-brightgreen)
![Security](https://img.shields.io/badge/Security-DevSecOps%20validated-10b981)

Portfolio professionnel Angular 22.1.0 avec **chaîne DevSecOps industrialisée v2.0.0** : CI/CD + SAST + SCA + contrôles de sécurité applicative.

Framework<br>

![Angular](https://img.shields.io/badge/-Angular-DD0031?style=flat-square&logo=angular&logoColor=white)

- CI/CD = Continuous Integration / Continuous Delivery (Continuous Delivery and Continuous Deployment)
- SAST = Static Application Security Testing (Analyse Statique de Sécurité des Applications)
- SCA = Software Composition Analysis (Analyse de Composition Logicielle)

> *Mini-organisation individuelle* : identité corporate, projets structurés, pipeline **CI/CD + DevSecOps**.

---

## 🌐 [Démo Live](https://sitechris07.vercel.app)
**Déploiement automatique Vercel après validation des Quality Gate et Security Gate** ✅

---

## 🚀 **Release v2.0.0** – *DevSecOps Industrialisé*

### ✨ **Fonctionnalités principales**

🏠 **HOME PROFESSIONNEL**  
├── Parcours : CAP → Compta → IT réseaux et systèmes → Développeur Fullstack  
├── Valeurs : **Résilience et persévérance, Adaptabilité, Professionnalisme, Montée en compétences continues**  
├── Présentation de la stack technique et des pratiques DevSecOps  
└── UI/UX production (dark/light theme, responsive)

- UI = User Interface → Interface Utilisateur
- UX = User Experience → Expérience Utilisateur

📊 **COMPTEUR VISITES LIVE**  
├── **Supabase PostgreSQL** (plus de 100 visites enregistrées : endpoints visités, volumes, timestamps et statistiques)  
├── Angular Signals + auto-refresh 30s  
├── 4 endpoints : `/`, `/contact`, `/projects`, `/projects/:id` (selon identifiants des projets)  
├── Endpoint `/projects/0` -> A propos de ce site  
└── **Dashboard privé** (100 dernières visites et + enregistrées)

✉️ **CONTACT FORMULAIRE**  
├── **Formspree** (protection côté service contre les attaques courantes)
├── Rate limiting 500/jour
└── Backend formulaire externalisé sécurisé

📁 **PROJETS**  
├── Liste dynamique des projets  
├── Navigation fluide (Angular Router)  
└── UI moderne et épurée

### 🛡️ **DevSecOps - Pipeline CI/CD (3 jobs / 1min45)**

```
QUALITY     🔧 Lint / Tests / Build                      → ✅
SECURITY    🔍 Semgrep (SAST) + Trivy (SCA npm HIGH)     → ✅
GitLeaks    🕵️ Secrets detection                         → ✅
Dependabot  🔄 npm auto-updates                          → ✅ Weekly
```

🔄 Gestion des dépendances

| Fonctionnalité | Description | Bénéfice |
|----------------|-------------|----------|
| `Scan hebdomadaire` | Dependabot analyse package.json chaque semaine | Dépendances à jour, réduction du risque lié aux vulnérabilités émergentes |
| `Limite 5 PR maximum` | 5 pull requests ouvertes simultanément au maximum | Pas de bruit, flux de travail maîtrisé |
| `Commits chore(deps)` | Préfixe standardisé pour commits auto | Historique Git lisible, Conventional Commits |



Pourquoi ce pipeline ?

    Qualité : linting, tests et build valident chaque changement.
    Sécurité : scans SAST/SCA détectent vulnérabilités et secrets.
    Maintenance : Dependabot garde les dépendances à jour.
    
    Résultat : déploiements maîtrisés et réduction des risques en production.

🧰 Stack technique

Frontend
Angular 22 • TypeScript 6 • RxJS • Angular Material • Swiper

Backend & Services
Supabase PostgreSQL • Formspree • Vercel

DevSecOps
GitHub Actions • Semgrep • Trivy • GitLeaks • Dependabot

### 🔄 Versions principales

| Technologie | Version |
|-------------|---------|
| Angular | 22.1.0 |
| Angular CLI | 22.1.2 |
| Angular Material | 22.1.0 |
| Node.js | 22.22.3 LTS |
| TypeScript | 6.0.3 |

## 🏗️ Architecture

### Frontend
- Angular 22 SPA
- Angular Router
- Angular Material
- Angular Signals

### Services
- Supabase PostgreSQL
- Formspree
- Vercel Hosting

### Pipeline CI/CD
- Quality Gate (contrôle qualité)
- Security Gate (contrôle sécurité)
- Automated Deployment (déploiement automatisé)

📈 Liens techniques & Contact

    🌐 Démo : sitechris07.vercel.app
    🔄 Dependabot intégré
    💼 Code source complet disponible sur demande professionnelle

👨‍💻 À propos

Démonstrateur technique illustrant une approche DevSecOps appliquée au développement Angular moderne : qualité, sécurité applicative, automatisation et maintenance continue.

    SiteChris07 v2.0.0 – Portfolio Fullstack Angular + DevSecOps Pipeline (2026)

