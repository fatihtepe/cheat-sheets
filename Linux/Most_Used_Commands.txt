## The Pipe Command ( | )
cat tepe.txt | grep “tepe"  ==> read tepe.txt and look for "tepe"




-# this is a comment

-echo "Hello World"  # print new line after Command
 printf "Hello World\n"

-cd ~ # move to Home directory of your Machine
# Or simply
cd


-pwd 
# My Current Path


ls 
# list all folders and files
ls -l
# List the contents of the directory, including file date, size, #permissions and other information
ls -1
# Display the contents of the directory in list mode, only the file #name is displayed
ls -a
#Show all files and directories, including hidden files 
#(file/directory names starting with.)


-touch app.js 
# create file app.js in your current path. ls to check
rm app.js
# remove file app.js from current directory


-mkdir myFolder 
# create folder named myFolder in current path. ls to check
mkdir myFolder\ with\ space 
# if you have space in folder name like myFolder with space




-rm *
// remove all files is current path/dir


- -rf myFolder
# remove folder i.e myFolder from current dir.
rm -rf myFolder\ with\ space
# Remove folder named myFolder with space



-open ./ 
# Open current directory in Finder App



-cp fileName destinationPath/fileName
Example
mkdir app && cd app && touch app.js
# Create a folder named app, move to app and create a file named app.js inside it
cp app.js ../app.js
# copy the file app.js and paste it in previous path


-mv fileName destinationPath/fileName
Example
mkdir app && cd app && touch app.js
# Create a folder named app, move to app and create a file named app.js inside it
mv app.js ../app.js
# move the file app.js and paste it in previous path


-mv app.js newApp.js
# Rename app.js to newApp.js


-top
# Show all running process in your machine. hit q to stop.









