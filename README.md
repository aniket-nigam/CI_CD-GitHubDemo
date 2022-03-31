This is a README.md file for GIT.


#Course 24

History and Making New Command with Alias

git log --oneline --graph --decorate --all # Used for viewing git logs in a graph format

git config --global alias.hist "log --oneline --graph --decorate --all" # Creating an alias for a command for a user

git config --global --list # View the list of the configs crated by the user

#Course 25 (Rename and Deleting a File)

git mv example.txt example_renamed.txt # Renaming a file from example.txt to example_renamed.txt

git rm example_renamed.txt # Deleting a file

#Course 26 (Managing File Outside GIT)

git add -A # Used for adding the files which are renamed or which are newly created 

#Course 32 (Simple Branching Example)

git branch # To see the list of all the branches 

git checkout -b branch_name # To switch to a different branch

git merge updates # Commit to the HEAD branch

git branch -d branch_name # To delete a branch in GIT 

#Course 35 (Saving work in Progress with Stashing)

git stash pop # Applies the stash and delets the applied stash from stashing area


#Course 42 (To verify if their is a remote branch)
 
git remote -v # Verify is their is a remote branch associated with the current repo

git remote add origin https://github.com/aniket-nigam/CI_CD-GitHubDemo.git # Add a new Repository to GitHub

#Course 46 (GitHub Authentication) 
 
