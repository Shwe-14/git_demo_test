# startup_namer

A new Flutter application.

## Making Contribution

### Step 1: Git Clone

Clone the repository into your local machine using HTTPS or SSH.

<img alt="git clone ssh" src="git_clone_ssh.png" width="300">  

`git clone git@github.com:Shwe-14/git_demo_test.git`

<img alt="git clone ssh" src="git_clone.png" width="600">  

### Step 2:  Git Status/ Add/ Commit

Before creating a new branch, you have to do the following steps.  

1. `git status` (to see the changes.)  
<img alt="git clone ssh" src="git_status.png" width="600">  

2. `git add .` (to add the changes to a stage.)  
<img alt="git clone ssh" src="git_add.png" width="400">  

3. `git commit -m "commit_message"` (to confirm the changes with a commit message.)  
<img alt="git clone ssh" src="git_commit.png" width="700">  

### Step 3:  Git Branch

Create a branch. Give the branch name something related to the feature you will work on or a bug supposed to be fixed. 
For example, `user_login_screen` or `login_error_fix`.  

1. `git checkout -b branch_name` (To create a new branch.)  
<img alt="git clone ssh" src="git_checkout.png" width="500">  

2. `git branch` (To see branches you have.)  
<img alt="git clone ssh" src="git_branch.png" width="150">  

3. `git checkout main` (To switch back to main branch)  
<img alt="git clone ssh" src="git_checkout_main.png" width="400">  

Note: You cannot checkout of a branch without commiting first.  

### Step 4: Git Push  

Now you have made changes in one of the branches, and you have to push it to Github.  
`git push origin branch_name`  

### Step 5: Github Pull Request  

After pushing your `branch_name` to github, now you have to do change branchin Github UI.  

### Step 6: Git Pull  

Now your newly created `branch_name` is updated, and you need to merge with `main` branch.  
`git pull origin main`  

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
