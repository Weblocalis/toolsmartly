# ToolSmartly

ToolSmartly est un projet web statique proposant des outils pratiques en ligne tels que des convertisseurs, des générateurs et des calculateurs. Ce README documente la structure du projet, les étapes d'installation et les outils utilisés pour le développement interne.

## Structure du Projet

```plaintext
/project-root
|
├── /assets              # Fichiers statiques
│   ├── /css             # Feuilles de style
│   │   ├── theme.css    # Styles personnalisés
│   │   ├── vendor.css   # Bibliothèques tierces
│   ├── /js              # Scripts JavaScript
│   │   ├── theme.js     # Scripts personnalisés
│   │   ├── vendor       # Scripts tiers
│   │   └── plugins      # Plugins spécifiques
│   ├── /img             # Images globales
│   ├── /img/pages       # Images liées aux pages
│   ├── /img/blog        # Images pour les articles de blog
│   ├── /icons           # Icônes (favicon, etc.)
│   └── /screenshots     # Captures d'écran
│
├── /components          # Composants réutilisables
│   ├── header.html      # Entête du site
│   ├── footer.html      # Pied de page
│   ├── fil-ariane.html  # Breadcrumb
│
├── /pages               # Pages principales
│   ├── index.html       # Page d'accueil
│   ├── a-propos.html    # À propos
│   ├── faq.html         # FAQ
│   ├── contact.html     # Contact
│
├── /blog                # Blog
│   ├── index.html       # Liste des articles
│   ├── blog-details.html # Détails d'un article
│
├── /legales             # Pages légales
│   ├── mention-legales.html
│   ├── politique-confidentialite.html
│   └── conditions-utilisation.html
│
├── /data                # Données statiques
│   ├── config.json      # Configuration globale
│   ├── menu.json        # Structure du menu
│   └── contenu-static.json # Contenus dynamiques
│
├── robots.txt           # Configuration des robots d'indexation
├── sitemap.xml          # Sitemap pour le SEO
├── manifest.json        # Manifest pour PWA
├── README.md            # Documentation du projet
└── package.json         # Informations du projet
```

## Installation

### 1. Préparation
Ce projet est privé et destiné à un usage interne uniquement. 

Assurez-vous d'avoir Node.js installé sur votre machine pour gérer les éventuelles automatisations et exécuter un serveur local.

### 2. Lancement local
Pour tester le site en local, utilisez un serveur simple comme `http-server` :
```bash
npx http-server
```

## Outils Utilisés

### Technologies
- **HTML5, CSS3, JavaScript** : Pour la structure, les styles et les interactions.
- **Bootstrap** : Pour la mise en page responsive.
- **jQuery** : Pour les interactions JavaScript simplifiées.

### Automatisation
- **Node.js & npm** : Pour la gestion des scripts de build (si applicable).

### Design
- **Canva** : Pour créer les éléments graphiques.

### SEO & Accessibilité
- **Sitemap.xml** : Optimisation de l'indexation.
- **robots.txt** : Contrôle des moteurs de recherche.
- **Balises Schema.org** : Pour enrichir les résultats de recherche.

## Conventions et Bonnes Pratiques

1. **Nom des fichiers**
   - Utilisez des noms explicites et cohérents pour les fichiers et dossiers.

2. **Organisation des ressources**
   - Catégorisez les images et scripts en fonction de leur contexte d'utilisation.

3. **Performances**
   - Minifiez les fichiers CSS et JS avant la mise en production.
   - Optimisez les images (formats modernes comme WebP).

4. **Accessibilité**
   - Respectez les normes WCAG pour garantir une expérience utilisateur inclusive.

5. **Testing**
   - Analysez les performances et l'accessibilité avec des outils comme Lighthouse.

## Confidentialité

Ce projet est strictement privé et ne doit pas être partagé en dehors des collaborateurs autorisés. Toute tentative de duplication ou de diffusion sans autorisation est interdite.