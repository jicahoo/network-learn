# network-learn
As title.

# LVS
* http://blog.51cto.com/atong/1348602

# tcp/dump + Wireshark
* sudo tcpdump -X -S -s 0 -i eth0 -vv ip6 | tee ipv6_packets.log
* sudo tcpdump -X -S -s 0 -i eth0 -vv ip6 -w wireshark.log
* sudo tcpdump -X -S -s 0 -i eth0 -w wireshark.log
* sudo tcpdump -X -S -s 0 -i lo -w wireshark.log
* sudo tcpdump -i eth0 


# TCP/IP
* 滑动窗口：https://blog.csdn.net/wdscq1234/article/details/52444277

# How does HTTP package go into gateway port.
* The gateway port is within Router
* Host will know the mac address of gateway port. You can check it with command `arp -a`
