# How to Update the GitHub Repository

After making any changes to the project directory (adding files, modifying existing ones, etc.), follow the steps below to update the repository on GitHub.

## Steps to Push Changes to GitHub

#### - Check the current status of your repository: This will show you the changes that have been made (files added, modified, or deleted).

`git status`

#### - Stage the changes: Add the changes you want to commit. You can stage all files or specific files:
####To stage all changes:

`git add .`

####To stage specific files:

`git add <file1> <file2>`

#### - Commit your changes: After staging the files, commit them with a descriptive message about the changes:

`git commit -m "Describe the changes made"`

#### - Push the changes to GitHub: Once the commit is made, push the changes to the main branch (or any other branch you're working on):

`git push origin main`

#### - Check the repository on GitHub: Visit the repository on GitHub to confirm that your changes have been successfully uploaded.

#### - If you've made a mistake or need to revert changes, use:

`git reset <file>`

#### - If you need to pull the latest changes from GitHub before making any new changes:

`git pull origin main`
