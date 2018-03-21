# Scheduling-Prediction
App web didactique sur le scheduling et la prédiction.

## Utilisation
Pour avoir un aperçu de l'app web, il suffit d'ouvrir le fichier `index.html`.
### Electron
Pour lancer l'application electron, il faut d'abord installer _electron_ avec npm :
```
npm install electron -g
```
Puis, effectuer la commande suivante à la racine du projet :
```
electron .
```
### Générer les applications Electron
Pour générer les applications, il faut installer _electron-packager_ :
```
npm install electron-packager -g --save-dev
```
Puis, comme exemples, effectuer les commandes suivantes à la racine du projet (toutes les plateformes) :
```
electron-packager . --all --name "SaP" --version "1.0.0" --electronVersion "1.7.11"
```
ou (seulement pour Linux)
```
electron-packager . --platform="linux" --name "SaP" --version "1.0.0" --electronVersion "1.7.11"
```
avec la version d'electron se trouvant avec la commande `electron --version`.
Plus d'infos, sur la [documentation officielle](https://github.com/electron-userland/electron-packager).
