# Module Name
Digesting Documentation
## Challenge Name
Some commands, rather than being programs with man pages and help options, are built into the shell itself. These are called builtins. Builtins are invoked just like commands, but the shell handles them internally instead of launching other programs. You can get a list of shell builtins by running the builtin help, as so:

hacker@dojo:~$ help
You can get help on a specific one by passing it to the help builtin. Let's look at a builtin that we've already used earlier, cd!

hacker@dojo:~$ help cd
cd: cd [-L|[-P [-e]] [-@]] [dir]
    Change the shell working directory.
    
    Change the current directory to DIR.  The default DIR is the value of the
    HOME shell variable.
...
Some good information! In this challenge, we'll practice using help to look up help for builtins. This challenge's challenge command is a shell builtin, rather than a program. Like before, you need to lookup its help to figure out the secret value to pass to it!

### Solve
**Flag:** 

I used help on the builtin challenge to find the secret argument, then ran challenge --secret 4mf8aABW to print the flag.

```bash
command 1 help challenge
command 2  challenge --secret 4mf8aABW
pwn.college{4mf8aABW_7RIQNHXomRwbytSbXq.QX0ETO0wyN1AzNzEzW}
```

### New Learnings
learned how to search in shell builtins

### References 
NA