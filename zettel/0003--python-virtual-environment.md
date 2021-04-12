# Python3 virtual environments via venv

To **create a virtual environment**, decide upon a directory where you want to place it, and run the venv module as a script with the directory path:

`python3 -m venv tutorial-env`

This will create the `tutorial-env` directory if it doesn't exist, and also create directories inside it containing a copy of the Python interpreter, the standard library, and various supporting files.

Once you've created a virtual environment, you may **activate it**.

* On Windows, run: `tutorial-env\Scripts\activate.bat`
* *On Unix or MacOS, run:* `source tutorial-env/bin/activate`

(This script is written for the bash shell. If you use the `csh` or `fish` shells, there are alternate `activate.csh` and `activate.fish` scripts you should use instead.)

To quit the virtual environment type `deactivate` into the terminal.

## Notes

Don't forget to add the venv folder to a .gitignore file.


## Connections

[Python Programing Language Index](../zettel/000E--python-lang-index.md)