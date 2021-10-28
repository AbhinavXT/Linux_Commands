## rmdir

rmdir is a commonly used linux command. It is used for removing empty folder/directories from the filesystem.

```
rmdir <options> 'folder-name'
```

This will remove the folder called folder-name in your current directory if it is empty; otherwise will show error message.

### Options and Examples:

```
rmdir mydir1 mydir2 mydir3
# remove folders with name mydir1, mydir2 nad mydir3 in case they are empty.
```

```
rmdir mydir/mydir1
# remove child directory if it is empty

rmdir mydir/mydir1
# Remove the directory mydir/mydir1 if it is empty.
# Then, remove directory mydir, if it is empty after mydir/mydir1 was removed
```

```
rmdir -p mydir/mydir1
# first remove the child directory and then remove parent directory.
```