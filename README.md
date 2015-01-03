backitup
========

a simple backup script written in Bash for Linux/Unix 

backitup is a bash shell script that does the following: 

1. copies any older backup to the "old" folder, and clears out the backup folder
2. creates a tar file of the specified directories in the newly cleared backup folder
3. encrypts the tar file (pgp keypair setup required for this step) 
4. deletes the un-encrypted tar file. 
