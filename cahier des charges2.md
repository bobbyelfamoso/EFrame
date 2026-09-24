## 1/ Contexte

EFrame est une jeune entreprise française développant une plateforme destinée à la communauté de l'EFREI.
L'entreprise souhaite proposer un espace permettant aux étudiants de découvrir plus facilement les personnes présentes dans leur école.

EFrame propose principalement :
- la création et la consultation de profils étudiants ;
- la recherche d'autres étudiants ;
- la gestion des abonnements entre utilisateurs.

L'entreprise compte 12 collaborateurs répartis entre :
- la direction ;
- le développement ;
- l'administration système ;
- le support ;
- la communication.

EFrame souhaite mettre en place un système d'information permettant d'héberger, sécuriser, administrer et faire évoluer sa plateforme tout en assurant sa disponibilité.

## 2/ Besoin/ Problématique

À l'EFREI, il n'existe pas actuellement de véritable annuaire accessible aux étudiants permettant de découvrir facilement les autres membres de l'école.

Lorsqu'un étudiant arrive dans l'établissement, il connaît généralement peu de personnes.
Retrouver quelqu'un peut également être difficile lorsqu'on ne connaît pas exactement son nom ou son prénom.
Les outils existants permettent parfois de rechercher une personne à partir de son identité, mais donnent peu d'informations permettant réellement de savoir qui elle est.
Les informations sont également réparties entre plusieurs plateformes comme Teams, Discord, Instagram ou différents outils internes.
EFrame souhaite centraliser ces informations dans une plateforme réservée à la communauté EFREI afin de faciliter la découverte et la mise en relation des étudiants.

**Problématique : Comment mettre en place une plateforme permettant aux étudiants de l'EFREI de retrouver et découvrir facilement les autres membres de leur école ?**

## 3/ Objectif

Le projet a pour objectif de mettre en place un système d'information permettant à EFrame :

- de proposer une plateforme accessible aux étudiants de l'EFREI ;
- de permettre la création et la consultation de profils étudiants ;
- de permettre la recherche d'utilisateurs ;
- de permettre aux étudiants de suivre d'autres utilisateurs ;
- de gérer les comptes et les droits d'accès ;
- de collecter et traiter les demandes des utilisateurs ;
- de protéger les données ;
- d'assurer la disponibilité du service ;
- d'administrer et superviser l'infrastructure.

## 4/ Utilisateurs

Le système sera utilisé par les collaborateurs d'EFrame ainsi que par les étudiants de l'EFREI.

| Utilisateur | Besoins principaux |
|---|---|
| Direction | Suivre l'activité de la plateforme et accéder aux informations importantes |
| Développement | Développer, maintenir et faire évoluer l'application |
| Administration système | Administrer, sécuriser et superviser l'infrastructure |
| Support | Traiter les demandes et incidents rencontrés par les utilisateurs |
| Communication | Présenter la plateforme et communiquer auprès de la communauté |
| Étudiants | Créer et personnaliser leur profil, découvrir d'autres étudiants et gérer leurs abonnements |

L'entreprise compte 12 collaborateurs utilisant les différents services du système d'information.
La plateforme sera également destinée aux étudiants de l'EFREI et devra pouvoir évoluer vers une utilisation à plus grande échelle.
## 5/ Fonctionnalités

### Gestion des comptes

La plateforme devra permettre :
- créer un compte ;
- se connecter ;
- se déconnecter ;
- modifier son profil.

L'accès à la plateforme devra être réservé aux membres autorisés de l'EFREI.

Une vérification par adresse e-mail scolaire pourra notamment être utilisée.

### Profils

Chaque étudiant devra disposer d'un profil permettant notamment :

- d'afficher son nom et son prénom ;
- d'afficher une photo ;
- d'afficher sa formation ou sa promotion ;
- d'afficher une courte description ;
- d'afficher quelques centres d'intérêt ;
- d'indiquer éventuellement son appartenance à une association.

Le contenu de présentation du profil pourra être rédigé dans un format Markdown simple, sur un principe similaire aux fichiers README de GitHub, afin de permettre une personnalisation légère tout en conservant une présentation claire et structurée.

### Recherche et découverte

La plateforme devra permettre :
- de rechercher un utilisateur ;
- de consulter les profils disponibles ;
- d'accéder au profil d'un utilisateur depuis les différentes pages de la plateforme.

L'objectif est de faciliter la découverte des membres de l'école.

### Relations entre utilisateurs

Le système devra permettre :
- de suivre un utilisateur ;
- de ne plus suivre un utilisateur ;
- de consulter ses abonnements ;
- de consulter ses abonnés.

### Signalement

La plateforme devra permettre :
- de signaler un utilisateur ;
- de préciser la raison du signalement.

Les signalements devront pouvoir être consultés par un administrateur.

### Support informatique

Les utilisateurs devront pouvoir transmettre une demande ou signaler un problème.
Le support devra pouvoir consulter, suivre et traiter ces demandes.

### Administration et supervision

Les administrateurs devront pouvoir :

- gérer les comptes utilisateurs ;
- gérer les droits d'accès ;
- consulter l'état des principaux services ;
- consulter les incidents techniques.

## 6/ Contraintes

### Infrastructure

L'infrastructure devra être adaptée aux besoins de l'entreprise et permettre l'hébergement des différents services.
Elle devra être documentée et pouvoir évoluer avec le nombre d'utilisateurs.

### Recensement des ressources

Les ressources numériques nécessaires au fonctionnement du système d'information devront être recensées et documentées.

### Services

Les services nécessaires au fonctionnement du système d'information devront être mis en place.
Les solutions techniques utilisées devront être adaptées aux besoins de l'entreprise et leurs choix devront être justifiés.

### Site Internet

Un site vitrine accessible depuis Internet devra présenter :
- l'entreprise ;
- la plateforme ;
- ses principales fonctionnalités ;
- les moyens de contacter EFrame.

### Application web

La plateforme devra :
- être accessible depuis Internet ;
- être reliée à une base de données ;
- communiquer avec au moins un service externe ;
- répondre au besoin de découverte et de mise en relation des étudiants.

### Sécurité du système

Le système devra notamment permettre :
- de contrôler les accès aux ressources ;
- de gérer les droits utilisateurs ;
- de sécuriser les comptes ;
- de sécuriser les services accessibles depuis Internet ;
- de limiter les accès administrateurs.

### Sécurité des données

Les données devront être protégées contre :
- la perte ;
- la modification non autorisée ;
- l'accès par des personnes non habilitées.

Une attention particulière devra être portée aux données personnelles des utilisateurs.

### Règles d'utilisation

Des règles d'utilisation et de sécurité de la plateforme devront être définies et communiquées aux utilisateurs.

### Continuité de service

Les services essentiels devront pouvoir être rétablis en cas de panne ou d'incident.
Des procédures de reprise devront être prévues pour les services critiques.

### Sauvegarde

Les données importantes devront être sauvegardées régulièrement.
Une procédure de restauration devra être définie et un test de restauration devra être réalisé.

### Supervision

L'infrastructure devra être supervisée afin de détecter les incidents.
La supervision devra notamment permettre de surveiller :
- les serveurs ;
- les services ;
- les ressources système ;
- la disponibilité de la plateforme.

### Gestion des demandes et incidents

 Les demandes utilisateurs ainsi que les incidents système, réseau et applicatifs devront pouvoir être :
- collectés ;
- suivis ;
- affectés ;
- traités ;
- documentés.

La gestion des tickets devra s'appuyer sur les principes ITIL.

### Analyse et suivi

Des indicateurs devront permettre de suivre :
- le trafic et l'utilisation de la plateforme ;
- la disponibilité des services ;
- l'avancement du projet ;
- les incidents rencontrés ;
- les résultats des tests.
Les différentes activités du projet devront être planifiées et suivies à l'aide d'un outil de gestion de projet.

### Tests et mise en production

Les différents services devront être testés et validés avant leur mise en production.
La mise en production devra être préparée, réalisée et documentée.

### Documentation et accompagnement

La documentation devra notamment présenter :
- l'architecture du système ;
- les utilisateurs et leurs droits ;
- les services ;
- les mesures de sécurité ;
- la sauvegarde ;
- les procédures d'administration et de reprise.

Des supports devront également permettre aux utilisateurs de prendre en main les services.

### Évolutivité

L'infrastructure devra pouvoir évoluer afin de permettre :

- l'ajout de nouveaux utilisateurs ;
- l'ajout de nouveaux services ;
- l'augmentation des ressources ;
- l'évolution de l'architecture.

La plateforme pourra également évoluer avec l'ajout de nouvelles fonctionnalités, notamment :

- des profils spécifiques pour les professeurs ;
- des pages dédiées aux associations ;
- des filtres de recherche avancés ;
- des notifications ;
- des publications ;
- une messagerie privée ;
- des fonctionnalités de modération plus avancées.

### Choix techniques

Les solutions retenues devront rester simples à mettre en œuvre, faciles à utiliser et faciles à maintenir.
Les choix techniques devront notamment favoriser :
- une prise en main rapide par l'équipe ;
- une architecture simple et compréhensible ;
- une maintenance facilitée ;
- la possibilité de modifier ou faire évoluer rapidement l'application ;
- l'utilisation de solutions largement documentées ;
- la limitation des dépendances ou technologies inutilement complexes ;
- la sécurité et la stabilité du système.

Les technologies pourront évoluer au cours du projet en fonction des besoins identifiés et des retours obtenus pendant le développement.