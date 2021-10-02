# lsof: List of Open File

List all the open files that are currently opened by some process.

Example:

```bash
$ lsof
```

## Options

This command also accept some options that can be used to distinguish different process by their user / id and other options.

**List the process of specific user**

To list the process from speicifc user, when we have multiple users on system:

```bash
lsof -u <username>
```

_Replace <username> with the user of your choice in your system_

**List the process running on specific port**

We can list the process that are currently running on a specific port. This can be useful when debugging a process conflicts with the port currently used by other process.

```bash
lsof -i :3000
```

There are many other options that we can make use based on the requirements to check the open files in our system.
