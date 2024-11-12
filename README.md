# Eventbrite Front-End Project

Ce projet est une interface front-end simulée pour une application de type Eventbrite, construite en utilisant le thème **Quartz** de [Bootswatch](https://bootswatch.com/quartz/). Il suit les principes de conception d'atomic design pour structurer les éléments en atomes, molécules et organismes. 

## Structure du Projet

Le projet est organisé avec une structure de dossiers qui sépare chaque composant pour faciliter la gestion et la maintenance.

### Arborescence

eventbrite_UI\
├── components\
│   ├── navbar.html\
│   ├── footer.html\
│   ├── authentication_form.html\
│   ├── banner.html\
│   ├── card_event.html\
│   └── comment.html\
├── css\
│   ├── quartz_bootswatch.css\
│   └── style.css\
└── index.html\

## Installation

1. Clone le repository dans votre répertoire local.

    ```bash
    git clone https://github.com/hellijah/eventbrite_ui.git
    ```

2. Navigue dans le dossier du projet.

    ```bash
    cd eventbrite_ui
    ```

3. Ouvre le fichier `index.html` dans un navigateur pour explorer les différents composants.

## Guide d'Utilisation

Chaque fichier HTML dans le dossier `components` représente un composant spécifique. Voici un aperçu de chaque composant inclus :

- **Navbar** (`navbar.html`) : une barre de navigation avec liens principaux.
- **Footer** (`footer.html`) : un pied de page contenant des liens d'information.
- **Formulaire d'authentification** (`authentication_form.html`) : un formulaire de connexion et d'inscription.
- **Bannière** (`banner.html`) : une bannière d'accueil avec image et bouton d'appel à l'action.
- **Carte d'événement** (`card_event.html`) : une carte illustrant un événement avec une image, un titre et une description.
- **Commentaire** (`comment.html`) : un modèle de section de commentaires.

Le fichier `index.html` est la page principale où tous les liens vers les composants sont listés pour une navigation facile.

## Personnalisation

Les styles personnalisés sont définis dans `css/style.css` pour adapter l'apparence des composants selon les besoins de l'application Eventbrite. Vous pouvez également modifier le fichier `css/quartz_bootswatch.css` pour ajuster les couleurs et autres styles du thème Quartz.

## Aperçu

Pour un aperçu du projet, ouvre `index.html` dans un navigateur, et explore les composants un par un pour voir leur rendu et tester leur style dans le thème Quartz.

## Technologies Utilisées

- **HTML5** : Structure des pages et composants.
- **CSS3** : Styles personnalisés pour chaque composant.
- **Bootstrap 5** : Mise en page et structure de composants, avec le thème Quartz de Bootswatch.

## Ressources et Références

- [Bootswatch - Quartz](https://bootswatch.com/quartz/) : Thème utilisé pour le design du projet.
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/getting-started/introduction/) : Documentation officielle de Bootstrap.

## Auteur

Ce projet a été conçu dans le cadre d'un exercice de formation sur le développement front-end et l'atomic design.

