# Documents of me

<b>1. Clone all last modifile in GitHub</b>

<code>git fetch --all</code>

git reset --hard origin/master

git pull origin master

#2. Show all Branch
git ls-remote

OR:
git branch -a

OR:
git branch -r

OR:
git remote show origin


#3. Add files to repository
Open Git Bash.

Change the current working directory to your local project.

Initialize the local directory as a Git repository.
git init

Add the files in your new local repository
git add . || git add <file_name.type>

Commit the files that you've staged in your local repository.
git commit -m "Desscription Details"

Sets the "new" remote (first)
git remote add origin <remote_repository_URL>

Verifies the new remote URL (second +)
git remote -v

Push the changes in your local repository to GitHub.
git push origin master || git push origin <branch_name>
