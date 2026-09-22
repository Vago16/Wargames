## Level 4
We will be using the ```ls``` command, or list, here to find the file.  
Before all that however, we need to get to the right directory where the file is. This is where change directory or ```cd <directory>``` comes in handy.  After an initial search with ```ls```, we see that there is a directory called "inhere". We then ```cd``` into the directory to continue our search.

Executing ```ls``` here will show nothing now.  What gives?  The trick is that it is a hidden file that just typing ```ls``` will not find in the directory.  For that we need a special flag.  

We can use the manual command as  ```man <command we wish to learn about>```; or in this case, ```man ls``` to find more info about the ```ls command```(or we could use google, but we're here to learn linux).
Doing this and scrolling down a fair amount shows us the ```-a``` or ```--all``` flag, which lets ```ls``` display hidden files(those that start with a period).

The sequence of commands is:

```cd inhere```

```ls -a```

```cat ...Hiding-From-You```

<details>
  <summary>Click me for Password</summary>
  xzTXq1rDJQVVAzdv5cHq1TQytTWufAMq
  
</details>
