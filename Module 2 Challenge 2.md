# Module Name 
Pondering Paths

## Challenge Name
Let's explore a slightly more complicated path! Except for in the previous level, challenges in pwn.college are in the challenge directory and the challenge directory is, in turn, right in the root directory (/). The path to the challenge directory is, thus, /challenge. The name of the challenge program in this level is run, and it lives in the /challenge directory. Thus, the path to the run challenge program is /challenge/run.

This challenge again requires you to execute it by invoking its absolute path. You'll want to execute the run file that is in the challenge directory that is, in turn, in the / directory. If you invoke the challenge correctly, it will give you the flag. Good luck!

### Solve
**Flag:** 
The challenge directory was in the root directory and the run file was in challenge directory
```bash
command 1 /challenge/run
pwn.college{s7n_cg-Bg598JRXgmAjl-X7F0ke.QX1QTN0wyN1AzNzEzW}
```

### New Learnings
Learned how to extract a file from a directory placed in another directory
### References 
NA
