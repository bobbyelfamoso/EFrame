
## Roadmap : plan d'action

### Mois 1 : Le Backend et la Logique de Données

#### Semaine 1 : Initialisation de l'environnement
- [ ] set up un environnement de dev (vm ou distro linux sur wsl.)
- [ ] Installer **Node.js** et **VS Code** sur ta machine si ce n'est pas déjà fait.
- [x] Créer un dépôt sur **GitHub** pour ton projet.
- [ ] Lancer le projet avec la commande : `npx create-next-app@latest` ( l'App Router, Tailwind CSS pour styliser vite, et JavaScript ou TypeScript).
- [ ] Faire le premier déploiement sur **Vercel** en y connectant ton GitHub. (site vide mais  en ligne !)

#### Semaine 2 : Configuration de Supabase & Base de données

- [ ] Créer un projet gratuit sur **Supabase**.
- Utiliser mon script SQL existant dans le l'onglet _SQL Editor_ de Supabase pour créer les tables 
- [ ] Insèrer à la main 2 ou 3 faux profils d'étudiants directement dans l'interface visuelle de Supabase pour avoir des données de test.

#### Semaine 3 : Authentification (Connexion / Inscription)

- [ ] Installer le SDK Supabase dans mon projet Next.js (`npm install @supabase/supabase-js`).
- [ ] Créer une page de connexion (`/login`) avec un formulaire simple (Email / Mot de passe).
- [ ] Utiliser la fonction `supabase.auth.signUp()` et `supabase.auth.signInWithPassword()` pour permettre aux étudiants de créer un compte et de se connecter.

#### Semaine 4 : La Sécurité Backend (Règles RLS)

- [ ] Activer les **RLS** (Row Level Security) sur la table `profiles` dans Supabase.
- [ ] Écrire la règle RLS pour la lecture : Tout le monde peut voir les profils (`true`).
- [ ] Écrire la règle RLS pour l'écriture : Un étudiant ne peut modifier que sa propre ligne (`auth.uid() = id`).
- [ ] **Objectif Fin de Mois 1 :** Avoir un site en ligne où on peut s'inscrire/se connecter et avoir des données sécurisées.

---

### Mois 2 : Le Frontend et les Finitions

#### Semaine 5 : La page "Annuaire" (Affichage public)

- [ ] Coder la page d'accueil (`/` ou `/etudiants`) qui liste tous les profils.
- [ ] Utilise ton code Next.js pour faire un `supabase.from('profiles').select('*')`.
- [ ] Intègre ta conception graphique (HTML/CSS) pour afficher les cartes des étudiants de manière propre.

#### Semaine 6 : La page "Mon Profil" (Modification de la Bio)

- [ ] Crée une page protégée `/mon-profil` (accessible uniquement si l'étudiant est connecté).
- [ ] Crée un formulaire avec un champ texte pré-rempli avec sa bio actuelle.
- [ ] Ajoute un bouton "Sauvegarder" qui déclenche un `.update()` vers Supabase pour enregistrer la nouvelle bio.

#### Semaine 7 : Tests avec de vrais utilisateurs (Bêta interne)

- [ ] Trouver des béta testeurs (mes amis).
- [ ] leur demander de créer un compte, remplir leur bio et de regarder si l'annuaire se met bien à jour.
- [ ] Note les bugs

#### Semaine 8 : Polissage et Lancement !

- [ ] Nettoyer le code
- [ ] Vérifier que le site s'affiche bien sur téléphone. (responsiveness)
- [ ] Partager l'URL finale à toute ta promotion ! 