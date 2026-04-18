I am Brady.  One of my hobbies is painting.

Below are some git commands:

# ITM350

git remote -v
# Check if your repository has a remote, and show the url with the -v or verbose flag (meaning tell me everything including the url)

git remote add origin __________ 
# Add a remote to the local repository called origin with the url specified 

git push -u origin main 
# Set the local branch to push to the remote branch with the same name, and push changes (includes new files) you have made 

git pull 
# Pulls code that was changed on the remote but is not yet on your local

git status
# What is the status of my files? 
--This tells you files that have been changed, but not added (red), and 
--Those that are added but not committed (green)

git add . 
# Adds the filename specified for the next commit 

git commit -m "__________________" 
# Creates a local commit with the message specified 

git push 
# Pushes the changes you have made locally to the remote repository


git checkout main
Changes your local repository to point to the the main branch


git pull 
Updates your local main with the changes made to the remote main


git checkout ________
--switches your local to point to the _________ feature branch
--This may be the first time you've seen the reference feature branch. It isn't as complicated as you may think. When something is referred to as a feature branch it just means that the branch in question is being used for a specific feature in the software you are using. Let's say you're making a video game and you wanted to add a jump functionality to the hero you play as. If you made a new branch that was specifically made to implement the jump functionality that jump branch would be considered a feature branch.

git merge main 
--Updates the ________ feature branch with the new updates to main
--Now we go into the file and decide which changes to keep. current change is your own changes in your local repository incoming change is the new change you got from the main branch 
--After that we delete all the ======== and other symbols. 
--To tell Git we have resolved the conflict: 

git add ** 
--Add the files we fixed to the new commit 

git commit -m "Merged changes from main" 
--Make a commit message git push or 

git push -u origin main 
--Push the change on your local feature branch to the remote feature branch
