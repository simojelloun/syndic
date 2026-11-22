# Syndic de la résidence

Application web mobile de gestion du syndic : lots et copropriétaires, cotisations mois par mois (y compris paiements anticipés), dépenses, incidents et annonces.

## Mise en ligne sur GitHub Pages

1. Créez un dépôt sur GitHub (par exemple `syndic`).
2. Déposez à la racine du dépôt tous les fichiers de ce dossier : `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `README.md`.
3. Dans le dépôt : **Settings › Pages › Build and deployment**, choisissez *Deploy from a branch*, branche `main`, dossier `/ (root)`, puis **Save**.
4. Après une à deux minutes, l'application est disponible à l'adresse `https://<votre-identifiant>.github.io/syndic/`.

## Installer sur le téléphone

- **Android (Chrome)** : ouvrir l'adresse, menu ⋮ › *Ajouter à l'écran d'accueil*.
- **iPhone (Safari)** : ouvrir l'adresse, bouton Partager › *Sur l'écran d'accueil*.

## Où sont les données ?

Les données sont enregistrées **dans le navigateur de l'appareil utilisé**, pas sur un serveur :

- elles ne sont pas partagées entre appareils ni entre personnes ;
- elles peuvent être perdues si l'on vide les données du navigateur ou change de téléphone.

Utilisez **Résidence › Sauvegarde › Télécharger une sauvegarde** régulièrement, et **Restaurer une sauvegarde** pour les récupérer sur un autre appareil.

Si le dépôt est public, le code est visible par tous, mais pas vos données, qui restent sur votre appareil.
