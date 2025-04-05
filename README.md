# Linux-labs
1. Install Ubuntu [Dual-boot, VM, Multipass]
2. What is the difference between cat and more command?
Answer : Cat command show the file content all in one time but more show the file content in parts.
3. What is the difference between rm and rmdir using man?
Answer : rmdir remove the directory but rm remove the files and the directories with the -r option which means recursive
4. Create the following hierarchy under your home directory:
 
a.	Remove dir11 in one-step. What did you notice? And how did you overcome that?
Answer : When I was using rmdir the command didn’t work and I had to use the -r option with rm command

b. Then remove dir12 using rmdir –p command. State what happened to the
hierarchy (Note: you are in your home directory).
Answer : It removes the directory 12 
b.	The output of the command pwd was /home/user. Write the absolute
Answer : /home/user
./user
and relative path for the file mycv
5. Copy the /etc/passwd file to your home directory making its name is mypasswd.
Answer : cp /etc/passwd mypasswd
6. Rename this new file to be oldpasswd.
Answer : mv mypasswd oldpasswd
7. You are in /usr/bin, list four ways to go to your home directory
1 – cd ~
2 – cd /home
3- cd 
4 – cd $HOME
8. List Linux commands in /usr/bin that start with letter w
Answer : ls /usr/bin | grep - w
9. Display the first 4 lines of /etc/passwd
Answer : head -n 5 /etc/passwd

10.Display the last 7 lines of /etc/passwd
Answer : tail -n 5 /etc/passwd

11.Display the man pages of passwd the command and the file sequentially in one command.
cp etc/passwd new_file | man passwd >> new_file more new_file
12.Display the man page of the passwd file.
Answer : man passwd
13.Display a list of all the commands that contain the keyword passwd in their man page.
Answer : man -k passwd

14. Using vi write your CV in the file mycv. Your CV should include your name, age, school,
college, experience,...
Answer : sudo vi mycv
getting into the insert mode with the i command then  
write the wanted text

15. Open mycv file using vi command then: Without using arrows state how to:
a. Move the cursor down one line at time.
Answer  : J
b. Move the cursor up one line at time.
Answer : K
c.	Search for word age
Answer : Enter shift + Q and write  /age
d.	Step to line 5 (assuming that you are in line 1 and file is more than 5 lines).
Answer:
        Enter shift + Q and write the line 5 
e. Delete the line you are on and line 5.
Answer : dd command to delete the line or shift S
f. How to step to the end of line and change to writing mode in one-step.
Answer : Shift A
16. st the available shells in your system.
