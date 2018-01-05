# <font color="red">Documents of me</font>

<b>#1. Clone all last modifile in GitHub</b>

<code>git fetch --all</code>

<code>git reset --hard origin/master</code>

<code>git pull origin master</code>

<b>#2. Show all Branch</b>

<code>git ls-remote</code>

<b><i>OR:</i></b>

<code>git branch -a</code>

<b><i>OR:</i></b>

<code>git branch -r</code>

<b><i>OR:</i></b>

<code>git remote show origin</code>


<b>#3. Add files to repository

• Open Git Bash.

• Change the current working directory to your local project.

• Initialize the local directory as a Git repository.

<code>git init</code>

• Add the files in your new local repository

<code>git add . || git add <file_name.type></code>

• Commit the files that you've staged in your local repository.

<code>git commit -m "Description Details"</code>

• Sets the "new" remote (first)

<code>git remote add origin <remote_repository_URL></code>

• Verifies the new remote URL (second +)

<code>git remote -v</code>

• Push the changes in your local repository to GitHub.

<code>git push origin master || git push origin <branch_name></code>
