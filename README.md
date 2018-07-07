# gitNote

<h3>Adding an existing project to GitHub using the command line</h3><br/>
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
