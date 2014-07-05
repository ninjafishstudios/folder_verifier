Folder Verifier
===============


Installation
------------

~~~ sh
$ git clone git@github.com:williamlocke/folder_verifier.git
$ cd folder_verifier
$ rake install
~~~


Commands
--------
~~~ sh
  folder_verifier clone SOURCE    # Clones folder at given source, to given dest. Looks at number of images in per folder in source and creates a .x filename (e.g. .12) in each folder representing the intended number of images for each...
  folder_verifier fill PATH       # Verifies folder at given path.
  folder_verifier help [COMMAND]  # Describe available commands or one specific command
  folder_verifier print PATH      # Prints a representation of folder directory.
  folder_verifier verify PATH     # Verifies folder at given path.

~~~ 


Usage
-----

Verify a given directory
~~~ sh
$ folder_verifier verify Images
~~~

Print a directory structure
~~~ sh
$ folder_verifier print Images
~~~


Help
----

View available commands
~~~ sh
$ folder_verifier 
~~~

