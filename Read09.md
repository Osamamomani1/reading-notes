## Text editors

### What is a text editor?

A text editor is a piece of software that you download and install on
your computer, or you access online through your web browser, that
allows you to write and manage text, especially the text that you write
to build a web site. The text editor has to be one of the most
important tools you can use as an aspiring web developer

* A great feature of any text editing software is code completion. Code
completion allows you to start typing, and the code completion
feature will display possible suggestions based on what you originally
typed. This saves you time by providing a choice, rather than allowing
you to finish typing and possibly encounter typos.


* Another nice feature is being able to write your HTML and CSS more
efficiently. There is a kind of shorthand language called Emmet that
can help. Emmet will speed up your code writing faster than you can
imagine. Some text editors come with Emmet built right in, or
Emmet can be added by the means of an extension.


* Another feature you should definitely look into is called syntax
highlighting. Syntax highlighting is a feature that takes the text you
type, and makes it more noticeable by colorizing the text. Attributes
are a different color than elements. And elements are a different color
than copy. This makes it so much easier when you’re looking for an
error and you can’t find it. As well as making your text easier to read.


###  Different classifications of text editors :

1- Software That Already Comes With Your Computer

2- onlin 

3- ( Third-Party Options)

* NotePad++
* TextWrangler/BB Edit
* Visual Studio Code 
* Atom 
* Brackets
* Sublime Text

## Introduction to using a terminal.

1- The Command Line :

A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands.

*Notice* : 

* in first line presents us with a prompt then first thing we type is command , After that we have what are referred to as command line arguments 


* Then we will have output in ** lins ** ( more than one line )


* After the command has run and the terminal is ready for you to enter another command it would presents us with a prompt again


### The shell and bach 

Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called **bash** which stands for Bourne again shell. This tutorial will assume you are using bash as your shell.

If you would like to know which shell you are using you may use a command called **echo** to display a system variable stating your current shell. echo is a command which is used to display messages.

## Basic Navigation.

### A lot of commands in linux are named as an abbreviation of a word or words describing them

* pwd : Print Working Directory - ie. Where are we currently.


* ls : List the contents of a directory.


* cd : change Directories - ie. move to another directory.

*Notice* :

Relative path :
A file or directory location relative to where we currently are in the file system.

Absolute path :
A file or directory location in relation to the root of the file system.

## More About Files

everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc. To begin with, this won't affect what we do too much but keep it in mind as it helps with understanding the behaviour of Linux as we manage files and directories.

* Linux is an Extensionless System .

Under Linux the system actually ignores the extension and looks inside the file to determine what type of file it is. So for instance I could have a file myself.png which is a picture of me. I could rename the file to myself.txt or just myself and Linux would still happily treat the file as an image file. As such it can sometimes be hard to know for certain what type of file a particular file is. Luckily there is a command called file which we can use to **find** this out.

```
file [path] 
```

* Linux is Case Sensitive

This is very important and a common source of problems for people new to Linux. Other systems such as Windows are case insensitive when it comes to referring to files. Linux is not like this. As such it is possible to have two or more files and directories with the same name but letters of different case.

* Spaces in names

Spaces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we seperate items. They are how we know what is the program name and can identify each command line argument. If we wanted to move into a directory called Holiday Photos for example the following would not work.

```
user@bash: ls Documents
FILE1.txt File1.txt file1.TXT Holiday Photos
...
user@bash: cd Holiday Photos
bash: cd: Holiday: No such file or directory
```
What happens is that Holiday Photos is seen as two command line arguments. cd moves into whichever directory is specified by the first command line argument only. To get around this we need to identify to the terminal that we wish Holiday Photos to be seen as a single command line argument. There are two ways to go about this, either way is just as valid.

1- Quotes : Anything inside quotes is considered a single item.

```
user@bash: cd 'Holiday Photos'
user@bash: pwd
/home/ryan/Documents/Holiday Photos
```

2- Escape Characters : Another method is to use what is called an escape character, which is a backslash ( \ ). What the backslash does is escape (or nullify) the special meaning of the next character.

```
user@bash: cd Holiday\ Photos
user@bash: pwd
/home/ryan/Documents/Holiday Photos
```

* hidden files and directories :

Linux actually has a very simple and elegant mechanism for specifying that a file or directory is hidden. If the file or directory's name begins with a . (full stop) then it is considered to be hidden. You don't even need a special command or action to make a file hidden. Files and directories may be hidden for a variety of reasons. Configuration files for a particular user (which are normally stored in their home directory) are hidden for instance so that they don't get in the way of the user doing their everyday tasks.

To make a file or directory hidden all you need to do is create the file or directory with it's name beginning with a . or rename it to be as such. Likewise you may rename a hidden file to remove the . and it will become unhidden. The command ls which we have seen in the previous section will not list hidden files and directories by default. We may modify it by including the command line option -a so that it does show hidden files and directories.


```
user@bash: ls Documents
FILE1.txt File1.txt file1.TXT
...
user@bash: ls -a Documents
. .. FILE1.txt File1.txt file1.TXT .hidden .file.txt
...
```







 