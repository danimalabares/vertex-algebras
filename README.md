#What is this

This is a copy of the 
[Stacks Project repository](https://github.com/stacks/stacks-project)
used for math notes.

#How to use

Make a clone of repo in your computer so that you have all the files.
Then you can edit and compile. The ``documentation`` directory contains
the original documentation files of the Stacks Project, which includes some
guidelines of how to write the tex files.

#How to compile

To compile I open a Terminal, go to the directory where I have the local files
of the repository and run the command

``latexmk -pdf derived-categories-of-sheaves.tex``

Or

``latexmk -pdf -pvc derived-categories-of-sheaves.tex``

for continuous compilation (which is most useful when editing a file).


Ideally we would use ``make``, for example

``make derived-categories-of-sheaves.pdf``

but for some reason this isn't working anymore.
Official Stacks Project repo uses a python script to compile the whole book,
i.e. all tex files in one pdf. 
I didn't manage to set that working, but it would be great if anyone figures
out how to do it.

This works:

``make clean``

to delete all the byproducts of compilation (including pdf).

#How I write in latex

1. “The seminal work on the subject”: [Gilles Castel’s blog](https://castel.dev/post/lecture-notes-1/)
2. Tutorial: [ejmastnak](https://ejmastnak.com/tutorials/vim-latex/intro/)

#Other links

3. PDF viewer: [Sioyek](https://sioyek.info/)
4. [Google Chrome extension](https://chromewebstore.google.com/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb?hl=en&pli=1) to facilitate navigation.
5. Shell for Mac OS: [Oh My SSH](https://ohmyz.sh/)
6. I use a window manager (for Mac) called Magnet, but there's also a free one 
called Amethyst that might work just as well.
7. I use a thing called AltTab to facilite swapping between windows using the
   keyboard (on Mac again).
