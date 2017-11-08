Description
--- 
Scripts for setting up exercise folders. Will create folders with 
html, javascript, and css files for class assignments in 
C4Q Access Code - 4.1 Web
_________________________________________________________________________

Setup Instructions (Mac)
---
1: If reading this on [github](https://github.com/Acostill/scripts), click on
the green "Clone or download" button.
Click on Download ZIP.

2: Unzip folder and rename the unzipped folder as "scripts".

3: Open your terminal and move the newly named scripts folder from 
its current directory to the home directory.

Example: If "scripts" folder is in your Downloads folder, 
run the command below  
```mv ~/Downloads/scripts ~/```

4: Open your .bash_profile file by running the following command.  
```open ~/.bash_profile```

5: Once your .bash_profile is open in the default text editor, copy the 
following lines below. (If you've done this step, no need for duplicates)  
```
export PATH=$PATH:~/scripts
alias makesite=bash\ makesite
alias edit=bash\ edit
```

6: Restart your terminal, change directory to the location where you save
your projects, and use the commands below.

7: Type Faster!!
_________________________________________________________________________

Commands
---
* makesite folder1 folder2 ... folderX
    * Creates new project folder(s) with the names you enter  
        Examples:  
        * ```makesite mySite```  
        (Above command will create a 
        new folder called mySite)
        * ```makesite sharks panda trailmix```  
        (Above command will create 3 new folders, one called 
        sharks, another called panda, and another called trailmix)

    * Each created folder will include html, css, javascript file, and images folder.  
        Example:  
        * ```makesite mySite```  
        (Inside mySite will be three files called mySite.html, 
        mySite.css, and mySite.js, and one folder called images)

    * Html file should launch in your default browser. Then the
    html, css, and js files should be opened in Visual Studio Code

* edit file1 file2 ... fileX
    * opens files in Visual Studio Code  
        Examples:  
        * ```edit *```  
        (Above command will open all files and folders in current directory)

        * ```edit exampl.html example.css```  
        (Above command will open only the 
        example.html and example.css files)
_________________________________________________________________________