# Module Name
File Globbing

## Challenge Name
Globbing happens on a path basis, so you can expand entire paths with your globbed arguments. For example:

hacker@dojo:~$ touch file_a
hacker@dojo:~$ touch file_b
hacker@dojo:~$ touch file_c
hacker@dojo:~$ ls
file_a	file_b	file_c
hacker@dojo:~$ echo Look: /home/hacker/file_[ab]
Look: /home/hacker/file_a /home/hacker/file_b
Now it's your turn. Once more, we've placed a bunch of files in /challenge/files. Starting from your home directory, run /challenge/run with a single argument that bracket-globs into the absolute paths to the file_b, file_a, file_s, and file_h files!

### Solve
I ran /challenge/run /challenge/files/file_[bash], letting the shell expand [bash] into b,a,s,h so the program received the four absolute paths.

```bash
command 1 /challenge/run /challenge/files/file_[bash]
pwn.college{k1tV-bhQYWV470CtvzlmBIFF0jY.QX0IDO0wyN1AzNzEzW}
```

### New Learnings
learned how to expand paths with globbed arguments

### References 
NA
