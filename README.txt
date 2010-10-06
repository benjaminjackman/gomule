The GoMule Project
==================

Date: 2010-09-16
Time-stamp: <2010-10-05>

What is GoMule?
---------------

GoMule a muling application for the computer game "Diablo 2" which allows
items to be stored and transferred between Single Player characters outside of
the game. The goals of GoMule are to:

    * Easily transfer items between Diablo 2 character files (d2s files)
    * Give infinite storage capabilities of both items and gold through the
      use of stashes (d2x files)
    * Allow users to easily locate and sort items in their stashes
    * Speed up common muling processes, through multiple pickup and drops
    * Allow Unix systems to easily mule their items
    * Support the latest patch (1.13c) of Diablo 2

Although GoMule does edit the Diablo 2 game files, it cannot be considered a
character or item 'editor'. There are very strict restrictions on what you can
edit, GoMule will never support stat, skill or item property editing.

About this fork
---------------

I want to add some new features to GoMule, so I forked it.

What's changed in this fork:
* 
* Max Gold in Stash is capped at 2500000 for all levels. [1.13c]
* version control system changed to Git
  CVS files removed.
  added dependent lirary: ws-xmlrpc
  added 'ant release' target, pdf manual is included in release.

How can I get GoMule?
---------------------

You can get the latest version on [github Downloads
page](http://github.com/sylecn/gomule/downloads).

The original version can also be found on [GoMule official
website](http://gomule.sourceforge.net/) or [sourceforge project
page](http://sourceforge.net/projects/gomule/)

Start using GoMule
------------------

You need [JRE (Java Runtime
Environment)](http://www.java.com/en/download/manual.jsp) Version 6 or higher
to run my patched version of GoMule.

The original version also requires JRE, I don't know the minimum version.

When JRE is installed, unzip the download file and double click GoMule.jar to
start the application. You may want to read the UserGuide.pdf to know how to
use it effectively.

In order to read the manual, you need [Acrobat Reader](http://get.adobe.com/reader/) or equivalent.


Current Status
--------------

This is what the old README file says:

> GoMule is considered in test stadium,
> do not use this program without backup your D2 characters !!!

I find GoMule very stable for everyday use. GoMule backup your saves and stash
file every day/week/month. I recommend off-disk backup for D2 saves and GoMule
stashes in case you get a disk failure. Either an online net disk or a local
USB drive is fine.

History
-------

The read/write character "core" is setup by Gohanman, a lot has changed
starting from the first release.

Note for the "All Item View":
- the clipboard is not included
- A file is only in memory once, if you open a specific char and the "all item
  view" the character is only read once. (both views point to the same
  character.) That means if you close and open the character without closing
  the all items view, the character is not readagain as it's still in
  memory. (if you play the game while leaving gomule open, close the all item
  view)


Authors
-------

Program by Randall, Silospen
Patch by Yuanle Song

