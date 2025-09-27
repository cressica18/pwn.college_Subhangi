# Module Name
File Globbing

## Challenge Name

Now, let's put the previous levels together! We put a few happy, but diversely-named files in /challenge/files. Go cd there and, using the globbing you've learned, write a single, short (6 characters or less) glob that (when passed as an argument to /challenge/run) will match the files "challenging", "educational", and "pwning"!
### Solve
i used a bracket glob [cep]* to match only filenames starting with c, e, or p.

```bash
command 1 cd /challenge/files
command 2 /challenge/run *[cep]*
pwn.college{0cFn-JS6RNwqr3IO0Rx-eoa_80R.QX1IDO0wyN1AzNzEzW}
```

### New Learnings
learned how to apply concepts of globs more

### References 
NA
