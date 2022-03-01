# Petit tutoriel rapide et concis sur comment installer et utiliser Python

## Index
- [Vocabulaire](https://github.com/reza0310/Tutorials/blob/python/README.fr.md#vocabulaire)
- [A savoir](https://github.com/reza0310/Tutorials/blob/python/README.fr.md#a-savoir)
- [Tutoriel](https://github.com/reza0310/Tutorials/blob/python/README.fr.md#tutoriel)
- [Dernière modification](https://github.com/reza0310/Tutorials/blob/python/README.fr.md#derni%C3%A8re-modification)

## Vocabulaire
IDLE: Environnement de développement intégré à Python. Là où beaucoup de logiciels similaires utilisent l'acronyme "IDE", Python utilise IDLE probablement en référence à Eric Idle, membre fondateur des Monty Python.<br>
PIP: Est un gestionnaire de packets pour Python. Il est utilisé pour télécharger et installer facilement des packets/bibliothèques/extensions open source depuis le dépôt PyPI (= Python Package Index).<br>
Path: Chemin d'un fichier de la forme "C:\Users\[nom d'utilisateur]\Desktop" pour un bureau windows en chemin absolu ou "dossier/fichier.txt" pour un fichier nommé "fichier.txt" dans le dossier "dossier" situé au même endroit que vous en chemin relatif par exemple.

## A savoir
Il y a bien des moyens d'éditer et d'exécuter du code Python. Si vous avez votre propre façon de faire, ce tutoriel ne sera pour vous que d'une utilité minime voire nulle mais si ce n'est pas le cas, laissez moi vous montrer la façon la plus simple de faire en utilisant IDLE et pip pour les bibliothèques manquantes.

## Tutoriel
1) Téléchargez Python depuis leur [site web officiel](https://www.python.org/downloads/).

<br><br><br>
2) Exécutez l'installateur. Sur le toute première page, vous aurez deux choses très importantes à faire: premièrement cocher la case "Add Python [...] to PATH" pour vous donner la possibilité d'utiliser Python mais aussi et surtout pip depuis l'invite de commande. Ensuite, cliquez bien sur le bouton "Install now". Ce sera plus rapide et ça vous installera pip et IDLE, nos outils pour ce tutoriel, dans la foulée.

![Image illustrant l'étape 2](https://github.com/reza0310/Tutorials/blob/python/1.PNG) 

<br><br><br>
3) Un peu plus tard, il vous sera proposé de désactiver la limite de taille du path (path length limit). Cette option ne changera rien pour la plupart d'entre vous mais si le path allant jusqu'à votre exécutable Python fait plus de 260 caractères, ça vous évitera bien des soucis. Je vous recommande donc de le faire.

![Image illustrant l'étape 3](https://github.com/reza0310/Tutorials/blob/python/2.PNG) 

<br><br><br>
4) Vous pouvez ensuite fermer l'installateur. 

![Image illustrant l'étape 4](https://github.com/reza0310/Tutorials/blob/python/3.PNG)  

<br><br><br>
5) Comme vous pouvez le voir, plusieurs applis ont été installées mais seulement 2 nous intéressent: Python et IDLE. 

![Image illustrant l'étape 5](https://github.com/reza0310/Tutorials/blob/python/4.PNG)  

<br><br><br>
6) Maintenant, vous pouvez télécharger le projet Python que vous souhaitez exécuter. Pour ce faire, rendez-vous sur la page github du projet et cliquez sur le gros bouton vert disant "Code" puis cliquez sur "Download ZIP" et extrayez les fichiers de l'archive où vous voulez. Si vous vous retrouvez avec plusieurs scripts Python (fichiers d'extension .py), pour savoir lequel exécuter, référez vous à la documentation du projet et, si elle n'est d'aucune aide, essayez d'exécuter le fichier nommé "main", "index" ou quelque chose du genre. Pour ma démonstration ici, j'ai utilisé mon propre [projet random pixels](https://github.com/reza0310/random_pixels).

<br><br><br>
7) Pour exécuter votre script fraichement acquis avec Python, vous pouvez le faire depuis l'invite de command en tapant "python \[path absolu ou relatif vers votre script]" (méthode inutilement compliquée) ou juste double-clicquez dessus. L'inconvénient du double click c'est que l'invite de commandes qui s'ouvrira avec cette action se fermera dès que le script se terminera ou plantera. Pour être capable de voir les résultats de votre script et le manipuler au besoin, vous allez avoir besoin d'un Environnement de développement comme IDLE ou Pycharm qui est un peu plus avancé mais beaucoup plus complexe. Pour ouvrir un script avec IDLE, faites juste un clique droit puis sélectionnez "Edit with IDLE".

![Image illustrant l'étape 7](https://github.com/reza0310/Tutorials/blob/python/5.PNG)

<br><br><br>
8) Pour exécuter le script, cliquez que "Run" -> "Run Module" ou juste appuyez sur F5.

![Image illustrant l'étape 8](https://github.com/reza0310/Tutorials/blob/python/6.PNG)

<br><br><br>
9) Si ça ne marche pas et affiche une erreur "ModuleNotFoundError", ne vous en faites pas je vais vous expliquer comment régler ça. Si ça affiche une quelconque autre erreur alors le problème provient du script et/ou de sa compatibilité avec votre système et si vous apprenez avec ce tutoriel, vous ne pourrez probablement pas réparer le script vous-même mais ce que vous pouvez faire c'est ouvrir une "issue" dans l'onglet correspondant de la page github du projet ce qui aidera grandement les développeurs du projet à régler votre problème. Assurez vous juste de leur donner toute information que vous pensez pertinente et de répondre s'ils vous posent ensuite des questions comme ça vous leur permettrez de réparer le problème le plus vite possible et ce ne sera pas du temps perdu ni pour vous ni pour eux.

![Image illustrant l'étape 9](https://github.com/reza0310/Tutorials/blob/python/7.PNG)

<br><br><br>
10) Pour toute erreur du type "ModuleNotFoundError", récupérez le nom du module problématique (qui est écrit à la fin de la ligne), ouvrez une i=nvite de commandes et tapez "pip install \[nom du module]" pour installer ledit module et retirer l'erreur. Si la commande pip échoue, essayer de remplacer les points avec des _ (underscores) et si ça ne marche toujours pas, cherchez sur Internet comment installer ce module là précisément.

![Image illustrant l'étape 10](https://github.com/reza0310/Tutorials/blob/python/8.PNG)

<br><br><br>
11) Pour finir, profitez ;)

![Image illustrant l'étape 11](https://github.com/reza0310/Tutorials/blob/python/9.PNG)

## Dernière modification
Dimanche 20 février 2022
