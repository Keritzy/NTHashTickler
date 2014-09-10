NTHashTickler
============

This program uses random brute force to try to find a matching plain-text password for the NT hash that you supply.

Windows stores NT (or NTLM) hashes as the MD4 hash of the UTF16/Unicode little endian encoded plain text.

There are plenty of other tools out there that already do this, and much better. I wrote this tool for myself as a learning
experience to exercise performance and multi threaded concepts in C#.

![Screenshot](./screen1.PNG)