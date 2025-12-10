# Générateur de poèmes

[Voir le projet complet sur microbit\.org](https://microbit.org/fr/projects/make-it-code-it/poetry-generator)

Pour coder ce projet vous-même, cliquez avec le bouton droit de la souris sur l'arrière-plan de l'espace de travail et sélectionnez « Supprimer tous les blocs », puis suivez la vidéo de codage ci-dessous. Vous trouverez les blocs `forever (répéter indéfiniment)` et `on start (au démarrage)` dans la section `Basique`.

### Qu'est-ce que c'est ?

Le projet de générateur de poésie crée des phrases aléatoires que vous pouvez utiliser dans un poème, comme mot de passe ou pour commencer une histoire. Il est agréable de partager des phrases particulièrement poétiques ou drôles avec vos amis.   

Ces deux vidéos vous montrent ce que vous allez faire et comment le coder :

https://www.youtube.com/watch?v=D5DNTn0cna8

https://www.youtube.com/watch?v=Ovq3dJiQQlM

### Qu'allez-vous apprendre?

Vous allez connaître les **tableaux**, une variable d'un type particulier. **Les tableaux** représentent une manière pratique de stocker des données dans des listes.

### Comment ça marche

* Lorsque vous secouez votre BBC micro:bit, une phrase aléatoire composée d'un adjectif, d'un nom, d'un verbe et d'un adverbe est créée, par exemple « un bel oiseau mange rapidement ».
* Vous pouvez utiliser votre phrase pour commencer un poème ou l'associer à d'autres phrases générées par ce programme pour écrire un poème entier.
* Le programme utilise quatre **tableaux** appelés ‘adjectifs’, ‘noms’, ‘verbes’, and ‘adverbes’.
* Chaque tableau contient une liste de mots. Chaque élement d'un tableau est appelé **élément**. Les éléments sont numérotés grâce à un **index**. Par exemple, le tableau "noms" comprend trois éléments : l'élément 0: oiseau ; l'élément 1: papillon et l'élément 2: libellule. Les indices sont numérotés à partir de 0 car les ordinateurs commencent à compter à 0.
* Lorsque vous secouez votre micro:bit, un nombre aléatoire entre 0 et 2 est choisi pour chaque tableau. Les éléments correspondants à ces indices sont affichés sur l'écran LED du micro:bit.

Visitez la [page des projets sur microbit\.org](https://microbit.org/fr/projects/make-it-code-it/) pour une description complète de ce projet et bien d'autres.