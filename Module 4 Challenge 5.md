# Module Name
Digesting Documentation
## Challenge Name
This level is tricky: it hides the manpage for the challenge by randomizing its name. Luckily, all of the manpages are gathered in a searchable database, so you'll be able to search the man page database to find the hidden challenge man page! To figure out how to search for the right manpage, read the man page manpage by doing: man man!

HINT 1: man man teaches you advanced usage of the man command itself, and you must use this knowledge to figure out how to search for the hidden manpage that will tell you how to use /challenge/challenge

HINT 2: though the manpage is randomly named, you still actually use /challenge/challenge to get the flag!

### Solve
**Flag:** 

I first searched the hidden file then used man to print its content found the hidden clue then used it to print the flag

```bash
command 1 man -k challenge
command 2 man fugtuahllk
command 3 /challenge/challenge --fugtua 999
pwn.college{AfuS9ALgLt9u9aGhFllMkMsnYf5.QX2EDO0wyN1AzNzEzW}
```

### New Learnings
learned how to search hidden file through man command.

### References 
NA