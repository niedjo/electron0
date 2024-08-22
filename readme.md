# Electron0

**Version :** 1.0.0  
**Auteur :** Electron0  
**Licence :** ISC  

## Description

Electron0 est un projet Electron créé pour s'amuser et explorer les possibilités de cette plateforme. Ce projet utilise Electron pour créer une application de bureau multiplateforme.

## Prérequis

- Node.js (v12 ou supérieur)
- npm (v6 ou supérieur)

## Installation

1. Clonez ce dépôt sur votre machine locale.
   ```bash
   git clone https://github.com/niedjo/electron0.git
   ```

2. Accédez au répertoire du projet.
   ```bash
   cd electron0
   ```

3. Installez les dépendances du projet.
   ```bash
   npm install
   ```

## Utilisation

Pour lancer l'application, utilisez la commande suivante :
```bash
npm start
```

Cela démarrera l'application Electron en utilisant le fichier `index.js` comme point d'entrée principal.

## Construire l'application

Si vous souhaitez empaqueter l'application pour la distribution, vous pouvez utiliser `electron-packager`. Voici une commande de base pour empaqueter l'application :
```bash
npx electron-packager . Electron0App --platform=win32 --arch=x64 --out=dist/
```

Cela créera une version empaquetée de votre application dans le dossier `dist/`.

## Dépendances

- `electron`: Pour créer l'application de bureau.
- `electron-packager`: Pour empaqueter l'application en vue de sa distribution.
- `php-server`: Pour lancer un serveur PHP simple si nécessaire.

---

Ce projet est principalement à des fins d'apprentissage et d'expérimentation avec Electron.

Ce `README.md` couvre les aspects essentiels du projet, comme l'installation, l'utilisation, et la construction de l'application, tout en étant simple et concis.