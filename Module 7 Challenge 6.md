# Module Name
Shell Variables

## Challenge Name
In the course of working with the shell, you will often want to store the output of some command into a variable. Luckily, the shell makes this quite easy using something called Command Substitution! Observe:

hacker@dojo:~$ FLAG=$(cat /flag)
hacker@dojo:~$ echo "$FLAG"
pwn.college{blahblahblah}
hacker@dojo:~$
Neat! Now, you practice. Read the output of the /challenge/run command directly into a variable called PWN, and it will contain the flag!

Trivia: You can also use backticks instead of $(): FLAG=`cat /flag` instead of FLAG=$(cat /flag) in the example above. This is an older format, and has some disadvantages (for example, imagine if you wanted to nest command substitutions. How would you do $(cat $(find / -name flag)) with backticks? The official stance of pwn.college is that you should use $(blah) instead of `blah`.
### Solve
I first read the flag then printed it

```bash
command 1: PWN=$(/challenge/run)
command 2: echo "$PWN"
pwn.college{keEZXAwnKCXuTqOCRDpyom1JrVL.QX1cDN1wyN1AzNzEzW}
```

### New Learnings
learned how to read the output

### References 
NA
