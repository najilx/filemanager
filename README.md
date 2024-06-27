**Simple File Manager**
This is a simple file manager script written in Python. The script organizes files in a specified directory into folders based on their file extensions.

**Features**
Automatically creates folders for each file extension.
Moves files into their respective folders based on file extension.
Handles existing and non-existing folders gracefully.

**Requirements**
Python 3.x
os and shutil modules (These are standard Python libraries and do not require separate installation.)

**Usage**
1.Clone the repository or download the script file.
2.Run the script using a Python interpreter.
3.Enter the path of the directory you want to organize when prompted.

*How It Works*
The script prompts the user to enter the path of the directory to be organized.
It lists all the files in the specified directory.
For each file, it extracts the file extension.
It checks if a folder for that extension already exists:
If it exists, it moves the file into the existing folder.
If it does not exist, it creates a new folder and then moves the file into it.
