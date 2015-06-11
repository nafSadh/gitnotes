# gitnotes
Notes about Git

handy commands
==============
#### Move a file to a new folder, keeping Git history
    git mv [-f] [-n] <source> <destination>
    git mv [-f] [-n] [-k] <source> ... <destination directory> 

#### Push only a subdir to a remote master
    git subtree push --prefix=subdir heroku master
