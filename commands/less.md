## less

Description
```
Less is a command line utility that displays the contents of a file or a command output, one page at a time.
```
To use less 
```
less filename
```
Output can be directed to less as an alternative to creating and appending a file.
```
output | less
```
`less` allows many options to interact with the program when running:

```
 F # will follow the input as it is received. 
```

```
 & filter # will filter all lines to only the lines that contain the string in the filter.
```

```
 / query # finds the next instance of query in the page
```
```
 ? query # finds the previous instance of query in the page
```

