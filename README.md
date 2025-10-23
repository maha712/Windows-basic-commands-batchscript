# Windows-basic-commands-batchscript

NAME:Mahalakshmi K

REG NO:212222240057

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

<img width="861" height="101" alt="500439613-6e31e28a-06ba-462e-82e2-f142db81dca2" src="https://github.com/user-attachments/assets/9ee50055-4ca9-4ab5-8772-dbf4c7ef27ca" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="939" height="105" alt="500439789-8d0ab4fa-cc28-4953-bb2d-b9082b984e93" src="https://github.com/user-attachments/assets/1de67dcd-9153-450d-9eaa-653883ea06c4" />

## COMMAND AND OUTPUT

Create the file Rose.txt

<img width="976" height="65" alt="500439948-73dd0bb2-7930-4f20-a2ae-e0ed3d0003e8" src="https://github.com/user-attachments/assets/10b227f5-33ef-4fbf-b04a-35c6f709e0d2" />

## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

<img width="1063" height="36" alt="500440343-ae2bce38-39e8-4b0e-bdc0-6fd525825ea6" src="https://github.com/user-attachments/assets/81394342-810b-4b1b-8de2-735cb036573c" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="990" height="115" alt="500440478-ad794fea-a16b-4fbe-aa61-a0deb25df2d6" src="https://github.com/user-attachments/assets/7454c1e1-1de5-492c-9460-e80a0b7c7911" />

## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="848" height="85" alt="500440830-4213e6cb-6277-44a5-83b4-9c72a82087a9" src="https://github.com/user-attachments/assets/760b72c2-8dfd-4bfe-b7d5-891e1a0886b5" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="944" height="184" alt="500440951-76661426-93dc-4fb3-88b5-58ea094b0d7a" src="https://github.com/user-attachments/assets/89a6920f-cbd2-430f-a524-4112722b8bcd" />

## COMMAND AND OUTPUT

List out all the associated file extensions

<img width="788" height="1064" alt="500441034-1af2cf24-0996-4254-8229-ee06e35dfab4" src="https://github.com/user-attachments/assets/f1b89bc6-905c-4ce2-b00c-c0337b324634" />

<img width="1059" height="1089" alt="500441161-633cdca9-3d65-4545-bb5a-ff650394637b" src="https://github.com/user-attachments/assets/2c4268f6-e7ab-4cef-94bd-56a836dd1c95" />

## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt

<img width="948" height="161" alt="500443265-f78dc30e-5fc5-4716-982e-edb8a6d8de6d" src="https://github.com/user-attachments/assets/699f312a-8bd6-4916-9b4f-2885a76facaa" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup.

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```

## OUTPUT

<img width="613" height="74" alt="376104140-ddf657d3-b54a-44c7-8393-615d081e9043" src="https://github.com/user-attachments/assets/14689a3c-d7a3-4181-989c-30cf59e5d3a0" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.


## OUTPUT

<img width="591" height="231" alt="500443587-a187e800-8d6e-4fd8-8caf-1a2ef69892c9" src="https://github.com/user-attachments/assets/f6655936-e461-4602-ac2d-a2d44342a153" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT

<img width="433" height="197" alt="500443672-272d0b8f-ee8e-4f89-9e2f-57cabd58aa20" src="https://github.com/user-attachments/assets/d52fa0c9-2a8c-414c-a092-f7cea34ac8b0" />

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="412" height="62" alt="500444002-45c154db-9bc2-465b-8be1-66bd61409460" src="https://github.com/user-attachments/assets/a610d17e-51b3-4197-90bb-9fc44a53de4c" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="380" height="159" alt="500444182-f729795b-814f-472d-a218-8a51a19cc70f" src="https://github.com/user-attachments/assets/489315b6-7754-4c58-ac92-5f1188f62f66" />

<img width="413" height="163" alt="500444246-f97dd16e-931d-4300-be6b-4e1e88dec21e" src="https://github.com/user-attachments/assets/250fe2e3-eb32-4c4a-9cdb-e64babc840b2" />

<img width="399" height="153" alt="500444685-c1b7b68d-afca-479c-92f8-eabf4c042104" src="https://github.com/user-attachments/assets/e3ba4751-d484-4330-bdab-44b283594705" />

# RESULT:
The commands/batch files are executed successfully.

