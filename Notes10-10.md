Notes October 10, 2017
#Command Line Basics

pwd : print working directory - tells you where you are at

ls : light switch - see what is in the folder you are in
ls -a : shows all files in your current folder
ls -al : gives all files 
cd : change directory (folder) - move into a different folder

absolute path   cd /Users/evansmith/Notes

cd ~ : change directory to the folder with your name on it
cd / : takes you to your home folder

// cd . : Doesn't do anything productive

mkdir : make directory (folder)

`.` : reference to the current folder
`..` : reference to the parent folder (the folder containing the current folder
touch <filename> : creat a file called <file name>
cp : takes 2 arguments - copies single thing at a time
cp -r <folder to copy> <new folder> :
mv <file to move> <place to move file> : lets us move files and folders
rm : remove a file - permanent
rm -r : deletes a folder

sudu <command> : run a command as root (Super User DO)
rmdir <directory name> : deletes an empty directory (not super useful)
clear : clears output on your screen
cmd+k : same as above, but can be used in situations where the terminal tab is busy

less <file name> : read a file with less
    -arrow keys: move up or down one line
    -space/b: move up or down one page
    -q: quit

man <command> : read documentation on any command, using less.
vim <file name> : open a file with vim 
    -quitting vim: 
        -press 'esc' a few times
        -':wq' : save and quit
        -':q' : quit without saving

