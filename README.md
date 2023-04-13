#### test-hub
This repository is for test purpose
#### git init
#### git clone <url from repo>
#### Edit the file
#### Save and exit the file
#### git add <file name>
#### git commit -m "<Commit message>"
#### git status
#### git push
For setting user.name and user.email:
#### git config --global user.name "Your Name"
#### git config --global user.email "your Email.com"
To see details about username nd useremail
#### git config --l or --list
Switching remote URLs from HTTPS to SSH:
#### git remote set-url origin git@github.com/USERNAME/REPOSITORY.git
Why we switch url from HTTPS to SSH
1. Authentication.
 ##### HTTPS requires you to enter your GitHub credentials every time you interact with the remote repository, while SSH uses a private-public key pair for authentication. By using SSH, you don't need to enter your GitHub credentials each time, which can be more convenient and secure.
2. Speed.
 ##### SSH can be faster than HTTPS when interacting with remote repositories, especially for large repositories or when making frequent commits. This is because SSH uses compression and is able to transfer data more efficiently.
3. Access.
##### Some Git operations require write access to the remote repository, such as pushing changes. If you are only able to access the repository via HTTPS, you may not have the necessary permissions to perform these operations. By using SSH, you can authenticate with your private-public key pair and have the necessary permissions to perform these operations.