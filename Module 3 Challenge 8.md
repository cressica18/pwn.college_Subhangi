# Module Name
Comprehending Commands

## Challenge Name
Files are all around you. Like candy wrappers, there'll eventually be too many of them. In this level, we'll learn to clean up!

In Linux, you remove files with the rm command, as so:

hacker@dojo:~$ touch PWN
hacker@dojo:~$ touch COLLEGE
hacker@dojo:~$ ls
COLLEGE     PWN
hacker@dojo:~$ rm PWN
hacker@dojo:~$ ls
COLLEGE
hacker@dojo:~$
Let's practice. This challenge will create a delete_me file in your home directory! Delete it, then run /challenge/check, which will make sure you've deleted it and then give you the flag!

### Solve

I did it by using the rm command to delte  the files and ran /challenge/check
```bash
command 1 touch delete_me
command 2 ls
command 3 rm delete_me
command 4 /challenge/check 
pwn.college{0fNPY5JsTDuqoE2sj7jEaGzQ8KE.QX2kDM1wyN1AzNzEzW}
```

### New Learnings
learned how to use delte file using rm

### References 
NA
