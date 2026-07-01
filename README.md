# Smart File Organizer

## Project Overview
This project is a smart tool written with C programming language. It helps users clean up cluttered folders. It automatically scans a folder and separates files into organized folders like Documents, Images, Music, Videos, and Programs. It runs automatically every 2 hours to keep the computer clean without any manual work.

## Features
- *Auto-Sorting*: Finds file types (.pdf, .jpg, .mp4, etc.) and moves them instantly.
- *Auto-Folder Creation*: Creates the target folders automatically if they are missing.
- *Runs in Background*: Checks the folders every 2 hours without disturbing the user.


## Programming Concepts Used
- *File System Handling*: Reading directories and finding files inside folders.
- *String Manipulation*: Looking at the letters at the end of a file name (like .txt) to find its extension.
- *Process Automation*: Using an endless loop with a built-in sleep timer to wait for 2 hours.
- *System Commands*: Using code to rename and move files from one place to another.

## How to Compile and Run

### How to Compile (Build)
Open your terminal or command prompt and type this command to build the program:
bash
gcc main.c -o SmartFileOrganizer


### How to Run
To clean and organize the files in your current folder, run this command:
bash
./SmartFileOrganizer
