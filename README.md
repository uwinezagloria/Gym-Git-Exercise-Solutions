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
  