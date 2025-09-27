# Module Name
File Globbing

## Challenge Name
Next, let's learn about ?. When it encounters a ? character in any argument, the shell will treat it as a single-character wildcard. This works like *, but only matches one character. For example:

hacker@dojo:~$ touch file_a
hacker@dojo:~$ touch file_b
hacker@dojo:~$ touch file_cc
hacker@dojo:~$ ls
file_a	file_b	file_cc
hacker@dojo:~$ echo Look: file_?
Look: file_a file_b
hacker@dojo:~$ echo Look: file_??
Look: file_cc
Now, practice this yourself! Starting from your home directory, change your directory to /challenge, but use the ? character instead of c and l in the argument to cd! Once you're there, run /challenge/run for the flag!

### Solve
i used ? to change the directory to challenge and then ran /challenge/run

```bash
command 1 cd /?ha??enge
command 2 /challenge/run
pwn.college{8aK5M3OicaFZyfEclXOB_JmzKTd.QXyIDO0wyN1AzNzEzW}
```

### New Learnings
learned how to use ?

### References 
NA
