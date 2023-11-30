# BUT1-Memory
Jeu de Memory codé en C pour la première SAE (projet) de l'année de BUT1.

### Comment lancer le programme ?
Ecrire dans un terminal à la racine du projet: "**make run**"

### Que fait ce programme ?
Pour ce projet, nous devions coder un jeu de memory (aussi appelé 'jeu de paires') en C.
> Quand le programme se lance, on arrive sur un menu qui nous demande avec combien de paires on veut jouer.
> Pour faire cela, il y a des flèches pour incrémenter ou décrémenter le nombre affiché à l'écran.
> Le nombre minimum est 1 paire, et le maximum est 20.
![image du menu](./imagesreade/menu.PNG)

> Après avoir appuyé sur le bouton START, la partie se lance avec le nombre de paires demandé, qui s'affichent face cachée.
> On voit sur la droite une croix pour arrêter le jeu (et revenir au menu), le temps en jeu qui défile, ainsi que le score (le nombre de paires trouvées).
> La place des images est aléatoire et est changée à chaque exécution.
> Quand on clique sur une image, elle se retourne. Et après avoir cliqué sur une deuxième, les deux se retournent si elles ne forment pas une paire, et restent affichées si c'est le cas.
![image du jeu caché](./imagesreade/jeucache.PNG)

> Il existe un mode de triche (en appuyant sur la touche T du clavier). 
> Cela met en pause le timer, et affiche face visible toutes les cartes. 
> Vous pouvez mettre fin au mode triche en rappuyant sur la touche T.
![image du jeu triche](./imagesreade/jeutriche.PNG)

> A la fin de la partie (quand toutes les paires sont trouvées), un message est affiché, et un bouton rejouer apparait, bouton qui ramène au menu.
![image de la fin du jeu](./imagesreade/finjeu.PNG)