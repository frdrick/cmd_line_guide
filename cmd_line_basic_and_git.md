# Directory Management with the Terminal : 
*bullet pointed stuff can be used in command line unless italics* 
### Show what is in current directory
* ls  
### Print current working directory:
* pwd 

### Home directory 
* *indicated by ~ as prompt*

To change back to the home directory use:
* cd ~
* *This is the default directory and allows us to change any other directory (as all are pathed starting here)*

To then change directory to desktop

* cd Desktop/

# Additional Command Line stuff
### Misc
For exiting manuals and other things:
* q 

### For more on macos command line:
Using the pipe operator and careful use of "/" after every single file location we have:
* cd ~/Desktop/drought_index/ | open mac-terminal-commands-cheat-sheet-pdf.pdf
* Note that we have a sole exception when just moving to one file for instance:
* cd ~
followed by
* cd Desktop
is allowed.



# Virtual Envirnoment management with conda

### For list of current environments use:
* conda env list 
* *"*" will be next to the current virtual environment*
### Activate a working environment:
* conda activate name_of_directory

Alternatively copy the path of the environment from "conda env list" and paste as path_of_directory:
* conda activate path_of_directory
### Deactivate a working environment:
* conda deactivate

### Show packages installed within environment:
* conda list

Or show packages starting with py:

* conda list ^py

regex can be used to filter for packages.

### Delete an environment fully:

* conda remove -n ENVNAME --all 

### Rename an environment:

* conda rename -n ENVNAME NEWENVNAME

### For more conda 
* open conda-4.14.pdf

# git in command line
To clone a github repository use:
* git clone https://github.com/frdrick/NAME_OF_REPOSITORY.git

### Five main commands with *3 key ones*:
## *git status*
* git status
1. Are we in a git repository
2. If we are which files are:
    * Untracked
    * Ready to be comitted

## *git add*
* git add file_name

**Using filenames without spaces makes this much easier**
## *git commit*
* git commit -m "commit_message"
    * This "commit_message" should be informative
## git push
## git pull

Can use nano to look at what is in README.md:
* nano README.md
