## ping

To view a the ping of an IP

```
The following is the output of running ping on Linux for sending five probes (
```

To view multiple files 
```
$ ping -c 5 www.example.com
PING www.example.com (93.184.216.34): 56 data bytes
64 bytes from 93.184.216.34: icmp_seq=0 ttl=56 time=11.632 ms
64 bytes from 93.184.216.34: icmp_seq=1 ttl=56 time=11.726 ms
64 bytes from 93.184.216.34: icmp_seq=2 ttl=56 time=10.683 ms
64 bytes from 93.184.216.34: icmp_seq=3 ttl=56 time=9.674 ms
64 bytes from 93.184.216.34: icmp_seq=4 ttl=56 time=11.127 ms

--- www.example.com ping statistics ---
5 packets transmitted, 5 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 9.674/10.968/11.726/0.748 ms
```

In cases of no response from the target host, most implementations display either nothing or periodically print notifications about timing out. Possible ping results indicating a problem include the following:
```
H, !N or !P – host, network or protocol unreachable
S – source route failed
F – fragmentation needed
U or !W – destination network/host unknown
I – source host is isolated
A – communication with destination network administratively prohibited
Z – communication with destination host administratively prohibited
Q – for this ToS the destination network is unreachable
T – for this ToS the destination host is unreachable
X – communication administratively prohibited
V – host precedence violation
C – precedence cutoff in effect
```


