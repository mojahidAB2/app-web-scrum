# 📘 Fiche Complète des Commandes Git (de A à Z)

## 🔰 Initialisation & Clone
| Commande              | Description |
|-----------------------|-------------|
| `git init`            | Initialiser un nouveau dépôt Git local |
| `git clone URL`       | Cloner un dépôt distant vers ton PC |

## 🔧 Travailler sur les Fichiers
| Commande                    | Description |
|-----------------------------|-------------|
| `git add fichier`           | Ajouter un fichier au staging |
| `git add .`                 | Ajouter tous les fichiers modifiés |
| `git mv ancien nouveau`     | Renommer un fichier |
| `git restore fichier`       | Restaurer un fichier |
| `git rm fichier`            | Supprimer un fichier |
| `git clean -f`              | Supprimer les fichiers non suivis |

## 📝 Commits
| Commande                  | Description |
|---------------------------|-------------|
| `git commit -m "msg"`     | Commit avec message |
| `git commit -am "msg"`    | Ajouter + commit direct |
| `git commit --amend`      | Modifier le dernier commit |

## 🌿 Branches & Historique
| Commande                      | Description |
|-------------------------------|-------------|
| `git branch`                  | Lister les branches |
| `git branch nom`              | Créer une branche |
| `git switch nom`              | Aller à une branche |
| `git checkout -b nom`         | Créer + switch branche |
| `git merge branche`           | Fusionner une branche |
| `git rebase branche`          | Réaligner les commits |
| `git log`                     | Historique complet |
| `git log --oneline`           | Historique résumé |
| `git diff`                    | Voir différences |
| `git show hash`               | Voir détails commit |

## 🔙 Restaurer & Réinitialiser
| Commande                         | Description |
|----------------------------------|-------------|
| `git reset --hard`               | Revenir à un état |
| `git reset fichier`              | Unstage fichier |
| `git restore --staged fichier`   | Retirer du staging |

## 🔎 Recherche & Filtres
| Commande                 | Description |
|--------------------------|-------------|
| `git grep "mot"`         | Chercher mot dans le code |
| `git bisect`             | Trouver un bug dans l’historique |

## 🔖 Tags
| Commande              | Description |
|-----------------------|-------------|
| `git tag`             | Voir les tags |
| `git tag v1.0`        | Créer un tag |
| `git tag -d v1.0`     | Supprimer un tag |

## 🌐 Remote avec GitHub
| Commande                                  | Description |
|-------------------------------------------|-------------|
| `git remote add origin URL`               | Lier dépôt distant |
| `git remote -v`                           | Voir les remote |
| `git fetch`                               | Récupérer sans intégrer |
| `git pull`                                | Récupérer + intégrer |
| `git push`                                | Pousser vers GitHub |
| `git push origin branche`                 | Push vers une branche |
| `git push --set-upstream origin branche`  | Lier branche locale à distante |
| `git push origin --delete branche`        | Supprimer une branche distante |

## 👥 Collaboration
| Action / Commande                         | Description |
|------------------------------------------|-------------|
| `git checkout -b branche`                | Nouvelle branche pour PR |
| `git push origin branche`               | Envoyer au dépôt |
| Créer une Pull Request                   | Comparer branche avec main |
| Merge la PR                              | Fusionner dans `main` |

## 💡 Astuces Bonus
| Commande                    | Description |
|----------------------------|-------------|
| `git config --global user.name "Nom"`         | Définir nom utilisateur |
| `git config --global user.email "mail"`       | Définir email |
| `git stash`                 | Sauver modifs non commit |
| `git stash pop`             | Restaurer les modifs |