# Standard Output
&#93; : after command to create and save output in file
cat : a command to display the content of a text file
&#93;&#93; : appends output to an extising file or create and write to a new file if it doesn't exist
&#91; : redirect input a file
(you can mix &#91; and &#93; in a single line)

**pipelines**
Pipeline feeds output of previous command to input of next command
command1 | command2 | command3|...
(*press "q"key toexit the screen*)

**Backslah**
\Backslah can be used to ignore line change in command(“enter”),  to enter a long command in multiple lines

## Permissions
- Linux is a multi-user system
- Files and directories have a permission assighned differently

chmod : changes permissions
(change the permission of a file "word.text" that only the owner can read and write, but all others can only read it. No execution is neededfor all users.)

Superuser : user who have all system administation authority.
(put "sudo" before the command if you are a superuser)
Type "exit" to get out of a superuser session

**Text edit**
- vi,vim : granddaddy of Unix text editor. vi is powerful and fast.
- Emacs : true giant of text editer. it should be noted that vi and Emacs fans fight bitter religious wars over which is better
- nano free clone of text editor. very easy but very short
- gedit : graphical interface. easy to use and contains enough feature to beginners.
- kwrite : advanced editor. helpful feature for programmers andscript writers.

History : can see previous command history or save it to text file
