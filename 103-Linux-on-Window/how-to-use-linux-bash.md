# How to Use Linux Bash Command Lines

On Linux|Ubuntu, you need to prefix a command with <b>sudo</b> to run it with root permissions. <br/>
The “root” user on UNIX platforms has full system access, like the “Administrator” user on Windows. <br/>
#### Your Windows file system is located at /mnt/c in the Bash shell environment <br/>

Use the same Linux terminal commands you’d use to get around. <br/>
If you’re used to the standard Windows Command Prompt with its DOS commands,  <br/>
here are a few basic commands common to both Bash and Windows: <br/>

=> Change Directory: <b>cd</b> in Bash, cd or  chdir in CMD <br/>
=> List Contents of Directory:  <b>ls</b> in Bash, dir in CMD <br/>
=> Move or Rename a File: <b>mv</b> in Bash, move and  rename in CMD <br/>
=> Copy a File: <b>cp</b> in Bash,  copy in CMD <br/>
=> Delete a File: <b>rm</b> in Bash,  del or erase in CMD <br/>
=> Create a Directory:  <b>mkdir</b> in Bash, mkdir in CMD <br/>
=> Use a Text Editor: vi or <b>nano</b> in Bash,  edit in CMD <br/>
![dir -al command image](https://github.com/SanjeevStephan/Kali-Linux/blob/master/102-Kali-Linux-on-Window/img/commandline-dir-al.JPG)
![dir -al command image](https://github.com/SanjeevStephan/Kali-Linux/blob/master/102-Kali-Linux-on-Window/img/commandline-cd-mnt.JPG)

It’s important to remember that, unlike Windows, the Bash shell and its Linux-imitating environment are case-sensitive.  <br/>
In other words, “File.txt” with a capital letter is different from “file.txt” without a capital. <br/>

For more instructions,
## Check out the Beginner’s guide to the Linux command-line and other similar introductions to the Bash shell,Linux terminal online.
( https://www.howtogeek.com/140679/beginner-geek-how-to-start-using-the-linux-terminal/ ) . <br/>

## You’ll need to use the apt command to install and update the Ubuntu environment’s software.
( https://www.howtogeek.com/234583/simplify-command-line-package-management-with-apt-instead-of-apt-get/ ) <br/>
Be sure to prefix these commands with sudo , which makes them run as root–the Linux equivalent of Administrator.  <br/>
#### Here are the apt-get commands you’ll need to know:
=> Download Updated Information About Available Packages: sudo apt update  <br/>
=> Install an Application Package:  sudo apt install packagename (Replace “packagename” with the package’s name.)  <br/>
=> Uninstall an Application Package:  sudo apt remove packagename (Replace “packagename” with the package’s name.)  <br/>
=> Search for Available Packages:  sudo apt search word (Replace “word” with a word you want to search package names and descriptions for.)  <br/>
=> Download and Install the Latest Versions of Your Installed Packages: sudo apt upgrade  <br/>
