* More on Git

+    ‘Branching’ is a feature of Git that allows a project to move in multiple different directions simultaneously. There is one master branch that is always usable, but any number of new branches can be created to develop new features. Once ready, these branches can then be merged back into master.
+    When working in a Git repository, HEAD refers to the current branch being worked on. When a different branch is ‘checked out’, the HEAD changes to indicate the new working branch.
+ When merging a branch back into master, there is the possibility for merge conflicts to arise. These can be resolved in the same way discussed in Lecture 0.
+    Some Git commands related to branching:

    +   git branch : list all the branches currently in a repository
    +   git branch <name> : create a new branch called name
    +    git checkout <name> : switch current working branch to name
    +    git merge <name> : merge branch name into current working branch (normally master)

+ Any version of a repository that is not stored locally on a device is called a ‘remote’. ‘Origin’ is used to refer to the remote from which the local repository was originally downloaded from.