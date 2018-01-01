This git repository is for storing misc. files and etc.  
Also for some git testing.

To establish the git repository and authentication:

- to initilize the empty git repo on SCS4:  git init
- to add files:  git add .
- to commit files:  git commit -m "blah blah"
- to link the local repo with the remote:  git remote add origin git@github.com:Quanto99/MiscRepo.git

- to generate the ssh key on SCS4:   ssh-keygen -t rsa -b 4096 -C "scottstavran@comcast.net"
- to verify the ssh agent was running on SCS4:  eval $(ssh-agent -s)
- to add the ssh key to the ssh agent:   ssh-add ~/.ssh/id_rsa

- to push the file from the local repo to the remote:   git push -u origin master

This is part of the git testing.
Another git test.

Initially it is going to contain just some random text files.

The test branch will add and remove some files.
