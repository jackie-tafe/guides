# Commands to navigate the file system from the command line

When you log into a Pi and open a terminal window, or you boot to the command line instead of the graphical user interface, you start in your home folder; this is located at `/home/pi`, assuming your username is `pi`.

This is where the user's own files are kept. In this case you are the user called `pi`. The contents of the user's desktop is in a directory here called Desktop, along with other files and folders.

Here are some helpful commands to use on the command line or terminal window in Raspbian that allow you to naviagte around the file system on your Raspberry Pi.

## ls

Type `ls` and press enter on your keyboard. A list of all the files and directories (sometimes called folders) will be listed for you to see. `ls` is an abbreviation for **list**.

## cd

If you want to move into a directory, perhaps to see what files are in it type `cd` followed by the name of the directory and press enter on your keyboard. E.g. `cd Documents`.

To move up a directory to a higher level in the file system type `cd ..`

## pwd

You can find out where you are within the file system on Raspbian and typing `pwd` and pressing enter. It will return a location similar to this `/home/pi` depedning on where you are. 
