<h2>create a new repository on the command line:</h2><br>
echo "# test" >> README.md<br>
git init<br>
git add README.md<br>
git commit -m "first commit"<br>
git branch -M main<br>
git remote add origin https://github.com/DoniBoye/test.git<br>
git push -u origin main<br>
<br>
<h2>push an existing repository from the command line:</h2><br>
git remote add origin https://github.com/DoniBoye/test.git<br>
git branch -M main<br>
git push -u origin main<br>
<br>
<h2>First time:</h2><br>
git remote add origin https://github.com/DoniBoye/test.git<br>
git init<br>
git branch -M main<br>
<br>
<h2>commiting:</h2><br>
git add .<br>
git commit -m "first commit"<br>
git push -u origin main/git push<br>
<br>
<h2>create new branch:</h2><br>
git branch [branch name]<br>
git checkout [branch name] (switch to the branch)<br>
<br>
<h2>send pull request:</h2><br>
git add .<br>
git commit -m "edit title"<br>
git push --set-upstream origin [github name]<br>