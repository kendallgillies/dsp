# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > 1. pwd: show current working directory path
> > 2. mkdir \[name\]: creating a directory
> > 3. rm \[name\]: deleting a directory (or rm -r [name] if stuff is in directory)
> > 4. touch \[name\]: creating a file using `touch` command
> > 5. rm \[name\]: deleting a file
> > 6. mv \[old name\]  \[new name\]:  renaming a file 
> > 7. ls -a: listing hidden files
> > 8. cp \[old directory/file name\] \[new directory/file name\] copying a file from one directory to another
> > 9. cd ..: backs up one directory 
> > 10. vi \[name\]: creates a new file that contains text

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > `ls`   - lists contents in alphabetical order
> > `ls -a`  - shows hidden files and directories as well as non-hidden contents shown using ls
> > `ls -l`   - does a long list...displays a lot of information about each file
> > `ls -lh`  - does a long list but displays the size of the file in "Human Readable Format" because large numbers are icky to look at
> > `ls -lah`  - long list, in "Human Readable Format", with hidden stuff
> > `ls -t`  - shows ls in order from time last edited
> > `ls -Glp`  - shows a long list, no group names printed and add a / to the end of a directory

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > Full disclosure: I only found one of these exciting...
> >
> > 1. ls -R: displays all subdirectories too, can easily check all files without having to dig
> > 2. ls -m: puts names as a comma-separated list (could be useful to add to csv file)
> > 3. ls -F: flags all the file names
> > 4. ls -g: I already know who owns the computer...
> > 5. ls -C: seems superfluous to list it since it is the default

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > I'm going to do my best to translate what I think the internet is telling me.  From what I can tell xargs is similar to a while loop in that when you apply it to a function (command?), it will apply that function to inputs either from the user (until Ctrl+D is applied) or from a file or command (using a pipe).  One website pointed out that it is nice because you can run multiple processes at a time.  The example they gave was taking music files and converting them from .wav files to some other file three files at a time.  

 

