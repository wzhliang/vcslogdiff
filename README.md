vcslogdiff
==========

Vim script for enhancing vcscommand.vim. You can visually view diff between two revision, etc.


Vim script for enhancing the vcscommand.vim script. You can easily diff between two 
revisions in the log window. It also add coloring to the log buffer too. Right now it supports svn and hg. 

USAGE 
=====
* Call `VCSLog`
* Go to revision a, press `s` 
* Go to revision b, press 's' 
* Press `d` to launch GUI diff
 
PLATFORM
========
Note: currently only works on Linux 

REQUIREMENT
===========
* `diffuse`
* vim compiled with +sign 

INSTALLATION
============
To install, simply drop it in ~/.vim/plugin.
