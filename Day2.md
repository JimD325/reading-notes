# Day 2

Raw Word Notes: 
Lecture

11/9/2021 

Make sure to do all of your stuff, make it up from yesterday if you missed it. 
Today we are installing everything that you need for code fellows. 

DevelopingTools: 
Text editor, Terminal 

Text Editor: 
Word Processors: Microsoft Word, Google Docs, Apple Pages, Word Perfect, and several more. 
Code Editors: Githubs Atom (3-4ish years old)
Microsofts Vs Code, Visual Studio, with VS Code is fundamental
Notepad ++
Vim Emacs Nano TextMate
And Many More
The Terminal (AKA the Command Lind Interface
File Explorer Tasks: Find Files, Change Directories, Move and copy files, open files, make new files/folders. 
Terminal Tasks: Find Files/content, change directories, move and copy files, open files, make new files and folders, waaaaay more. Far more powerful than just the file explorer tasks. 

Terminal: pwd= an important command( present working directory) things are abbreviated because old timey computers had severe limits on their available memory. Allows you to look around. 
Ls= list. So when you enter LS it tells you the name of every file in your directory. 
You can also make a new folder on the terminal. You type in “mkdir folder name”. so the terminal and the user interface are all pointing to the same direction. 
Type in clear to clear the terminal. 
To go into a file in UI, you double click. To do it in the terminal, you have to change directory, or type in cd in the terminal.. 
Directory is the terminal name for a folder. 
You can make a text file in terminal by using the “touch” Command. So touch stanta.txt will give a text file with the name “santa”. 
Remove is rm. So type rm X.yz will remove file X.yz. 
Touch adds files, mkdir adds folders. 
Cd goes into file, so cd [filename] goes into file. 
. denotes current working directory
.. brings you back to the previous directory. 
Cd ../../../..
Copy command is cp. Use cp then two arguments, they are the file name/location and then where you want to copy it to. So cp[filename] [destination location]
To go back is cd (change directory) then ..

Reading notes 

Text Editors: 
There are many different kinds out there, but the good ones have (according to the author) code completeion, syntax highlighting, a variety of themes, and a healthy number of extensions. 

Notepad on windows, text edit on mac are built in text editors. Linus computers may have a wide variety of text editors.

Q: Whats the main difference between Linux vs PC/Mac=? 

Your main HTML file should be called "index.html", your CSS file should be called "style.css"

Notepad++: free text editor for windows computers only. Has all the features the author likes in a text editor. 

TextWrangler/BB Edit: Mac only. Textwrangler was discontinued, but it was packed into BB Edit, another feature laden text editor. Must purchase it if you want the full features of BB edit. 

VS CODE: Literally what I'm typing in right now. Author really likes this one; has all the features, works for windows/mac/linux, has emmet shorthand, and an active developing community. 

Atom: free for WML, made by github team. Author likes this one. 

Brackets: WML compatible, made by adobe team. Only supports HTML CSS and JavaScript, need to add extensions to support more. Has live preview. 

Sublime Text 3: Costs 70 dollars (booooo) it has all the necessary tools though, and a reputation for being fast and responsive. 

Terminal Reading Notes: 
Look at it as an addition to the GUI. 
Is a text Based interface to the system. 
A command is typically the first thing that you type, and after that you have the command line arguements, typically separated by spaces. The first fcommand line arguement is reffered to as an option, and options modify the behavior of the command. They are usually listed before other arguements and start with a -
Shell: Part of the OS tha defines how the terminal will behave and look while executing commands. 
The Shell I am running on currently is Bash, which stands for Bourne again shell. 
PWD: stands for print working directory. tells you what the current working directory is. 
ls: tells us what is in our current directory. ls[options][location] square brackets indicate optionality in entering them. 
Path: a means to get to a particular file or directory on a system. 
Absolute path: specify a directory in relation to the root directory. They always begin with a /
Relative Path: specify a directory in relation to where we currently are in the system, DO NOT begin with a /. 
Root: file system under linux is a hierarchical structure. The Roots is at the top of this structure. 
~: shortcut for home directory.if your home directory is /home/jim then you can refer to the directory documents with the path /home/jim/documents OR just ~/documents. 
. : reference to your current directory. 
.. : Reference to the parent directory. 
cd: Change directory. 

EVERYTHING IS A FILE
    Directories, keyboards, monitors, everything. This becomes important later. 
Linux is an Extentionless System: 
    an extension is the .exe or .gif or .txt. The extensions denote what type of file it is. In Windows this is imporant, But linux ignores  the extension and looks into the file itself to see what kind of file it is. This is why for an HTML document you have to write the code to tell linux that the file is an HTML. 
This can lead to confusion by identifying what kind of file it is without opening it and taking a look. use file[path] to determine. 
Directories are just a special kind of file, so it is accurate to say that a path is a means to get to a particular location in the system, and that location is a file. 
LINUX IS CASE SENSITIVE
This includes file naming as well as commands. 

Spaces
    Can use spaces in file names but have to be careful. Spaces on the command line are how we separate items, how we know what is the program name and identify each command line arguement. 
If you want to use spaces, either put the spaced item in quotes 'my photos' or use an escape character. Quotes tell the terminal that anything inside the quotes should be considered a single item, and the escape character (\) nullifies the special meaning of the next character (the space intbetween the words my photos in this instance.)

Hidden Files: 
if the file or directory name begins with a . (full stop) then it is considered hidden. There are reasons to hide files, for instance, configuration files are often hidden so they dont interfere with your daily tasks. 