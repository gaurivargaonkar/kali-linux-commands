
# Kali Linux Commands

A collection of basic Linux/Kali commands I practiced, saved as PowerShell (.ps1) files with notes on what each command does.

## Files

### Commands/Basic_Command.ps1
Basic commands to list files and check the current directory:
- `ls` - list files and directories
- `ls -la` - show hidden files with details
- `pwd` - show current directory path

### Commands/Viewing_Updating_file_content....ps1
Commands to create, view, and read file content:
- `echo "text" > file.txt` - write text to a file (replaces content)
- `echo "text" >> file.txt` - add text to a file (without deleting existing content)
- `cat file.txt` - print full file content in the terminal
- `head file.txt` - show first 10 lines by default
- `head -n7 file.txt` - show first 7 lines
- `tail file.txt` - show last 10 lines by default
- `tail -n5 file.txt` - show last 5 lines
- `tail -f file.txt` - live monitor a file for new content being added

### Commands/file_folder_operation.ps1
Commands to manage files and folders:
- `mkdir foldername` - create a new folder
- `touch file.txt` - create a new empty file
- `cp file.txt ~` - copy a file to another location
- `mv file.txt destination/` - move a file to another folder
- `mv oldname.txt newname.txt` - rename a file
- `rm file.txt` - delete a file
- `rm -r foldername` - delete a folder and its contents

## Purpose
This repo is a personal reference for basic Linux command-line skills, practiced in Kali Linux.
