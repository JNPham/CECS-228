
Step 1. Save folder clara-bin in a directory, such as OneDrive.

Step 2: Open a dos command prompt (type dos in search bar) to add clara-bin to your PATH variable.

DOS command for adding a directory to your path:

setx path "%path%;c:\directoryPath"

Example:

setx path "%path%;c:\Users\todde\OneDrive\clara-bin"

Step 3. In clara-bin, right click clara-script.BAT to edit line number 2, so that the 
directory address is the directory where you plan to write your Clara programs.
For example, I write my programs in C:\Users\todde\OneDrive\Documents\clara-programs

@ECHO OFF
cd C:\Users\todde\OneDrive\Documents\clara-programs
clara.exe

Step 4. Run clara-script.BAT by left clicking on its icon. This has the effect of opening
a command prompt, and allowing you to type clara statements.


