# Module Name
Digesting Documentation
## Challenge Name
Some programs don't have a man page, but might tell you how to run them if invoked with a special argument. Usually, this argument is --help, but it can often be -h or, in rare cases, -?, help, or other esoteric values like /? (though that latter is more frequently encountered on Windows).

In this level, you will practice reading a program's documentation with --help. Try it out!

### Solve
**Flag:** 

I first searched the hidden file then used man to print its content found the hidden clue then used it to print the flag

```bash
command 1 /challenge/challenge --help
command 2  /challenge/challenge -p
command 3 /challenge/challenge -g 
pwn.college{AS0PYHqh0ZxISmvuj--v1RcIRsv.QX3IDO0wyN1AzNzEzW}
```

### New Learnings
learned how to search hidden file through man command.

### References 
NA