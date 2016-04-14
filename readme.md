(Not sure where I originally found this code, probably a recipe...but it had numerous bugs and most of them should be fixed)

This script will scan a directory tree looking for duplicate files

## Running Duplicate files
An example of running this script to just list all the duplicate files would be:
    python DuplicateFiles.py /Users/Daniel/Documents
    
An example of running this script to list and delete all the duplicate files would be:
        python DuplicateFiles.py /Users/Daniel/Documents -remove

To run the gui:
        python DuplicateFiles.py -gui
