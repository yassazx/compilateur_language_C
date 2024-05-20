# Compilateur Language C
Ce projet implémente un compilateur simple en langage C, comprenant une analyse lexicale et syntaxique de programmes écrits dans un langage spécifique.

## Fonctionnalités
Analyse Lexicale : Vérifie si les mots (instructions) présents dans le code source existent dans un dictionnaire prédéfini.
Analyse Syntaxique : Assure la cohérence syntaxique du code en vérifiant les structures et les règles définies.

## Description des Fichiers du Projet
Le projet de compilateur en langage C utilise plusieurs fichiers pour ses différentes étapes de traitement : analyse lexicale, analyse syntaxique et génération de logs. Voici une brève description des fichiers impliqués :

* programmes.txt
Ce fichier contient le code source à compiler. Il utilise une syntaxe spécifique définie par le compilateur pour déclarer des variables, lire des entrées, exécuter des conditions et afficher des sorties.

* lexique.txt
Ce fichier sert de dictionnaire pour l'analyse lexicale. Il contient les mots-clés, les opérateurs et les caractères spéciaux valides dans le langage de programmation spécifique du compilateur.

* log.txt
Ce fichier est généré par le compilateur pour consigner les erreurs et les avertissements détectés lors de l'analyse lexicale et syntaxique du fichier source.

**Description des éléments du fichier :**

* **Analyse Lexicale :**
    * Signale les mots du fichier source qui ne sont pas trouvés dans le dictionnaire (`lexique.txt`).
    * Exemple : `'var'` et `'Lir'` sont signalés comme erreurs lexicales car ils ne sont pas dans le dictionnaire.
* **Analyse Syntaxique :**
    * Signale les erreurs de syntaxe dans le code source.
    * Exemple : Une erreur syntaxique est signalée à la ligne 5 parce qu'un opérateur est manquant dans la condition `Si`.

