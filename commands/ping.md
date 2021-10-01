## ping

PING (Packet Internet Groper) command is used to check the network connectivity between host and server/host. 
Usage example:

```
ping github.com
```
The command can be stopped using ctrl-C or it keeps sending packets.

The number of psckets sent can be controlled by using the -c option like:

```
ping -c 3 github.com
```

This sends 3 packets to github.com and stops.

The time interval between each packets sent can be changed using the -i option.

```
ping -i 2 github.com
```
This command send packets to github.com with an interval of 2 seconds between each packets.

For more options, you can use the -h or --help option like so

```
ping --help
```