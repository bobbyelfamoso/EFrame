
## Conception bdd 

Pour le MVP d’EFrame, seules les données essentielles au fonctionnement de la plateforme seront stockées. Les informations liées au compte et au profil seront regroupées dans une même entité utilisateur afin de conserver une base de données simple. Pour chaque utilisateur, l’application enregistrera un identifiant unique, une adresse e-mail, un pseudo, un nom, un prénom, une photo de profil éventuelle, une biographie ainsi que la date de création du compte.

L’application devra également stocker les abonnements entre les utilisateurs. Pour chaque abonnement, il sera nécessaire d’enregistrer l’utilisateur qui suit, l’utilisateur suivi et la date à laquelle l’abonnement a été créé.

Certaines données, comme l’adresse e-mail, le nom, le prénom ou la photo de profil, devront être protégées car elles peuvent être considérées comme personnelles. La biographie est facultative et peut également contenir des informations personnelles selon ce que l’utilisateur décide d’y inscrire.

Dans cette première version, les fonctionnalités comme les publications, les likes et les commentaires ne seront pas intégrées afin de garder un MVP simple et centré sur la découverte des profils et les abonnements entre utilisateurs.

|Catégorie|Donnée|Type|Obligatoire ?|Utilité|Sensible ?|
|---|---|---|---|---|---|
|Utilisateur|Identifiant|nombre / identifiant|Oui|Identifier un utilisateur de manière unique|Non|
|Utilisateur|Email|texte|Oui|Identifier le compte et permettre la connexion|Oui|
|Utilisateur|Pseudo|texte|Oui|Identifier publiquement l’utilisateur|Non|
|Utilisateur|Nom|texte|Oui|Afficher l’identité de l’étudiant|Oui|
|Utilisateur|Prénom|texte|Oui|Afficher l’identité de l’étudiant|Oui|
|Utilisateur|Photo de profil|texte / URL|Non|Personnaliser le profil|Oui|
|Utilisateur|Biographie|texte|Non|Présenter librement l’utilisateur|Potentiellement|
|Utilisateur|Date de création|date|Oui|Connaître la date de création du compte|Non|
|Abonnement|Utilisateur qui suit|identifiant|Oui|Identifier l’utilisateur à l’origine de l’abonnement|Non|
|Abonnement|Utilisateur suivi|identifiant|Oui|Identifier l’utilisateur suivi|Non|
|Abonnement|Date d’abonnement|date|Oui|Conserver la date du suivi|Non|