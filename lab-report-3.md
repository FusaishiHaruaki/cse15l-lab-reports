# CSE15L Lab Report 3

## Find

`find` - "searches the directory tree rooted at each given starting-point". 
https://man7.org/linux/man-pages/man1/find.1.html

### -iname
The `iname` option behaves similar to `-name`, taking its following string as an argument, and searches for all files with names matching the given argument. Only that it is case insensitive when taking the argument for the file name. 


### -type
The `-type` option specifies the type of files found and returned. A few of the arguments include: f - regular file; d - directory. 

### -path 
The `-path` option takes the argument as a path and find all files matching the given path. 

### -size 
The `-size` option specifies the size limits to the files and directories being searched for. 
