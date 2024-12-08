# V1 : Sauvegarder les voisins dans une base de données locales
Dans ce TP, vous allez améliorer la version précédente de l'application en y ajoutant un mécanisme de sauvegarde des données dans une base de données locale; 

## Concepts et notions envisagés
- Room
- Coroutines
- Préférences
- Menu

## Etape 1 : Synchroniser le projet précédent 
- Modifier le remote du TP précédent pour le pointer vers ce repository

## Etape 2: Mise en place de la base de données 
Dans cette section, vous allez ajouter les composants nécessaires permettant de gérer les neighbors dans une base de données SQL. 
- Ajouter les composants nécessaires (Entity, DAO, Database) pour gérer les voisins dans une base de données SQLite, en utilisant la librairie Room
- Ajouter une nouvelle implémentation du service afin de gérer la nouvelle source de données (i.e. base de données Room)
- Adapter le repository pour qu'il puisse s'instancier avec l'un ou l'autre des services (memory ou base de données)
- Ajouter un mécanisme permettant de remplir la base de données avec des données de teste

## Etape 3: Gestion des préférences
- Modifier la toolbar de l'application pour y ajouter un menu permettant de basculer sur le mode memory ou base de données
- Utiliser les Préférences pour sauvegarder le choix de l'utilisateur (memory ou database). Quand l'utilisateur choisit un mode dans le menu (memory ou database), sauvegarder son choix dans les préférences afin qu'au redémarrage de l'application son choix soit sauvegardé.


# Contraintes :
- Repartir des sources du projet précédent
- Utiliser les coroutines
- Travailler en binôme
- Utiliser l'injection de dépendances   
