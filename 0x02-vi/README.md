# vi

In this project we will talk about:

* What is vi?
* Who is Bill Joy?
* How to start and exit vi?
* What are the command and insert modes, and how to switch from one to the other?
* How to edit text?
* How to cut and paste lines?
* How to search forward and backward?
* How to undo?
* How to quit vi?


## What is vi?

Vi is the text editor that comes by default in the UNIX operating system, it has two modes of operation that are: command mode and insertion mode.


## Who is Bill Joy?

Bill Joy is known as a systems engineer and helped with the development of Berkeley Unix. He founded Sun Microsystems in 1983 and contributed to the development of the Java programming language.

## How to start and exit vi?

### to start Vi:

To use vi on a file, type in vi filename. If the file named filename exists, then the first page (or screen) of the file will be displayed; if the file does not exist, then an empty file and screen are created into which you may enter text.

```
vi filename | edit filename starting at line 1
```

### To Exit Vi:

Usually the new or modified file is saved when you leave vi. However, it is also possible to quit vi without saving the file.

```
:x<Return> | quit vi, writing out modified file to file named in original invocation
```

```
:q!<Return> | quit vi even though latest changes have not been saved for this vi call
```

## What are the command and insert modes, and how to switch from one to the other?

When we open a file we will enter it in command mode and in this mode you can use the keyboard keys to navigate, delete, copy, paste and perform other tasks (since in Vi, almost all letters on the keyboard have a function), except entering text. To enter text we must enter the insert mode by pressing the i key. To return to the command mode we must press the Esc key.

```
i | insert text before cursor, until <Esc> hit
```
```
o | open and put text in a new line below current line, until <Esc> hit
```
```
O | open and put text in a new line above current line, until <Esc> hit
```
## How to edit text?

We can edit a text in Vi, using the cut and paste functions, as well as the insert and delete, these are the most used options when editing a text.


## How to cut and paste lines?

The following commands allow you to copy and paste text:

```
yy | copy (yank, cut) the current line into the buffer
```

```
Nyy or yNy | copy (yank, cut) the next N lines, including the current line, into the buffer
```

```
p | put (paste) the line(s) in the buffer into the text after the current line
```

## How to search forward and backward?

To search forward and backward, we have the following commands in Vi:

```
/string	| search forward for occurrence of string in text
```

```
?string | search backward for occurrence of string in text
```
## How to undo?

Using the following command:

```
u | UNDO WHATEVER YOU JUST DID; a simple toggle
```

## How to quit Vi?

In Vi we have several options to quit, among the most used are the following:

```
:x<Return> | quit vi, writing out modified file to file named in original invocation
```
```
:wq<Return> | quit vi, writing out modified file to file named in original invocation
```
```
:q!<Return> | quit vi even though latest changes have not been saved for this vi call
```

## Authors

* **Julián Sandoval** - [Derhks](https://twitter.com/Derhks)


## Acknowledgments

I thank the following pages for the information I have extracted from them to make this README.md.

* https://www.cs.colostate.edu/helpdocs/vi.html
* https://ethw.org/Bill_Joy
* https://www.redhat.com/sysadmin/introduction-vi-editor
