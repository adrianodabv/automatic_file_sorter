# Automatic File Sorter
Python code for a MacOS file sorter that automatically organizes your Downloads folder every hour


## Overview
The Automatic File Sorter is a Python script designed to organize files in your Downloads folder into specific subfolders based on their file types. This project helps keep your Downloads directory clean and makes it easier to find files by automatically sorting them into designated categories.

## Features
- **File Organization:** Automatically sorts files into predefined folders:
  - Image Files
  - Movie Files
  - PDF Files
  - Document Files
  - Excel Files
  - PowerPoint Files
    
- **Continuous Sorting:** The script runs indefinitely, checking for new files every hour and sorting them accordingly.

## Prerequisites
- Necessary permissions to create folders and move files in your Downloads directory.

The script will create the necessary folders in your Downloads directory if they don't already exist and start moving files based on their types.


**Code Explanation
- The script imports necessary modules: os, shutil, and time.
- It defines the path to the Downloads folder and the names of the subfolders to create.
- A function move_files() is defined to handle the sorting of files based on their extensions.
- The script runs indefinitely, checking for new files every hour and sorting them into the appropriate folders.

**Note
- Make sure to customize the path variable for your Downloads folder.
- You can adjust the time interval in the time.sleep() function (currently set to 3600 seconds) if you want the script to check for new files more or less frequently.
