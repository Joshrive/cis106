# Lab 7 | Managing Data

## Question 1 | Tar Utility

2. List all the members of the archive.
   
![image1-2](../imgs/Lab7/question1-2.png)


3. Create another text file with some text. Use the command `lorem` to generate...
   
![image3](../imgs/Lab7/question3.png)


4. Add the new file to the archive.
   
![image4](../imgs/Lab7/question4.png)

5. List all the members of the archive.
   
![image5](../imgs/Lab7/question5.png)


## Question 2 | Cpio Utility

1. Move the allfiles.tar archive from question 1 to the question2 directory and extract all the files.
   
![image1](../imgs/Lab7/q2p1.png)  

2. Remove the archive and create a new archive with cpio of all the files.
   
![image2](../imgs/Lab7/q2p1.1.png)  

3. Create a tar archive with cpio of all the files including the cpio archive.

![image3](../imgs/Lab7/q2p3.png) 

4. Remove all the files except the tar archive

![image4](../imgs/Lab7/q2p4.png) 

5. Extract all the archive using cpio

![image5](../imgs/Lab7/q2p5.png) 


## Question 3 | Gzip, bzip2, xz
1. In the question3 directory you will find 1 file called mynotes.txt. What is the size of this file?
   
![image1](../imgs/Lab7/q3p1.png)

2. Compress mynotes.txt. using gzip keeping the original file.
   
![image2](../imgs/Lab7/q3p2.png)

3. Compress smynotes.txt. using bzip2 keeping the original file.
   
![image3](../imgs/Lab7/q3p3.png)

4. Compress smynotes.txt. using xz keeping the original file.
   
![image4](../imgs/Lab7/q3p4.png)

5. Long list all the files. Which tool gave you the best compression?
   
![image5](../imgs/Lab7/q3p5.png)

** bz2 was the smallest of all files

## Question 4 | Zip, 7zip and Rar
   
1. Decompress all the compressed files from question 3 in the question4 directory. Make sure to rename the file after decompressing them.
   
![image1](../imgs/Lab7/q4p1.png)

2. Using zip, create a zip archive of all the files.
   
![image2](../imgs/Lab7/q4p2.png)

3. Create a 7zip archive of all the files.
   
![image3](../imgs/Lab7/q4p3.png)

4. Create a rar archive using 7zip of all the files.

![image4](../imgs/Lab7/q4p4.png)

5. Long list all the archives. Which one gave you the best compression ratio?

![image5](../imgs/Lab7/q4p5.png)

