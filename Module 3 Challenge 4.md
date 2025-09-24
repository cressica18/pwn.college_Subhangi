# Module Name

## Challenge Name
Sometimes, the files that you might cat out are too big. Luckily, we have the grep command to search for the contents we need! We'll learn it in this challenge.

There are many ways to grep, and we'll learn one way here:

hacker@dojo:~$ grep SEARCH_STRING /path/to/file
Invoked like this, grep will search the file for lines of text containing SEARCH_STRING and print them to the console.

In this challenge, I've put a hundred thousand lines of text into the /challenge/data.txt file. grep it for the flag!

HINT: The flag always starts with the text pwn.college.

### Solve

I did it by using the grep command to search for string pwn\.college  in the given file

```bash
command 1 grep 'pwn\.college' /challenge/data.txt
pwn.college{8IKgi8_4KXdgGKsHCeCB9EesqFR.QX3EDO0wyN1AzNzEzW}
```

### New Learnings
learned how to use grep

### References 
NA