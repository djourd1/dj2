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

# Branching

Branching is a feature of Git that allows a project to move in multiple different directions simultaneously. There is one master branch that is always usable, but any number of new branches can be created to develop new features. Once ready, these branches can then be merged back into master.

When working in a Git repository, HEAD refers to the current branch being worked on. When a different branch is ‘checked out’, the HEAD changes to indicate the new working branch.

When merging a branch back into master, there is the possibility for merge conflicts to arise. These can be resolved in the same way discussed in Lecture 0.

Some Git commands related to branching:

    +   git branch : list all the branches currently in a repository
    +   git branch <name> : create a new branch called name
    +    git checkout <name> : switch current working branch to name
    +    git merge <name> : merge branch name into current working branch (normally master)

Any version of a repository that is not stored locally on a device is called a ‘remote’. ‘Origin’ is used to refer to the remote from which the local repository was originally downloaded from.