# Summary #

### Git ### 
- It is version control system.
- Where multiple developers work on the same code.
- Get keeps a history.
- Each time you save a changed version of your project Git creates a snapshot of the file and stores a reference to it.
- If the file has not changed, Git only stores a reference to the already-stored identical version of it.
### GitHub ###
- Way to shre code with others.
- An online placeto store your code.
### Commit ###
- Commit means "save as".
- New snapshot means new commit.
- Every commit has label message and ID.
# Git+GitHub=awesome #

Files in Git can reside in three main states: 
##### committed, modified and staged. #####

###### Committed ######
Data is securely stored in a local database.

###### Modified ######
File has been changed but not committed to the database.

###### Staged ######
Flagged a file’s changed version to be committed in the next snapshot.

 ### Cloning ###
 A copy of an existing Git repo from a particular server by using the clone command with a repository’s URL:$ git clone https://github.com/test .

We do this commands :
- git clone :Create a copy.
- code .
- git status:See information regarding change.
- git add :After using these commands, file are tracked and staged for committing.
- git commit -m "your msg":This step has committed changes for the file or files (you can have one commit message for multiple files, if applicable) to the HEAD.
- git push origin master :This command pushes changes from the local “master” branch to the remote repository named “origin”.
- git remote -v :You can view all the remote URLs next to their corresponding short names.
