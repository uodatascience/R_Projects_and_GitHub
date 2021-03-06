true

Integrating Rstudio and GitHub with Projects
============================================

Requirements:
-------------

1.  R and Rstudio installed and updated
2.  Github account
3.  Git insatlled and functioning from the command line

Steps (there are other ways, but this works best for me)
--------------------------------------------------------

### Create repository on GitHub

1.  Navigate to your GitHub repository page (click on repositories from
    your home page)  
2.  Name the repository  
3.  Choose public or private (if you are unable to choose private sign
    up for a free student account)  
4.  Click YES initialize this repository with a README  
5.  Click green "Create Repository" button

### Create project in Rstudio

1.  File &gt; New Project  
2.  Select version Control  
3.  Select Git, create from Git repository

### Connect

1.  Navigate to GitHub page for your newly created repository  
2.  Click clone or download and copy the SSH key and passphrase  
3.  Paste in Repository URL box in Rstudio  
4.  Select the directory to place the project in  
    note: The directory you place the project in will be the working
    directory when you open the project. I have found it best to store
    data files for the project in the same directory.

### Start controlling your versions!

1.  Open the project you created  
2.  modify a file  
3.  Select the Git button in upper right pane of Rstudio  
4.  check the staged box for any files you have altered  
5.  Select "commit" and type a commit message  
6.  Select "Push" and your changes will be pushed to GitHub
