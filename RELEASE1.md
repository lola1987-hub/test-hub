When I created new file it shows untracked. And I checked what does it mean.
##### In Visual Studio Code, an untracked file refers to a file that has been created or modified in a repository, but it has not been added to the version control system. This means that the file is not being tracked by Git, which is a popular version control system used by developers to manage changes to their code.

How to create new branch n order to make some changes in the repsitory and how to merge them.
Need to create new branch in repository
#### git checkout -b "new branch name"
Edit the file and save and exit.
#### git add . or git add "file name"
#### git commit -m "commit message"
need send pull request to the main repository
#### git pull origin "branch name"
We will see the link for PR in output. Copy and paste to the brawser. and click te button "send PR".
Then you will see merge button there. You can merge them and you will see your changes in that file. In real invironment we need get approvals first in order to do some changes in repository files.