# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.




## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
![image](https://github.com/Jwalamukhi/Windows-basic-commands-batchscript/assets/145953628/10f393a3-b51c-4f0b-ad2d-eff5d1a01a82)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![image](https://github.com/Jwalamukhi/Windows-basic-commands-batchscript/assets/145953628/a5c541b9-bab0-4b99-8034-720a18ad0154)

![image](https://github.com/Jwalamukhi/Windows-basic-commands-batchscript/assets/145953628/c28b287e-6ad2-4c40-94fd-fb59ed0a3339)




## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![image](https://github.com/Jwalamukhi/Windows-basic-commands-batchscript/assets/145953628/ef08b1c2-a95a-4e2b-9e30-c18687c1357e)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![image](https://github.com/Jwalamukhi/Windows-basic-commands-batchscript/assets/145953628/6ce26363-6fc7-4269-acab-fb47ba4216d2)

![image](https://github.com/Jwalamukhi/Windows-basic-commands-batchscript/assets/145953628/9ca878e7-9630-4427-a285-2925f02d0175)




## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents

![image](https://github.com/Jwalamukhi/Windows-basic-commands-batchscript/assets/145953628/0ee1f3c3-36f7-45cd-b531-7844d941f196)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!




## OUTPUT
![image](https://github.com/Jwalamukhi/Windows-basic-commands-batchscript/assets/145953628/84ecfd4e-8417-4c81-a53b-52970723a912)





# RESULT:
The commands/batch files are executed successfully.

