#MinGW
A portable version of MinGW prepared for OpenGL development.

##Get started
- Copy the MinGW folder to the root of the drive which has a project you want to compile. For example if your project is in C:\Users\username\Documents then the MinGW folder needs to be placed in C:\MinGW.
- Create an GNU Makefile and call it Makefile. Make sure the executable is called Program.exe.
- Copy the .bat files to the same folder as the makefile.
- Use run.bat to "make and run" your program.
- Use make_clean.bat to "make clean, make and run"

You can place the MinGW folder in another drive if you edit the bat files line

	set MINGW_PATH=%CD:~0,2%\MinGW

to the following, assuming you want to place it on C:

	set MINGW_PATH=C:\MinGW

The same goes for the executable name.

##Licence
This project is simply a pre-compiled version if MinGW configured with the following libraries. The bat files is MIT licenced.

- MinGW, http://www.mingw.org/
- GLEW, http://glew.sourceforge.net/
- GLFW, http://www.glfw.org/
- libpng, http://www.libpng.org/pub/png/libpng.html
- zlib, http://zlib.net/