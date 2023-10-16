## Week 14 Quiz - Debugging, Git, & GitHub

You have just joined your favorite company and have been tasked with printing new data to a webpage. However, the existing files/directories are all jumbled up, and the code seems to have errors. Fix the bugs and sile structure. 

1. Debug the broken code so that it's working
    I added an "s" to items on line 13 of App.js
2. Correct the file architecture using command line
    I had to cd to main directory of quiz.
    Then, I ran this command 'mv client/server .'
3. node_modules are committed, remove them from repo on GitHub
    I added **/node_modules to the .gitignore in the server AND the client
    This can also be done by running the following command in the terminal
    git rm -r --cached node_modules 
4. Correct the server file’s directory by moving it to the appropriate directory
    I had to cd to main directory of quiz.
    Then, I ran this command 'mv client/server .'
5. Update README with
    - screenshot of the app's webpage, 
    ![Screenshot of text](<Screenshot 2023-10-16 at 12.31.37 PM.png>)
    - document errors you encountered and how you fixed them, 
    - detail the git commands you used to remove the node_modules, and
    - detail the git commands you used to correct the file structure