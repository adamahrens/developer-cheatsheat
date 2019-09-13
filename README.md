# developer-cheatsheet
Developer Cheatsheet

# Terminal

To open do `command + spacebar` then type `Terminal` and hit `Enter`

## Listing files

Use the `ls` command to list files and folders in the current directory

```~/Development/python-challenge: $ ls```

Returns

`PyBank		PyPoll		README.md`

## Print Working Directory

Will return the full file path you're at. Use `pwd` to see this in action

```~/Development/python-challenge: $ pwd```

Returns

`/Users/adamahrens/Development/python-challenge`

## Change Directories

Lets say we have this as a folder structure

- Documents
  - python-challenge
    - PyBank
    - PyPoll
     
  Lets attempt to get to the PyBank folder
  If we do a `ls` and it returns `Documents`. Then we'd write `cd python-challenge/PyBank/`
  
  We're now located at
  > Documents/python-challenge/PyBank
  
  Lets attempt to get back to the `Documents` folder
  Type `cd ../..` will cause you to jump back two folders
  Anytime you type `cd ..` it will take you to the parent folder.
  
  ## Making a new Folder
  
  Use the `mkdir name_you_want_for_your_folder` to make a new Folder
  
  Lets attempt to add a new folder under `python-challenge`
  
  `cd ~/Documents/python-challenge`
  
  `mkdir MyNewFolder`
  
  We can verify it with `ls` which will now show
  > MyNewFolder	PyBank		PyPoll		README.md
  
  ## Open Current Location in Terminal in Mac Finder
  
  Sometimes you just want to move, delete, copy, paste a file or folder in the Mac Finder with your GUI.
  
  To do that from a location in Terminal just type `open .`
