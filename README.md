# Modélisation de données librement choisies

## Avant-propos

Ce projet s'étale sur plusieurs modules du cours de Science des Données Biologiques 2. Il nécessite d'avoir assimilé l'ensemble des notions des modules 1 à 4.

Ce projet correspond au dépôt GitHub <https://github.com/BioDataScience-Course/B02Ga_models>.

## Objectifs

Ce projet est libre et sera réalisé par groupe de quatre étudiants. Répartissez-vous le travail. Il permettra de démontrer que vous avez acquis les compétences suivantes :

-   trouver des données qui se prêtent à la modélisation linéaire

-   décrire les données (graphiques et tableaux)

-   réaliser différents modèles linéaires pertinents (régression linéaire simple, régression linéaire multiple, régression linéaire polynomiale, modèle linéaire...)

-   analyser les modèles réalisés (analyse du résumé, analyse des résidus) et les paramétrer

## Consignes

Ce projet comprend 4 étapes qu'il faut réaliser dans l'ordre croissant.

### Étape 1 (module 2)

La première étape de ce travail consiste dans la recherche de données. Cette étape est cruciale pour le bon déroulement de vos analyses. Vos données doivent être sous la forme d'un tableau de données.

-   avec au **minimum 50 lignes**
-   avec au moins 5 variables quantitatives continues
-   avec au moins 5 variables qualitatives
    -   au minimum une variable à 2 niveaux
    -   au minimum une variable à plusieurs niveaux

Vous devez être particulièrement vigilant sur la "qualité" des données et des métadonnées.

-   Avez-vous assez d'information pour comprendre l'objectif des auteurs relatif à ces données ?
-   Avez-vous assez d'information pour comprendre chaque colonne ?
-   Assurez-vous d'avoir au moins 30 lignes sans valeur manquantes
-   Assurez-vous pour les variables facteurs que le nombre d'occurrences par niveau de la variable est relativement homogène.

Voici plusieurs sites que vous pouvez utiliser pour rechercher vos données :

-   [Zenodo](https://zenodo.org/)

-   [Dryad](https://datadryad.org/)

-   [Free and open access to biodiversity data](https://www.gbif.org/)

-   [The Knowledge Network for Biocomplexity](https://knb.ecoinformatics.org/data)

-   [EDI Data Portal](https://portal.edirepository.org/nis/home.jsp)

Vous suivrez les instructions du fichier `data/README` pour récupérer vos données depuis une URL de téléchargement directe avec mise en cache dans `data/cache`.

### Étape 2 (module 2)

-   Rédigez une courte introduction et un but à votre carnet de notes nommés `models_notebook.qmd`.
-   Complétez la section relative aux régressions linéaires simples, polynomiales et multiples.

### Étape 3 (module 3)

-   Complétez la section relative aux modèles linéaires.

### Étape 4 (module 4)

-   Complétez la section relative aux modèles linéaires généralisés.

## Important

Faites des commit - pull -push réguliers et gérez les conflits éventuels immédiatement.

Effectuez un 'Rendu' du document final en HTML et assurez-vous que ce rendu se fait sans erreurs à la fin de votre travail (c'est très important car c'est en effet ce document final que l'on souhaite obtenir en éditant un fichier Quarto) !

À la fin, vérifiez que le dernier commit est bien pris en compte dans votre dépôt sur GitHub. Nous ne voyons que la version GitHub et c'est cette dernière qui sera corrigée et évaluée. Il est donc crucial que vos dépôts locaux soient bien synchronisés avec GitHub à la fin de votre travail.