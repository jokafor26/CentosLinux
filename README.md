# CentosLinux

Creating a Linux Virtual Machine Using Centos Linux & Virtual Box


A quick virtual machine lab with a few commands to see what happens.



Downloading the image (iso file) from the centos website I loaded the iso into virtual box with the following properties

 





After starting the image, I renamed the default user with my firstname initial and lastname making Jokafor as the username with a strong password.
 


After rebooting from the initial installation stage my user account is created and could be clicked on to put in the password to login.

  

Using the pwd command it shows the user account on the operating system.

 

Going to create a text file by using the touch command and name the file quiz1.txt. This is just one of a numerous way to create a file on Linux. Would then use the ls command to see the text files within the current file location which has other files like aaa and color.1.txt.

 










I’m going to use the ps – A command which would display all running processes running on the system

 



After seeing what processes were running, I used the standard input to put the output of what the ps -A command displayed which was the running processes and put it into the quiz1.txt file using the ps -A < quiz1.txt command.

 

I could now use the cat command to view the contents of the quiz1.txt file. Using cat quiz1.txt I could see the results of the input from the ps -A command in the text file.

 



Using the ls -l command I could see what’s in the current directory but using ls -l quiz1.txt I would be able to see just the created file and properties like permissions, the and my username as well as date and time the file was created.

 

