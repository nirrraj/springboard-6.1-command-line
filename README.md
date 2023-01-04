Part I
1. make a directory called first
mkdir first
2. change directory to the first folder
cd first
3. create a file called person.txt
touch person.txt
4. change the name of person.txt to another.txt
mv person.txt another.txt
5. make a copy of the another.txt file and call it copy.txt
cp another.txt copy.txt
6. remove the copy.txt file
rm copy.txt
7. make a copy of the first folder and call it second
cp -r first second
8. delete the second folder
rm -rf second

Part II
1. What does the man command do? Type in man rm. How do you scroll and get out?
Manual for a command, describing the main function and available flags for that command. To scroll, use CTRL+D and CTRL+U to go forward and back half a page respectively. Use CTRL+B to go back one page.

2. Look at the man page for ls. What does the -l flag do? What does the -a flag do?
The -l flag will make the ls command display more detail about each file in the directory. The -a flag will display all files in the directory including hidden ones.

3. How do you jump between words in the terminal?
CTRL+left/right arrow

4. How do you get to the end of a line in terminal?
CTRL + e

5. How do you move your cursor to the beginning in terminal?
CTRL + a

6. How do you delete a word (without pressing backspace multiple times) in terminal?
CTRL + w

7. What is the difference between a terminal and shell?
The terminal is the interface where you can type commands and read results. The shell is the program that handles commands and executes the specified actions, returning the results to be displayed on the terminal.

8. What is an absolute path?
Complete address to a file location, starting from the root

9. What is an relative path?
Path to a file location from the current directory

10. What is a flag? Give three examples of flags you have used.
Add-on letters that refine the actions of a command. I have used -a and -l (ls command) and -r (rm command and cp command).

11. What do the r and f flags do with the rm command?
The -r flag will allow the rm command to recursively access and remove everything inside a folder, and the -f flag forces removal.
