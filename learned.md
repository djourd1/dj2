# Git basic commands

## Monter-descendre des fichiers

+ `git clone https://github.com/djourd1/dj2.git`  : clone un site qui est disponible sur git
+ `git add xx.html`  : va tracker le fichier xx.html
+ `git commit -m "message"` va faire une photographie des fichiers qui sont suivis et attache un message
+ `git push`   va pousser les fichiers vers leur version cloud
+ `git pull`   va descendre les versions cloud des fichiers

Discussion sur la résolution de conflit quand on a utilisé pull ou push. Il se peut que les deux versions ne soient pas au meme niveau.



## Autres commandes utiles

+ `git status`
+ `git log`
+ `git reflog`
+ git reset --hard numerodehashcorrespondant
+ git reset --hard origin/master

When combining different versions of code, e.g. using `git pull`, a merge conflict can occur if the different versions have different data in the same location. Git will try to take care of merging automatically, but if two users edit, for example, the same line, a merge conflict will have to be manually resolved.

*To resolve a merge conflict, simply locally remove all lines and code that are not wanted and push the results.*
