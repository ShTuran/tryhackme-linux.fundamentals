# Research: What year was the first release of a Linux operating system?

(Use power of Google)
- 1991


# If we wanted to output the text "TryHackMe", what would our command be?

- To ouutput a text to screen `echo` command will be right, so:

`echo TryHackMe` -> TryHackMe

![image](https://github.com/ShTuran/tryhackme-linux.fundamentals/assets/111232034/f73ef002-9f7e-43cd-bbce-f47ffd43a584)

I used single, double quotes and without them :)


# What is the username of who you're logged in as on your deployed Linux machine?

- To display current username use `whoami` command

`whoami` -> will output 'tryhackme'

![image](https://github.com/ShTuran/tryhackme-linux.fundamentals/assets/111232034/5e8032a9-f614-4108-951f-e1eeac365f18)


# On the Linux machine that you deploy, how many folders are there? 

`ls` command will list all current directory content. To answer quetion use `ls` and see the number of folder which will be '4'.

![image](https://github.com/ShTuran/tryhackme-linux.fundamentals/assets/111232034/824b7de3-ae27-458d-9d1e-81cb68ce4ce8)


# Which directory contains a file? 

`cd` command will change directory, to enter the directory use `cd 'filenmae'`. If you navigate to folder4 and list its content (`ls`) you will see that there is file there. 

![image](https://github.com/ShTuran/tryhackme-linux.fundamentals/assets/111232034/628780b7-2f29-474c-bfd9-ff0b95b224ff)


# What is the contents of this file?

- To see content of any file `cat` is most used one. In our case,

`cat 'note.txt'`  -> "Hello World!"

![image](https://github.com/ShTuran/tryhackme-linux.fundamentals/assets/111232034/8a14c0cb-f854-45b3-9028-4969ab93ec70)


# Use the cd command to navigate to this file and find out the new current working directory. What is the path?

- After navigating to file location (use above knowledge),
- To learn your absolute directory type `pwd` -> print working directory -> will output this: '/home/tryhackme/folder4'


# Use grep on "access.log" to find the flag that has a prefix of "THM". What is the flag?

- 'grep' command will search any text pattern provided by the user.

  `grep "THM" access.log` will reveal the flag. -> THM{******}


# If we wanted to run a command in the background, what operator would we want to use? 

`&`  will make process to run in the background, usually using this sign when assuming that command result relatively will be late.


# If I wanted to replace the contents of a file named "passwords" with the word "password123", what would my command be?

`echo password123 > passwords`

 `>` will overwrite it!

# Now if I wanted to add "tryhackme" to this file named "passwords" but also keep "passwords123", what would my command be

`echo tryhackme >> passwords`

`>>` append it!
