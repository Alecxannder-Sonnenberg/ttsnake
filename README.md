
 TexTron Snake
 ==============================

 TexTron Snake is very simple ascii snake game tributed to classic Tron arcade.
 It was meant to be developed as a collaborative programming exercise
 in course on Open Source Systems taught for undergraduate CS students.

 INSTALL
 --------------------------------------------------

 Quick instructions:

 * If you have obtained the project source from the version control repository

Excute the script 

 ```
 $ ./autogen.sh
 ```

to boostrap the build configuration scripts `configure`. You'll need GNU Build
System (Autotools) installed. In debian/ubuntu based plataforms, you may
install required software with

```
sudo apt install automake autoconf
```

* If you have either obtanied the project from a distribution repository or
bootstraped the build system as described above, and already have the build
configuration script `configure`, then execute it

```
 $ ./configure
 $ make
 ```
 
*  Alternatively, if you have obtained the source from a distribution tarball,
 you should already have the configuration script pre-built. In this case,
 you may skip evoking autotools and use just


```
 $ ./configure
 $ make
```

 Optionally, if you wish to build and install the software under /tmp/foo

```
 $ ./configure --prefix=/tmp/foo
 $ make
 $ make install
```

## Notes

 Scene files are installed under` $(prefix)/share/textronsnake`.

 You'll need `libncurses` and pthread support to build the software.

 * Detailed instructions: refer to file `INSTALL`

 PROGRAM EXECUTION
 --------------------------------------------------

 Usage:  ttsnake


 FUNCTIONALITY
 --------------------------------------------------

 The program will load scene files from the scenes directory.

 Controls:

	+ decreases the game speed
	- increases the game speed 
	q quits


