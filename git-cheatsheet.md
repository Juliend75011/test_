
# 📌 Git Cheatsheet – Commandes essentielles

## 🚀 Démarrer un projet
```bash
git init                # Initialise un dépôt Git dans le dossier actuel
git clone URL           # Clone un dépôt existant (depuis GitHub par ex.)
```

## 📂 Travailler avec les fichiers
```bash
git status              # Vérifie l'état du dépôt (modifications, fichiers suivis…)
git add fichier.txt     # Ajoute un fichier à l'index (prêt à être commit)
git add .               # Ajoute *tous* les fichiers modifiés
git commit -m "Message" # Enregistre les changements avec un message
```

## 🔄 Envoyer / Récupérer du code
```bash
git push origin branch  # Envoie tes commits vers GitHub
git pull origin branch  # Récupère les changements depuis GitHub
```

## 🌿 Branches
```bash
git branch              # Liste les branches
git branch nouvelle     # Crée une nouvelle branche
git checkout nouvelle   # Bascule sur une autre branche
git checkout -b nouvelle # Crée et bascule en une commande
git merge branche       # Fusionne une branche dans celle où tu es
```

## 🧹 Nettoyage / corrections
```bash
git log                 # Historique des commits
git diff                # Voir les différences non ajoutées
git reset --hard HEAD   # ⚠️ Annule tout pour revenir au dernier commit
```
