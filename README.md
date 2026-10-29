# experiment-2
exploriing git and github commands. 

## Important Git Commands

git --version – Checks the installed Git version.
git config --global user.name "Name" – Sets your Git username.
git config --global user.email "email" – Sets your Git email address.
git init – Initializes a new Git repository.
git clone <URL> – Copies a remote repository to a local system.
git status – Displays the current working-tree status.
git add . – Stages all changes for a commit.
git add filename – Stages a specific file.
git commit -m "message" – Records staged changes in the repository.
git log – Displays the commit history.
git log --oneline – Displays commit history in a compact format.
git branch – Lists local branches.
git branch feature – Creates a new branch named feature.
git switch feature – Switches to the specified branch.
git merge feature – Merges the specified branch into the current branch.
git remote -v – Displays remote repository URLs.
git remote add origin <URL> – Connects the local repository to a remote GitHub repository.
git push – Uploads local commits to a remote repository.
git push origin main – Pushes the local main branch to GitHub.
git push -u origin main – Pushes the main branch and sets its upstream.
git pull – Retrieves and integrates remote changes.
git pull origin main – Fetches and integrates changes from the remote main branch.
git fetch origin – Downloads updates from the remote repository without merging them.
git diff – Displays unstaged changes.
git restore filename – Discards unstaged changes in a file.
git restore --staged filename – Removes a file from staging while preserving its changes.
git rm filename – Removes a tracked file and stages the deletion.
git mv oldname newname – Renames or moves a tracked file.
git show – Displays details of a commit.
git switch -c feature – Creates and switches to a new branch.
git branch -d feature – Deletes a merged local branch.
git reset --soft HEAD~1 – Undoes the latest commit while keeping its changes staged.
git tag – Lists available tags.
git help – Displays help for Git commands.
