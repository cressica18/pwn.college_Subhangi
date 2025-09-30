# Module Name
Practicing Piping

## Challenge Name
The grep command has a very useful option: -v (invert match). While normal grep shows lines that MATCH a pattern, grep -v shows lines that do NOT match a pattern:

hacker@dojo:~$ cat data.txt
hello hackers!
hello world!
hacker@dojo:~$ cat data.txt | grep -v world
hello hackers!
hacker@dojo:~$
Sometimes, the only way to filter to just the data you want is to filter out the data you don't want. In this challenge, /challenge/run will output the flag to stdout, but it will also output over 1000 decoy flags (containing the word DECOY somewhere in the flag) mixed in with the real flag. You'll need to filter out the decoys while keeping the real flag!

Use grep -v to filter out all the lines containing "DECOY" and reveal the real flag!
### Solve
I piped out the decoys and found the flag

```bash
command 1 /challenge/run | grep -v 'DECOY' | grep 'pwn.college'
pwn.college{MTuLncVLsb8P8E4KZMCppNTmHrb.0FOxEzNxwyN1AzNzEzW}
```

### New Learnings
learned how to pipe out specific texts

### References 
NA
