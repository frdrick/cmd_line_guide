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