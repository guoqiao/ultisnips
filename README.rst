why fork
=========
forked from https://github.com/SirVer/ultisnips
if you set filetype in vimrc for django like this:

    autocmd FileType python set ft=python.django
    autocmd FileType html set ft=htmldjango.html

yes, it will make snippets work for django py and html file.
however, taglist will not work for django any more.
to fix this, just make python and html snippets extends from  django.snippets.
so the python and html snippets will support django.

UltiSnips
=========

This is the official repository for UltiSnips. Send Pull request to
SirVer/ultisnips, not the automatic clone from vim-scripts or any
other fork of this project.

Screencasts
-----------

The blog posts of the screencasts contain more advanced examples of the things
discussed in the videos.

* `Episode 1: What are snippets and do I need them?`__
* `Episode 2: Creating Basic Snippets`__
* `Episode 3: What's new in version 2.0`__
* `Episode 4: Python Interpolation`__

__ http://www.sirver.net/blog/2011/12/30/first-episode-of-ultisnips-screencast/
__ http://www.sirver.net/blog/2012/01/08/second-episode-of-ultisnips-screencast/
__ http://www.sirver.net/blog/2012/02/05/third-episode-of-ultisnips-screencast/
__ http://www.sirver.net/blog/2012/03/31/fourth-episode-of-ultisnips-screencast/
