# Module Name
Comprehending Commands

## Challenge Name
Of course, you can also create files! There are several ways to do this, but we'll look at a simple command here. You can create a new, blank file by touching it with the touch command:

hacker@dojo:~$ cd /tmp
hacker@dojo:/tmp$ ls
hacker@dojo:/tmp$ touch pwnfile
hacker@dojo:/tmp$ ls
pwnfile
hacker@dojo:/tmp$
It's that simple! In this level, please create two files: /tmp/pwn and /tmp/college, and run /challenge/run to get your flag!

### Solve

I did it by using the touch command to create the files and ran /challenge/run
```bash
command 1 cd /tmp
command 2 touch /tmp/pwn
command 3 touch /tmp/college
command 4 ls /tmp   
command 5 /challenge/run
pwn.college{cXIk_sQ7c06iMM1SRIbGiNG5DkI.QXwMDO0wyN1AzNzEzW}
```

### New Learnings
learned how to use touch

### References 
NA
