# Working With Files and Directories
## Solutions
* Python: [Jupyter Notebook](answers/python/files-and-directories-solution.ipynb)  || [HTML](answers/python/files-and-directories-solution.html)


## A - Easy

### A1: Get current working directory

### A2: Get absolute path of a file
e.g.  /home/ubuntu/dev/python/a.txt

### A3: Extract path and short file name given an absolute file path
input : /home/ubuntu/dev/python/a.txt   
output : path=/home/ubuntu/dev/python,   file name=a.txt

### A4: Extract base file name and extension given a file
input : letter.docx   
output: base name = letter,   extension = docx

### A5: Create file in current working directory

### A6 : Print absolute path of user's home directory

-----------------------------------

## B - Medium

### B1: List all contents of a directory

### B2: List files and directories under a directory separately

### B3: List directory contents in alphabetical order (ignore case)

### B4: Print sizes of files in a directory

### B5 : Print number of lines and length of a given file

### B6 : Print number of lines for each file in a directory

### B7: Calculate hashes (md5, sha1 and sha256) for a given file
Extend this to calculate hashes for all files in a directory.  
How well your code is working for large files (several gigs in size)?  
You can generate some random file as follows (unix like systems)
```
    # this generates a 1G file
    dd if="/dev/random" of="file" bs=1M count=1000
```

### B8: Identify duplicate files in a directory
Files can arbitrarily large.  
Hint : use the 'hash' solution above
