# Emacs

In this project we will talk about:

* What is Emacs?
* Who is Richard Stallman?
* How to open and save files?
* What is a buffer and how to switch from one to the other?
* How to use the mark and the point to set the region?
* How to cut and paste lines and regions?
* How to search forward and backward?
* How to undo?
* How to quit Emacs?


## What is Emacs?

EMACS is a text editor, the original was written in 1976 by Carl Mikkelsen, David A. Moon and Guy L. Steele Jr. but the most popular and port version of Emacs is GNU Emacs, which was created by Richard Stallman.


## Who is Richard Stallman?

Richard Matthew Stallman is an American free software movement activist and programmer. Stallman launched the GNU Project, founded the Free Software Foundation, developed the GNU Compiler Collection and GNU Emacs, and wrote the GNU General Public License.


## How to open and save files?

To open a file with Emacs we can do it in the following way:

```
vagrant@vagrant-ubuntu-trusty-64:~$ emacs newfile
```

If the file already exists emacs will show it on the screen, otherwise, if the file does not exist emacs will create the file at the same time it shows it on the screen.

We can also open a new file already in Emacs with the following sequence of keys:

```
C-x C-f
```

Then the following message will appear in the buffer:

```
Find file: ~/
```

there we will write the name of the file that we want to open, for example

```
Find file: ~/ README.md
```

pressing enter Emcas will open the file we have indicated.

To save the file that we have edited we must press the following sequence of keys:

```
C-x C-s
```

and a similar message will appear in the buffer of the file

```
Wrote /home/vagrant/newfile
```

## What is a buffer and how to switch from one to the other?

Is a region of a physical memory storage used to temporarily store data while it is being moved from one place to another.

```
C-f | Forward one character
C-n | Next line
M-v | Previous screen
M-< | Beginning of buffer
```

## How to use the mark and the point to set the region?

Emacs remembers something called the mark, which is a previous cursor position. You can set mark to indicate a particular place in your buffer so you can return to it easily. C-x C-x at a later time will return point to mark. Actually, that command also moves mark to where point formerly was; therefore, a second C-x C-x returns point to its original position.

```
C-SPC | Set mark to the current location
```

```
C-x C-x	| Swap point and mark
```

## How to cut and paste lines and regions?

The following commands operate on the region, and are the closest analogs to "cut" and "copy" in Emacs:

```
C-w | Kill region ("cut")
```

```
C-y | Yanks last killed text
```

## How to search forward and backward?

You can perform a backward incremental search with C-r. (All the above commands can be activated similarly from within backward search.) At any time during a forward (or backward) search, you can type C-r (C-s) to switch to a backward (forward) search.

```
C-s C-s	| Search for most recently searched item
```

```
C-r | Backward incremental search
```
## How to undo?

Emacs provides us with three different keys to undo:

```
C-/ | Undo
```

```
C-_ | Undo
```

```
C-x u | Undo
```

## How to quit Emacs?

To exit Emacs we must use the following sequence of keys:

```
C-x C-c
```


## Authors

* **Julián Sandoval** - [Derhks](https://twitter.com/Derhks)


## Acknowledgments

I thank the following pages for the information I have extracted from them to make this README.md.

* https://en.wikipedia.org/wiki/Emacs
* https://en.wikipedia.org/wiki/Richard_Stallman
* https://en.wikipedia.org/wiki/Data_buffer
* https://www.gnu.org/savannah-checkouts/gnu/emacs/tour/index.html