# Linux防火牆

## [10 Useful Open Source Security Firewalls for Linux Systems](https://www.tecmint.com/open-source-security-firewalls-for-linux-systems/)
```
1. Iptables
2. IPCop Firewall
3. Shorewall
4. UFW – Uncomplicated Firewall
5. Vuurmuur
6. pfSense(FreeBSD)
7. IPFire
8. SmoothWall & SmoothWall Express
9. Endian
10. ConfigServer Security Firewall
```
## [Top 10 Linux Firewall Solutions in 2021](https://www.toolbox.com/it-security/network-security/articles/top-10-linux-firewall-solutions/)

## [LINUX FIREWALLS ：善用 NFTABLES 等超強工具捍衛 LINUX 防火牆的安全性](https://www.tenlong.com.tw/products/9789864344239)
```
LINUX FIREWALLS ：善用 NFTABLES 等超強工具捍衛 LINUX 防火牆的安全性, 4/e (中文版) 
Linux Firewalls: Enhancing Security with nftables and Beyond, 4/e
Steve Suehring 王文燁

博碩文化  2019-09-12

Part I 封包過濾(packet filter Firewall)以及基本安全措施
Chapter 1 封包過濾防火牆的預備知識
Chapter 2 封包過濾防火牆概念

Chapter 3 iptables：傳統的 Linux 防火牆管理程式
Chapter 4 nftables:（新）Linux 防火牆管理程式

Part II 進階議題、多個防火牆和邊界網路
Chapter 7 封包轉發
Chapter 8 網路位址轉換NAT(Network address translation) https://en.wikipedia.org/wiki/Network_address_translation
Chapter 10 虛擬專用網路

Part III iptables 和nftables 之外的事
Chapter 11 入侵檢測和響應
Chapter 12 入侵檢測工具
Chapter 13 網路監控TCPDump 和攻擊檢測 Snort 
Chapter 14 檔案系統完整性 AIDE == Advanced Intrusion Detection Environment :file and directory integrity checker.
           https://aide.github.io/
```
## [iptables command in Linux with Examples](https://www.geeksforgeeks.org/iptables-command-in-linux-with-examples/)
```
TABLE ==>  There are five possible tables:
1.filter: Default used table for packet filtering. It includes chains like INPUT, OUTPUT and FORWARD.
2.nat : Related to Network Address Translation. It includes PREROUTING and POSTROUTING chains.
3.mangle : For specialised packet alteration. Inbuilt chains include PREROUTING and OUTPUT.
4.raw : Configures exemptions from connection tracking. Built-in chains are PREROUTING and OUTPUT.
5.security : Used for Mandatory Access Control
```
```
CHAINS ==>  There are few built-in chains that are included in tables. They are:

1.INPUT :set of rules for packets destined to localhost sockets.
2.FORWARD :for packets routed through the device.
3.OUTPUT :for locally generated packets, meant to be transmitted outside.
4.PREROUTING :for modifying packets as they arrive.
5.POSTROUTING :for modifying packets as they are leaving.
```
## [25 Useful IPtable Firewall Rules Every Linux Administrator Should Know](https://www.tecmint.com/linux-iptables-firewall-rules-examples-commands/)
```
Iptables uses a set of tables which have chains that contain set of built-in or user defined rules. Thanks to them a system administrator can properly filter the network traffic of his system.

Per iptables manual, there are currently 3 types of tables:

FILTER – this is the default table, which contains the built in chains for:
INPUT  – packages destined for local sockets
FORWARD – packets routed through the system
OUTPUT – packets generated locally
NAT – a table that is consulted when a packet tries to create a new connection. It has the following built-in:
PREROUTING – used for altering a packet as soon as it’s received
OUTPUT – used for altering locally generated packets
POSTROUTING – used for altering packets as they are about to go out
MANGLE – this table is used for packet altering. Until kernel version 2.4 this table had only two chains, but they are now 5:
PREROUTING – for altering incoming connections
OUTPUT – for altering locally generated  packets
INPUT – for incoming packets
POSTROUTING – for altering packets as they are about to go out
FORWARD – for packets routed through the box

```

```
4. Unblock IP Address in IPtables Firewall

```
