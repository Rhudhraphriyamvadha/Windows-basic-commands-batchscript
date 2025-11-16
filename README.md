# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

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
## Exercise 1: BASIC DIRECTORY AND FILE OPERATIONS

### Create a directory named "my-folder"
### COMMAND AND OUTPUT

<img width="452" height="53" alt="image" src="https://github.com/user-attachments/assets/383780f1-2ae7-4889-9c18-03ebc33d06e0" />


### Remove the directory "my-folder"
### COMMAND AND OUTPUT

<img width="540" height="98" alt="image" src="https://github.com/user-attachments/assets/911ca24d-c1c5-413e-a5a3-7d8af53e82aa" />


### Create the file Rose.txt
### COMMAND AND OUTPUT

<img width="642" height="346" alt="image" src="https://github.com/user-attachments/assets/8943437f-b632-4393-85d7-2eac11ec92bb" />


### Create the file hello.txt using echo and redirection
### COMMAND AND OUTPUT

<img width="676" height="129" alt="image" src="https://github.com/user-attachments/assets/89a81fbd-e480-45a9-9ae4-a3afc5a0dc43" />


### Copy the file hello.txt into the file hello1.txt
### COMMAND AND OUTPUT

<img width="604" height="148" alt="image" src="https://github.com/user-attachments/assets/692d4225-d555-4d00-b234-4471a809e9ab" />


### Remove the file hello1.txt
### COMMAND AND OUTPUT

<img width="434" height="52" alt="image" src="https://github.com/user-attachments/assets/d79b2984-951f-4436-868c-abc5aa84ecb5" />


### List out the file hi.txt in the current directory
### COMMAND AND OUTPUT

<img width="544" height="198" alt="image" src="https://github.com/user-attachments/assets/71471b3f-722c-4eb3-a41c-d9c2e3d4c523" />


### List out all the associated file extensions 
### COMMAND AND OUTPUT

<img width="624" height="918" alt="image" src="https://github.com/user-attachments/assets/0345eaaf-1366-4c38-9716-a7ce6b9716a9" />


### Compare the file hello.txt and rose.txt
### COMMAND AND OUTPUT

<img width="534" height="172" alt="image" src="https://github.com/user-attachments/assets/20d289c6-7137-4eaf-a0a2-e3ceed70e5d1" />


## Exercise 2: ADVANCED BATCH SCRIPTING

1. Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

### OUTPUT

<img width="426" height="99" alt="image" src="https://github.com/user-attachments/assets/9f6af243-0df5-440f-94a0-f3b06cae368c" />


2. Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

### OUTPUT

<img width="589" height="215" alt="image" src="https://github.com/user-attachments/assets/1f6cab98-bc79-4374-a644-17d5c4b212a9" />



3. Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

### OUTPUT

<img width="421" height="176" alt="image" src="https://github.com/user-attachments/assets/651a2f4c-7210-4c44-8c35-69a37c877436" />



4. Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

### OUTPUT

<img width="640" height="213" alt="image" src="https://github.com/user-attachments/assets/472c3f34-677d-4849-a00f-0f1febbb1f3d" />



5. Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


### OUTPUT

<img width="442" height="380" alt="image" src="https://github.com/user-attachments/assets/2b26d76d-9a92-4cbb-9821-2a6e35b9de5b" />


# RESULT:
The commands/batch files are executed successfully.

