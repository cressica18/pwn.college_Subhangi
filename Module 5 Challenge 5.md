# Module Name
File Globbing

## Challenge Name
So far, you've specified one glob at a time, but you can do more! Bash supports the expansion of multiple globs in a single word. For example:

hacker@dojo:~$ cat /*fl*
pwn.college{YEAH}
hacker@dojo:~$
What happens above is that the shell looks for all files in / that start with anything (including nothing), then have an f and an l, and end in anything (including ag, which makes flag).

Now you try it. We put a few happy, but diversely-named files in /challenge/files. Go cd there and run /challenge/run, providing a single argument: a short (3 characters or less) globbed word with two * globs in it that covers every word that contains the letter p.

### Solve
i first changed the directory then used two globs to get every word which has p in it.

```bash
command 1 cd /challenge/files
command 2 /challenge/run *p*
pwn.college{oWhE-L2_yAKCX6O6eP5MWfmlr2t.0lM3kjNxwyN1AzNzEzW}
```

### New Learnings
learned how to use more than one globs.

### References 
NA
