# My command line "cheat-sheet" 

## Terminal

### Line 1: 
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
       - **/etc** :not to list our current directory but instead to list that directories contents

### Paths
- root directory - very top of hierarchy - denoted by a single slash ( / )
- **absolute** - specify a location (file or directory) in relation to the root directory
  - always begins with a forward slash ( / )
- **relative** - specify a location (file or directory) in relation to where we currently are in the system
  - not begin with slash
- ~ (tilde) - shortcut for your home directory
  - ome directory is /home/ryan

