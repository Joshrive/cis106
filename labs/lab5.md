# Lab 5 | Handling Text Files Answers to lab
 
## Question 1 
Cat, head and tail commands are used for displaying the content of a file.
1. Display the content of the `/etc/passwd` file.
      ![Image1.1](../imgs/Lab5/Q1.1.png)
2. Display the content of the `/etc/passwd` file in reverse order.
    ![Image1.2](../imgs/Lab5/Q1.2.png)
3. Display the content of the `/etc/passwd` file with line numbers and the $ to indicate the end of every line.
    ![Image1.3](../imgs/Lab5/Q1.3.png)
4. Display the first 5 lines of a the `/etc/passwd` file.
    ![Image1.4](../imgs/Lab5/Q1.4.png)
5. Display the last 5 lines of the `/etc/passwd` file.
    ![Image1.5](../imgs/Lab5/Q1.5.png)

---
## Question 2
The cut command is very useful when working with files that are already formatted using a field separator. The cut command can show specific information about each line of text in a given file.

1. Display the first field of the `/etc/passwd` file.
    ![Image2.1](../imgs/Lab5/Q2.1.png)
2. Display the last 5 users in the `/etc/passwd` file.
    ![Image2.2](../imgs/Lab5/Q2.2.png)
3. Display a list of all the users and their designated login shell separated by an `=` sign.
    ![Image2.3](../imgs/Lab5/Q2.3.png)
4. The sort command is another amazing tool in any linux user’s tool box. Sort allows you to display data in a given order. Cut the first and 3rd field of the `/etc/passwd` field and sort the output. 
    ![Image2.4](../imgs/Lab5/Q2.4.png)
5. Repeat the previous command but this time only show the last 5 entries.
    ![Image2.5](../imgs/Lab5/Q2.5.png)



## Question 3
The wc command is used to count the number of lines, characters and words in a file.

1. How many lines does the `/etc/passwd` file have?
2. How many words does the `/etc/passwd` file have?

   ![image3.1](../imgs/Lab5/Q3.1-2.png)


3. How many users can login with the `/bin/bash` shell?
   ![image3.3](../imgs/Lab5/Q3.3.png)
4. How many users have the `/sbin/nologin` shell assigned?
   ![image3.4](../imgs/Lab5/Q3.4.png)
5. Display your user’s information in `/etc/passwd` file
   ![image3.1](../imgs/Lab5/Q3.5.png)


## Question 4

The ip command is used to manage network interfaces. To display the current NICs configuration, type: `ip ad` which is short for `ip address`. We are going to use the commands we learned to parse the output of the ip command.



1. Run the `ip ad` command and display all the lines that match the string `inet`. How many lines did you get? 
   ![image4.1](../imgs/Lab5/Q4.1.png)
2. Run the `ip ad` command and display all the lines that match the string `inet6`. Display the output in reverse order.
   ![image4.2](../imgs/Lab5/Q4.2.png)
3. Run the `ip ad` command and display all the lines that match the string `inet` or `inet6` sort the output and save it to a file.
   ![image4.3](../imgs/Lab5/Q4.3.png)
4. Run the `ip ad` command and display only the 3rd line that matches the string `inet`.
5. ![image4.4](../imgs/Lab5/Q4.4.png)
6. Run the `ip ad` command and display all the ipv4 addresses sorted.
   ![image4.5](../imgs/Lab5/Q4.5.png)

## Question 5

1. Run the following command and save the output to a markdown file: `echo "# Information about my pc"`. You can use any naming convention you want for the file as long as it is a markdown file.
   ![image5.1](../imgs/Lab5/Q5.1.png)
2. Run the following command and append the output to the markdown file you created earlier: `echo "## CPU Information"`
   ![image5.2](../imgs/Lab5/Q5.2.png)
3. The `lscpu` command displays a lot of information about the CPU the computer has. Use the `lscpu`, `grep`, and the pipe (|) to extract, and append to the file you created earlier, the following information from the output of the `lscpu` command:
   * Architecture
   * Threads
   * Cores
   * Model name
   * CPU Frequency
   * Virtualiation technology supported
  ![image5.3](../imgs/Lab5/Q5.3.png)
4. Run the following command and append the output to the markdown file you created earlier: `echo "## RAM Information"`
  ![image5.4](../imgs/Lab5/Q5.4.png)
5. The command `lshw -c memory` displays information about the RAM installed in your system. Extract and append to the file the following information:
    * Memory size:
  ![image5.5](../imgs/Lab5/Q5.5.png)
6. Display the content of the file you created earlier showing all the data that has been appended so far.
  ![image5.6](../imgs/Lab5/Q5.6.png)

