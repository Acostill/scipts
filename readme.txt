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
~$ bash makesite folder1 folder2 ... folderX
    1: Creates new project folders with the names you enter
        Examples: 
            ~$ bash makesite html-exercise
            (Above command will create a new folder called html-exercise)

            ~$ bash makesite sharks panda trailmix
            (Above command will create 3 new folders, one called sharks,
            another called panda, and another called trailmix)

    2: Each created folder will include html, css, javascript file,
       and images folder.
        Examples:
            ~$ bash makesite mySite
            (Inside mySite will be mySite.html, mySite.css, and mySite.js)

    3: Html file will be launched in default application (should be browser)
    html, css, and js files will be opened in Visual Studio Code

~$ bash edit file1 file2 ... fileX
    - opens files in Visual Studio Code
        Examples:
            ~$ bash edit *
            (Above command will open all files in current directory)

            ~$ bash edit index.html stylesheet.css
            (Above command will open only the index.html 
            and stylesheet.css files)
-------------------------------------------------------------------------