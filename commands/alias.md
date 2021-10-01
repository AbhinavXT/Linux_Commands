## alias

An alias lets you create a shortcut name for a command, file name, or any shell text.

For example, you can create an alias for the `cd` command to reach a cretain folder in your system.

```
alias cf='cd folder-name'
```

Once you do, you can call `cf` just like it was a regular UNIX command:

```
cf
```

The alias will work until the terminal session is closed.

To make it permanent, you need to add it to the shell
configuration, which could be `~/.bashrc` or `~/.profile` or
`~/.bash_profile` if you use the Bash shell, depending on the use case.

Be careful with quotes if you have variables in the command: using double quotes the variable is resolved at definition time, using single quotes it's resolved at invocation time.
