# Module Name
Practicing Piping

## Challenge Name
First, let's look at redirecting stdout to files. You can accomplish this with the > character, as so:

hacker@dojo:~$ echo hi > asdf
This will redirect the output of echo hi (which will be hi) to the file asdf. You can then use a program such as cat to output this file:

hacker@dojo:~$ cat asdf
hi
In this challenge, you must use this output redirection to write the word PWN (all uppercase) to the filename COLLEGE (all uppercase).

### Solve
I used > to direct it to the file COLLEGE

```bash
command 1 echo PWN > COLLEGE
pwn.college{YUJExzVm33b1nsNsYZipSU0je27.QX0YTN0wyN1AzNzEzW}
```

### New Learnings
learned how to use >

### References 
NA
