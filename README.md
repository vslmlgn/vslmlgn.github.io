# 🚀 Guide de démarrage – VS Code, Live Server & Git

Ce guide explique comment installer Visual Studio Code, configurer l’extension Live Server pour le développement web, et utiliser les commandes Git essentielles pour gérer un projet.

## 📦 Installation de Visual Studio Code

**1. Télécharger VS Code**
- Aller sur le site officiel : https://code.visualstudio.com
- Télécharger la version correspondant à votre système (Windows, macOS ou Linux)

**2. Installer VS Code**
- Lancer l’installateur téléchargé
- Suivre les étapes par défaut
- Une fois l’installation terminée, ouvrir Visual Studio Code

## 🔌 Installation de l’extension Live Server

Live Server permet de lancer un serveur local avec rechargement automatique du navigateur.

**Étapes :**

**1.** Ouvrir Visual Studio Code

**2.** Cliquer sur l’icône Extensions ```(ou Ctrl + Shift + X)```

**3.** Rechercher Live Server

**4.** Installer l’extension créée par Ritwick Dey

**5.** Redémarrer VS Code si nécessaire

## 🌐 Utilisation de Live Server
**Démarrer Live Server**

- Ouvrir un dossier de projet contenant un fichier ```index.html```
- Clic droit sur ```index.html```
- Sélectionner "Open with Live Server"

👉 Le navigateur s’ouvre automatiquement (généralement sur ```http://127.0.0.1:5500```)

**Avantages**

- Rechargement automatique à chaque sauvegarde
- Pas besoin de rafraîchir manuellement le navigateur
- Idéal pour HTML, CSS et JavaScript

**Arrêter Live Server**

- Cliquer sur "Port : 5500" en bas à droite de VS Code
- ou
- Fermer la fenêtre du navigateur

## 🌱 Commandes Git basiques
**Initialiser un dépôt Git**
```
git init
```

**Vérifier l’état du dépôt**
```
git status
```

**Ajouter des fichiers à l’index**

- Ajouter un fichier :
```
git add fichier.html
```


**Ajouter tous les fichiers :**
```
git add .
```

**Créer un commit**
```
git commit -m "Message du commit"
```

**Voir l’historique des commits**
```
git log
```

**Lier un dépôt distant**
```
git remote add origin URL_DU_DEPOT
```

**Envoyer le code vers le dépôt distant**
```
git push -u origin main
```

**Récupérer les dernières modifications**
```
git pull
```

**Cloner un dépôt existant**
```
git clone URL_DU_DEPOT
```

## 🧠 Bonnes pratiques

- Toujours vérifier ```git status``` avant un commit
- Faire des commits réguliers avec des messages clairs
- Sauvegarder souvent son travail
- Tester avec Live Server avant de pousser le code