1: Create a scripts in your home directory by running the following command in terminal
mkdir ~/scripts

2: Then open your .bash_profile file by running the following command
open ~/.bash_profile


3: Once your .bash_profile is open in the default text editor,
add the line below, no duplicates are necessary
export PATH=$PATH:~/scripts

4: Restart your terminal, and change directory to the desired location 
that you want to run the following commands

Commands:
bash makesite folder1 folder2 ... folderX
    - creates folders with html, css, javascript file, and images folder.
    It then opens html file in browser and opens all files in visual studio

bash edit file1 file2 ... fileX
    - opens files in visual studio