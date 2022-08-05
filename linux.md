# Linux Essential Commands

**to list down all the contents of a directory**
``` 
ls 
```

**Change directory and goes to bin directly**
``` 
cd /bin/ 
```

**change directory to home directory**
``` 
cd ~ 
```

**means to change directory one level up**
``` 
cd .. 
```

**create directory**
``` 
mkdir 
```

**current working directory**
``` 
pwd 
```

**print/show the contents of the file** 
``` 
cat <filename> 
```

**copy the contents from /home/ to /tmp**
``` 
cp /home/ /tmp/ 
```

**to move the file1.txt to the /NewDirectory**
``` 
mv /directoryName/fiel1.txt /NewDirectory 
```

**to delete the file**
```
rm fiel.txt
```

**search for any file or directory with a name that starts with linux**
```
find / -name "linux"
```

**This command displays information about the machine, the processor architecture, and the operating system details**
```
uname -a
```

**This command returns more information about the system such as the number of CPUs and the CPU speed**
```
lscpu
```

**This is a file that contains more information than the one displayed using the lscpu command**
```
cat /proc/cpuinfo/
```

**displays the disk space usage in all of the mounted devices**
```
df -h
```

**Displays all the files inside the specified directory and their corresponding file sizes. You can also specify a filename**
```
du ~/Downloads
```

**–s option provides the total file size of the specified directory and -h makes it human readable form**
```
du ~/Downloads -sh
```

**to create and empty file**
```
touch <file name>
```

**to change permissons (execute=1, write=2, read=4)**
```
chmod777 <file-name>
```

**While administering your system, it may be necessary to act as the super user (also called root). This is where the sudo (or super user do) command comes in. Assuming you're trying to do something that your computer alerts you that only an administrator (or root) user can do**
```
sudo <operation>
```

**to shut down from terminal**
```
sudo poweroff
```

