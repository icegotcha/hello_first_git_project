
# Command line instructions
## Git global setup

git config --global user.name "[my name]"
git config --global user.email "[my email]"

## Create a new repository

git clone [git url]
cd oauth
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

## Existing folder

cd existing_folder
git init
git remote add origin [git url]
git add .
git commit -m "Initial commit"
git push -u origin master

## Existing Git repository

cd existing_repo
git remote add origin [git url]
git push -u origin --all
git push -u origin --tags


