# Module Name

## Challenge Name
You can also move files around with the mv command. The usage is simple:

hacker@dojo:~$ ls
my-file
hacker@dojo:~$ cat my-file
PWN!
hacker@dojo:~$ mv my-file your-file
hacker@dojo:~$ ls
your-file
hacker@dojo:~$ cat your-file
PWN!
hacker@dojo:~$
This challenge wants you to move the /flag file into /tmp/hack-the-planet (do it)! When you're done, run /challenge/check, which will check things out and give the flag to you.

### Solve

I did it by using the mv command to move the files
```bash
command 1  mv /flag /tmp/hack-the-planet
command 2 /challenge/check
pwn.college{UKZnJzpzJXHF575tpn0EoCfcA_Q.0VOxEzNxwyN1AzNzEzW}
```

### New Learnings
learned how to use move files using mv

### References 
NA