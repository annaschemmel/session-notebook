Create new repository in Github

1. New repository
   Choose myself as owner
   Select SSH to retrieve the git-link

Create and link local repository

1. Create a new local repository: "git init"
   -> to check if a folder is a repo: "ls -la", this shows hidden folders and if there's a file called .git it's a repository
2. Add the items that should be shared: "git add <filename>" or "git add \*"
   -> files/folders are now in Staging
   -> to moved back files back from staging to workspace: "git restore --staged <filename>"
3. Move the items from staging to local repo: "git commit -m "<commit message>" "
   -> files are now in local repository
4. Link the repository created in Github to the local repo: "git remote add origin <link from github>"
   -> linked remote repositories can be checked with "git remote -v"
5. Push the items from the local repo to remote repo (github): "git push origin main"
   -> files should now be in github repository
