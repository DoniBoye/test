<h3>create a new repository on the command line:</h3><br>
echo "# test" >> README.md<br>
git init<br>
git add README.md<br>
git commit -m "first commit"<br>
git branch -M main<br>
git remote add origin https://github.com/DoniBoye/test.git<br>
git push -u origin main<br>
<br>
<h3>push an existing repository from the command line:</h3><br>
git remote add origin https://github.com/DoniBoye/test.git<br>
git branch -M main<br>
git push -u origin main<br>
<br>
<h3>First time:</h3><br>
git remote add origin https://github.com/DoniBoye/test.git<br>
git init<br>
git branch -M main<br>
<br>
<h3>commiting:</h3><br>
git add .<br>
git commit -m "first commit"<br>
git push -u origin main/git push<br>
<br>
<h3>create new branch:</h3><br>
git branch [branch name]<br>
git checkout [branch name] (switch to the branch)<br>
<br>
<h3>send pull request:</h3><br>
git add .<br>
git commit -m "edit title"<br>
git push --set-upstream origin [github name]<br>
<br>
<h3>get master</h3><br>
git pull<br>