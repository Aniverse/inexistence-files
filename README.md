# inexistence-files

#### About binary files
ioping static is from [nench](https://github.com/n-st/nench).  
fio and iperf3 static are from [yabs](https://github.com/masonr/yet-another-bench-script).  
smartctl (7.2 2020-07-07 r5074) static can be downloaded from: https://builds.smartmontools.org  

installation
```
list="smartctl fio ioping iperf3"
mkdir -p $HOME/.abench/bin && cd $HOME/.abench/bin
for app in $list ; do
    wget https://github.com/Aniverse/inexistence-files/raw/master/binary/amd64/$app -q
    chmod 755 $HOME/.abench/bin/$app
done
```

#### rTorrent IPv6 patches

https://amefs.net/archives/1825.html  
https://github.com/amefs/QB/tree/master/setup/sources  
https://github.com/flag2010/rtorrent-0.9.2-ipv6.patch/blob/master/rtorrent-0.9.2-ipv6.patch  
