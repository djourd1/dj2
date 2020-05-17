---
title: What have we leared
author: Damien Jourdain
rights:  Creative Commons Non-Commercial Share Alike 3.0
language: en-US
...

# Git basic commands

## Monter-descendre des fichiers

+ `git clone https://github.com/djourd1/dj2.git`  : clone un site qui est disponible sur git
+ `git add xx.html`  : va tracker le fichier xx.html
+ `git commit -m "message"` va faire une photographie des fichiers qui sont suivis et attache un message
+ `git push`   va pousser les fichiers vers leur version cloud
+ `git pull`   va descendre les versions cloud des fichiers

Discussion sur la résolution de conflit quand on a utilisé pull ou push. Il se peut que les deux versions ne soient pas au meme niveau.



## Autres commandes utiles

+ `git log`
+ `git reflog`
+ git reset --hard numerodehashcorrespondant
+ git reset --hard origin/master