# CHEZ FLORENCE — Vente de Lapins

Site moderne de présentation et de vente de lapins d'élevage, conçu et développé avec un focus sur l'expérience utilisateur et la performance.

## 🎯 Caractéristiques

- **Progressive Web App (PWA)** — Fonctionnalité offline via Service Worker
- **Design responsive** — Optimisé mobile, tablet, desktop
- **Animations fluides** — GSAP + Lenis pour l'expérience scroll
- **Polices personnalisées** — Bodoni Moda, Newsreader, IBM Plex Mono
- **Favicon & manifeste** — Support multi-navigateurs

## 📁 Structure

```
├── index.html          # Page principale (HTML + CSS + JS)
├── manifest.json       # PWA Manifest
├── sw.js               # Service Worker
├── IMAGES/             # Ressources médias
│   ├── logo.png
│   ├── logo.svg
│   └── [images produits]
├── README.md           # Cette documentation
└── [favicons & icons]
```

## 🚀 Déploiement sur Vercel

### 1. Cloner le repo

```bash
git clone https://github.com/wthomasss06-stack/CHEZ-FLORENCE.git
cd CHEZ-FLORENCE
```

### 2. Pousser vers GitHub

```bash
git add .
git commit -m "Déploiement initial CHEZ FLORENCE"
git push origin main
```

### 3. Déployer sur Vercel

#### Option A : Via l'interface Vercel
1. Aller sur [vercel.com](https://vercel.com)
2. Cliquer sur "New Project"
3. Importer ton repo GitHub
4. Vercel détectera automatiquement que c'est un site statique
5. Cliquer "Deploy"

#### Option B : Via CLI Vercel
```bash
npm install -g vercel
vercel
```

Puis suivre les étapes interactives.

## 📝 Contact

- **Email** : wthomasss06@gmail.com
- **WhatsApp** : +225 0142507750
- **Instagram/TikTok** : Liens dans la page
- **Portfolio** : [AKATech](https://akatech.vercel.app/)

## 🛠 Technologies utilisées

- **HTML5** / **CSS3 Grid & Flexbox**
- **JavaScript vanilla** avec GSAP & ScrollTrigger
- **Lenis** pour smooth scrolling
- **Remixicon** pour les icônes
- **Google Fonts** (Bodoni Moda, Newsreader, IBM Plex Mono)

## 📦 Performances

- Assets optimisés (WebP, lazy loading)
- Service Worker pour le cache offline
- Minimal CSS-in-JS (tout inline)
- Aucune dépendance npm requise

## 🎨 Couleurs & Typographie

- **Marron (principal)** : #7C2A1A
- **Rouille (accent)** : #C2723D
- **Papier (clair)** : #F3E9DA
- **Encre (sombre)** : #2A100B

**Polices** :
- Display: Bodoni Moda (titres)
- Body: Newsreader (texte)
- Label: IBM Plex Mono (nav, étiquettes)

---

**Conçu par AKATech** — [https://akatech.vercel.app/](https://akatech.vercel.app/)
