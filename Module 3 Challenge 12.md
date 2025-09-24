# Module Name
Comprehending Commands

## Challenge Name
We can create files. How about directories? You make directories using the mkdir command. Then you can stick files in there!

Watch:

hacker@dojo:~$ cd /tmp
hacker@dojo:/tmp$ ls
hacker@dojo:/tmp$ ls
hacker@dojo:/tmp$ mkdir my_directory
hacker@dojo:/tmp$ ls
my_directory
hacker@dojo:/tmp$ cd my_directory
hacker@dojo:/tmp/my_directory$ touch my_file
hacker@dojo:/tmp/my_directory$ ls
my_file
hacker@dojo:/tmp/my_directory$ ls /tmp/my_directory/my_file
/tmp/my_directory/my_file
hacker@dojo:/tmp/my_directory$
Now, go forth and create a /tmp/pwn directory and make a college file in it! Then run /challenge/run, which will check your solution and give you the flag!

### Solve

I did it by using the mkdir command to create the directory then used the touch command to create the file.
```bash
Command 1: cd /tmp
Command 2: ls
Command 3: ls
Command 4: mkdir my_directory
Command 5: ls
Command 6: cd my_directory
Command 7: touch my_file
Command 8: ls
Command 9: ls /tmp/my_directory/my_file
pwn.college{85UlMImmRkgaNtVxJQf_lgQB96p.QXxMDO0wyN1AzNzEzW}
```

### New Learnings
learned how to create directories

### References 
NA
