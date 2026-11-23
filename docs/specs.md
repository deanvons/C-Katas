# Get The Line Dynamically

Implement a function that acquires a line from the console and has this prototype:

```text
char *get_line_alloc(int *plen)
```

**Goals:**
 - don't use scanf!
 - acquire a string up to the newline character
 - always put a null characher at the end of the buffer
 - return a newly allocated buffer containig the entire input string
 - if given, store the length of the input string in plen
 - plen may be NULL
 - return NULL if an error occurs
 - implement a main loop that asks the user to insert a line, acquire it and print it
 - terminate the main loop when the user enters "END"
 - in the main loop manage the allocated buffer

**Tips:**
 - something might be useful to dynamically allocate memory...
