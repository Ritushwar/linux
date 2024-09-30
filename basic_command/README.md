Linux Basic Commands For Beginner

man command_name: to know more about the command in terminal

1) pwd command: present working directory

2) cd command: change directory <br>
    • cd directory_name: goes inside the directory <br>
    • cd .. : get outside the directory <br>
    • cd / : root directory <br>
    • cd ~ : home directory <br> 
    • cd *My Book* : to enter inside the directory which have space <br>

3) ls command: list out the directory and files <br>
    [ls option file/directory]  <br>
    • ls / : root directory  <br>
    • ls .. : list out from the one step back from present <br>
    • ls ../.. : two step back  <br>
      in option <br>
      -l : in long format <br>
      -a : show hidden files <br>
      -al : hidden in long format <br>
      -lS : short by size <br>
      /*.html : file which have have only html extension <br>
      /*.* : all file with all extension <br>
      -ls > output_file : save the output in file <br>
      -d */ : only directory <br>

4) cp command: to copy the files and directory <br>
    [ cp options sources destination] <br>
      in option <br>
        -i : prompts you before overwriting. <br>
       -n : avoids overwriting without prompting. <br>
       -R : recursive copy(copying the directory) <br>

5) cat command: related to text file (display, combining, creating) <br>
    [cat option files_name] <br>
    • cat : echo the input <br>
    • cat file_name: to print the content of file in terminal <br>
    • cat -E file_name : add $ at each of the end of line <br>
    • ctrl + D : to get out of the cat command <br>
6) I/O redirection: capturing output from the file, command or program and sending it to another file, command or the program as input <br>
   [output > file_name] <br>
    • cat > file_name.txt : (creating the file) convert enter text from terminal into text file <br>
    • cat >> file_name.txt:  to append <br>
    • cat file1 file2 > combined_file: combined_file = file1 + file2(>> → for appending) <br>
    • cat file1>> file2 : file2 = file1 + file2 <br>



 

7) mkdir command: making directory <br>
    • mkdir directory_name: creating the directory <br>
    • mkdir directory_name/ sub_directory_name : create sub directory inside the existing dir <br>
    • mkdir -p directory/sub_directory_name : even though directory doesn’t exist <br>
    • mkdir -p directory/ {sub_directory_lists}: to create multiple sub directory <br>

8) rm and rmdir command: remove the file and directory <br>
    • -r : recursive remove <br>


9) mv command : to move files from one location to another <br>
    • [mv options source destinations]  <br>
      in options <br>
        -i : for overwritten or not <br>

10) less command : to read the file <br>
    • less file_name.txt <br>
    • q : get back to the terminal <br>

11) touch command : to create new empty file and change the time stamping in existing file <br>
    • touch file_name <br>
        1) if not exist : create the new empty file <br>
        2) if already exist : change the time stamp <br>


12) nano command : text editor for search, replace,…… <br>


13) sudo command : <br>
    • sudo passwd : to set password in the user <br>

14) top command : dynamic and the real time view of the system <br>

15) kill command : to kill the current process <br>
    • kill -flags pid <br>
      to know about the pid <br>
    • ps -ux <br>
    • ps -aux <br>
    • ps -U user_name <br>
    • ps -C <br>

16) echo command : <br>
    • var_name=“ value “ : for creating the variable <br>
    • echo $var_name : print the variable <br>
    • echo -e : for escape sequence <br>
    • echo -e \t : horizontal tab <br>
    • echo -e  \n : new line <br>

17) file permission : control the access that users have to files and directories. Each file and directory has three types of permissions for three different categories of users. <br>
     chmod [who][+/-][permission] [file_or_directory] <br>
      In who: <br>
    • -u (user or owner), -g(group), -o(others), a(all) <br>
      + for add and – for remove the permission <br>
      In permission <br>
    • -r (read), -w(write), -x(execute)<br>

18) directory permissions : it is same as but for the directory <br>


19) octal and numerical permission : giving the permission using the number <br>
        r    w    x  <br>
        1    1    1    (1→ yes) <br>
        4    2    1    (0 → no) <br>
        4+2+1 = 7 (for rwx permission) <br>

20) Bash scripting : Script is the a test file that contains sequence of command. Its is better to give .sh extension for scripting file. Ex: my_script.sh . Inside the scripting file first line should be <br>
 #! location of the bash then interpreter notice that is a scripting file. To find the location of bash use which bash inside the other new terminal. <br>
    • ./my_script.sh : to execute the bash script <br>
    • to execute the bash script you must have the execute permission <br>
      Note: after script execute, the working directory return to where the script was initially called <br>


21) which and whatis command : <br>
    • which [command/file_name] : return the path of a file_name or command and it is better to use the full location of a command <br>
    • whatis : return the short description of command <br>


22) useradd commands : Is used to create a new user account on the system. It allows you to specify various options for the new user, such as the home directory, shell, and user ID. <br>
    • sudo useradd name_user flags : <br>
      in flags <br>
    •  -m : create default home directory <br>
    • -s : default shell <br>
    • -g : default user <br>
    • -c : to add comment in the user <br>


23) userdel commands: to delete the user <br>
    • sudo userdel user_name: <br>
    • sudo userdel -r user_name: also delete home directory <br>
    • sudo rm -r /home/user_name <br>


24) Basic group management: to create, modify, and delete groups of users.<br>
    • groups : gives groups added with user<br>
    • cat /etc/group : all the group in system <br>
    • sudo groupadd group_name : to add group <br>
    • sudo groupdel group_name : <br>
    • sudo gpasswd -a user_name group_name : to assign a user to a particular group <br>
      -a→ adding group <br>
      -d→ removing group <br>


25) .bashrc file: bash script runs whenever a user opens a new interactive non-login shell. <br>
    • nano .bashrc : to see/edit the contain inside the bashrc file <br>
