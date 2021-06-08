## Instructions for setting up the computing environment

The first two days of tutorials will follow along with parts of the Software
Carpentry [Unix tutorial](http://swcarpentry.github.io/shell-novice/) and
[Python tutorial](https://swcarpentry.github.io/python-novice-inflammation/).
The third day will focus on Python for Heliophysics.

### Install the Unix (bash) shell

Please follow Software Carpentry's [instructions for installing the bash
shell](https://carpentries.github.io/workshop-template/#shell).

### Download this repository to your computer

Please download the [zip file for this
repository](https://github.com/namurphy/Solar_Computing_Tutorial/archive/refs/heads/main.zip)
and unzip it.  It will create a directory called `Solar_Computing_Tutorial-main`
that contains the files needed for these tutorials.

### Install Anaconda

Please follow these instructions for
[installing Anaconda](https://docs.anaconda.com/anaconda/install/).
When this is done, you should have Anaconda Navigator installed.

### Create a Python environment with Anaconda

The `Solar_Computing_Tutorial-main` directory that was created after
[downloading and unzipping the
repository](https://github.com/namurphy/Solar_Computing_Tutorial/blob/main/setup_instructions.md#download-this-repository-to-your-computer) in a previous step will contain a file called
`environment.yml`.  This file contains information about the Python packages
that need to be installed for this tutorial.

[Open Anaconda
Navigator](https://docs.anaconda.com/anaconda/user-guide/getting-started/#open-navigator),
and [follow these
instructions](https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/#importing-an-environment) 
with the `environment.yml` file.  This should create a new environment
called `sreu` that has everything we need installed in it.

If you go to the "Environments" tab on Anaconda Navigator, the `sreu`
environment should be listed.  Click on the arrow for that 
environment, and select the option to "Open with Jupyter Notebook".
If that opens successfully in your browser, then type
```Python
import aiapy
```
and use shift-enter to execute the cell.  If everything installed correctly,
then this should run without any errors.  

## Using binder as a backup

If you have difficulty installing the software, an alternative is to go to this
**[binder link](https://mybinder.org/v2/gh/namurphy/Solar_Computing_Tutorial/main)**,
which will create a computing environment with everything that you need installed.
The disadvantage of binder is that it doesn't automatically save your progress, so
you might lose your progress if your internet connection is intermittent. This won't
be a huge problem when we go through the Unix shell, but we ran into problems with
it last year when covering Python.
