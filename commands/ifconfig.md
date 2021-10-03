## ifconfig

It is used to configure the kernel-resident network interfaces.

```
ifconfig [options] [interface]  
```

Here, interface is usually a driver name followed by unit number. 
For example, <b>eth0</b> for the first Ethernet interface.

### Options

```
-a     display all interfaces which are currently available, even if down

-s     display a short list (like netstat -i)

-v     be more verbose for some error conditions

```

If no arguments are given, ifconfig displays the status of the currently active interfaces.  
If a single interface argument is given, it displays the status of the given interface only. 
if a single <b>-a</b> argument is given, it displays the status of all interfaces, even those that are down. 
Otherwise, it configures an interface.
