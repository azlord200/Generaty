# Générateur de fichiers / File Generator
# Testez ici / test here : 👉🏻 https://generify.pages.dev/
## 🇫🇷 Français

Cette page Web est un petit outil qui permet de générer des fichiers binaires de n'importe quelle taille de façon conviviale.

### Fonctionnalités

* **Choix du nom et de la taille** : indiquez le nom du fichier et sa taille, puis choisissez l'unité (kilooctets, mégaoctets ou gigaoctets).
* **Barre de progression** : pendant la création du fichier, une barre affiche l'avancement en temps réel et vous pouvez annuler à tout moment.
* **Compatibilité avancée** :
  * Sur les navigateurs basés sur Chromium (Chrome, Edge…), l'application écrit le fichier directement sur disque via l'API *File System Access* (plus rapide et sans risque de saturer la mémoire).
  * Sur les navigateurs n'ayant pas accès direct au disque (comme Firefox), le fichier est construit en mémoire puis proposé au téléchargement.
  * Un avertissement est affiché sous Firefox lorsqu'on demande des fichiers de grande taille (> 200 Mo) pour éviter les plantages.
* **Thème clair/sombre** : basculez entre un thème clair et un thème sombre en cliquant sur l'icône (☀️ / 🌙). La préférence est mémorisée dans votre navigateur.
* **Liens utiles** : deux boutons en bas de page permettent d’accéder rapidement au serveur Discord du projet et au profil GitHub du créateur.

### Comment l'utiliser

Ouvrez simplement le fichier `index.html` dans un navigateur moderne.

1. Saisissez le nom du fichier, la taille souhaitée et sélectionnez l'unité.
2. Cliquez sur **Générer** ; une barre de progression indique l'avancement de la création.
3. Le fichier sera automatiquement enregistré (ou proposé au téléchargement selon les capacités du navigateur).

Les boutons **Annuler** et **Réinitialiser** permettent respectivement d'interrompre la génération en cours ou de revenir aux valeurs par défaut.

### Dépendances

Ce projet est entièrement côté client : il ne nécessite pas de serveur ni de librairies externes. Il utilise uniquement des API standards du navigateur et peut être ouvert localement ou déployé sur un serveur statique.

---

Si vous rencontrez un problème ou souhaitez contribuer, n'hésitez pas à ouvrir une *issue* sur GitHub ou à rejoindre le serveur Discord pour en discuter.

## 🇬🇧 English

This web page is a small tool that allows you to generate binary files of any size in a friendly way.

### Features

* **Choose the file name and size**: enter the file name and its size, then choose the unit (kilobytes, megabytes or gigabytes).
* **Progress bar**: while the file is being created, a bar shows the progress in real time and you can cancel at any time.
* **Advanced compatibility**:
  * On browsers based on Chromium (Chrome, Edge, etc.), the application writes the file directly to disk via the *File System Access* API (faster and safer for memory).
  * On browsers without direct disk access (such as Firefox), the file is built in memory and then offered for download.
  * A warning is displayed in Firefox when requesting very large files (> 200 MB) to prevent crashes.
* **Light/dark theme**: switch between a light and a dark theme by clicking on the icon (☀️ / 🌙). The preference is stored in your browser.
* **Useful links**: two buttons at the bottom of the page give quick access to the project's Discord server and the creator's GitHub profile.

### How to use it

Simply open the `index.html` file in a modern browser.

1. Enter the file name, the desired size and select the unit.
2. Click **Generate**; a progress bar will indicate the file creation progress.
3. The file will be automatically saved (or offered for download depending on your browser's capabilities).

The **Cancel** and **Reset** buttons allow you to interrupt the current generation or to return to the default values.

### Dependencies

This project is entirely client-side: it does not require a server or external libraries. It uses only standard browser APIs and can be opened locally or deployed on a static server.

---

If you encounter a problem or wish to contribute, please open an *issue* on GitHub or join the Discord server to discuss it.
