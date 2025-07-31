# Gym-Git-Exercise-Solutions
## Bundel 1
### Exercise 1
``` bash
  git init
  git add --all
  git commit -m "exercise 1"
  git remote add origin "https://github.com/Raissa12best/Gym-Git-Exercise-Solutions.git"
  git push -u origin
  git push -u origin main
  git branch "dev"
  git checkout dev
  git branch "test"
  git branch
  git branch -D test


Exercise 2 Bundle 1


 touch home.html
    git add home.html
     git stash push -m "Added home.html" home.html
    touch about.html
    git add about.html
    git stash push -m"Added about.html"
    touch team.html
    git add team.html
    git stash push -m "Added team.html"
    git stash list
    git stash pop stash@{1}    
    git stash pop stash@{2}    
    git stash pop stash@{2}    
   git stash pop stash@{2}    
    git stash list
    git stash pop stash@{1}    
    git add --all
     git commit -m "After Git stash pop changes"
     git push
    git stash pop stash@{0}    
     git reset --hard
     history
Exercise 1 Bundle 2

git fetch origin
   git status
   git log origin/main
   git diff origin/main
   git branch ft/bundle-2
   git checkout ft/bundle-2
    touch services.html
    git add services.html
    git commit -m "added the page  of services"
    git push -u origin ft/bundle-2        
    git checkout main
    created a pull request and merge branches on Github
    history