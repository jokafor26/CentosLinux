# Centos Linux

Creating a Linux Virtual Machine Using Centos Linux & Virtual Box

A quick virtual machine with a few commands.

Downloaded the image (iso file) from the centos website then loaded the iso into virtual box with the following properties.

<img width="801" height="727" alt="image" src="https://github.com/user-attachments/assets/ef443c2e-7a97-447a-9c34-6a8ba40af70b" />

After starting the image, I renamed the default user with my firstname initial and lastname making Jokafor as the username with a strong password.
 
<img width="879" height="723" alt="image" src="https://github.com/user-attachments/assets/0df3629d-54e0-4626-81e2-c7a936aec2b0" />

After rebooting from the initial installation stage my user account is created and it could be clicked on to put input the password.

<img width="693" height="598" alt="image" src="https://github.com/user-attachments/assets/007d5cbd-08ef-4406-a576-4431491a69db" />

Using the pwd command it shows the user account on the operating system.

<img width="1091" height="320" alt="image" src="https://github.com/user-attachments/assets/ad1a3681-1b8b-47e5-b551-0e4add9993b4" />
 
Going to create a text file by using the touch command and name the file quiz1.txt. This is just one of a numerous way to create a file on Linux. Would then use the ls command to see the text files within the current file location which has other files like aaa and color.1.txt.

<img width="593" height="504" alt="image" src="https://github.com/user-attachments/assets/479a16b1-6a5b-49d8-ac28-cddbf3fc9f01" />

I used the ps – A command which would display all running processes running on the system

<img width="757" height="583" alt="image" src="https://github.com/user-attachments/assets/d8c9017e-8fad-44f3-945d-78922298a861" />

After seeing what processes were running, I used the standard input to put the output of what the ps -A command displayed which was the running processes and put it into the quiz1.txt file using the ps -A < quiz1.txt command.

<img width="717" height="497" alt="image" src="https://github.com/user-attachments/assets/09bf7127-285d-413e-b927-a89741ac89df" />

I could now use the cat command to view the contents of the quiz1.txt file. Using cat quiz1.txt I could see the results of the input from the ps -A command in the text file.

<img width="836" height="570" alt="image" src="https://github.com/user-attachments/assets/5cc2a9d0-2be6-4b59-8155-571120dd26f9" />

Using the ls -l command I could see what’s in the current directory but using ls -l quiz1.txt I would be able to see just the created file and properties like permissions, my username, date and time the file was created.

<img width="887" height="170" alt="image" src="https://github.com/user-attachments/assets/c25945b8-d87d-4746-abf3-fc936d88ca7e" />

