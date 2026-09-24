## Level 12

The new command ```tr```, translate, can translate or delete characters.  The tricky part of this level comes from the rot13 cipher used to "encrypt" the file(I used google to easily get the arguments for rotating the letters to decrypt it). I would suggest reading on the wiki provided on the level if you're unfamiliar with Caesar cipher, it's an interesting topic and still relevant!

There are two ways to go about getting the password this time, either with piping from ```cat``` to ```tr```, or by redirecting, which can directly read data from a file and send to a program or vice versa, depending on the operator(```>``` or ```<```).

Steps:

```tr 'A-Za-z' 'N-ZA-Mn-za-m' < input.txt```

 or
 
```cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'```

After doing so, the password is:

<details>
  <summary>Click me for Password</summary>
  GROozWPO8QyN0mGrjUkID0WCYkZiQxrN
  
</details>
