# Basic BASH / Terminal commands on Linux

Again thanks to [\<rwxrob\>](https://duckduckgo.com/?q=rwxrob+github). 



## List of Commands / Programs

* `pwd          ->` Print working directory

* `ls           ->` List files in current directory

* `clear        ->` Clears the terminal frame

* `cd dirname   ->` Change directory to `dirname`. If you give no argument it defaults to the home folder.

* `cd ..        ->` Go up one folder

* `mkdir        ->` Create a directory

* `mv           ->` Stands for "move". But it is also used to rename files and folders.

* `touch        ->` Updates the timestamp of a file or folder. If the file does not exists it will be created (empty).

* `rm           ->` Deletes a file

* `chmod +x     ->` Makes a file executable

* `./filname    ->` If you want to execute a file that is not in the "PATH" and you deem trustworthy.

* `cat          ->` Print out contents of file

* `ssh          ->` Try to establish a secure shell connection to the target. *For example to test if the secure shell key you gave to gitlab works and everything is correctly setup: `ssh git@gitlab.com`*

* `ping         ->` Tries to ping a target and see if a connection can be established.

* `which        ->` Looks if an application / command is installed on the system and writes the full path of COMMAND(s) to standard output.

* `cp           ->` Copy file first argument is the source file or the path to the source file and the second argument is the target directory. If a `.`is used the source file will be copied into the current working directory.

* `type         ->` Get a short description of the type the command is linked to. Example: alias, shell builtin...


## Connections
[More basic terminal commands from tlcl 2nd edition](../zettel/0002--more-basic-bash-terminal-commands-tlcl-2nd-ed.md)

[Back to Main Index](../README.md)