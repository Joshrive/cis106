https://github.com/ra559/cis106/blob/main/homework/homework4.md 

# Homework: 4  The Linux Filesystem

Watch the video [“Linux Filesystem Explained”](https://www.youtube.com/watch?v=HbgzrKJvDRw) and read the presentation [“How to navigate the filesystem”](http://bit.ly/3t30rMQ) then answer the questions below.

1. **Explain the difference between absolute path and relative path:**
   
* An absolute path is defined as the specifying the location of a file or directory from the root directory(/).
* Relative path is defined as the path related to the present working directly(pwd). It starts at your current directory and never starts with a /.


2. **Why Linux uses / instead of \ for its directory paths?**
   
Unix introduced the forward slash character as its directory separator around 1970. We don’t really know why they chose this one, but that’s the one they picked.Backward slash is used by Windows. 

3. **In Windows, these files are all the same: File FILE file and FiLE. But in Linux this is not the case, Why?**

Linux is "dumb" therefore it is case-sensitive. 

4. **What is the Filesystem Hierarchy Standard (FHS) and who maintains it?**

FHS defines the directory structure and directory contents in Linux. It is maintained by the linux foundation. 


5. **Explain what type of files are stored in the following directories:**

Directory | What is it used for?
--------- | --------------------
/bin    | Standard subdirectory of the root directory
/dev    | Is the location of special or device files
/etc    | Contains configuration files which is generated be 
/home   | Directory for a particular user of the system and consists of individual files.
/lib    | Directory which contains all helpful library files used by the system
/opt    | Reserved for the installation of add-on application software packages.” 
/tmp    | Contains mostly files that are required temporarily
/var    | Var is a standard subdirectory of the root directory
/proc   | This directory holds all the details about the linux system
/usr    | Contains the user-land programs

6. **How does a period at the beginning of a file name means (example .bashrc)?**
A file with a leading period means the file is hidden and will not appear when running the "ls" command.

7. **Which command would you use to list all the files inside the /usr/share/ directory?**

` ls /user/share/ `

`ls -a /user/share `

-a should list hidden files

8. **If you are working in the /usr/share/icons directory and want to move to your home directory, which command would you use?**

` cd `

9. **Explain what these commands do:**

`cd .config/.htop; cd ../; ls -lX`

cd changes directory, ; starts a new commands, change to the directory before .htop, then ls -l will long list, -X will sort alphabetically by file extension 


1.  **John has a lot of files in the directory /var/www/html/webapp. He wants to long list all the files, including hidden files, by modification time (newest first), and with human-readable file sizes. Which command should he use conjuring that his current working directory is:** 
    
`/home/john/.git/`


Command should be ` ls -lath `