Running fcrackzip on the zip file with the wordlist will give the password. The command is below.
~~~
sudo fcrackzip -u -D -p path_to_wordlist/wordlist.txt fun.zip
~~~

The password is Cinnamon. Unzipping fun.zip will give a txt file with the flag.

Flag: phxCTF{w0rdl1sTs_arE_c00l}
