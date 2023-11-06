# Ennemis (Orc + Mouche) 👹🦟

Maintenant que notre personnage et notre UI sont prêts, il est temps d'ajouter un peu de défi à notre jeu en créant des ennemis. Nous allons créer deux types d'ennemis : un Orc et une Mouche. C'est comme si on invitait deux invités indésirables à notre fête ! 🎉🚫

## Commençons par l'Orc 👹

### Variables 📊

Nous allons définir certaines variables pour notre Orc. Ces variables vont contrôler des choses comme la santé de l'Orc, etc.

(Pour ma part, les Orcs n'ont pas de variable au contact du tir de notre personnage, ils se détruisent directement, mais vous pouvez vous rajouter si vous le souhaitez des PV à votre Orc)

### Comportements 🧠 

Nous allons ajouter des comportements à notre Orc. Ces comportements vont contrôler comment l'Orc se déplace et vers quelle direction.

![ImagesOrc](Images/ComportementORC.png)

### Code 💻 
Enfin, nous allons écrire le code qui contrôle l'Orc. Ce code va utiliser les variables et les comportements que nous avons définis pour donner vie à l'Orc.

![ImagesCodeOrc](Images/CodeOrc.png)

## La Mouche 🦟

### Variables 📊
Nous allons définir certaines variables pour notre Mouche.

![VariableMouche](Images/VariableMouche.png)

### Comportements 🧠
Nous allons ajouter des comportements à notre Mouche. Ces comportements vont contrôler comment la Mouche se déplace, attaque.

![ComportementMouche](Images/ComportementMouche.png)

### Code 💻 
Enfin, nous allons écrire le code qui contrôle la Mouche. Ce code va utiliser les variables et les comportements que nous avons définis pour donner vie à la Mouche.

#### Déplacements et tirs 🚁🔫
Dans cette partie du code, nous allons définir comment la Mouche se déplace et tire. Nous allons utiliser le comportement "Pathfinding" pour faire en sorte que la Mouche suive le personnage du joueur. Nous allons également définir un intervalle de temps entre chaque tir de la Mouche pour qu'elle ne tire pas en continu.

![CodeMoucheP1](Images/CodeMoucheP1.png)

#### Dégâts 💥🩹 
Dans cette partie du code, nous allons définir comment la Mouche prend des dégâts. Lorsque la Mouche est touchée par un tir du personnage du joueur, nous allons réduire sa santé et la faire réagir en conséquence. Si la santé de la Mouche atteint zéro, nous allons la supprimer du jeu.

![CodeMoucheP2](Images/CodeMoucheP2.png)

Il est temps de passer à la partie des items. C'est comme si on préparait des cadeaux pour notre personnage à travers le monde du jeu ! 🎁🌍 Alors, prêts à créer des items pour notre personnage ? Allons-y ! 🚀🎉

[Items](https://github.com/g404-code-gaming/DoomLike_CodeGaming/blob/main/Création-Du-Jeu/06_Item%20(coeur%20%2B%20sac%20de%20munition%20).md)
