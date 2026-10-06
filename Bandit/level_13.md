## Level 13

This level introduces compressed data and unzipping it

Steps:

```mktemp -d```

```cp data.txt <temporary directory>```

```mv data.txt hexdump```

```xxd -r hexdump compressed_data```

```file compressed_data``` and ```cat compressed_data``` to see what type of file it is, to see how to decompress it

```mv compressed_data compressed_data.gz```

```gzip -d compressed_data.gz```

```file compressed data``` to see what new type of file it is

```mv compressed_data compressed_data.bz2```

```bzip2 -d compressed_data.bz2```

file again...

```mv compressed_data compressed_data.gz```

```gzip -d compressed_data.gz```

file once more...

```mv compressed_data compressed_data.tar```

```tar -xf compressed_data.tar ```

```ls```

Weird, there's an archive, let's extract again.

```tar -xf data5.bin```

```ls```

```file data8.bin``` to see it needs gzip to extract the file

```mv data8.bin data8.gz```

```gzip -d data8.gz```

```ls``` and ```file data8``` and then finally, ```cat data8```

After doing so, the password is:

<details>
  <summary>Click me for Password</summary>
  qQYQiHOBPR8zR61qxYqX45quvihF2uzk
  
</details>
