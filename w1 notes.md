6.S081 2020 Lecture 1: O/S overview

Terminologies

- h/w: hardware
- under the hood: 在后台，在底层
- &c: etc.

Notes

1. ```
   fd = open("out", 1);
   write(fd, "hello\n", 6);
   pid = fork();
   ```
   These look like function calls but they aren't, they are application/kernel interfaces.

2. Kernighan and Ritchie (K&R) book is good for learning C