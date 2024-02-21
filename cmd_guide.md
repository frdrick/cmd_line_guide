# Command Prompt Guide 

## Using fzf (fuzzy finder) 

Open file search:
* *control+t*

Then type rough name of file name or folder containing said file. When selected press:
* *enter*

Escape search:
* *esc*

### To set as current (or working) directory
Now again press:
* *enter*
setting this as the working directory.

### Open this directory in vscode:
When in chosen directory from the above fzf search, use:
* *code .*

to open the directory straight to vscode.

### Opening a file
We don't have to change directory at all and can simply search for our desired file and open.

Prefix our *control+t* fuzzy search so we have:
* *open* *(control+t)* **SELECT FILE** *enter*

### Removing files from a directory:

* *rm* **filename**

## Takeaway
The key point here is that we can weave fuzzy searches into the cmd line at any time by using *control+t*