------------------------------ Description ------------------------------
Scripts for setting up exercise folder. Will create folders with 
html, javascript, and css files for class assignments in 
C4Q Access Code - 4.1 Web

Original link: https://github.com/Acostill/scipts
-------------------------------------------------------------------------

--------------------------- Setup Instructions --------------------------
1: Download ZIP folder into downloads folder 

2: Unzip folder and rename the unzipped folder as "scripts"

3: Open your terminal and move the newly named scripts folder 
by typing the following - 
mv ~/Downloads/scripts ~/

4: Open your .bash_profile file by running the following command
open ~/.bash_profile

5: Once your .bash_profile is open in the default text editor,
add the line below, no duplicates are necessary
export PATH=$PATH:~/scripts

6: Restart your terminal, change directory to the desired location 
that you want to work in, and use one of the commands below

7: Type Faster!!
-------------------------------------------------------------------------

------------------------------- Commands --------------------------------
bash makesite folder1 folder2 ... folderX
    - creates folders with html, css, javascript file, and images folder.
    It then opens html file in browser and opens all files in 
    Visual Studio Code

bash edit file1 file2 ... fileX
    - opens files in Visual Studio Code
-------------------------------------------------------------------------