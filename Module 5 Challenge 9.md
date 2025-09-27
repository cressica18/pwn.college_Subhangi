# Module Name
File Globbing

## Challenge Name
Consider the following situation:

hacker@dojo:~$ ls
flag  flamingo  flowers
hacker@dojo:~$ cat f<TAB>
There are multiple options! What happens?

What happens varies based on the specific shell and its options. By default bash will auto-expand until the first point when there are multiple options (in this case, fl). When you hit tab a second time, it'll print out those options. Other shells and configurations, instead, will cycle through the options.

This challenge has a /challenge/files directory with a bunch of files starting with pwncollege. Tab-complete from /challenge/files/p or so, and make your way to the flag!


### Solve
I used tab-completion to expand pwncollege-… name, then cat the completed filename to read the flag.

```bash
command 1 cd /challenge/files
command 2 cat /challenge/files/pwnc<TAB><TAB>
command 3 cat /challenge/files/pwncollege-flag
pwn.college{Yjj0RnWJaSW1GWr46Hq1QtKul0Z.0lN0EzNxwyN1AzNzEzW}
```

### New Learnings
learned how to do tab completion at a better level

### References 
NA
