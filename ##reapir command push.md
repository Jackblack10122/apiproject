##reapir command push 


PS C:\Users\jlaffont\Documents\Apiproject> git fetch origin
PS C:\Users\jlaffont\Documents\Apiproject> git rebase
There is no tracking information for the current branch.
Please specify which branch you want to rebase against. 
See git-rebase(1) for details.

    git rebase '<branch>'

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> main

PS C:\Users\jlaffont\Documents\Apiproject> git rebase main
Current branch main is up to date.
PS C:\Users\jlaffont\Documents\Apiproject> git push origin HEAD:main