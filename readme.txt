------------------------------ Description ------------------------------
Scripts for creating folders with html, javascript, and css files for
class assignments in C4Q Access Code - 4.1 Web
Original link: https://github.com/Acostill/scipts
-------------------------------------------------------------------------
1: Download ZIP folder into downloads folder 

2: Unzip folder and rename the unzipped folder to "scripts"

3: Open your terminal and move the newly named scripts folder by typing the following
mv ~/Downloads/scripts ~/

3: Then open your .bash_profile file by running the following command
open ~/.bash_profile

4: Once your .bash_profile is open in the default text editor,
add the line below, no duplicates are necessary
export PATH=$PATH:~/scripts

5: Restart your terminal, and change directory to the desired location 
that you want to run the following commands

------------------------------- Commands -------------------------------
bash makesite folder1 folder2 ... folderX
    - creates folders with html, css, javascript file, and images folder.
    It then opens html file in browser and opens all files in visual studio

bash edit file1 file2 ... fileX
    - opens files in visual studio
------------------------------------------------------------------------