# Module Name
Practicing Piping

## Challenge Name
It turns out that you can "cut out the middleman" and avoid the need to store results to a file, like you did in the last level. You can do this by using the | (pipe) operator. Standard output from the command to the left of the pipe will be connected to (piped into) the standard input of the command to the right of the pipe. For example:

hacker@dojo:~$ echo no-no | grep yes
hacker@dojo:~$ echo yes-yes | grep yes
yes-yes
hacker@dojo:~$ echo yes-yes | grep no
hacker@dojo:~$ echo no-no | grep no
no-no
Now try it for yourself! /challenge/run will output a hundred thousand lines of text, including the flag. grep for the flag!
### Solve
I used the pipe operator to print the output from the file directly.

```bash
command 1 /challenge/run | grep 'pwn\.college'
pwn.college{EqcTg0OXvZ0dZu0mzSpQN9ZUr9F.QX5EDO0wyN1AzNzEzW}
```

### New Learnings
learned how to use pipe operator.

### References 
NA
