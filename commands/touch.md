## touch

The `touch` command is a standard command used in the UNIX/Linux operating system which is used to create, change and modify timestamps of a file.

You can create a single empty file using the touch command.

```bash
touch file_name
```

Touch command can be used to create multiple files at the same time. These files would be empty on creation.

```bash
touch file1 file2 file3
```

Command Options for `touch`

Like all other commands, the `touch` command has various options. Examples are:

`touch -a`: This command is used to change the access time of the specified file. By default, it will take the current time of your system.

```bash
touch -a file_name
```

`touch -c` : Using the -c option with touch command will not create an empty file, if that file doesn't exist.

```bash
touch -c file_name
```

`touch -c-d` : This is used to update the access and modification time of the file.

```bash
touch -c-d file_name
```

`touch -m` : This is used to alter the last modification time of the file.

```bash
touch -m file_name
```

`touch -t` : This is used to create a new file with a specified time.

```bash
touch -t YYMMDDHHMM fileName
```