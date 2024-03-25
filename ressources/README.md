# TP_Mot

Il s'agit d'une implémentation simple du jeu Wordle en C. Le jeu permet aux joueurs de deviner des mots de 5 lettres sélectionnés au hasard dans une liste jusqu'à ce qu'ils devinent correctement ou qu'ils épuisent leurs essais.

## Comment compiler et exécuter

1. Accédez au répertoire du projet dans le terminal.
2. Compilez le programme C à l'aide de la commande gcc. Par exemple, si le fichier C s'appelle « wordle.c », vous tapez « gcc wordle.c -o wordle ».
3. Exécutez l'exécutable résultant. Par exemple, tapez « ./wordle ».

## Regles du jeu

- Si vous devinez correctement une lettre et qu'elle se trouve au bon endroit, la lettre sera marquée en vert.
- Si vous devinez correctement une lettre mais qu'elle est au mauvais endroit, la lettre sera marquée en jaune.
- Si la lettre ne figure pas du tout dans le mot, elle sera marquée en gris.
- Vous disposez de 6 tentatives pour deviner le mot. Bonne chance!
