# Module Name
Practicing Piping

## Challenge Name
Aside from redirecting the output of echo, you can, of course, redirect the output of any command. In this level, /challenge/run will once more give you a flag, but only if you redirect its output to the file myflag. Your flag will, of course, end up in the myflag file!

You'll notice that /challenge/run will still happily print to your terminal, despite you redirecting stdout. That's because it communicates its instructions and feedback over standard error, and only prints the flag over standard out!
### Solve
I redirected the output to myflag and the errors to instructions

```bash
command 1 /challenge/run > myflag
command 2 cat myflag
pwn.college{0tati1NVTMAG-MdwsRVj6Rro1rX.QX1YTN0wyN1AzNzEzW}
```

### New Learnings
learned how to use redirect more output

### References 
NA
