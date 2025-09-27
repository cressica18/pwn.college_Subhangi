# Module Name
File Globbing

## Challenge Name
Next, we will cover []. The square brackets are, essentially, a limited form of ?, in that instead of matching any character, [] is a wildcard for some subset of potential characters, specified within the brackets. For example, [pwn] will match the character p, w, or n. For example:

hacker@dojo:~$ touch file_a
hacker@dojo:~$ touch file_b
hacker@dojo:~$ touch file_c
hacker@dojo:~$ ls
file_a	file_b	file_c
hacker@dojo:~$ echo Look: file_[ab]
Look: file_a file_b
Try it here! We've placed a bunch of files in /challenge/files. Change your working directory to /challenge/files and run /challenge/run with a single argument that bracket-globs into file_b, file_a, file_s, and file_h!

### Solve
i first changed the directory to challenge and then used [] to match the file

```bash
command 1 cd /challenge/files
command 2 /challenge/run file_[bash]
pwn.college{c-IuUXrvtO5YouReubmiRNSXBYw.QXzIDO0wyN1AzNzEzW}
```

### New Learnings
learned how to match with []

### References 
NA
