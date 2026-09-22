## Level 7

We will be using the ```find``` command again, now with the criteria of:owned by user bandit7, owned by group bandit6, and 33 bytes in size.  The vital flags will be ```-user``` and ```-group```.  The ```2>/dev/null``` is not strictly necessary here, but helps with filtering out files that are permission denied.

Steps:

```find / -user bandit7 -group bandit6  -type f -size 33c 2>/dev/null```

```cat /var/lib/dpkg/info/bandit7.password```

After doing so, the password is:

<details>
  <summary>Click me for Password</summary>
  Bmnnvf82KzQlfxgAI2d1zYbr1u9pr3E3
  
</details>
