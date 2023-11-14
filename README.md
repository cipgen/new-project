# Instructions

1. Create a new directory named "new-project" in your environment. 
	**mkdir new-project**
2. Navigate to the "new-project" directory.
	**cd new project**  
3. Initialize a new public Git repository inside the "new-project" directory.
	**git init** 
4. Create a new file named "README.md" and add initial text to it.
	**touch README.md**
5. Stage the "README.md" file for commit.
	**git add README.md**
6. Commit the changes to the repository with the commit message "init."
	**git commit -m "init"**
7. Create a new branch named "development" and switch to it.
	**git branch development**
	**git switch development**
8. Add instructions to the "README.md" file and stage them for commit.
	**nano README.md** --> add instructions
	**git add README.md**
9. Commit the changes in the "development" branch with a commit message.
	**git commit -m "add instructions to README.md"**
10. Merge the changes from the "development" branch into the "main" branch.
	**git switch master**
	**git merge development**
11. Check the status to ensure everything is up-to-date.
	**git status**
12. Commit the changes.
	**git branch -M main**
	**git remote add origin https://github.com/cipgen/new-project.git**
	**git push -u origin main**
