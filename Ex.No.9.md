# 19CS545-Ex1 - User Access and System Configuration in Linux in GitHub
### Name: Vignesh R
### Reg no: 212223240177
# AIM:
To create a Repository

# Procedure:
1.The first command is: useradd -u 1326 alies

2.This command creates a new user account on the system. Here's a breakdown of the op ons used:

3.useradd: This is the command used to create a new user account. 2.-u 1326: This op on specifies the user ID (UID) for the new user account. The UID is a unique iden 
4.fier associated with each user account. In this case, the new user account will have a UID of 1326.

5.alies: This op on specifies the username for the new user account. The username is the name that the user will use to log in to the system.

6.The second command is: cat /etc/passwd | grep "alies"

7.This command is used to verify the informa on about the newly created user account. Here's a breakdown of the op ons used:

8.cat: This command is used to display the contents of a file. In this case, it's used to display the contents of the /etc/passwd file.

9./etc/passwd: This file contains informa on about all user accounts on the system. Each line in the file contains informa on about one user account in the following 
10.format: username:password:UID:GID:full name or comment:home directory:default shell

11.grep "alies": This op on pipes the output of the cat command to the grep command. The grep command is used to search for a specific pa ern in the input. In this case, it's used to search for lines that contain the username "alies".

13.The third line in the image is a shell prompt, which indicates that the user is ready to enter another command.

14.In summary, these commands create a new user account named "alies" with a UID of 1326 and then verify the informa on about the newly created user account.
# Output:
<img width="861" height="127" alt="448685427-640b2e25-359d-49d7-b158-7cae566dc28a" src="https://github.com/user-attachments/assets/9b41f9c7-2e6b-4ea3-9615-4283c7931db8" />

# Result:
Thus a Repository has been created successfully.
