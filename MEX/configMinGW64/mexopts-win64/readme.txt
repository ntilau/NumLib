Configuring MATLAB with GNU C compiler (gcc) from Cygwin
 •
Install a Cygwin environment (see http://www.cygwin.com). If your MATLAB is 32-bit, you need the "mingw64-i686-gcc" package. If your MATLAB is 64-bit, you need the "mingw64-x86_64-gcc" package. 

•
The configuration file is called mexopts-win32.bat for MATLAB 32-bit, and mexopts-win64.bat for MATLAB 64-bit (these files are also distributed in recent packages of Dynare) 

•
Rename the configuration file to mexopts.bat, and copy it to c:\Documents and Settings\<User name>\Application Data\MathWorks\MATLAB\<release number>\. 

•
Note that if you installed Cygwin in a non-standard directory (i.e. elsewhere than C:\CYGWIN), you need to edit the mexopts.bat and change the set PATH=... line accordingly. 

