The title of the challenge should point you to "John the Ripper", a hash cracking tool.
Find the hash type using an online tool: MD5. Run the command below on the hash.txt on UNIX system.
~~~
  $ john --single --format=raw-md5 hash.txt
~~~
This gives "treasure" as the password which is the flag.
