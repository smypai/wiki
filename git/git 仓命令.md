```
Git global setup
git config --global user.name "smypai1"
git config --global user.email "smypai@hotmail.com"
Create a new repository
git clone git@gitlab.com:smypai1/wiki.git
cd wiki
git switch -c main
touch README.md
git add README.md
git commit -m "add README"
git push -u origin main
Push an existing folder
cd existing_folder
git init --initial-branch=main
git remote add origin git@gitlab.com:smypai1/wiki.git
git add .
git commit -m "Initial commit"
git push -u origin main
Push an existing Git repository
cd existing_repo
git remote rename origin old-origin
git remote add origin git@gitlab.com:smypai1/wiki.git
git push -u origin --all
git push -u origin --tags