# How to use

Download/clone the test folder and put it into your asgn2 directory. You can add "test/" to .gitignore and the test folder will not be tracked by git. This script depends on `httpserver` being in your `$PATH` variable.  

The  simplest way to do this is to edit .bashrc and add the line `export PATH=$PATH:./`. `.bashrc` can be found in you home directory (`~`). If you open terminal, this is where it opens by default or you can do `cd ~`.   

The script also needs your makefile to support the `all` and `spotless` target, which it should anyway for the assignment.  

Finally, from your asgn2 directory `cd test` and type `a2test`. You may need to do `chmod +x a2test` so that the script will be executable.
