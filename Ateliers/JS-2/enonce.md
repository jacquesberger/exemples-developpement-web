Formulaires et Javascript
==========================

Le Javascript peut servir à effectuer des vérifications au niveau du fureteur
avant de contacter le serveur. Par exemple, il est très fréquent de valider le
contenu d'un formulaire avant de le soumettre au serveur. Évidemment, le serveur
va refaire toutes les validations de son côté, mais la validation dans le
fureteur permet d'améliorer la convivialité des applications web.

Objectifs
---------

* Manipuler du Javascript.
* Valider un formulaire avec du Javascript.

Exercices
---------

Pour toutes les validations à faire : en cas d'erreur, le formulaire n'est pas
envoyé au serveur et un message d'erreur significatif apparaît à côté du champs
qui produit l'erreur.

1. Créez une page HTML avec un formulaire contenant les champs suivants :
  * nom;
  * prénom;
  * date de naissance;
  * code permanent.

2. Ajoutez une validation avec Javascript pour vérifier que la date de naissance
   est dans le format `AAAA-MM-JJ`.

3. Ajoutez une validation pour vérifier que tous les champs contiennent une
   valeur (ils sont tous obligatoires).

4. Ajoutez un champ texte pour le genre de la personne. Ajoutez une validation
   pour vous assurer que les seules valeurs possibles dans ce champ sont `F` et
   `M`.

5. Ajoutez une validation sur le code permanent. Le code permanent doit être
   composé, dans l'ordre, des éléments suivants :
   * les 3 premières lettres du nom, sans accent, en majuscules;
   * la première lettre du prénom, sans accent, en majuscule;
   * le jour de naissance sur 2 caractères;
   * le mois de naissance sur 2 caractères, additionné de 50 si c'est une femme;
   * l'année de naissance sur 2 caractères;
   * une valeur séquentielle sur 2 caractères, uniquement des chiffres.
