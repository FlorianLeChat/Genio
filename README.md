# 🧞 Genio

⚠️ **[FRENCH] Ce projet n'est pas destiné à un environnement production en dehors du cadre pédagogique et/ou de l'Université Côte d'Azur. L'utilisation hors de ce cadre est à proscrire.**

⚠️ **[ENGLISH] This project is not intended for use in a production environment outside the educational context and/or the Université Côte d'Azur. Usage outside of this scope is not allowed.**

Ce projet scolaire consiste en la création d'un site Internet de création d'arbres généalogiques. Le site est développé en utilisant le framework Symfony 6 et la base de données MySQL. Il offre plusieurs fonctionnalités permettant aux utilisateurs de s'inscrire, de se connecter, de visualiser, de créer et de modifier des arbres généalogiques, ainsi que de rechercher, filtrer et partager des arbres.

## Installation

Pour installer et exécuter ce projet localement, suivez les étapes ci-dessous :

### Prérequis :

    - PHP 7.4 ou version ultérieure
    - Composer
    - MySQL

    Clonez ce dépôt GitHub :

    1.  git clone https://github.com/votre-utilisateur/votre-repo.git

    2.  Accédez au répertoire du projet :
        cd votre-repo

    3.  Installez les dépendances en exécutant la commande suivante :
        composer install

    4.  Créez la base de données MySQL pour le projet.

    5.  Renommez le fichier .env.example en .env et configurez les informations de connexion à la base de données dans ce fichier.

    6.  Exécutez les migrations pour créer les tables de la base de données :
        php bin/console doctrine:migrations:migrate

    7.  Démarrez le serveur Symfony :

    8.  symfony server:start

    9.  Accédez à l'URL indiquée par le serveur Symfony pour accéder au site.

## Fonctionnalités

### Inscription et Connexion

- Les utilisateurs peuvent créer un compte en remplissant un formulaire d'inscription.
- Les utilisateurs enregistrés peuvent se connecter de manière sécurisée en fournissant leurs identifiants.

### Visualisation des arbres généalogiques

- Les arbres généalogiques existants sont affichés avec la possibilité de recherche et de filtrage.
- Les utilisateurs peuvent naviguer intuitivement à travers les différentes générations de l'arbre.
- Les informations relatives aux individus tels que les noms, les dates de naissance, etc. sont affichées.

### Création d'un arbre généalogique

- Une interface conviviale permet aux utilisateurs de créer et de modifier un arbre généalogique.
- Les utilisateurs peuvent ajouter, modifier et supprimer des individus de l'arbre.
- Ils peuvent établir des liens familiaux entre les individus.
- Des informations détaillées peuvent être attribuées à chaque individu.

### Recherches et filtrages

- Les utilisateurs peuvent effectuer des recherches d'individus par nom, date de naissance, lieu, etc.
- Les résultats peuvent être filtrés en fonction de critères spécifiques.

### Partage des arbres

- Les utilisateurs ont la possibilité de partager leurs arbres généalogiques avec d'autres utilisateurs.

### Import de fichier GEDCOM

- Les utilisateurs peuvent importer des fichiers GEDCOM pour faciliter la création de leur arbre généalogique.