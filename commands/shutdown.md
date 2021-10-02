## shutdown

The shutdown command lets you shut down or reboot your Linux system in a safe way. When the shutdown is initiated, all logged-in users and processes are notified that the system is going down, and no further logins are allowed.

**Syntax**

```bash
shutdown [OPTIONS] [TIME] [MESSAGE]
```

**Usage**

Using shutdown with no parameters will shut down your computer in one minute.

```bash
shutdown
```

To shut down immediately, use the now parameter.

```bash
shutdown now
```

To shutdown the system at specific time , we can use the time argument can be in two different formats. It can be an absolute time in the format `hh:mm` and relative time in the format `+m` where m is the number of minutes from now.

```bash
shutdown 11:00
```

```bash
shutdown +10
```

To cancel the scheduled shutdown use -c parameter.

```bash
shutdown -c
```
