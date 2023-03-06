API complet
===========

Cet atelier introduit la validation de documents JSON à l'aide de json-schema et
la documentation des services REST avec RAML. Vous serez amené à construire une
application web avec des services d'ajout et de modification de ressource. Il
sera nécessaire de valider les données du client.

Testez vos services à l'aide d'un client REST.

Objectifs
---------

* Valider les données provenant du client.
* Manipuler json-schema.
* Manipuler RAML.

Exercices
---------

1. Créez une application Flask avec un service de création d'une fiche
   de personne. Les données reçues du client doivent être :
   * un nom;
   * un prénom;
   * un âge;
   * une date de naissance;
   * une liste de grades universitaires (des strings).

   Tous les champs sont obligatoires.

   Le service doit valider les données du client à l'aide de json-schema.

2. Créez un service de modification d'une fiche de personne. Tous les champs
   sont optionnels et le client n'envoie que les valeurs qui ont changé. Le
   service doit valider les données du client à l'aide de json-schema.

3. Ajoutez une documentation RAML pour les services web de l'application.
   Intégrez la documentation HTML produite par [raml2html](https://github.com/raml2html/raml2html)
   sur une route du projet. Assurez-vous d'utiliser `json-schema` pour définir
   le schéma des entrées de données dans la documentation.

4. Ajoutez un service `GET` pour obtenir la liste de toutes les ressources de votre
   application et documentez-le avec RAML. Utilisez `json-schema` pour
   documenter la sortie du service.
