# GitDemo
# https://education.github.com/git-cheat-sheet-education.pdf

setup 
git config --global user.name "name"
git config --global user.email "email"

download the git repository:
Clone: $git clone https://github.com/xinx9/GitDemo.git

branching:
what branch are you on:
$git branch
create a new branch:
$git branch new-branch-name
change branch:
$git checkout branch-name
mergeing:
$git merge branch-name

staging your files:
$git add (filename)
$git add *

see staged files:
$git status

commit your staged files:
$git commit -m "commit message"
$git push

get new changes
$git pull

accidently worked on master?
$git stash
$git stash apply

