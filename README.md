create a new repository on the command line:<br>
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/DoniBoye/test.git
git push -u origin main

push an existing repository from the command line:<br>
git remote add origin https://github.com/DoniBoye/test.git
git branch -M main
git push -u origin main

First time:<br>
git remote add origin https://github.com/DoniBoye/test.git
git init
git branch -M main

commiting:<br>
git add .
git commit -m "first commit"
git push -u origin main/git push

create new branch:<br>
git branch [branch name]
git checkout [branch name] (switch to the branch)

send pull request:<br>
git add .
git commit -m "edit title"
git push --set-upstream origin [github name]