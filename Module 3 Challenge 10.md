# Module Name
Comprehending Commands

## Challenge Name
Interestingly, ls doesn't list all the files by default. Linux has a convention where files that start with a . don't show up by default in ls and in a few other contexts. To view them with ls, you need to invoke ls with the -a flag, as so:

hacker@dojo:~$ touch pwn
hacker@dojo:~$ touch .college
hacker@dojo:~$ ls
pwn
hacker@dojo:~$ ls -a
.college	pwn
hacker@dojo:~$
Now, it's your turn! Go find the flag, hidden as a dot-prepended file in /.

### Solve

I did it by using the ls -a command to find the hidden file then to see it used the cat command.
```bash
command 1  ls -a /
command 2 cat /.flag-288972062817050
pwn.college{4k1LCGsgt4ZrXX6JYk3jb4UVKMc.QXwUDO0wyN1AzNzEzW}
```

### New Learnings
learned how to use find hidden files 

### References 
NA