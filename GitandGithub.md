# Git & GitHub

## 1. What is a Version Control System?

> Version control, also known as source control, is tracking and managing software code changes.

Famous VCS:

<ul>
<li>Git (Most Famous) </li>
<li>Apache SubVersion </li>
<li>Piper (Used by Google) </li>
</ul>

## 2. Introduction to Git VCS

<ul>
<li>What is Git?
<ul>
    <li>Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. 
    </li>
</ul>

 </li>
<li>Installation of Git CLI: <a> https://www.git-scm.com/downloads </a> </li>
<li>Basic Git Commands: (refer cheat-sheet)
<ul> 
<li> git init(to initialise the repository)</li>
<li> git add "file_path" (to add files) </li>
<li> git add . (to add all files) </li>
<li> git commit -m "message"  (to commit code changes) </li>
<li> git commit -a -m "message"  (to add and commit code changes) </li>
<li> git log   (to check commit history) </li>
<li> git log --oneline (to check commit history in one line) </li>
<li> git push  (to push the code changes) </li>
<li> git branch "branch_name"  (to create a branch) </li>
<li> git checkout "branch_name"  (to checkout a branch or go to that branch) </li>
<li> git checkout -b "branch_name"  (to create and checkout a branch) </li>
</ul>
</li>
<li>Setting up Git Global Configuration:
<ul> 
<li> git config --global user.name "YOUR_NAME" </li>
<li> git config --global user.email "YOUR_EMAIL" </li>
</ul>
</li>
</ul>

## 3. Version Controlling with Git:

<ul>
   <li> Initializing Git Project </li>
   <li> Adding Files to VCS </li> 
   <li> Removing Files from VCS </li> 
   <li> Introduction to Commits </li> 
   <li> Staging Area </li> 
   <li> Logging Commit History </li> 
   <li> Reverting Back </li> 
</ul>


## 4. Git VS GitHub:

<ul>
   <li> What are Git and GitServer </li>
   <li> Popular Git Servers
   <ul>
   <li> GitHub </li>
   <li> GitLab </li> 
   <li>BitBucket </li> 
</ul>
    </li> 
   <li> Git Remotes </li> 
   <li> Pushing and Pulling in Git </li> 
   <li> Self-Hosted Git Server </li> 
</ul>


## 5. Branching in Git:

<ul>
   <li> Introduction to Branching Concept. </li>
   <li> Creating Branches
   <ul>
   <li> git brach "BRANCH NAME" </li>
   <li> git checkout 'BR_NAME' </li> 
   <li> git checkout -b "BR_NAME" </li> 
   
</ul>
</li> 
<li> Branch Tags
   <ul>
   <li> feat/feat-name </li>
   <li> bug/bug-name </li> 
   <li> and many others </li>   
</ul>
</li>  
<li> Merging Branches
   <ul>
   <li> Merge </li>
   <li> Rebase </li>    
</ul>
</li>  
   <li> Stashing:
   <ul>
   <li> git stash (Save modified and staged changes) </li>
   <li> git stash apply (apply saved changes)</li>    
</ul>
</li> 
</ul>
