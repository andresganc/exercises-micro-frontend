
# GitHub to replace master with main starting in October: What developers need to do now

<br>

## Steps
### Step 1 - Move the master branch to ‘main’
### Step 2 - Push ‘main’ to remote repo
### Step 3 - Point HEAD to ‘main’ branch
### Step 4 - Change default branch to ‘main’ on GitHub site
### Step 5 - Delete ‘master’ branch on the remote repo

<br><br>


### Step 1 - Move the ‘master’ branch to ‘main’
Run the following command which creates a branch called ‘main’ using the history from ‘master’. Using the argument -m will transfer all of the commit history on the ‘master’ branch to your new ‘main’ branch so nothing gets lost.

$ git branch -m master main

<br>

<img src='../readme/img/steps-01.png' width="600" >

<br><br>


### Step 2 - Push ‘main’ to remote repo
Remember that git is version control software on your local machine and GitHub is the remote server that stores your code. For this reason, you’ll have to push your new ‘main’ branch up to GitHub and tell the local branch to start tracking the remote branch with the same name.

$ git push -u origin main

<br><br>


### Step 3 - Point HEAD to ‘main’ branch
At this stage if ‘master’ was your default branch you cannot remove it without first changing HEAD, the pointer to the current branch reference. This following command will point it to ‘main’.

$ git symbolic-ref refs/remotes/origin/HEAD refs/remotes/origin/main

All three steps are shown in the screenshot below:

At this point you can take a breather. You’re on the home stretch! If you want to check that things are going as planned then you’re welcome to run the following that should show the HEAD is pointing to main which now frees you up to delete ‘master’. Note: When you enter this command in your Terminal you will have to type :q to exit it. Not CTRL+C, ESC, etc.

git branch -a

<br>

<img src='../readme/img/steps-03.png' width="400" >


<br><br>


### Step 4 - Change default branch to ‘main’ on GitHub site
At this point you’ve succesfully transitioned everything to the ‘main’ branch, but you can’t delete the ‘master’ branch without changing the default branch in GitHub to something other than ‘master’. This is the only step that requires you to leave the Terminal and navigate in your browser to your GitHub repository. From there, click "Settings" -> "Branches" on the left rail and change the default branch to ‘main’. I’ve included some screenshots below and GitHub provides instructions for doing this here: https://docs.github.com/en/github/administering-a-repository/setting-the-default-branch.

<br>

<img src='../readme/img/step-04a-go-to-settings.png' width="600" >

<br>

<img src='../readme/img/step-04b-select-main-as-default.png' width="600" >

<br>

<img src='../readme/img/step-04c-confirm-change.png' width="600" >

<br><br>


### Step 5 

$ git push origin --delete master