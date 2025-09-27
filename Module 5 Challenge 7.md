# Module Name
File Globbing

## Challenge Name
Sometimes, you want to filter out files in a glob! Luckily, [] helps you do just this. If the first character in the brackets is a ! or (in newer versions of bash) a ^, the glob inverts, and that bracket instance matches characters that aren't listed. For example:

hacker@dojo:~$ touch file_a
hacker@dojo:~$ touch file_b
hacker@dojo:~$ touch file_c
hacker@dojo:~$ ls
file_a	file_b	file_c
hacker@dojo:~$ echo Look: file_[!ab]
Look: file_c
hacker@dojo:~$ echo Look: file_[^ab]
Look: file_c
hacker@dojo:~$ echo Look: file_[ab]
Look: file_a file_b
Armed with this knowledge, go forth to /challenge/files and run /challenge/run with all files that don't start with p, w, or n!

NOTE: The ! character has a different special meaning in bash when it's not the first character of a [] glob, so keep that in mind if things stop making sense! ^ does not have this problem, but is also not compatible with older shells.

### Solve
i used a bracket glob [^pwn]* so no file starting with these 3 letters do not get included.

```bash
command 1 cd /challenge/files
command 2 /challenge/run [^pwn]*
pwn.college{IW8D3cbYFKeqitg_J_skRFzHzVb.QX2IDO0wyN1AzNzEzW}
```

### New Learnings
learned how to apply concepts of globs more

### References 
NA
