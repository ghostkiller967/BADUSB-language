if you have any other questions you can contact me in discord:
GHOST#2377

btw, I will not be responsible for any damage done to any pc.

commands:

DEFAULTDELAY - Note: MUST put this in the first line of the script.
add a number to the end of it, this will be the amout of miliseconds are in between commands.
if you forget this line the whole program will most likely not work (recommended ammout: 100).
if you put 0 or any other low number at the start the script will also not work, because its too fast.


VAR - add text to the end to set the var variable, this only works with the string command.
STRING - add a text after it and it will type that text directly on the keyboard. use STRING VAR to type the variable

example:
VAR hello
STRING VAR - will type hello


STRINGWAIT - this is used for shortcuts (example: STRINGWAIT %{F4} which will do alt + F4).
look at the bottom for all the special keys.


DELAY - add a number after this to make it wait that amount of miliseconds.


DOWNLOADFILE - add a direct download link after it and it will download that file (example: DOWNLOADFILE https://exemple.link/download.png).
STARTPROCESS - add a directory with file and it will start that process (example: C:/WINDOWS/system32/notepad.exe) WARNING: MUST USE / INSTEAD OF \.
DELETEFILE - add a directory with file and it will delete that file (example: C:/Users/<username>/desktop/Google Chrome.lnk) WARNING: MUST USE / INSTEAD OF \.
DELETEDIR - add a directory and it will delete that directory (example: C:/Users/<username>/roaming) WARNING: MUST USE / INSTEAD OF \.
CREATEFILE - add a directory location with name of the file name at the end and it will create a file there (example: C:/Users/<username>/desktop/new text file.txt) WARNING: MUST USE / INSTEAD OF \ AND ADD A TYPE AT THE END LIKE .txt OR .zip.
CREATEDIR - add a directory location with name at the end and it will create a folder there (example: C:/Users/<username>/desktop/new folder) WARNING: MUST USE / INSTEAD OF \.

use ./ to get the current location of where the executor file is located (example: ./scripts/script.txt)


SETLOCATION- add a directory at the end, to specify a directory (only works with the EDITFILE command and DOWNLOADFILE command)
EDITFILE - add a text behind it to put it in the specified file.

example 1:
CREATEFILE C:/Temp/script.txt
SETLOCATION C:/Temp/script.txt
EDITFILE script - will create a script.txt file and edit it to say script inside of it

example 2:
SETLOCATION C:/Temp
DOWNLOADFILE <downloadlink> - will download that file to C:/Temp



RUNPROMPT - will open the run prompt.
CMD - will open the command prompt
GUI - will press the windows key (not hold).


special keys for STRING and STRINGWAIT command:

BACKSPACE	{BACKSPACE}, {BS} or {BKSP}
BREAK		{BREAK}
CAPS LOCK	{CAPSLOCK}
DEL or DELETE	{DELETE} or {DEL}
DOWN ARROW	{DOWN}
END		{END}
ENTER		{ENTER}or ~
ESC		{ESC}
HELP		{HELP}
HOME		{HOME}
INS or INSERT	{INSERT} or {INS}
LEFT ARROW	{LEFT}
NUM LOCK	{NUMLOCK}
PAGE DOWN	{PGDN}
PAGE UP		{PGUP}
PRINT SCREEN	{PRTSC} (reserved for future use)
RIGHT ARROW	{RIGHT}
SCROLL LOCK	{SCROLLLOCK}
TAB		{TAB}
UP ARROW	{UP}
F1		{F1}
F2		{F2}
F3		{F3}
F4		{F4}
F5		{F5}
F6		{F6}
F7		{F7}
F8		{F8}
F9		{F9}
F10		{F10}
F11		{F11}
F12		{F12}
Keypad add	{ADD}
Keypad subtract	{SUBTRACT}
Keypad multiply	{MULTIPLY}
Keypad divide	{DIVIDE}
SHIFT		+
CTRL		^
ALT		%
