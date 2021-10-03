## grep

The grep filter searches a file for a particular pattern of characters, and displays all lines that contain that pattern.

```
grep [options] pattern [files]
```

The pattern that is searched in the file is referred to as the regular expressions.

### Options Description

```
-c : This prints only a count of the lines that match a pattern
-h : Display the matched lines, but do not display the filenames.
-i : Ignores, case for matching
-l : Displays list of a filenames only.
-n : Display the matched lines and their line numbers.
-v : This prints out all the lines that do not matches the pattern
-e exp : Specifies expression with this option. Can use multiple times.
-f file : Takes patterns from file, one per line.
-E : Treats pattern as an extended regular expression (ERE)
-w : Match whole word
-o : Print only the matched parts of a matching line,
 with each such part on a separate output line.

-A n : Prints searched line and nlines after the result.
-B n : Prints searched line and n line before the result.
-C n : Prints searched line and n lines after before the result.

```

### Example

This finds the number of lines that matches the given string/pattern.

```
grep -c "hactoberfest" filename.txt
```
