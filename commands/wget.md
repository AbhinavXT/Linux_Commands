## wget

wget is a command line feature use for downloading file from the internet. It supports feature like multiple-downloading, downloading in background, limitize bandwidth, etc.

```
Syntex: wget [options] [url]
```

### Example

```
wget https://cdn.kernel.org/pub/linux/kernel/v4.x/linux-4.17.2.tar.xz
```

### Option

 ```
 wget --limit-rate=1m https://dl.google.com/go/go1.10.3.linux-amd64.tar.gz
 # --limit-rate will limitize bandwidth; in this case 1m
 ```
 
 ```
 wget -b https://download.opensuse.org/tumbleweed/iso/openSUSE-Tumbleweed-DVD-x86_64-Current.iso
 # -b will download file in background.
 ```
