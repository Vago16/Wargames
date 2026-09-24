## Level 9

This level introduces multiple new concepts at once.  Let us start with the commands.  ```sort``` does, as the name suggests, displays a sorted concatenation of all file/s to standard output.  ```uniq``` is also on the nose, and will omit or report repeated lines that occur next to each other.  We will be using ```uniq -u``` to make sure only unique adjacent lines are printed for this exercise.

Now, trying out ```uniq -u``` seems like it would work, right?  Try it and see what the output is.

The reason it prints all that out is because the file is not sorted.  However, if you sort the file with ```sort```, the changes are not saved for you to then run the ```uniq -u``` command, so we need a way to do both commands concurrently.

This is where piping comes in handy.  It is a mechanism for sending data from one program to another, and we use the ```|``` character for the operation.  An example would be ```command1 | command2```.

Steps:

```sort data.txt | uniq -u```


After doing so, the password is:

<details>
  <summary>Click me for Password</summary>
  EjmOSvuAu7sGAHqHVcBDPirRe9T03kxl
  
</details>
