## nslookup

It stands for Name Server Lookup which is used for getting information from the DNS server. It it a tool for quering the DNS to obtain domain name or IP address mapping or any other specific DNS record. 

```
nslookup [options]
```

### Examples

```
nslookup google.com
```

```
nslookup 192.168.0.10 //For reverse DNS lookup.
```

Also we can provide <b>-type</b> argument to view only desired information of any domain.

```
-type = any ,to view all the available DNS records.

-type = soa, provides the authorative information about the domain, etc

-type = ns, record maps a domain name to a list of DNS servers authoritative for that domain.

-type = a, view all the available DNS records for a particular record.

-type = mx, record maps a domain name to a list of all mail exchange servers for that domain.

```

### Example

```
nslookup -type=ns google.com
```