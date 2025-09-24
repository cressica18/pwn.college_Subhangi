# Module Name

## Challenge Name
So far, we've told you which files to interact with. But directories can have lots of files (and other directories) inside them, and we won't always be here to tell you their names. You'll need to learn to list their contents using the ls command!

ls will list files in all the directories provided to it as arguments, and in the current directory if no arguments are provided. Observe:

hacker@dojo:~$ ls /challenge
run
hacker@dojo:~$ ls
Desktop    Downloads  Pictures  Templates
Documents  Music      Public    Videos
hacker@dojo:~$ ls /home/hacker
Desktop    Downloads  Pictures  Templates
Documents  Music      Public    Videos
hacker@dojo:~$
In this challenge, we've named /challenge/run with some random name! List the files in /challenge to find it.

### Solve

I did it by using the ls /challenge command to get teh random file name then used it to list the files
```bash
command 1 ls /challenge
command 2 /challenge/7221-renamed-run-2294
pwn.college{I3ONCb2XN-6N8PCWsoagxe9H9Gu.QX4IDO0wyN1AzNzEzW}
```

### New Learnings
learned how to use ls

### References 
NA