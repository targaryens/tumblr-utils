# #mac install instructions

This is a basic overview of how to backup a tumblr via tumblr-utils using a Mac - for any code issues, best to contact the owner of the original repo: https://github.com/bbolli/tumblr-utils 

I'm happy to help with mac commands etc.

## #check python installation status
1. Open Terminal - to find Terminal, open the Launchpad and type in Terminal in the search bar.
2. Run the following command: python -V
3. If the terminal comes back with a Python version, you're good to go.
4. If you don't have Python, follow the instructions in the link:
https://docs.python-guide.org/starting/install3/osx/ 
5. Keep Terminal open

## #download the tumblr backup files
1. Download the zip file of this repo

![alt text](https://github.com/targaryens/tumblr-utils/blob/master/download%20zip.png)


2. Unzip the file
3. Open the 'tumblr-utils-master' folder
4. Look for the 'tumblr-backup.py' file
5. Drag the file into Terminal
6. Once the file is in Terminal you will see a line that looks something like: ```'/Users/yourcoolname/Downloads/tumblr-utils-master/tumblr_backup.py'```
7. Add the tumblr that you want to backup to the end of the line. ```'/Users/yourcoolname/Downloads/tumblr-utils-master/tumblr_backup.py' taylorswift```
8. This will back up the tumblr URL

![alt text](https://github.com/targaryens/tumblr-utils/blob/master/terminal.png)

9. Once it has finished backing up, you will see a folder with the blogname in your folders

![alt text](https://github.com/targaryens/tumblr-utils/blob/master/folders.png)
