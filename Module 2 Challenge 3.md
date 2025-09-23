# Module Name 
Pondering Paths

## Challenge Name
The Linux filesystem has tons of directories with tons of files. You can navigate around directories by using the cd (change directory) command and passing a path to it as an argument, as so:

hacker@dojo:~$ cd /some/new/directory
hacker@dojo:/some/new/directory$
This affects the "current working directory" of your process (in this case, the bash shell). Each process has a directory in which it's currently hanging out. The reasons for this will become clear later in the module.

As an aside, now you can see what the ~ was in the prompt! It shows the current path that your shell is located at.

This challenge will require you to execute the /challenge/run program from a specific path (which it will tell you). You'll need to cd to that directory before rerunning the challenge program. Good luck!

### Solve
**Flag:** 
Ran /challenge/run to check required location; it reported I must be in /etc, so I changed directory with \cd /etc and reran the program.
```bash
command 1 cd/etc
command 2 /challenge/run
pwn.college{MKAc8mR6cSscKPpXiHhWavyjPNk.QX2QTN0wyN1AzNzEzW}
```

### New Learnings
learned the use of cd
### References 
NA
