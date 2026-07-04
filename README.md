# Portfolio — Denis Yaniss

![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-latest-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-latest-0055FF?style=flat-square&logo=framer&logoColor=white)
![Status](https://img.shields.io/badge/Status-En_ligne-22c55e?style=flat-square)
![Licence](https://img.shields.io/badge/Licence-MIT-gray?style=flat-square)

Site web personnel de Denis Yaniss, étudiant développeur à l'Université Don Bosco de Lubumbashi, passionné de tech.

## Voir le portfolio en ligne

**[https://7d83c7c1-e73b-4770-97d9-b7edcf5540f6-00-j7txtt2g7jis.picard.replit.dev](https://7d83c7c1-e73b-4770-97d9-b7edcf5540f6-00-j7txtt2g7jis.picard.replit.dev)**

## Fonctionnalités

- **Hero** — Introduction avec nom, tagline et boutons d'action
- **About** — Présentation personnelle avec bloc de code décoratif
- **Skills** — Compétences techniques par catégorie (langages, outils, en apprentissage)
- **Projects** — 3 projets avec descriptions et tags technologiques
- **Blog** — Articles techniques avec pages de détail
- **Contact** — Formulaire de contact fonctionnel (mailto)
- **CV** — Page CV imprimable et exportable en PDF (`/cv`)
- **Navigation sticky** — Barre de navigation fixe avec détection de section active
- **Mode clair/sombre** — Toggle thème persistant (localStorage)
- **Animation de chargement** — Écran d'intro "DY" au démarrage

## Stack technique

- **React 18** + **TypeScript**
- **Vite** — Build tool
- **Tailwind CSS v4** — Styles
- **Framer Motion** — Animations
- **Wouter** — Routing
- **shadcn/ui** — Composants UI
- **Lucide React** — Icônes

## Structure du projet

```
artifacts/portfolio/src/
├── components/
│   ├── Hero.tsx          # Section d'accueil
│   ├── About.tsx         # Section à propos
│   ├── Skills.tsx        # Compétences
│   ├── Projects.tsx      # Projets
│   ├── Blog.tsx          # Liste des articles
│   ├── Contact.tsx       # Formulaire de contact
│   ├── Navbar.tsx        # Navigation sticky
│   └── Loader.tsx        # Animation de chargement
├── pages/
│   ├── BlogPost.tsx      # Page de détail d'un article
│   └── CVPage.tsx        # Page CV imprimable
├── data/
│   └── articles.ts       # Contenu des articles de blog
├── hooks/
│   └── use-theme.tsx     # Gestion du thème clair/sombre
├── App.tsx               # Routeur principal
└── index.css             # Thème et variables CSS
```

## Personnalisation

Pour adapter le portfolio à tes informations :

| Ce que tu veux changer | Fichier à modifier |
|---|---|
| Nom, tagline, bio | `components/Hero.tsx`, `components/About.tsx` |
| Compétences | `components/Skills.tsx` |
| Projets | `components/Projects.tsx` |
| Articles de blog | `data/articles.ts` |
| Liens email / GitHub / LinkedIn | `components/Contact.tsx`, `pages/CVPage.tsx` |
| CV complet | `pages/CVPage.tsx` |

## Lancer en local

```bash
pnpm install
pnpm --filter @workspace/portfolio run dev
```

## Auteur

**Denis Yaniss** — Étudiant développeur, Université Don Bosco de Lubumbashi
