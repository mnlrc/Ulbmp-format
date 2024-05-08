# Ulbmp-format
The ULBMP format is a personalized picture compression format that we had to implement.
I added the pdf file of the directives (in french) that describes the format and all its versions well.

The interaction with the program is made using a PySide6 window.

There is one notable issue:

When I save a picture, it's possible that it will take forever to do. I never found the issue nor took the time to search for it. I suspect the multiple 'f.write' that I use in the program.
Apart from that, you can load any image in ulbmp format or save them.

You can find all the pictures that were given to us is the imgs folder. There is also a script made by a teacher, 'toulbmp.py', that lets you convert any picture to UBLMP format.
