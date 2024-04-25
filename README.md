# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript
#### Developed by: JAGADEESH P
#### Register number: 212223230083
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
mkdir %userprofile%\Desktop\MyLab

![Screenshot 2024-04-25 133425](https://github.com/PremkumarG3/Windows-basic-commands-batchscript/assets/138955646/87135a53-46fb-4434-bc7e-48a9b89bef8a)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab

![Screenshot 2024-04-25 133440](https://github.com/PremkumarG3/Windows-basic-commands-batchscript/assets/138955646/a837e661-0502-48bd-8c47-77377ea5a11c)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab

![Screenshot 2024-04-25 133447](https://github.com/PremkumarG3/Windows-basic-commands-batchscript/assets/138955646/25b03d45-ace6-42ec-9c39-a1848f7d1650)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![Screenshot 2024-04-25 133455](https://github.com/PremkumarG3/Windows-basic-commands-batchscript/assets/138955646/009ec9c0-1564-4ded-a52b-6b81e0a4e5fc)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents

![Screenshot 2024-04-25 133502](https://github.com/PremkumarG3/Windows-basic-commands-batchscript/assets/138955646/5be87448-4a7a-4ed0-a851-29ed2444a6ce)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!






## OUTPUT

![Screenshot 2024-04-25 133507](https://github.com/PremkumarG3/Windows-basic-commands-batchscript/assets/138955646/7dc8c005-1de7-48b0-8aae-805122837df5)



# RESULT:
The commands/batch files are executed successfully.

