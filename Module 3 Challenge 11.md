# Module Name
Comprehending Commands

## Challenge Name
With your knowledge of cd, ls, and cat, we're ready to play a little game!

We'll start it out in /. Normally:

hacker@dojo:~$ cd /
hacker@dojo:/$ ls
bin   challenge  etc   home  lib32  libx32  mnt  proc  run   srv  tmp  var
boot  dev        flag  lib   lib64  media   opt  root  sbin  sys  usr
That's a lot of contents! One day, you will be quite familiar with them, but already, you might recognize the flag file and the challenge directory.

In this challenge, I have hidden the flag! Here, you will use ls and cat to follow my breadcrumbs and find it! Here's how it'll work:

Your first clue is in /. Head on over there.
Look around with ls. There'll be a file named HINT or CLUE or something along those lines!
cat that file to read the clue!
Depending on what the clue says, head on over to the next directory (or don't!).
Follow the clues to the flag!
Good luck!
### Solve

I followed the breadcrumbs: using ls and cat to read clues, ls -a to reveal hidden files, and cd only when the clue is delayed
```bash
**Command 1:** `cd /`
**Command 2:** `ls`
**Command 3:** `cat /NUGGET`
**Command 4:** `ls /opt/linux/linux-5.4/arch/powerpc/mm`
**Command 5:** `cat /opt/linux/linux-5.4/arch/powerpc/mm/INSIGHT-TRAPPED`
**Command 6:** `ls /usr/local/lib/python3.8/dist-packages/Crypto/Protocol/__pycache__`
**Command 7:** `cat /usr/local/lib/python3.8/dist-packages/Crypto/Protocol/__pycache__/INFO`
**Command 8:** `ls -a /opt/linux/linux-5.4/Documentation/firmware-guide/acpi`
**Command 9:** `cat /opt/linux/linux-5.4/Documentation/firmware-guide/acpi/.BRIEF`
**Command 10:** `ls -a /opt/linux/linux-5.4/drivers/staging/unisys/visorhba`
**Command 11:** `cat /opt/linux/linux-5.4/drivers/staging/unisys/visorhba/.MESSAGE`
**Command 12:** `ls -a /usr/aarch64-linux-gnu/include/linux/mmc`
**Command 13:** `cat /usr/aarch64-linux-gnu/include/linux/mmc/.DOSSIER`
**Command 14:** `cd /opt/libslub/libslub/frontend/breakpoints/gdb`
**Command 15:** `ls`
**Command 16:** `cat /opt/libslub/libslub/frontend/breakpoints/gdb/BLUEPRINT`
**Command 17:** `ls /usr/lib/R/library/tools/html`
**Command 18:** `cat /usr/lib/R/library/tools/html/ALERT-TRAPPED`
**Command 19:** `cd /opt/busybox/busybox-1.33.2/include/config/first`
**Command 20:** `ls`
**Command 21:** `cat MEMO`
pwn.college{QUVFFa85ejQW84nwooaYEp4DZ_n.QX5IDO0wyN1AzNzEzW}
```

### New Learnings
learned how to use ls,cat and cd according to situations

### References 
NA
