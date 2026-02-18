# CentosLinux

Creating a Linux Virtual Machine Using Centos Linux & Virtual Box


A quick virtual machine lab with a few commands to see what happens.



Downloading the image (iso file) from the centos website I loaded the iso into virtual box with the following properties

 ![Image](https://github.com/user-attachments/assets/da3ac602-d044-4a44-8e36-fcca64870375)





After starting the image, I renamed the default user with my firstname initial and lastname making Jokafor as the username with a strong password.
 
![Image](https://github.com/user-attachments/assets/7ea83319-27a0-42b3-ad09-e0f11c58c6c2)

After rebooting from the initial installation stage my user account is created and could be clicked on to put in the password to login.

  ![Image](https://github.com/user-attachments/assets/7ea83319-27a0-42b3-ad09-e0f11c58c6c2)

Using the pwd command it shows the user account on the operating system.

![Image](https://github.com/user-attachments/assets/9a58d187-034b-4e16-95c0-a21933cd0178)
 

Going to create a text file by using the touch command and name the file quiz1.txt. This is just one of a numerous way to create a file on Linux. Would then use the ls command to see the text files within the current file location which has other files like aaa and color.1.txt.

 ![Image](https://github.com/user-attachments/assets/ef6603d5-ef23-4ad4-9fa4-6be738965f25)










I’m going to use the ps – A command which would display all running processes running on the system

 ![Image](https://github.com/user-attachments/assets/06d2e7a3-da2a-4132-bab6-69482a9e2285)



After seeing what processes were running, I used the standard input to put the output of what the ps -A command displayed which was the running processes and put it into the quiz1.txt file using the ps -A < quiz1.txt command.

 ![Image](https://github.com/user-attachments/assets/4d1c1916-0a16-478c-a55e-60254817950b)

I could now use the cat command to view the contents of the quiz1.txt file. Using cat quiz1.txt I could see the results of the input from the ps -A command in the text file.

 ![Image](https://github.com/user-attachments/assets/3148e267-50d7-4be4-85fe-7416f644fed9)



Using the ls -l command I could see what’s in the current directory but using ls -l quiz1.txt I would be able to see just the created file and properties like permissions, the and my username as well as date and time the file was created.

![Image](https://github.com/user-attachments/assets/298175fc-9702-4497-9be6-758b71347bab) 

