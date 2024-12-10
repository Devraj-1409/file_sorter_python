# Automatic File Sorter

## Overview
This Python script automates the process of organizing files in a folder by their file types. It creates separate subfolders for Excel files, text files, and image files, and then moves the respective files into their designated folders.

## How It Works
1. **Folder Creation**: Checks if folders for file types (`excel files`, `text files`, `image files`) exist. If not, it creates them.
2. **File Sorting**: Iterates through the main folder, identifies files by their extensions (`.xlsx`, `.png`, `.txt`), and moves them to the corresponding subfolder.

## Features
- Automatically identifies file types based on their extensions.
- Creates subfolders dynamically if they don't already exist.
- Ensures files are not duplicated in the destination folder.

## Prerequisites
- Python 3.x
- `os` and `shutil` libraries (both are part of Python's standard library).

## Performed on:
- Jupyter Notebooks

## How to Use:
Update the path variable in the script to the directory you want to sort.
Run the script.
The files will be organized into subfolders based on their type.
