## Level 6

If you ```cd``` into the directory ```inhere```, you'll see a ton of subdirectories, each with a lot of files.  To save time, we will be using a new command.

The key to this level is using the ```find``` command, along with flags that let you search for the specific criteria mentioned in the challenge. 
These criteria are: human-readable, 1033 bytes in size, and not executable.

These flags are as follows: ```-type f``` to restrict the search to just files(not strictly needed), ```size #c``` where # is the number and c stands for bytes, and ```! -executable``` where the exclamation mark means not and the rest means the file can be executed.  You can add more flags, such as one to check for human readability, but this should be enough to narrow down the search.

*Note to Remember - Commands in line can executed either through the relative path if you are in the same directory, or absolute path if you are not in the same directory.  Unless specified in the instructions, I will avoid adding ```cd``` or ```ls``` if I did not need them.

Steps :

```find -type f -size 1033c ! -executable```

```cat ./inherecat./maybehere07/.file2```

After doing so, the password is:

<details>
  <summary>Click me for Password</summary>
  pXa26xhMWaC2SvDotA4r9EgZkulOeSBW
  
</details>
