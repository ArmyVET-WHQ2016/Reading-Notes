# Reading 2 Notes

What is a Editor

A text editor is a piece of software that you download and install on your computer, or you access online through your web browser, that allows you to write and manage text, especially the text that you write to build a web site. Some text editors comes with features that other do not.

## What text editor features to look for

1.Code completion
2. Syntax highlights
3. Themes

### Key Notes

1. With code completion, you're provided a possible suggestion from what have been type before which saves time. The code completion feature includes the closing of tags when they're open, or the closing of brackets when opened, or the closing of quotation marks when they're opened, thus making sure that you’re always writing your code.
2. Syntax highlights is a feature that takes the text you typed, and make it more noticeable by colorizing the text which makes it better for the tech to distinguish errors.
3. Theme allows changes to the color of the background, the series of colors in your text.Themes may affect other aspects of your text editing software as well.

#### Command Line

A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text. The command line typically presents you with a prompt. As you type, it will be displayed after the prompt.

1. The *Terminal*- If on Linux then you will probably find it in Applications -> System or Applications -> Utilities. Alternatively you may be able to 'right-click' on the desktop and there may be an option 'Open in terminal'. The terminal has within a **Shell**.
2. The *Shell*- This is a part of the operating system that defines how the terminal will behave and looks after running or executing commands for you. The most common used is called the *bash* which stands for Bourne again shell. If you are unsure of what shell is being used for your system "there is a command for that called *echo*. **Echo** is a command which is used to display messages.

##### Navigation

The basics of moving around the system. Many tasks rely on being able to get to, or reference the correct location in the system. Here we will cover a few of those commands.

1. *pwd* which stands for Print Working Directory. It tells you what your current or present working directory is.
2. *ls* "It's short for list. **ls** is a little more powerful. We have to run it here with no arguments in which case it will just do a plain listing of our current location.
3. *cd* In order to move around in the system we use the command *cd* which stands for change directory. The command **cd** may be run without a location but usually will be run with a single command line argument which is the location we would like to change into.

[^note] With Linux is that under the hood, everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file one that the system reads from only, your monitor is a file one that the system writes to on. A file extension is normally a set of 2 - 4  characters after a full stop at the end of a file, which denotes what type of file it is Under Linux the system actually ignores the extension and looks inside the file to determine what type of file
it is.This is very important and a common source of problems for people new to Linux. Other systems such as Windows are case insensitive when it comes to referring to files. Linux is not like this.As such it is possible to have two or more files and directories with the same name but letters of different case. Linux actually has a very simple and elegant mechanism for specifying that a file or directory is hidden. If the file or directory's name begins with a. full stop then it is considered to be hidden. To make a file or directory hidden all you need to do is create the file or directory with it's name beginning with a . or rename it to be as such. Likewise you may rename a hidden file to remove the . and it will become unhidden. The command ls which we have seen in the previous section will not list hidden files and directories by default. We may modify it by including the command line option -a so that it does show hidden files and directories.
