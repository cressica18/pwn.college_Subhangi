# Module Name

## Challenge Name
In the last level, you did cat flag to read the flag out of your home directory! You can, of course, specify cat's arguments as absolute paths:

hacker@dojo:~$ cat /challenge/DESCRIPTION.md
In the last level, you did `cat flag` to read the flag out of your home directory!
You can, of course, specify `cat`'s arguments as absolute paths:
...
In this directory, I will not copy it to your home directory, but I will make it readable. You can read it with cat at its absolute path: /flag.

### Solve

I did it by using the concept of cat function and absolute path.

```bash
command 1 cat /flag
pwn.college{82aYG8qKh6qxvq-PpfTqPaLpmDB.QX5ETO0wyN1AzNzEzW}
```

### New Learnings
learned how to use cat to access absolute files

### References 
NA