# Module Name
Digesting Documentation
## Challenge Name
While using most commands is straightforward, the usage of some commands can get quite complex. For example, the arguments to commands like sed and awk, which we're definitely not getting into right now, are entire programs in an esoteric programming language! Somewhere on the spectrum between cd and awk are commands that take arguments to their arguments...

This sounds crazy, but you've already encountered this with the find level in Basic Commands. find has a -name argument, and the -name argument itself takes an argument specifying the name to search for. Many other commands are analogous.

Here is this level's documentation for /challenge/challenge:

Welcome to the documentation for /challenge/challenge! This program allows you to print arbitrary files to the terminal, when given the --printfile argument. The argument to the --printfile argument is the path of the flag to read. For example, /challenge/challenge --printfile /challenge/DESCRIPTION.md will print out the description of the level!

Given that documentation, go get the flag!

### Solve
**Flag:** 

I first printed the description using printfile and then i used the flag file to get the flag.

```bash
command 1 /challenge/challenge --printfile /challenge/DESCRIPTION.md
command 2 /challenge/challenge --printfile /flag
pwn.college{YeLQ25sunJiFA0ljw2VN_G8agTx.QX1ITO0wyN1AzNzEzW}
```

### New Learnings
learned how to print out files

### References 
NA