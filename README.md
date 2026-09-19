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
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"
<img width="1606" height="979" alt="image" src="https://github.com/user-attachments/assets/c0d0d94f-8f96-4c65-908e-05a34dba31ce" />



## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="2172" height="724" alt="image" src="https://github.com/user-attachments/assets/72e8b536-c564-4289-b1d3-9aece3f8c4fe" />


## COMMAND AND OUTPUT


Create the file Rose.txt
<img width="1591" height="989" alt="image" src="https://github.com/user-attachments/assets/40e8bcce-18b1-49be-aac6-a29e3b3d4ca4" />



## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
<img width="2172" height="724" alt="image" src="https://github.com/user-attachments/assets/8a85184f-1d83-4d44-a8c5-9ac22c29a3cb" />



## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="2001" height="786" alt="v5" src="https://github.com/user-attachments/assets/19ee0f3f-d90f-4567-8fa7-65dda3297e6b" />


## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="2086" height="754" alt="v6" src="https://github.com/user-attachments/assets/408d172c-0142-421d-9410-17f7c58ef6a3" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
<img width="1054" height="1492" alt="v7" src="https://github.com/user-attachments/assets/49a191ec-56f7-4a13-8cf2-bda03b48add9" />


## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="800" height="1967" alt="ChatGPT Image Aug 30, 2026, 01_26_31 PM" src="https://github.com/user-attachments/assets/8172ff88-7dd9-40ef-9872-a0c5a1947b2e" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
<img width="1907" height="825" alt="v8" src="https://github.com/user-attachments/assets/a8ffdda8-cf3f-4b98-8545-a202a33a7d54" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT


<img width="2170" height="725" alt="v9" src="https://github.com/user-attachments/assets/32573e18-b5d6-43fd-ad53-fcbbddf2b179" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="1508" height="1043" alt="v10" src="https://github.com/user-attachments/assets/d38bc16f-4727-43f0-ad31-1f193eeaf9e5" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="1490" height="1055" alt="v11" src="https://github.com/user-attachments/assets/3d5a812b-74ea-4570-b6fb-a29ad0970902" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="1984" height="793" alt="v12" src="https://github.com/user-attachments/assets/39c7ba5f-6235-4ed2-8c4d-cf092c151a5e" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT


<img width="1174" height="1340" alt="v13" src="https://github.com/user-attachments/assets/c3746fc4-4345-415e-bf4f-d0ae176c09d9" />

# RESULT:
The commands/batch files are executed successfully.
