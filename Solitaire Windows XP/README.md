# About
This is a program that I have done some reverse engineering on. You can download the actual program from the ZIP. If you do not trust the PE files in the ZIP folder, you can download from the archive website hosted by others. I cannot guarantee it is completely safe. Thus, run the file on a virtual machine is the safest choice.

Link to Solitaire Windows XP from arhive website: https://archive.org/details/ms_solitaire_windows_xp

The IDA database, sol.i64, consist of some key assembly instructions I have renamed the functions, variables as well as commented on some instructions. Hopefully, it will be useful for you.

I have also reverse engineered the cheatcode / easter egg which can be seen in the IDA database. I used IDA Free version 7.0.190307 Windows x64. Thus you have to use the same version of IDA or newer to open it.

Enjoy!

# Cheatcode / Easter egg
1. Instant win
    * Shortcut - Alt+Shift+2
    * Stored in keyboard Accelerator (Access via Resource Hacker)
2. Single draw
    * Shortcut - ClickOnDeck+Alt+Control+Shift
    * Used GetKeyState()