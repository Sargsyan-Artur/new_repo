#Homework learning both git and github with using gitbash
Created user name  and user.email 
Created .gitignore file with files which should be ignored  

#New Repository with SSH key
Generated an SSH keypair on my computer and added the public key to my GitHub account

#Pasted the text below, substituting in my GitHub email address.

ssh-keygen -t ed25519 -C "your_email@example.com"

Enter a file in which to save the key (/c/Users/you/.ssh/id***):[Press enter]

#Add SSH key to the ssh-agent

eval `ssh-agent -s`

ssh-add ~/.ssh/id

#Add the SSH key to your GitHub account.

#Clone Github Repository 
git clone "SSH link"