# Gestion des tickets

Les projets ESE'OS utiliseront les tableaux Kanbans proposés par Github. Ces derniers seront en partie automatisés pour permettre un fonctionnement simplifié et intuitif. il est cependant important de s'en servir correctement et avec rigueur, car une mauvaise utilisation entraîne souvent des erreurs et des incompréhensions entre membres du projet.

## Règles importantes

 - Un ticket devra toujours être associé à une *issue*.
 - Toujours détailler les tickets afin qu'ils soient rapidement compréhensibles.
 - Un ticket mal formé ne peut être pris pour être réalisé.

## Structure d'un ticket

### Titre
Il doit être le plus court et précis possible. (On y intégrera le numéro de l'*issue* traitée). 
 - Exemple : `Revoir le design de la liste des fiches`

### Quoi ? _(obligatoire)_
Une brève description de ce qui est attendu pour réaliser ce ticket. Elle doit être exhaustive et ne pas être juste une simple recopie du titre du ticket.
 - Exemple : `En tant qu’utilisateur, je souhaite pouvoir afficher plus de fiches sur la même page en ne conservant que les informations importantes.`

### Comment ? _(obligatoire)_
Détailler sa vision de la tâche et proposer une piste de résolution pour aider celui qui va s'en charger.
 - Exemple : `Partir sur des tuiles comme en mode mobile, placées les unes à coté des autres.`


### Problèmes actuels ? _(facultatif)_
Si le ticket a pour objectif de corriger des problèmes actuellement présents dans le projet, il est important d'expliquer ces soucis afin que le responsable du ticket puisse en tenir compte lors de son travail.
 - Exemple : `Actuellement les tuiles sont trop grosses, trop de blanc et donc trop d’espace perdu. Toutes les informations ne sont pas utiles (Ex: Agence) ou peuvent être simplifiées avec juste une icône (Ex: pour le matériel, changer l’icône si c’est un ordinateur, écran ou autre).`

### Risques potentiels ? _(facultatif)_
S'il est possible de la réalisation du ticket entraîne la création de nouveaux bugs ou de problèmes au sein de l'application, il faut les noter dans cette catégorie. Le responsable du ticket pourra ainsi faire attention à limiter ces risques et pourra orienter ses tests pour la vérification.
 - Exemple : `Compresser le tout sans perdre le responsive. L’application doit pouvoir être utilisée aussi bien sur tablette que sur ordinateur.` 