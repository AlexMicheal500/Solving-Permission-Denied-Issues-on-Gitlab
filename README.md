# Solving-Permission-Denied-Issues-on-Gitlab
To solve theis, follow the following steps:
1. Using ssh-keygen, cat the public keypair
2. Run the belo command to add it to teh authorized keys:
   cat /home/ubuntu/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys
3. On teh gitlab GUI, add the public key to the ssh key.
