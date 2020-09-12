# My "cheat-sheet" for basic terminal usage

## Terminal cmd Line

### Line 1

- Line 1: prompt 'user@bash' command 'ls' commmand line argument ( -l /home/ryan ) **space separated**
  - the first cmd line argument '-l' aka an *option*
    - Options - used to modify the behavior the cmd line
- returns to prompt after cmd has run & the terminal isready for you

### The Shell Bash

- Shell: defines how the terminal will behave and looks after running (or executing) commands for you
- bash:Bourne again shell

### Shortcuts

- traverse this history using the up and down arrow keys

### Commands

- __pwd__ :Print Working Directory - your current or present working directory (where are we)
- __ls__ : List - show what's there - by itself - plain listing of our current location
  - __ls__ __[options]__ __[location]__ : square brackets ([]) = optional
  - **ls -a** : shows all files - even hidden
  - **ls -l** : long listing
    - First character indicates whether it is a normal file ( - ) or directory ( d )
    - Next 9 characters are permissions for the file or directory (we'll learn more about them in section 6).
    - The next field is the number of blocks (don't worry too much about this).
    - The next field is the owner of the file or directory (ryan in this case).
    - The next field is the group the file or directory belongs to (users in this case).
    - Following this is the file size.
    - Next up is the file modification time.
    - Finally we have the actual name of the file or directory.
      - **/etc** : Stores config files for the system
        - not to list our current directory but instead to list that directories contents
- **cd [location]** : Change Directory - cd without any arguments will always take back to home directory
- **/var/log** - Stores log files for various system programs
- **/bin** - The location of several commonly used programs
- **usr/bin** - Another location for programs on the system
- **file [path]** - obtains file details
  - path whenever a file or directory on the cmd line it is actually a path
  - a path is a means to get to a particular location in the system and that location is a file
- **man** **<command to look up>** - command to invoke manual pages
- **man** **-k** **<search term>** - to do a keyword search on the Manual pages
  - search w/in pages forward slash '/' followed by the term to search for
  - hit 'enter'; use 'n' button (for next) to cycle through multiple

- __mkdir__ __[options]__ __<Directory>__ - Make Directory: run mkdir supplying only a directory and it will create it forx us

  - -p which tells mkdir to make parent directories as needed
  - -v which makes mkdir tell us what it is doing

- __rmdir__ __[options]__ __<Directory>__ - removes directory
  - no undo!
  - directory must be empty
- __touch__ __[options]__ __<filenames>__- Creates blank file - if we touch a file and it does not exist, the command will do us a favor and automatically create it for us
- __cp__ __[options]__ __<source>__ __<destination>__ - both the source and destination are paths can use both absolute and relative paths
- __mv__ __[options]__ __<source>__ __<destination>__ - move file or directory
  - can be used to rename file & dir as well
- __rm__ __[options]__ __<file>__ - removing or deleting file or dir
  - removing a file is an action that may not be undone so be careful

### Paths

- root directory - very top of hierarchy - denoted by a single slash ( / )
- **absolute** - specify a location (file or directory) in relation to the root directory
  - always begins with a forward slash ( / )
- **relative** - specify a location (file or directory) in relation to where we currently are in the system
  - not begin with slash
- ~ (tilde) - shortcut for your home directory
  - /home/ryan/Documents or ~/Documents
- . (dot) - This is a reference to your current directory
- .. (dotdot)- This is a reference to the parent directory. use several times in a path to go up the hierarchy

## More About Files

- *Everything in Linux is actually a file
Linux ignores file extensions
- Linux **IS** case sensitive
- **Caution** spaces - on cmd line spaces used to separate items
  - single or double quotes around entire item - inside quotes is single item
  - *escape* *characters* - a backslash (\) escape (or nullify) the special meaning of the next character - auto when using Tab complete

## Manual Pages

- a set of pages that explain every command available on your system
  - including what they do
  - the specifics of how you run them
  - what command line arguments they accept
- 'q' for quit to exit
- long hand options begin with two dashes (--) while short hand begin with single dash (-)

## Wildcards

- '*' represents zero or more characters
- ? represents a single character
- [] represents a range of characters
