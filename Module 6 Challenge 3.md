# Module Name
Practicing Piping

## Challenge Name
A common use-case of output redirection is to save off some command results for later analysis. Often times, you want to do this in aggregate: run a bunch of commands, save their output, and grep through it later. In this case, you might want all that output to keep appending to the same file, but > will create a new output file every time, deleting the old contents.

You can redirect input in append mode using >> instead of >, as so:

hacker@dojo:~$ echo pwn > outfile
hacker@dojo:~$ echo college >> outfile
hacker@dojo:~$ cat outfile
pwn
college
hacker@dojo:$
To practice, run /challenge/run with an append-mode redirect of the output to the file /home/hacker/the-flag. The practice will write the first half of the flag to the file, and the second half to stdout if stdout is redirected to the file. If you properly redirect in append-mode, the second half will be appended to the first, but if you redirect in truncation mode (>), the second half will overwrite the first and you won't get the flag!

### Solve
I redirected /challenge/run with >> /home/hacker/the-flag so the program’s first-half output stayed in the file and the second-half was appended.

```bash
command 1 /challenge/run >> /home/hacker/the-flag
command 2 cat /home/hacker/the-flag
pwn.college{wS6MP47P3Ke8ZoW1icqONTRT_i0.QX3ATO0wyN1AzNzEzW}
```

### New Learnings
>> appends to the end of a file so we shld use >> when you want to keep previous output and add more. 

### References 
NA
