------------------------------ Description ------------------------------
Scripts for setting up exercise folder. Will create folders with 
html, javascript, and css files for class assignments in 
C4Q Access Code - 4.1 Web
-------------------------------------------------------------------------

----------------------- Setup Instructions (Mac) ------------------------
1: If reading on github(https://github.com/Acostill/scripts), click on
the green "Clone or download" button.
Click on Download ZIP.

2: Unzip folder and rename the unzipped folder as "scripts"

3: Open your terminal and move the newly named scripts folder from 
its current directory to the home directory -

        Example: If "scripts" folder is in your Downloads folder, 
        run the command below
        mv ~/Downloads/scripts ~/

4: Open your .bash_profile file by running the following command
open ~/.bash_profile

5: Once your .bash_profile is open in the default text editor,
add the line below, no duplicates are necessary
export PATH=$PATH:~/scripts

6: Restart your terminal, change directory to the location where you save
your projects, and use the commands below

7: Type Faster!!
-------------------------------------------------------------------------

------------------------------- Commands --------------------------------
bash makesite folder1 folder2 ... folderX
    - Creates new folders the names you enter
        Example: 
    -with html, css, javascript file, and images folder.
    It then opens html file in browser and opens all files in 
    Visual Studio Code

bash edit file1 file2 ... fileX
    - opens files in Visual Studio Code
-------------------------------------------------------------------------