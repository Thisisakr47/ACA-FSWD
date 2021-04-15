# Basic CMD Commands

## CD (Change Directory)
This command enables us to change the current directory or in simple words enable us to navigate to another folder from our PC.
*Example - If you want to go to a folder named "IITK" in D Drive, type **cd /d D:\IITK**.*

## DIR (Directory)
This command enable us to view the contents(files) of a *folder*. 
*Example - If you want to see contents of folder named "IITK", navigate to the folder using CD command and type **dir**.*
To view :- hidden folders use *dir /a*
           hidden files   use *dir /a:h*
           hidden dir     use *dir /a:d*

## MKDIR/MD (Make Directory)
We can create a new *folder* using this command.
*Example - If you want to create a folder named IITK,navigate to the location where you want to create the folder and then type **mkdir IITK**.* 

## REN (Rename)
To rename *files and folders*, we need to use the REN command.
*Example - **ren IITK IIT_Kanpur** will change the folder name to "IIT_Kanpur" from "IITK".*

## COPY
The Copy command allows you to copy *files* from one location to another. 
*Example - **copy D:\IITK\image.jpeg C:\Users\new_image.jpeg** will allow us to copy a file name "image" from IITK folder to C:\Users with new filename as "new_image".*

## XCOPY
Using this command we can copy a *folder and its contents* from one location to another.
*Example - **xcopy /s /i D:\IITK C:\Backup_IITK** will copy all the contents of the folder "IITK" to "Backup_IITK".*

## DEL (Delete)
The DEL (Delete) is used to delete *files* from the folders you have created. To delete all the files from a folder, you can run the command **del folder**.
*Example - **Del IITK** will delete all the files from the folder named "IITK".*

## RD (Remove Directory)
This command allows us to delete *folders*.
*Example - **rd IITK** will delete this folder with all its contents(if present) completely*

## LAUNCH AN APP
To launch an *.exe* file(application), simply navigate to the folder containing the .exe file and the program’s name.
*Example - **IITK.cpp** will launch a this C++ executable file named as "IITK".

## HELP
To access help in the Command Prompt, we have to type the help command and then press Enter.
************************************
***Relevant Links***
https://www.digitalcitizen.life/command-prompt-how-use-basic-commands/