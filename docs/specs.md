# Get The Line

Implement a function that acquires a line from the console and has this prototype:

```text
int get_line(char dst[], int size)
```

**Goals:**
 - don't use scanf!
 - acquire a string up to the newline character
 - always put a null characher at the end of the buffer
 - truncate the acquisition to leave space at the end of the buffer for the null character
 - return the number of characters acquired, excluding the null character
 - implement a main loop that asks the user to insert a line, acquire it and print it
 - terminate the main loop when the user enters "END"
