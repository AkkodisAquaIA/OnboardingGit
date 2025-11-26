## :gear: OnboardingGit
Un court tutoriel pour apprendre les commandes basiques et essentielles de Git.

## 🧰 Tutoriel Git : Les bases indispensables
### 📌 Qu’est-ce que Git ?

Git est un système de contrôle de version distribué.
Il permet de :
  - Suivre l’historique des modifications d’un projet
  - Travailler à plusieurs sans écraser le travail des autres
  - Créer des branches pour développer des fonctionnalités séparément
  - Revenir facilement en arrière en cas d’erreur
  - Git fonctionne en local, sur ton ordinateur : tu possèdes ta propre copie complète du dépôt.

### 📌 Qu’est-ce que GitHub ?

GitHub est une plateforme en ligne (un service) hébergeant des dépôts Git.
Il permet de :
  - Stocker ton code dans le cloud
  - Collaborer via des Pull Requests
  - Réviser du code
  - Gérer les tickets, la documentation, la CI/CD, etc.

⚠️ GitHub n’est pas Git, c’est un hébergeur et un écosystème autour de Git.

### 📌 Différences entre Git et GitHub
| **Git** | **GitHub** |
|:-|:-|
| Outil installé sur ton ordinateur | Plateforme web en ligne |
| Permet de versionner et gérer les commits  | Permet de partager, collaborer, faire des PR |
| Fonctionne même sans internet  | Nécessite internet |
| Gratuit, open-source | Gratuit + options payantes |
| Commandes en ligne de commande  | Interface web + API + intégrations |```

En résumé :
👉 Git = Le moteur
👉 GitHub = Le garage où tu stockes et partages ton moteur

## 🧪 Travaux pratiques

Nous allons utiliser un repo test pour manipuler les commandes les plus courantes.
Ces exercices supposent que le dépôt existe déjà sur GitHub.

Assure-toi d’avoir :
  - Git installé,
  - VS Code avec l’extension GitHub recommandée par VS Code.

## 1️⃣ Cloner un dépôt (Clone)
### Via VS Code

1. Ouvre VS Code
2. Clique sur Source Control (icône branche dans la barre latérale)
3. Clique sur Clone Repository
4. Colle l’URL GitHub : https://github.com/AkkodisAquaIA/OnboardingGit.git
5. Choisis un dossier de destination
6. VS Code propose d’ouvrir le dossier → clique sur Open

➡️ Le dépôt est maintenant en local.

## 2️⃣ Récupérer les dernières modifications (Pull)

Dans VS Code :
1. Ouvre le menu Source Control
2. En haut, clique sur les …
3. Sélectionne Pull

➡️ VS Code télécharge et fusionne automatiquement les changements.

## 3️⃣ Récupérer sans modifier le code local (Fetch)

Toujours dans Source Control :
1. Menu … → Fetch
  
➡️ Met à jour les infos distantes sans toucher à tes fichiers locaux.

## 4️⃣ Enregistrer une modification (Commit)

1. Modifie un fichier dans VS Code
2. Ouvre Source Control
3. Tous les fichiers modifiés apparaissent
4. Tape un message dans la zone Message
5. Clique sur Commit

➡️ Le commit est enregistré localement.

## 5️⃣ Envoyer les commits sur GitHub (Push)

Après un commit, un bouton Sync ou Push apparaît en haut du Source Control :
1. Clique sur Push

➡️ VS Code envoie les commits sur GitHub.

## 6️⃣ Synchroniser les changements (Sync)

Le bouton Sync effectue automatiquement :
- un Pull
- puis un Push

C’est l’action recommandée si tu travailles en équipe.

## 7️⃣ Créer une nouvelle branche (Create Branch)

Dans VS Code :
1. Clique sur le nom de la branche en bas à gauche (ex : main)
2. Choisis Create new branch
3. Donne un nom : feature/nouvelle-fonctionnalité

VS Code se place automatiquement sur la nouvelle branche.

##8️⃣ Fusionner une branche (Merge)

1. En bas à gauche → clique sur ta branche actuelle
2. Sélectionne la branche sur laquelle tu souhaites fusionner tes modifications pour revenir dessus
3. Menu … → Merge Branch
4. Choisis la branche à fusionner from (ex : feature/...)

➡️ La fusion est appliquée localement, pense ensuite à Push.

##9️⃣ Ouvrir une Pull Request (PR)

Après avoir push ta branche :
1. Aller sur le compte GitHub du repository, et un bouton devrait apparaître, "Create Pull Request".
2. Vérifier bien de rabattre la branche avec les modifications sur la branche voulue
3. S'il n'y a pas de conflits, faire la demande de Pull request
4. Attendre qu'elle soit validée par un admin du projet.

➡️ La PR est créée sur GitHub.
