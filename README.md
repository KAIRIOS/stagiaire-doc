# Documentations et outils

## Outils de développements
Selon vos systèmes d'exploitation, certains outils peuvent changer, je pars du principe que vous êtes sous Windows, nous n'avons pas forcément besoin d'une Distribution linux pour les projets sur lesquels vous allez travailler. Dans le cas contraire, on prendra un moment pour setup tout ça.
### Git
Git est un outil de gestionnaire de versionning, il va nous servir à garder un historique de notre application et pouvoir travailler en collaboration tous ensemble.

Pour Windows il faudra installer Git qui n'est pas inclus dans cet OS. Il suffit simplement de télécharger [Git for Windows](https://gitforwindows.org/). Il intègrera bien sur Git mais aussi Git Bash, qui est un terminal qui colle un peu plus à nos besoins que le Cmd de Windows.

### Editeur de Code
Il n'y a pas forcément un bon ou un mauvais editeur de code, ils embarquent juste plus ou moins de fonctionnalités. De ce fait, je ne peux vous imposer un editeur, ce sera en fonction de votre goût. Je peux néanmoins vous en conseiller quelques-un :
* [Sublime Text](https://www.sublimetext.com/) est un éditeur de code - texte qui embarque les fonctionnalités de bases ([coloration syntaxique](https://fr.wikipedia.org/wiki/Coloration_syntaxique#:~:text=La%20coloration%20syntaxique%20est%20une,fonte%20caract%C3%A9ristiques%20de%20son%20type.), [style d'indenation](https://fr.wikipedia.org/wiki/Style_d%27indentation) par exemple) sans embarquer un tas de fonctionnalités gourmandes en ressources et peut-être pas utile dans vôtre cas.
* [Visual Studio Code](https://code.visualstudio.com/) est un editeur de code un peu plus poussé que le précédent. Il est assez utilisé car il a une bonne compatibilité avec (à condition d'avoir les extensions correspondantes) tous les langages. Il est très light mais peut devenir extrêmement puissant en lui ajoutant quelques extensions utiles ([vue](https://marketplace.visualstudio.com/items?itemName=jcbuisson.vue), [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client) par exemple).
* [PHPStorm](https://www.jetbrains.com/fr-fr/phpstorm/), ce dernier est considéré comme un IDE (environnement de développement), cela veut dire qu'il intègre déjà tout un tas de fonctionnalités afin de pouvoir développer dans le langage souhaité (ici PHP). C'est un peu la Rolls Royce des éditeurs de code, cependant il reste très gourmand en ressources et payant (une version d'essai est quand même disponible).

### Plateforme de développement
Nous travaillons essentiellement sous la plateforme [LAMP](https://fr.wikipedia.org/wiki/LAMP) (Linux, Apache, MySql, PHP), de ce fait plusieurs plateforme sont disponibles pour Windows la plus connue etant [Wamp Manager](https://sourceforge.net/projects/wampserver/).

Ce dernier nous permettra de mettre nos projets en local (le serveur tournera sur votre machine) et ainsi, avoir des méthodes de développements plus faciles. Si vous savez pas réellement comment il fonctionne, vous pouvez trouver un [tuto d'installation et d'utilisation](https://alcatiz.developpez.com/tutoriel/installer-wamp-windows10/).

## Documentation
Nous avons plusieurs projets qui utilisent différentes technologies. Sur ceux que vous allez travailler, elles resteront normalement identiques.

Je vais mettre dans un liste, toutes les documentations potentiellement utiles et qui seront liées de près ou de loin aux projets sur lesquels vous allez travailler.

* Nous possedons comme Framework de développement côté PHP [Symfony](https://symfony.com/) qui nous permet de regrouper un ensemble de composant logique et cohérent utile à notre développement d'application ([ORM](https://fr.wikipedia.org/wiki/Mapping_objet-relationnel), [Routage HTTP](https://fr.wikipedia.org/wiki/Routage), [Système MVC](https://fr.wikipedia.org/wiki/Mod%C3%A8le-vue-contr%C3%B4leur#:~:text=Mod%C3%A8le%2Dvue%2Dcontr%C3%B4leur%20ou%20MVC,les%20vues%20et%20les%20contr%C3%B4leurs.) et j'en passe ...). Vous pouvez trouver plein de tutoriels sur Google concernant ce Framework, mais je peux vous conseiller [l'excellent tuto de Grafikart sur Symfony](https://www.grafikart.fr/formations/symfony-4-pratique).
* Idem côté Front, nous utilisons la star montante de ces dernières années en matière de Framework JS : [Vue JS](https://vuejs.org/). Il nous permet de mettre en page facilement notre application et la rendre très réactive et compatible avec les différents support actuellement. Pareillement, je peux que vous conseiller [le tuto de Grafikart sur Vue JS ](https://www.grafikart.fr/formations/vuejs) ainsi qu'une [cheat sheet de Marozed](https://marozed.ma/vue-cheatsheet/) assez utile pour énumérer tous les fonctionnalités de Vue regroupées à un même endroit. 
* Comme dit plus haut, nous utilisons aussi Git avec comme plateforme [Github](https://github.com/), cet outil étant assez compliqué à prendre en main, je vous laisserais revenir vers moi afin d'avoir plus d'informations ou en cas de problèmes. Je peux cependant vous laisser (encore et toujours) une formation sur [Git de Grafikart](https://www.grafikart.fr/formations/git) qui vous permettra de voir les bases de cet outil.

Je pense avoir fait un tour à peu près détaillé de ce que vous aurez besoin pour pouvoir travailler sereinement sur les outils. N'hésitez surtout pas à me solliciter afin d'avoir plus de renseignement ou alors de vous aider sur quelques choses de bloquant / trop dur, je suis là pour ça ! :smile:

Bon courage à vous !! :muscle:
