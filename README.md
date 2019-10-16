# MiniScript UDL for Notepad++
 User-Defined Language for MiniScipt, for use in Notepad++

This is a standard UDL which can be downloaded and imported into the Notepad++ User Defined Language interface, to create syntax highlighting for MiniScript (http://miniscript.org)

The standard file, named just MiniScript was created with the default theme in Notepad++ v7.7.1

The initial release has some highlighting inconsistencies due to the UDL definitions not being able to identify some operators when not space delimited.
If anyone has any suggestions on how to improve the existing UDL, please let me know.

I will probably also add a dark themed version at some stage, and if anyone else wants to contribute versions for other themes, let me know.

-----

Also included here is the file miniscript-macros.xml. This is a set of macros with shortcuts for the basic code templates for the Miniscript
"for loop", "while loop","if then" and "if then else" and "function()" statements. Adding them to Notepad++ involves editing your existing shortcuts.xml macro file, and inserting the
contents of minscript-macros.xml in the middle of this file.

In Windows the macros are saved at %AppData%\Notepad++\shortcuts.xml (Windows logo key + E and copy&paste %AppData%\Notepad++\ into the address bar to find it)

Russell.