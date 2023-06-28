![cover image](https://github.com/SanjeevStephan/Kali-Linux/blob/master/102-Kali-Linux-on-Window/figlet-images/figlet-all-commands.jpg)

# Index
* <a href="https://github.com/SanjeevStephan/Kali-Linux/blob/master/101-Getting-Started-with-Linux/commands.md#file-commands">File commands</a>
* <a href="https://github.com/SanjeevStephan/Kali-Linux/blob/master/101-Getting-Started-with-Linux/commands.md#file-permissions">File Permissions</a>
* <a href="https://github.com/SanjeevStephan/Kali-Linux/blob/master/101-Getting-Started-with-Linux/commands.md#system-info-commands">System Info Commands</a>
* <a href="https://github.com/SanjeevStephan/Kali-Linux/blob/master/101-Getting-Started-with-Linux/commands.md#search-commands">Search Commands</a>
* <a href="https://github.com/SanjeevStephan/Kali-Linux/blob/master/101-Getting-Started-with-Linux/commands.md#process-management">Process Management</a>
* <a href="https://github.com/SanjeevStephan/Kali-Linux/blob/master/101-Getting-Started-with-Linux/commands.md#network-commands">Network Commands</a>
* <a href="https://github.com/SanjeevStephan/Kali-Linux/blob/master/101-Getting-Started-with-Linux/commands.md#ssh-commands">SSH Commands</a>
* <a href="https://github.com/SanjeevStephan/Kali-Linux/blob/master/101-Getting-Started-with-Linux/commands.md#execute-shell-sh-command">Execute Shell Command</a>
* <a href="">title</a>

# Bash Shell Command
Install Apt Packages as $uperuser (root access)

    sudo apt-get install <pkgname>
Execute Shell 

    sh <file.sh>    |OR|
    ./file.sh
# File Commands
 Directory Listing

    ls
 Formated List files|directories   

    ls -n
Create Symbolic shortcut link to file

    ln -s <file> <link-path> 
Formated hidden list files|direcories  

     ls -al
Change Directory

    cd <dir-name>
Change Directory

    cd <dir-name>  
 Show Current Directory

    pwd
Create or Update File    

    touch <file> or nano <file>
Create or Make Directory   

    mkdir <dir>
Remove or delete file  

     rm <file> 
Forcefully Remove file  

     rm -f <file>     
Delete directory

     rm -r <dir>
Change Directory

    cd <dir-name>    
Copy the content of <file1> into <file2>
 
    cp <file1> <file2>
Rename the <file1> to <file2>
 
    mv -i <file1> <file2>
Output first 10 lines of the file   

    head <file>
Output last 10 lines of the file    

    tail <file>
Output contents of file as it grows   

    tail -f <file>
Output More the content of the file    

    more <file>
Output Less the content of the file    

    less <file>
    
# System Info Commands    
who are you logged in as

    whoami 
show current date/time

    date
show this month's calendar

    cal    
show uptime 

    uptime    
display who is online and what they are doing

    w    
show kernal config

    uname -a
cpu info

    cat /proc/cpuinfo    
memory informatione

    cat /proc/meminfo    
show disk usage

    df    
show directory space usage

    du -sh
human readable size in GB

    date    
show memory and swap usage

    free    
show possible location of app

    whereis app    
show which app will be run by default

    which app
    
# Search Commands
search for pattern in files

    grep <pattern> <files>    
search recursively for pattern in dir

    grep -r <pattern> <dir>    
search for pattern in the output of command

    command | grep pattern 
find all instances of file

    locate <file>
    
# File Permissions    
 Change permission of file <br/> 
  4 - read(r)  <br/>
  2 - write(w)  <br/>
  1 - execute(x)  <br/>

    chmod +x <file.sh>
  for everyone

    chmod 777 -rwx <file.sh> 
  for owner

     chmod 755 -rwx <file.sh>
  for group|world 

    chmod 755 -rx <file.sh>
    
# Process Management    
Display currently active process

    ps  
 Ps with a lot of details

    ps aux
Kill process with pid 'pid'    

    kill pid
Kill al process named proc  

    killall proc
Lists background jobs  

     bg 
Bring most recent job to foreground  

     fg     
Bring job n to foreground

     fg n
     
# Apache2 Web Server Commands     
Start Apache2 Server

    service start apache2
    |or|
    systemctl start apache2.service
Stop Apache2 Server

    service stop apache2
    |or|
    systemctl stop apache2.service
Restart Apache2 Server

    service restart apache2
    |or|
    systemctl restart apache2.service   
    
# SSH Commands     
Connect to host as user

    ssh user@host    
Connect using port p
 
    ssh -p port user@host
Connect and use bind port
 
    ssh -D port user@host
    
# Network Commands    
Ping host host   

    ping host
Show Network Interface

    ifconfig
Show Monitor Interface

    iwconfig    
Get whois for domain  

    whois domain
Get DNS for domain   

    dig domain 
Reverse lookup host    

    dig -x host
    
# Download Command    
Download file    

    wget file   
Continue stopped downloads

    wget -c file
Recursively download file from url

    wget -r url    
Git Clone

    git clone https://github.com/SanjeevStephan/Kali-Linux.git
Download YouTube 

    youtube-dl https://www.youtube.com/channel/UC0ZTPkdxlAKf-V33tqXwi3Q
# Mount Commands    
List all formate disk

    fdisk -l    
Disk mount

    mount /dev/sda3  
ISO mount

    mount /home/disk-images/dwva.iso
    ( will be mounted to /root/dwva )

# Linux Window Commands    
Open GNONE Terminal 

    gnome-terminal    
show current date/time

    date    
show current date/time

    date    
show current date/time

    date
show current date/time

    date    
show current date/time

    date    
show current date/time

    date    
show current date/time

    date
show current date/time

    date    
show current date/time

    date    
show current date/time

    date
# File Commands
 Directory Listing

    ls
 Formated List files|directories   

    ls -n
Create Symbolic shortcut link to file

    ln -s <file> <link-path> 
Formated hidden list files|direcories  

     ls -al
Change Directory

    cd <dir-name>
Change Directory

    cd <dir-name>  
 Show Current Directory

    pwd
Create or Update File    

    touch <file> or nano <file>
Create or Make Directory   

    mkdir <dir>
Remove or delete file  

     rm <file> 
Forcefully Remove file  

     rm -f <file>     
Delete directory

     rm -r <dir>
Change Directory

    cd <dir-name>    
Copy the content of <file1> into <file2>
 
    cp <file1> <file2>
Rename the <file1> to <file2>
 
    mv -i <file1> <file2>
Output first 10 lines of the file   

    head <file>
Output last 10 lines of the file    

    tail <file>
Output contents of file as it grows   

    tail -f <file>
Output More the content of the file    

    more <file>
Output Less the content of the file    

    less <file>
    
# System Info Commands    
show current date/time

    date
show current date/time

    date    
show current date/time

    date    
show current date/time

    date    
show current date/time

    date
show current date/time

    date    
show current date/time

    date    
show current date/time

    date    
show current date/time

    date
show current date/time

    date    
show current date/time

    date    
show current date/time

    date    
show current date/time

    date
show current date/time

    date    
show current date/time

    date    
show current date/time

    date
# File Commands
 Directory Listing

    ls
 Formated List files|directories   

    ls -n
Create Symbolic shortcut link to file

    ln -s <file> <link-path> 
Formated hidden list files|direcories  

     ls -al
Change Directory

    cd <dir-name>
Change Directory

    cd <dir-name>  
 Show Current Directory

    pwd
Create or Update File    

    touch <file> or nano <file>
Create or Make Directory   

    mkdir <dir>
Remove or delete file  

     rm <file> 
Forcefully Remove file  

     rm -f <file>     
Delete directory

     rm -r <dir>
Change Directory

    cd <dir-name>    
Copy the content of <file1> into <file2>
 
    cp <file1> <file2>
Rename the <file1> to <file2>
 
    mv -i <file1> <file2>
Output first 10 lines of the file   

    head <file>
Output last 10 lines of the file    

    tail <file>
Output contents of file as it grows   

    tail -f <file>
Output More the content of the file    

    more <file>
Output Less the content of the file    

    less <file>
    
# System Info Commands    
show current date/time

    date
show current date/time

    date    
show current date/time

    date    
show current date/time

    date    
show current date/time

    date
show current date/time

    date    
show current date/time

    date    
show current date/time

    date    
show current date/time

    date
show current date/time

    date    
show current date/time

    date    
show current date/time

    date    
show current date/time

    date
show current date/time

    date    
show current date/time

    date    
show current date/time

    date 
    
