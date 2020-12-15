                              A brief description about the steps related with the creation of github repo creation

Git installation can be done through various sources either through command line or by direct installation .
I used the terminal to install the git using the command $sudo apt git install.all
After this creating an account in github is not a big deal. signup with the information required and login .
to create a new repository in git hub using the new button and named it with programming lab name for readibilty.
Creating a local  repo is a task .using a terminal and several commands like -->git init
-->git add readme.md 
-->git commit -m "message"
-->git add origin master
-->git push
these kinds of commands are available in the git guidence itself. for my case errors have been occured clamming existing file 
fatal errors,i solved the problems by clonning the repo using the https link from the remote repo.

After the push command we can see the files have been updated in remote repo of the github.
After any changes we just need to add the command -->"git add ." will help to commit the changes to occur in the repo as well
 and just push it.
using these commands i have added several html files to the remote repo from the local repo.

ssh key  creation-for this we have open the terminal and check and list out the existing  ssh key.
Inorder to generate the new key use the commands like"$keygen" which will ask you for the file to saved to
and passphrase as a security measure. when the ssh key is created a,2 new files will be generated on to the respective 
file.Which consisting of public key and private key use the public key and add it in the new ssh key option in the github 
Account which will ask you for the account password and the key is now added and it is confirmed throuugh a email also.
As by creating a ssh key it will make easier way to transfer the files from the local to remote repo.

