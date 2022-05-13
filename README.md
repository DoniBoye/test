create a new repository on the command line:<br>
echo "# test" >> README.md<br>
git init<br>
git add README.md<br>
git commit -m "first commit"<br>
git branch -M main<br>
git remote add origin https://github.com/DoniBoye/test.git<br>
git push -u origin main<br>
<br>
push an existing repository from the command line:<br>
git remote add origin https://github.com/DoniBoye/test.git<br>
git branch -M main<br>
git push -u origin main<br>
<br>
First time:<br>
git remote add origin https://github.com/DoniBoye/test.git<br>
git init<br>
git branch -M main<br>
<br>
commiting:<br>
git add .<br>
git commit -m "first commit"<br>
git push -u origin main/git push<br>
<br>
create new branch:<br>
git branch [branch name]<br>
git checkout [branch name] (switch to the branch)<br>
<br>
send pull request:<br>
git add .<br>
git commit -m "edit title"<br>
git push --set-upstream origin [github name]<br>