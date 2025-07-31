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

```
### Exercise 2 Bundle 1

```bash
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
```
### Exercise 1 Bundle 2
``` bash
   git branch ft/bundle-2
   git checkout ft/bundle-2
    touch services.html
    git add services.html
    git commit -m "added the page  of services"
    git push -u origin ft/bundle-2        
    git checkout main
    created a pull request and merge branches on Github
    history
```
 ### Exercise 2 Bundle 2
 ``` bash
  git checkout main   

   70  git pull origin main   
   git branch ft/service-redesign  
   71  git checkout ft/service-redesign
   72 
   
   75  git add service.html     
   76  git add services.html    
   77  
   78  git commit -m "updated Files"
   79  git push -u ft/service-redesign
   git checkout main
   git add services.html
   git commit -m "updated"
   git push
   git checkout ft/service-redesign
   git diff main ft/service-redesign
   git merge main
   git add service.html
   git commit -m "updated"
   git push 
```
  ### Exercise 1 Bundle 3

```  bash

   
  
git checkout -b ft/team-page

touch team.html
team.html
git commit -m "feat: add team.html with team content"
git push -u origin ft/team-page
```
### Exercise 2 Bundle 3
``` bash
git checkout main

git checkout -b ft/contact-page

git checkout ft/team-page




git checkout ft/contact-page
git cherry-pick 6b6b295

git push -u origin ft/contact-page

git checkout -b ft/faq-page

touch faq.html
git add faq.html
git commit -m "feat: add faq.html "
git push -u origin ft/faq-page
git checkout ft/team-page
git revert 6b6b295

git push origin ft/team-page
```

### Bundle 4 exercise 1
``` bash
54  git checkout main
   55  git remote add git-copy https://github.com/Raissa12best/Gym-Git-Copy.git
   56  git remote -v
   57  git push git-copy main
   58  git add .
   59  git commit -m "Updated version"   
    git push origin HEAD
   61  git push git-copy HEAD
   62  git remote -v
   63  history
   ```
   ### Bundle 4 Exercise 2
   ``` bash
   git branch ft/footer
   65  git checkout ft/footer
   66  git add home.html
   67  git commit -m " feat : add basic footer section"
   68  git add home.html
   69  git commit -m "footer text"    
   70  git push -u origin ft/footer   
   71  git checkout main
   72  git branch ft/squashing        
   
   73  git checkout ft/squashing      
   74  git merge --squash ft/footer   
   75 git commit -m " footer changes 
squashing"
   76 git push -u origin ft/squashing
```
