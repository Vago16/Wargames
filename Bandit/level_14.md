## Level 14

Since we are told there is no password to progress, we must try something different.  We have to make use of ```scp``` and ```chmod```, commands which copy from one device to another, and edit permissions on a file, respectively.  The file HINT has some helpful advice too.

Steps:
You can exit the level after making sure you can login in first and know the location of the RSA private key. Then you will:

```scp -P 2220 bandit13@bandit.labs.overthewire.org:sshkey.private .```, input the password again for the level, and make sure it copied the key correctly to the directory you're currently in.

```ls -l sshkey.private``` to check permissions and see it will not let us execute if we were to try

```chmod -i sshkey.private``` to edit permissions

```ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220``` should take us to Level 14 now!

There is no password for this level, woo!
