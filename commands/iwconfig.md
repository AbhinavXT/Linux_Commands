## iwconfig

It is used to configure wireless network interface.

```
iwconfig [interface] [option]
```

Here, interface is usually a driver name followed by unit number. 
For example, <b>wlan0</b> for the first wireless interface.

### Options

```
down     if will disable the wireless driver.
# iwconfig [interface] down
```

```
up     if will start the wireless driver.
# iwconfig [interface] up
```

If no arguments are given, iwconfig displays the status of the currently active wireless interfaces.
If a single interface argument is given, it displays the status of the particular interface only.
if a single <b>-a</b> argument is given, it displays the status of all wireless interfaces, even those that are down.
