
# 💻 Commandes Git Complètes – Style Mojahid

## 🔰 Démarrer une zone de travail
📁 Répertoire du projet
   |
   |---> git init            => Créer un nouveau dépôt à partir de zéro
   |---> git clone URL       => Cloner un dépôt depuis GitHub vers ton PC
```

## 🔧 Travailler sur les modifications en cours
📁 Répertoire de travail
   |
   |---> git add fichier     => Ajouter un fichier à la zone de staging
   |---> git mv ancien nouveau => Renommer un fichier (ou dossier)
   |---> git restore fichier => Restaurer la version précédente d’un fichier
   |---> git rm fichier      => Supprimer un fichier du projet et de Git
```

## 🔍 Examiner l’historique et l’état
📂 Dépôt Git
   |
   |---> git bisect          => Trouver quand un bug est apparu (recherche binaire)
   |---> git diff            => Voir les différences entre les commits
   |---> git grep "texte"    => Chercher un mot dans le code
   |---> git log             => Afficher l’historique des commits
   |---> git show hash       => Détails d’un commit spécifique
   |---> git status          => Voir les fichiers modifiés ou en attente
```

## 🌿 Gérer l’historique et les branches
🌿 Branches et fusions
   |
   |---> git branch          => Lister/créer des branches
   |---> git checkout        => Changer de branche
   |---> git commit -m ""    => Enregistrer un snapshot du projet
   |---> git merge branche   => Fusionner une branche dans une autre
   |---> git rebase branche  => Réaligner l’historique des commits
   |---> git reset --hard    => Revenir à un état antérieur
   |---> git switch branche  => Nouvelle façon de changer de branche
   |---> git tag             => Créer un tag (marque) sur un commit
```

## 🌐 Collaborer (avec GitHub ou autre dépôt distant)
☁️ Connexion GitHub
   |
   |---> git remote add origin URL => Lier ton projet à un dépôt GitHub
   |---> git fetch                 => Récupérer les commits sans les intégrer dans la branche
   |---> git pull                  => Récupérer et intégrer les commits
   |---> git push                  => Envoyer tes commits vers GitHub
```
