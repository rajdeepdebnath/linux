## linux useful commands

### sudo
Short for “SuperUser Do”, this command enables you to perform tasks that require administrative or root permissions. May be the logged in user do not have permission to remove a file from a folder, with sudo you can do this (but this practice is not recommended). Like `sudo rm -rf index.html`

### ls
List the contents of a folder. 
ls -R: includes subdirectories
ls -a: shows hidden files
ls -al: files with detaild information like permissions, size, owner etc.

### mkdir
to make a new directory

### find
to locate files within a folder. Like `find /var/ -name index.html` command will search for a file called notes.txt within the home directory and its subdirectories.

### grep
To search through all the text in a given file. `grep class index.html`

### df
To get a report on the system’s disk space usage (kb).

### head
To view the first lines of any text file. `head -n 5 filename.ext`.

### tail
To view the last lines of any text file. `tail -n 5 filename.ext`.


### diff
To compare the contents of two files line by line and output the lines that do not match. `diff file1.ext file2.ext`


### tar
To zip multiple files into one. 

### chmod
To change the ownership of a file. `chmod u=rwx,g=rx,o=r test.txt`. u = user, g = group, o = other user. So user can read, write, execute test.txt file; group can read and execute the text.txt file and other user can only read test.txt file.

### chown
To transfer the ownership of a file. `chown user2 file.text`.

### kill
To terminate execution of a program. You need process id of the program. `kill [pid]`

### ping
To check your connectivity status to a server.

### wget
To download file from internet. `wget http://test.123.co/abcd.zip`.

### history
To show history of all the commands ran in the terminal.

### echo
To write some data into a file. `echo 'Hellow world' >> test.txt`

### pwd
To find out the path of the current working directory.

### cd
To change directories. If you are in /var directory and want to go to /www directory which is inside /var directory, type `cd var` (relative path) or `cd /www/var` (absolute path)

### cat
To display the contents of a file. `cat index.html`.

### cp
To copy files from the current directory to a different directory. `cp index.html /var/www/html`

### mv
To move or rename files. `mv file.txt /home.`, `mv oldname.html newname.html`

### Update
To update linux os packages. `sudo apt update`

### apache2
Web server. To install `sudo apt install apache2`
