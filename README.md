# 19CSE101-LINUX-COMMANDS
SOME SHORT FORMS
NOD                                                      NAME OF THE DIRECTRYY
sod                                                      sub directry
NOD                                                      NAME OF THE DIRECTRY
CN                                                       COMMAND NAME
ls                                                       list of directries
ls -a                                                    Files beginning with a dot (.) are known as hidden files and helps you list all the files
mkdir NOD                                                We can now make a directory
mkdir NOD1 NOD2 NOD3 NOD4                                to create multiple directries in one command
mkdir -p NOD1/sod2/sod3/sod4                             to create subdirectries in one directry
ls -lrt                                                  to get long lasting information
ls -R NOD                                                to see what are the sub directries present in directry
cd NOD                                                   will take you to the directry directly
cd ..                                                    will take you to back directry
cd                                                       will take you to home directry
pwd                                                      print working directry
cd ~                                                     will also take you to the home directry
cp file1.txt file2.txt                                   to copy from file1.txt to file2.txt
mv file1.txt file2.txt                                   to rename the file or to move the file
rmdir NOD                                                to remove directry without content
rm -rf NOD                                               to remove directry with directry
rm file.txt                                              to remove file
clear                                                    will clear the screen
cat NOD                                                  to see the content in the directry
less NOD                                                 to see content in the directry in one page
head NOD                                                 to see first 10 lines in the directry
tail nod                                                 to see the last 10 lines in the directry
head -n NOD                                              to see first n lines in the directry
tail -n NOD                                              to see last n lines in the directry
cat >> NOD                                               to write text in directry
cat file1.txt >> file2.txt                               to copy text from one directry to another directry
touch NOD                                                to create new directry
wc                                                       to see number of lines and words and letters in directry
wc -l                                                    to see number of lines in directry
wc -w                                                    to see number of words
grep NOW NOD                                             to see a specific keyword in a directry
cat file1.txt file2.txt >> NOD                           to combile 2 files into one file.txt
who                                                      to see who is online now
who | sort                                               sort list of names who are online now
who | wc -l                                              to see number of people are online now
ls | more                                                to see directry in an order
ls-l | wc -l                                             to see total number of directrys
who | grep name                                          to check for a specific person is oneline or not
file *                                                   to see type of files
date                                                     to see today date in pst
cal                                                      to see this month calender
which CN                                                 to see location of the command
ls list*                                                 This will list all files in the current directory starting with list.... 
ls *list                                                 This will list all files in the current directory ending with ....list
ls ?list                                                 So ?ouse will match files like house and mouse, but not grouse.
man cn                                                   gives you the manual about the command
whatis cn                                                gives a one-line description of the command, but omits any information about options etc!
apropos KEYWORD                                          When you are not sure of the exact name of a command
drwxrwxrwx                                               r : read  w : write x : xeicute
chmod go-rwx NOD                                         For example, to remove read write and execute permissions on the file biglist for the group and others
chmod a+rw biglist                                       to give a specific permission             U : USER  g:GROUP  O:OTHER
chmod a-rw biglist                                       to remove a specific permission










