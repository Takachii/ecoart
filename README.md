# 🌱 EcoArt — Artisans du Recyclage

> Plateforme web moderne dédiée à la valorisation et à la vente d'objets d'artisanat éco-responsables issus du recyclage.  
> Projet développé par la startup **Nexora** pour **EcoArt**.

---

## 📌 Liens & Livrables

| Livrable | Lien |
| :--- | :--- |
| 🌐 **Site en ligne (GitHub Pages)** | [Voir la démo](https://takachii.github.io/ecoart/) |
| 🎨 **Maquette & Prototype Figma** | [Lien Figma](#) *(à compléter)* |
| 📋 **Gestion de projet (GitHub Projects / Trello)** | [Lien Planification](#) *(à compléter)* |
| 🃏 **Planning Poker** | [Lien Planning Poker](#) *(à compléter)* |
| 📑 **Support de présentation** | [Lien Présentation](#) *(à compléter)* |

---

## 📑 Pages du Site

Le projet intègre les 5 pages obligatoires, toutes reliées et navigables :

1. **🏠 Accueil (`index.html`)** : Présentation du projet EcoArt, des nouveautés et des engagements éco-responsables.
2. **🛋️ Produits (`produits.html`)** : Catalogue d'objets recyclés (bois, tissu, verre, plastique) avec filtres et grille dynamique.
3. **🛠️ Services (`services.html`)** : Ateliers créatifs et formulaire de réservation interactif.
4. **👨‍🎨 Artisans (`artisans.html`)** : Mise en avant des créateurs et de leur savoir-faire artisanal.
5. **📊 Impact & Contact (`contact.html`)** : Chiffres clés de l'impact écologique (déchets revalorisés) et formulaire de contact accessible.

---

## 🛠️ Stack Technique & Bonnes Pratiques

- **HTML5 Sémantique** : Balises structurées (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) validées W3C.
- **CSS3 Pur (Natif)** :
  - Variables CSS globales (`:root` dans [css/variables.css](file:///c:/Users/Takachii/Desktop/ecoart/css/variables.css)).
  - Layouts modernes avec **CSS Grid** et **Flexbox**.
  - Approche **Mobile-First** avec Media Queries adaptées.
- **Accessibilité (A11y / WCAG)** :
  - Typographie inclusive ([Atkinson Hyperlegible](https://fonts.google.com/specimen/Atkinson+Hyperlegible) & Space Grotesk).
  - Navigation au clavier fluide (`focus-visible`, ordre du `tabindex`).
  - Textes alternatifs (`alt`) sur toutes les images.
  - Ratios de contraste conformes aux normes d'accessibilité.

---

## 📱 Breakpoints Responsive (Mobile-First)

| Écran | Résolution | Mécanisme |
| :--- | :--- | :--- |
| 📱 **Mobile** | Jusqu'à `767px` | Styles de base (par défaut) |
| 📱 **Tablette** | `min-width: 768px` | `@media (min-width: 768px)` |
| 💻 **Ordinateur portable** | `min-width: 1024px` | `@media (min-width: 1024px)` |
| 🖥️ **Grand écran** | `min-width: 1280px` | `@media (min-width: 1280px)` |

---

## 📂 Structure du Projet

```text
ecoart/
├── index.html              # Page d'accueil
├── produits.html           # Catalogue de produits
├── services.html           # Ateliers & réservations
├── artisans.html           # Présentation des artisans
├── contact.html            # Impact écologique & formulaire
├── css/
│   ├── variables.css       # Charte graphique & variables CSS (:root)
│   ├── style.css           # Styles généraux
│   ├── responsive.css      # Règles responsive & media queries
│   ├── produits.css        # Styles spécifiques à la page catalogue
│   ├── artisans.css        # Styles spécifiques à la page artisans
│   └── contact.css         # Styles spécifiques à la page contact & impact
├── assets/
│   ├── images/             # Photographies et visuels du projet
│   └── icons/              # Icônes SVG
└── README.md
```
