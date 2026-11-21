# Portfolio de Titouan Genève

Portfolio personnel réalisé dans le cadre du BTS SIO, option SLAM. Il présente
mon parcours, mes compétences, mes projets, mes expériences et mes photographies.

## Aperçu

Le site est une page web statique responsive. Il ne nécessite ni installation de
dépendances ni étape de compilation.

## Technologies

- HTML5 pour la structure et le contenu des pages
- CSS3 pour la mise en page, les couleurs, les animations et l'adaptation aux
  différentes tailles d'écran
- Images WebP pour les photographies et les icônes
- Vidéo MP4 de démonstration du jeu Clowork Empire

## Crédits

Les icônes de contact (GitHub, LinkedIn, e-mail, téléphone et adresse)
proviennent de [Icons8](https://icons8.com/).

## Structure du projet

```text
portfolio-eval/
├── index.html
├── html/
│   ├── centres_interet.html
│   ├── competences.html
│   ├── contact.html
│   ├── experiences.html
│   ├── formation.html
│   ├── projets.html
│   └── technologies.html
├── css/
│   └── style.css
├── assets/
│   ├── favicon.ico
│   ├── img/
│   │   ├── 1.webp à 8.webp
│   │   ├── arrow-up.webp
│   │   ├── logo/
│   │   │   ├── adresse.webp
│   │   │   ├── clockwork_empire.webp
│   │   │   ├── csharo.webp
│   │   │   ├── css.webp
│   │   │   ├── github.webp
│   │   │   ├── html.webp
│   │   │   ├── javascript.webp
│   │   │   ├── linkedin.webp
│   │   │   ├── luanti.webp
│   │   │   ├── mail.webp
│   │   │   ├── phone.webp
│   │   │   ├── python.webp
│   │   │   └── sql.webp
│   │   ├── logo_github.webp
│   │   ├── logo_linkedin.webp
│   │   └── photo-profil.webp
│   └── video/
│       ├── clockwork_empire.mp4
│       └── luanti.mp4
├── .gitignore
├── CNAME
├── LICENSE.txt
├── robots.txt
├── sitemap.xml
└── README.md
```

## Lancer le site

1. Cloner ou télécharger le dépôt.
2. Ouvrir le dossier du projet dans VS Code.
3. Ouvrir `index.html` dans un navigateur.

Le formulaire de contact est uniquement présent côté interface. Son action
cible `mon_action.php`, mais aucun script de traitement n'est fourni.

## Modifier le site

- Modifier `index.html` pour changer la page d'accueil.
- Modifier les pages dans `html/` pour mettre à jour les différentes rubriques.
- Modifier `css/style.css` pour changer le style et la mise en page responsive.
- Placer les images et les icônes dans `assets/img/`.

Les pages secondaires partagent la feuille de style `css/style.css`.

## Licence

Ce projet est distribué sous licence MIT. Voir le fichier [LICENSE.txt](LICENSE.txt).
