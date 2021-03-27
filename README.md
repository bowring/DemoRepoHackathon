# DemoRepoHackathon

Instructions:

Install Git on your machine o use with command line

Fork this repo (see [this](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow))

Clone this forked repo to your machine and then change directories into the clone: >>git clone [link to your fork of this repo]

Try >> git status

Make a feature branch on your machine: >> git checkout -b myNewFeatureBranch

Create a new text file named your LastName_FirstName.txt and tell us a little about yourself

Add this file to your local branch: >> git add LastName_FirstName.txt

Commit this file to your local branch: >> git commit -m "My first commit"

Your cloned fork is your remote "origin" for your local repo

Push your local branch to your GitHub fork: >> git push origin myNewFeatureBranch

Go to your fork on GitHub and make a pull request to this repo "DemoRepoHackathon"

Setup a remote "upstream" link pointing to this repo "DemoRepo" (not your fork) : 

     >> git remote add upstream https://github.com/bowring/DemoRepoHackathon.git

Switch to your main branch: >> git checkout main

Later, pull the upstream into your local main to get what others have committed: >> git pull upstream main

Have fun


