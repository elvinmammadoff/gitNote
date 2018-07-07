# gitNote

<h3>Adding an existing project to GitHub using the command line</h3>
https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/

1. Create a new repository on GitHub. 
2. Change the current working directory to your local project in terminal.
3. Initialize the local directory as a Git repository. <strong>git init</strong>
4. Add the files in local repository. <strong>git add .</strong>
5. Commit the files. <strong>git commit -m "First commit"</strong>
6. Copy the remote repository URL and add where your local repository will be pushed. <br/>
    <em>(Sets the new remote)</em> <strong>git remote add origin remote repository URL</strong><br/>
    <em>(Verifies the new remote URL)</em> <strong>git remote -v</strong>
7. Push the changes to GitHub. <strong>git push -u origin master

<hr>

<h3>Exit from the text window in Git?</h3>
http://vimdoc.sourceforge.net/htmldoc/editing.html#:wq
<br/>
[Esc] <strong>:wq</strong> 

<hr>

<h3>rejected master -> master (non-fast-forward)</h3>
<p>I'm trying to push my project (all files in a new repository). I follow the steps but when I push with git push -u origin master I get this error:</p>
<strong>git push origin master --force</strong>

<hr>

<h3>Moving Git repository content to another repository preserving history</h3>
https://stackoverflow.com/questions/17371150/moving-git-repository-content-to-another-repository-preserving-history
<srtong>
cd repo2<br/>
git checkout master<br/>
git remote add r1remote **url-of-repo1**<br/>
git fetch r1remote<br/>
git merge r1remote/master --allow-unrelated-histories<br/>
git remote rm r1remote
</strong>
<p>After that repo2/master will contain everything from repo2/master and repo1/master, and will also have the history of both of them.</p>

<hr>

<h3>Copying a GitHub Repository to Your Local Computer</h3>
https://www.youtube.com/watch?v=O72FWNeO-xY


clone repo: <strong>git clone [URL]</strong><br/>
list files: <strong>ls</strong><br/>
change directory: <strong>cd</strong><br/>
check remotes: <strong>git remote -v</strong><br/>
add origin: <strong>git remote add origin [URL]</strong>
