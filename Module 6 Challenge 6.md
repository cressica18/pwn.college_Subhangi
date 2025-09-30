# Module Name
Practicing Piping

## Challenge Name
You know how to run commands, how to redirect their output (e.g., >), and how to search through the resulting file (e.g., grep). Let's put this together!

In preparation for more complex levels, we want you to:

Redirect the output of /challenge/run to /tmp/data.txt.
This will result in a hundred thousand lines of text, with one of them being the flag, in /tmp/data.txt.
grep that for the flag!
### Solve
I redirected the output then grepped the flag from the fi;e.

```bash
command 1 /challenge/run 1> /tmp/data.txt
command 2 grep -o -m1 'pwn\.college[^[:space:]]*' /tmp/data.txt
pwn.college{MG1b226eJ9S1dMY8MkOt3of4Z7V.QX4EDO0wyN1AzNzEzW}
```

### New Learnings
learned how to use redirection an grep together.

### References 
NA
