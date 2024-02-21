# Directory Management with the Terminal : 
bullet pointed stuff can be used in command line unless bold
### Show what is in current directory
* ls

### Show current directory and hidden files (not .. or . special directories):
* ls -A

### Show only hidden files in current directory:
* ls -a | grep "^\."
* We are using a pipe, | and the cmd grep here
    * **cmd line pipe: |**
    * **grep is a global regex search** 
    * **combined this translates to:**
    starts with the character '.'
     
### Print full current working directory:
* pwd 

### Home directory 
* *indicated by ~ as prompt*

To change back to the home directory use:
* cd ~
* **This is the default directory and allows us to change any other directory (as all are pathed starting here)**

To then change directory to desktop

* cd Desktop/

# Additional Command Line stuff
### Misc
For exiting manuals and other things:
* q

### For more on macos command line:
Using the pipe operator and careful use of "/" after every single file location we have:
* *cd ~/Desktop/drought_index/ | open mac-terminal-commands-cheat-sheet-pdf.pdf*
* **Note that we have a sole exception when just moving to one file for instance:**
* *cd ~*
followed by
* *cd Desktop*
is allowed.