## Level 10

Another level, another command to learn. This time, it's the ```strings``` commands, which is used to extract and print to standard output readable characters from files.

Technically that's all you need for this level, since you can do ```strings data.txt``` and scroll through output to find the password, but that's not as fun and you can possibly make a mistake.

Let's instead use piping like before and add ```grep``` to the mix to filter through for the ```==``` character(since the level mentioned multiple), so we can practice.

Steps:

```strings data.txt | grep "=="```

After doing so, the password is:

<details>
  <summary>Click me for Password</summary>
  B0s2khmbT9u0geKuOoVGW3JZKhndE3BG
  
</details>
