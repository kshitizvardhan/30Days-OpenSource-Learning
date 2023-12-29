# Understanding Git (Local Repo) and GitHub (Remote Repo)

### Create a new repository on GitHub :
1. Go to the GitHub website(www.github.com) to create an account, it’s free.
2. Once you have created an account and signed in, go to the top-right and click on the plus arrow to a create a new repository.
3. After clicking on a new repository, a new tab will be opened and you need to name your repo. Next, scroll down and click on Create repository (green button)

### Branching and Merging
- git branch: Shows which branch you are working on
- git branch \<name of the branch you want to create >: Will create a new branch.
By using git branch, it shows below that we have two branches main or master and working-branch. The asterisk sign let us know which branch you are working on.
- git checkout: it makes you switch from one branch to another. Now, let’s switch to my working-branch.
- syntax: git checkout \<name of the branch you would like to switch to>

- Next, I am going to use respectively the following commands : git add., git status and git commit. At this point, you are familiar with those commands.

### Merging
- We need to switch to the main or master branch before we could initiate any merging.
- git merge \<name of the branch you would like to merge with>:
- After merging both branches, git push to transfer from local repo to GitHub repo the commit that is made.

#### Back to the GitHub repo, you can see that it has been updated.
