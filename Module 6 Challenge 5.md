# Module Name
Practicing Piping

## Challenge Name
Just like you can redirect output from programs, you can redirect input to programs! This is done using <, as so:

hacker@dojo:~$ echo yo > message
hacker@dojo:~$ cat message
yo
hacker@dojo:~$ rev < message
oy
You can do interesting things with a lot of different programs using input redirection! In this level, we will practice using /challenge/run, which will require you to redirect the PWN file to it and have the PWN file contain the value COLLEGE! To write that value to the PWN file, recall the prior challenge on output redirection from echo!
### Solve
I redirected 

```bash
command 1 echo COLLEGE > PWN
command 2 /challenge/run < PWN
pwn.college{MX3H3M-5kDoNAP2p5xmOL5jgk3Q.QXwcTN0wyN1AzNzEzW}
```

### New Learnings
learned how to use input redirection.

### References 
NA
