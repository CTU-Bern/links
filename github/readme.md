# Useful stuff for github and/or git

[Happy git with R](https://happygitwithr.com/) a bookdown site from Jenny Bryan. Particularly useful are 
 - [Connect RStudio to git and github](https://happygitwithr.com/rstudio-git-github.html)
 - chapters 15-17 on projects (I generally go down the route of [chapter 16](https://happygitwithr.com/existing-github-first.html))

[Learning git branching](https://learngitbranching.js.org/) is a nice interactive tool for learning git

[OH MY GIT!](https://ohmygit.org/) game for learning git


## github markdown

[Githubs flavour of markdown](https://guides.github.com/features/mastering-markdown/)


# Some commands

```
git clone path-to-your-forked-repo
git remote ctu path-to-ctu-main-repo
```


## Merge upstream repo into your fork

```
git pull https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git BRANCH_NAME
git commit -i * -m 'merge with upstream master'
```

Ref:  
https://help.github.com/en/articles/merging-an-upstream-repository-into-your-fork  
https://stackoverflow.com/questions/5827944/git-error-on-commit-after-merge-fatal-cannot-do-a-partial-commit-during-a-mer  

You can also define a remote...
```
# only necessary once
git remote REMOTE_NAME https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git
# pull via
git pull REMOTE_NAME BRANCH_NAME
```
...which normally automatically merges and commits.

## Push local branch to origin (i.e. github) 
E.g. if you've created a branch while not being connected to the internet...
```
git push origin develop
```

Ref:  
https://www.git-tower.com/learn/git/commands/git-push

## Renaming a branch
Could be useful...

Ref:  
https://www.hostinger.com/tutorials/how-to-rename-a-git-branch/
