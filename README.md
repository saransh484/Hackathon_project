# C++ Repo for Clg

this is my college C++ repository!

```
Git global setup
-  -  -  -  -  -
git config --global user.name "Saransh Bhatnagar"
git config --global user.email "saransh8@hotmail.com"
-------------------------------------------------------
Create a new repository
-  -  -  -  -  -  -  -
git clone https://gitlab.com/saransh_repo/portfolio.git
cd portfolio
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
-------------------------------------------------------
Push an existing folder
-  -  -  -  -  -  -  - 
cd existing_folder
git init
git remote add origin https://gitlab.com/saransh_repo/portfolio.git
git add .
git commit -m "Initial commit"
git push -u origin master
--------------------------------------------------------
Push an existing Git repository
-  -  -  -  -  -  -  -  -  -  -
cd existing_repo
git remote rename origin old-origin
git remote add origin https://gitlab.com/saransh_repo/portfolio.git
git push -u origin --all
git push -u origin --t
```
yeah  mabn