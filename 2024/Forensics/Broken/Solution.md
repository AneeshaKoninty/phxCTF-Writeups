The image file is a PNG file which can be found through the byte header of the file. The first 8 bytes of the file look like this:
~~~
83 88 EE 47 0D 0A
~~~

The byte header needs to be changed so the image is recognized as a PNG file. The byte order needs to be changed to this:
~~~
89 50 4E 47 0D 1A 0A
~~~

The image has the flag, phxCTF{good_job}
