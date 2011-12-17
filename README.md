# Description

A collection of unix-style utilities that I find useful

## Install

Simply:

    git clone git@github.com:tobym/bin.git ~/bin

and ensure this is in your path by adding this in .bash_profile:

    export PATH=$HOME/bin:$PATH

## Binaries included:

* `trim` - trims whitespace from STDIN. Requires ruby to be on the PATH. Developed purely for `pwd | trim | pbcopy`.
* `pbappend` - append STDIN to Mac pastebuffer. Like `xsel -a` in Linux; complements built-in `pbcopy` and `pbpaste`.
