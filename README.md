# Canvas Sketch Project

## Description
Ce projet utilise la bibliothèque canvas-sketch pour créer une animation interactive basée sur le texte saisi par l'utilisateur. Le texte saisi est rendu dynamiquement sur un canvas HTML5, transformé en glyphes visuels avec des effets aléatoires.

## Prérequis
Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

Node.js (version 14.x ou supérieure)
Git

## Cloner le Dépôt
Pour cloner le projet depuis GitHub, ouvrez votre terminal et exécutez les commandes suivantes :
`
git clone https://github.com/FonAl52/JS-Research-Canvas-sketch.git
cd JS-Research-Canvas-sketch
`

## Installer les Dépendances
Une fois le dépôt cloné, vous devez installer les dépendances du projet. Exécutez la commande suivante dans le répertoire du projet :

`
npm install
`
Cela installera toutes les dépendances nécessaires, y compris canvas-sketch et canvas-sketch-util.

## Exécuter le Projet
Pour lancer le projet et voir l'animation en action, exécutez la commande suivante :

`
npx canvas-sketch sketch-05.js
`
Cette commande démarre canvas-sketch et exécute le script sketch-05.js, où vous pouvez voir l'animation dynamique directement dans une fenêtre ou un navigateur si vous utilisez un serveur local.

## Utilisation
Saisissez du texte : Cliquez dans le canvas et tapez une lettre. Le texte apparaîtra sur le canvas et sera transformé en glyphes dynamiques.
Interactions : Vous pouvez modifier le texte en appuyant sur différentes touches du clavier. L'animation se mettra à jour en temps réel pour refléter le nouveau texte.

## Personnalisation
Vous pouvez ajuster la taille de la police, la famille de polices et d'autres paramètres en modifiant les variables dans le code source :

fontSize : Ajuste la taille de la police du texte.
fontFamily : Change la famille de polices utilisée pour le rendu du texte.

## Dépendances
Le projet utilise les bibliothèques suivantes :

canvas-sketch : Pour la création et l'animation du canvas.
canvas-sketch-util : Pour les utilitaires liés aux graphiques et aux mathématiques.

## Contribuer
Les contributions sont les bienvenues ! Si vous avez des suggestions ou des améliorations, veuillez créer une pull request ou ouvrir une issue.

## License
Ce projet est sous la licence MIT. Consultez le fichier LICENSE pour plus d'informations.

