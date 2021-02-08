# Workshop Github et Gitkraken !

Ce workshop a pour but de vous faire comprendre comment fonctionne les issues GitHub et l'outil Gitkraken à travers quelques exercices pratiques contenant des situations complexe qui peuvent vous arrivez lorsque vous travailler en groupe.

Notamment :

* Fork un repo
* Paramètrer son GitKraken
* Résoudre des conflits de branches et de commits
* Récuperer le commit d'une autre branche
* Mettre un jour une branche avec le master/main
* Gérer vos branches
* Créer, récupérer, modifier ou supprimer des stashs
* Rename un commit

A chaque fin d'exercice, une explication sera faite pour vous expliquer comment correctement effectuer les actions nécessaires pour résoudre l'exercice.

Quelques liens qui pourront vous être utiles :

* [GitKraken](https://www.gitkraken.com/)
* [Ressources GitKraken](https://support.gitkraken.com/)
* [GitKraken Documentation](https://www.gitkraken.com/downloads/gitkraken-cheat-sheet-v1.6.pdf)
* [Cherry Pick](https://support.gitkraken.com/working-with-commits/cherrypick/)

Pour ce workshop, vous aurez besoin de `Gitkraken` disponible via le lien au dessus. GitKraken est un logiciel avec une version gratuite et payante, la version payante est disponible gratuitement si vous êtes étudiant (Epitech) à l'aide du Student Pack Github via [ce lien](https://education.github.com/pack).

*N.B: Il est préférable d'avoir la version payante qui est disponible jusqu'à la fin de vos études mais sous vous n'avez pas encore le Student Pack ou si vous ne pouvez pas l'avoir vous pouvez sauter certains exercices, nous ferons l'explication directement sur Discord*

# 0 - Init

Pour le première exercice nous vous demandons d'installer GitKraken et de préparer l'environnement.

Pour cela :

* Installer [GitKraken](https://www.gitkraken.com/)
* [Fork](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) ce répertoire Github
* Cloner le fork de ce répertoire
* Lancer GitKraken et ouvrir le dossier que vous venez de cloner

Tout devrais être bon maintenant, faites attention à bien cloner votre répertoire et pas celui là, c'est obligatoire pour passer à la suite.

# 1 - Static Analysis and ASM

*Challenge Name: translate_me*

Static analysis is the process of studying a program without running it.
To do so, we can use GDB to interpret the asm code in binary form to plaintext binary.
Then we read this code and deduce the way the program work.
So go ahead and open *translate_me* with `gdb ./translate_me` !
To display the asm instructions of a function, use `pdisas function_name` or `pd function_name`.

The purpose of this challenge is not to find a flag but to translate the asm code you get with gdb to C code.