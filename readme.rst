-------------
filebrowse.pl
-------------

A Gtk2 filebrowser written in Perl. Created by "Team Perl" at the 2nd Red Bull Programming Competition at RIT (2003). This program was created in 12 hours, and hasn't been touched since. It's still pretty cool.

.. image:: http://lewk.org/img/filebrowse.png

Authors
=======
 - Luke Macken
 - John Resig
 - Jordan Sissel
 - Chris Klieber
 - Pete Fritchman

Features
========
 - Browse and preview files in compressed archives (tar|gz) without file extraction.
 - Preview items in compressed archive without extraction.
 - Hot preview pane.
 - Detailed directory listings.
 - MP3 preview information from IDv[2|3] tags.
 - Shows thumbnails for images, and dimensions.
 - File and Folder copy, move, and deletion. 
 - File and folder permission changing.

Requirements
============

The following perl modules are required

- Gtk2
- Stat::lsMode
- File::Type
- MP3::Tag
- Image::Size
- Module::Build

Running
=======

  $ perl gui/old.pl
