# Empty Recycle Bin Batch Script

## Description
This is a simple batch script that empties the Windows Recycle Bin. It is designed for learning purposes and can be used for automation tasks in a Windows environment.

## Usage
1. Clone this repository to your local machine.
2. Open Command Prompt.
3. Navigate to the directory where the script is located.
4. Run the script by typing `EmptyRecycleBin.bat`.

## Script Overview
```batch
@echo off
echo Emptying Recycle Bin...
rd /s /q C:\$Recycle.Bin
echo Recycle Bin emptied successfully.
cls
```

## Prerequisites
- Windows operating system

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing
If you'd like to contribute, please fork the repository and create a pull request.

## Acknowledgments
Inspired by learning batch scripting and automation.
