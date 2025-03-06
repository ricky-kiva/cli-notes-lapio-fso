# The Command Line (notes)

##### Commands
- `ls`: List files inside directory
- `cd`: Change Directory
- `mkdir`: Make Directory
- `nano`: Text editor
- `vim`: Another text editor
- `touch`: Make file
- `cp`: Copy file
- `mv`: Move file (cut)
- `rm`: Remove file / folder (add `-r`)
- `cat`: Examine file's text
- `tail`: Examine file from bottom with `-n` parameter to specify the number of lines
- `head`: Examine file from top with `-n` parameter to specify the number of lines
- `grep`: Returns filtered specific lines from some search criteria
- `wget`: World wide web Get (download from internet)
- `chmod`: Change Mode (change permissions)
- `--help`: Display command's details

##### Operators
- `|`: The Pipe. Pass the output of a command, to another command
- `>`: Writes output of a command to a file
- `<`: Give contents of a file to a command
- `>>`: Writes output of a command to the new line of a file (keeping the old contents)

##### Paths
- `~`: Home directory
- `./`: Current Folder
- `../`: Parent of current folder

##### Wildcards
- `*`: Example, `*.txt` will select all text files inside the directory

##### Permissions
<img src="../main/stock/permission-structure.png" alt="File Permission Structure in Command Line">

- `r`: Read permission
- `w`: Write permission
- `x`: Execute permission
- `u`: Owner of the file
- `g`: Users belonging to the group of the file
- `o`: All other users
- `+`: Gives a permission
- `-`: Removes a permission

###### Permission Examples
- `chmod u+x example.txt`: Gives owner of the file execute permission
- `chmod o-w example.txt`: Removes other users the write permission
- `chmod go+r example.txt`: Gives group of the file & other users the read permission
