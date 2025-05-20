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


## COMMAND AND OUTPUT

```
mkdir %userprofile%\Desktop\MyLab
```

## COMMAND AND OUTPUT
```
cd %userprofile%\Desktop\MyLab
```


## COMMAND AND OUTPUT
```
dir %userprofile%\Desktop\MyLab
```


## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup

copy MyFile.txt %userprofile%\Desktop\Backup
```

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup

copy MyFile.txt %userprofile%\Desktop\Backup
```

## COMMAND AND OUTPUT

```
mv Myfile.txt %userprofile%\Documents
```
## COMMAND AND OUTPUT


```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
![444900815-fd2d326c-f1ba-4dad-b9d7-c55bb2ec299d](https://github.com/user-attachments/assets/2de963c7-0393-42ab-b567-61b16d5eb808)



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
![444900999-e4bfc3ed-8a90-45d6-88ea-d52c4b521802](https://github.com/user-attachments/assets/00f10d93-375b-4212-86a0-bab0be319625)
![444901010-e67aba7c-98a1-4c49-9c0d-db70774b1955](https://github.com/user-attachments/assets/f47fae8d-f374-4801-9b64-fbeff91ce8ab)




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

![444901093-2636f608-2fe4-4a37-a54f-8dfd66a489e1](https://github.com/user-attachments/assets/ad368ce6-9713-4343-b5bf-676ae5f28982)



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
![444901134-705228ff-697e-426f-a46f-6382d2274d6e](https://github.com/user-attachments/assets/257bf246-c5d1-435c-905e-f11ef91adf05)
![444901161-110411d6-84d1-42de-acf1-8bec4af23015](https://github.com/user-attachments/assets/37a612b7-ed6c-4f24-9ccb-07d38e7a790c)


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
![444901291-a84632ba-76b2-462b-8dfe-11b12422a999](https://github.com/user-attachments/assets/9e5711c5-178d-449e-8e29-21838b60757c)

![444902919-159d2f85-38cb-4a97-be4f-0d4b0eb6fe79](https://github.com/user-attachments/assets/eb49d8ee-76b5-47fd-8fe8-323d614ef0d6)


# RESULT:
The commands/batch files are executed successfully.

