# Gym-Git-Exercise-Solutions
## Bundle 1
### Exercise 1
``` bash
 mkdir bundles
     cd bundles
     git init
    git branch -m "main"
     git add .
     git commit -m "my first git "
git remote add origin "https://github.com/uwinezagloria/Gym-Git-Exercise-Solutions.git"
  git push -u origin main
   git branch "dev"
  git checkout dev
     git branch "test"
    git branch
    git branch -D test
   ``` 
### Exercise 2
    ``` bash
      git add home.html
     git stash push -m "home.html"
     git add about.html
    git stash push -m "about.html"
    git add team.html
     git stash push -m "team .html"
     git stash list
     git stash pop stash@{2}
     git stash pop stash@{1}
      git commit -m "home and about page"
     git push
    git reset --hard
    git clean -fd
    ``` 
  ## Bundle 2
   ### Exercise 1
   ```  bash 
   git branch "ft/bundle-2"
    git checkout "ft/bundle-2"
     git add service.html
    git commit -m "Add services.html page"
   git push -u origin ft/bundle-2
  ```
### Exercise 2   
```bash
 git checkout main
    git pull origin main
    git checkout -b "ft/service-redesign"
    git add .
    git commit -m "adding paragraph in service.html page"
    git push -u origin ft/service-redesign
    git checkout main
    git add .
    git commit -m "adding welcome message to service.html page"
    git push
    git add .
    git commit -m "adding paragraph to service.html page"
   git push
   git checkout ft/service-redesign
   git diff main..ft/service-redesign 
   git checkout main
   git pull origin main
    git merge ft/service-redesign
 git add .
   git commit -m "paragraph merged"
   git push
```
## Bundle 3
### Exercise 1
``` bash
git checkout -b ft/team-page
git add team.html
git commit -m "Add team.html page"
git push -u origin ft/team-page
git checkout main
git checkout -b ft/contact-page
git checkout ft/team-page
git log -1
git checkout ft/contact-page
git cherry-pick dd74e47072fda1811e054a1d1a931326fda94c51
git add contact.html
git commit -m "Add contact.html page"
git push -u origin ft/contact-page
git checkout -b ft/faq-page
git add faq.html
git commit -m "Add faq.html page"
git push -u origin ft/faq-page
git checkout ft/team-page
git log
git revert dd74e47072fda1811e054a1d1a931326fda94c51
git push origin ft/team-page
```
### Exercise 2
``` bash
git checkout ft/faq-page
    git branch ft/home-page-redesign
     git checkout main
     git add .
     git commit -m "adding welcome paragraph to index page"
     git push
     git checkout ft/home-page-redesign
     git rebase main
     git add .
  git commit -m "adding paragraph to home page"
    git push -u origin ft/home-page-redesign


