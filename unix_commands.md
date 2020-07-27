- inside our VM ubuntu 16.04

## sudo apt-get update -y  

- Where Am I?  #pwd - is the command to see your current location
- Who am I?  #who - which machine am I on
- What do I have available in current dir  #ls - List current files in my directory
- What do I have available in current dir that is hidden  #ls -a - Shows hidden files (a - all)
- How can I find out the name of the system im using  # uname  - This prints ou the current system name (Linux)

- How can we create a file?  #touch myfirstfile.txt - this creates a file in your directory (ls) can show it
- How can we make a directory?  #mkdir myfirstdir - this create a directory in your current directory (ls) can show it
- How to navigate inside a directory?  #cd myfirstdir


EXERCISE
- Create 2 folders, directory 1 and directory 2.
- In each folder create 2 files test1.txt and test2.txt
- Check the current dir location and document the command to access the dir and exit
- How to save the file in nano
- (..cd) takes you back 1 directoryy

- **Continuation**

- How can we navigate in Linux
- Go back a directory is (..cd)
- Go back to home location is (cd) for example the base drive or VM root
- How do we remove a file #sudo rm myfirstfile.txt (this removes the file) - doesn't work as directory
- If you want to access the root/ admin rights inside a virtual machine use #sudo su (can be password protected)
- how to check who is using the machine #id (this will give you a rundown of all users in the machine)
- In order to print on the command line use #echo (like in a programming language)

- How can we install packages - sudo apt-get install nginx -
- We can then check the status, start or stop the service.  - systemctl status nginx -  


