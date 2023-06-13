### This README contains instructions on how to create required GitHub repository.

Note: GitHub no longer supports authorization in terminal via login and password. In order to push to GitHub from terminal install GitHub CLI, run `gh auth login` and follow instructions to authorize.

1. Create [new public repository](https://github.com/new) with the name "new-project" (keep other settings as default).
2. Create folder "new-project" in your environment.

`mkdir new-project`

3. Initialize a git repository in it.

`cd new-project`

`git init`

4. Create "development" branch and switch to it.

`git branch development`

`git switch development`

5. Add and commit changes.

`git add .`

`git commit -am 'Added "development" branch'`

6. Switch back to main branch and merge "development" branch into it.

`git switch main`

`git merge development`

7. Add and commit changes.

`git add .`

`git commit -am '"Development" branch merged'`

8. Add your GitHub repository as remote and push to it.

`git remote add origin https://github.com/<your_GitHub_account_name>/new-project.git`

`git push -u origin main`
