Construire une application web avec Flask
=========================================

Il est temps de rassembler tous les éléments vus en classe :
* Python
* Flask
* Jinja2

Objectifs
---------

* Construire une application complète.

Exercices
---------

1. Construisez une application Flask avec au moins 3 routes :
    * une route affichant un formulaire avec les champs nécessaires pour créer
      une personne (nom, prénom, âge);
    * une route recevant les données du formulaire et ajoutant les données dans
      la base de données (dans notre cas, un fichier texte);
    * une route affichant la liste des personnes dans un tableau (élément
      `table`, attention : il faudra lire le fichier où les personnes sont
      stockées).

3. Ajoutez une validation (backend) dans la route qui reçoit les données du formulaire
   pour vous assurer que tous les champs sont remplis. Si un ou plusieurs champs
   ne sont pas remplis, affichez le formulaire avec un message d'erreur.
   Assurez-vous de ne pas perdre les données du formulaire dans le processus
   (lorsqu'on affiche le formulaire avec le message d'erreur, les valeurs du
   formulaire doivent être dans les champs du formulaire).

4. Ajoutez du Javascript afin de pouvoir trier la liste de personnes en ordre
   croissant de nom de famille lorsque l'utilisateur clique sur un bouton.
