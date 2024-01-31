# Overview
If you're like me, you also refer to your projects or repositories using only their abbreviations. And this helps! It helps refer to things easily, it helps simplify the number of words you need to remember. However, when you want to open said project/repo on you local machine, you have no choice but to refer to it by it's actual name. And isn't that a pain! \
Hence, the completion function to help you open projects easily! (P.S. It might barely save 2 milliseconds but isn't that what life's all about :P) \
These completions are written particularly for the command `code` which I use. You can change it to anything you like. This and few other changes you can do have been mentioned and explained in subsequent sections. \
Have fun :))

# Bash
## How do I make it work?
Copy the contents in the file `bash/bash_completion` into a file which is sourced when your terminal starts up (for example, `~/.bash_completion` or `~/.bashrc`). An explanation of how this completion function works and what changes you might want to make is added in subsequent sections.

# Zsh
## How do I make it work?
Copy the contents in the file `zsh/zsh_completion` into a file recognized by the completion system (The result of `echo $fpath` will show you which folders are scanned). After this, do a `compinit` and you should be good to go.

# How does it work?
## Bash
## Zsh

# Modifications Suggested
