# myhexdump
Works like the hexdump command.

No redirection.

Only -c can be used. 

Use the test directory and *.txt as a test.
# Notes
The output is not the same if the file could not be opened.

Offset after decimal:268435455, hex:ffffff is undefined.
# usage 
```
make re
./hexdump filename
```
# function used
write, open, close, read, malloc, free, strerror
# test
```
make re
make test > my.txt
make oritest > ori.txt
diff my.txt ori.txt
```
Now you can see that it works the same way.
