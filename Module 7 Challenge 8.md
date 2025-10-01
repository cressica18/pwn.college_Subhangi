# Module Name
Shell Variables

## Challenge Name
Often, when shell users want to read a file into an environment variable, they do something like:

hacker@dojo:~$ echo "test" > some_file
hacker@dojo:~$ VAR=$(cat some_file)
hacker@dojo:~$ echo $VAR
test
This works, but it represents what grouchy hackers call a "Useless Use of Cat". That is, running a whole other program just to read the file is a waste. It turns out that you can just use the powers of the shell!

Previously, you read user input into a variable. You've also previously redirected files into command input! Put them together, and you can read files with the shell.
### Solve
I redirected /challenge/read_me into the shell read

```bash
command 1: read PWN < /challenge/read_me
pwn.college{UuV2hH92-YadpK90ntf7aKOMSrA.QXwIDO0wyN1AzNzEzW}
```

### New Learnings
learned how to read command

### References 
NA
