Environnement de travail
========================

Dans cet atelier, vous allez débuter l'apprentissage de vos principaux outils de
travail : le fureteur et l'éditeur texte.

Objectifs
---------

* Manipuler les outils du fureteur.
* Écrire un premier document HTML.

Au début de la séance de l'atelier, le moniteur fera une présentation du
fureteur Google Chrome et de ses outils intégrés :
* l'affichage du code source de la page HTML;
* l'inspecteur d'éléments;
* la console Javascript (pour y voir certains messages d'erreur);
* la visualisation des requêtes et réponses HTTP (headers et body).

Exercices
---------

1. Faites une requête HTTP GET à l'adresse uqam.ca. Quelle est la version
   utilisée par le serveur qui vous répond?

2. Allez sur la page du cours INF3190 en cliquant navigant sur le site. 
   Trouvez la requête HTTP que le fureteur a envoyé pour produire la page du
   cours.

3. À l'aide de l'inspecteur d'éléments, trouvez l'élément HTML contenant le
   titre du cours.

4. À l'aide de l'inspecteur d'éléments, modifiez le titre du cours.

5. À l'aide de l'inspecteur d'éléments, supprimez le titre du cours.

6. Choisissez un éditeur texte qui supporte le HTML (c'est-à-dire qui offrira de
   la coloration syntaxique et des outils de manipulation de HTML). Il est
   important que l'éditeur enregistre les fichiers HTML avec l'encodage de
   caractères Unicode (utf-8). Le moniteur pourra vous faire des suggestions
   d'outils.

7. Créez un fichier HTML avec le contenu suivant :

```
<!DOCTYPE html>
<html>
<body>

<h1>L'en-tête</h1>

<p>Le paragraphe.</p>

</body>
</html>
```

Ouvrez ce fichier avec Chrome. Observez le résultat.

8. Expérimentez avec ce fichier en ajoutant du texte et des paragraphes.
