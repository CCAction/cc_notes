# Idées générales sur l'action "En vrac"

## Que présenter de Clean Code ?

Uniquement des choses qui restent générales, mais applicables.

* Ne pas présenter tout ce qui est concurrence

On the Cover
Introduction
Acknowledgments
Chapter 1: Clean Code
Chapter 2: Meaningful Names &hearts;
Chapter 3: Functions &hearts;
Chapter 4: Comments &hearts;
Chapter 5: Formatting
Chapter 6: Objects and Data Structures
Chapter 7: Error Handling
Chapter 8: Boundaries &hearts;
Chapter 9: Unit Tests
Chapter 10: Classes &hearts;
Chapter 11: Systems 
Chapter 12: Emergence
Chapter 13: Concurrency
Chapter 14: Successive Refinement
Chapter 15: JUnit Internals
Chapter 16: Refactoring SerialDate
Chapter 17: Smells and Heuristics
Appendix A: Concurrency II
Appendix B: org.jfree.date.SerialDate
Appendix C: Cross References of Heuristics
Epilogue
Index


## Développement logiciel

### une activité à ne pas négliger

Même si ce n'est pas votre activitée **principale**,
le développement logiciel est un **outil**
qui peut représenter un part **très importante**
de votre quotidien.

## Utiliser des outils
* Arrêter de bricoler
## Nécessité d'utiliser un gestionnaire de version
* Ne pas travailler uniquement sur son ordinateur
* Utiliser des IDEs

## Ce n'est pas perdre du temps

"Image: can't stop, too busy"

* Apprendre le langage 

* RTFM

  

### Mettre le code en sécurité

Utiliser un gestionnaire de version distant (SVN, Git)

* gitlab.u-psud.fr
* fournir d'autres références 

## Rendre son code transportable

* Favoriser le partage (directeur de thèse, collègue)
* Code reproductible

### Eviter l'effet

```
I Don't Understand...

¯\＿(ツ)＿/¯

It Works On My Machine
```

### Situation normale

Toute personne (collègue, directeur de thèse, reviewer, ...)
doit pouvoir lancer votre code avec *uniquement*

- Vos codes sources,
- La documentation; 
- Des outils courants (compilateur, runtime, build systems, ...).

### Indicateurs alarmants

Votre code ne **doit pas** fonctionner 

- Que sur votre ordinateur ou serveur (*),
- Que en votre présence,
- Que dans votre éditeur.



# Reprendre les chapitres de la présentation de la présentation sur la maintenabilité.

# Code for human

Principe de base à rappeler en toute circonstance

*Coder ce n'est pas un concours pour impressionner les crédules, c'est un outil !*

### Pourquoi bien coder ou coder en utilisant les bonnes pratiques
* Parce que tomber en marche ne suffit pas toujours
* Parce que celui qui sera le plus victime de votre mauvaise pratique ce sera vous-même.
  - En tant que relecteur, que mainteneur
  - 90% du temps vous lisez, 10% vous codez
* Un mauvais code ne donne pas envie de s'investir, c'est comme un mauvais livre
* 

