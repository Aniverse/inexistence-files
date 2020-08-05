# inexistence-files

#### About binary files
ioping static is from [nench](https://github.com/n-st/nench).
fio and iperf3 static is from [yabs](https://github.com/masonr/yet-another-bench-script).

```
list="smartctl fio ioping iperf3"
for app in $list ; do
    wget https://github.com/Aniverse/inexistence-files/raw/master/binary/amd64/$app -qO $HOME/.abench/bin/$app
    chmod 755 $HOME/.abench/bin/$app
done
```

#### rTorrent IPv6 patches

https://amefs.net/archives/1825.html
https://github.com/amefs/QB/tree/master/setup/sources
https://github.com/flag2010/rtorrent-0.9.2-ipv6.patch/blob/master/rtorrent-0.9.2-ipv6.patch
