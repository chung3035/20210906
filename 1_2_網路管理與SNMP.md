# [SNMP](https://en.wikipedia.org/wiki/Simple_Network_Management_Protocol)  [[中文版]](https://zh.wikipedia.org/wiki/%E7%AE%80%E5%8D%95%E7%BD%91%E7%BB%9C%E7%AE%A1%E7%90%86%E5%8D%8F%E8%AE%AE)

```
簡單網路管理協定（SNMP，Simple Network Management Protocol）構成了網際網路工程工作小組（IETF，Internet Engineering Task Force）定義的Internet協定族的一部分。
SNMP協定能夠支援網路管理系統，用以監測連接到網路上的裝置是否有任何引起管理上關注的情況。
SNMP由一組網路管理的標準組成，包含一個應用層協定（application layer protocol）、資料庫模式（database schema），和一組資料物件。
```
## SNMP基本元件
```
一個SNMP管理的網路由下列三個關鍵元件組成：

網路管理系統（NMSs，Network-management systems）
被管理的裝置（managed device）
代理者（agent）
```
```
SNMP主要分為
1.管理端（Manager） ==> 利用SNMP通訊協定向代理者（Agent）查詢所需的相關資訊
                       如網路設備運作狀態、CPU使用率、硬碟利用率等。 
2.代理者（Agent）
3.管理資訊庫（Management Information Base，MIB）
```

## SNMP v1
```
第一版中指定五種核心PDU：
GET REQUEST ，用來得到一條管理資訊
GET NEXT REQUEST ，用來反覆得到管理資訊的序列
GET RESPONSE，讀取回應
SET REQUEST，設定值，主動管理系統
TRAP ，主動通知管理端，警告一個異常事件
```
## SNMP v2
```
SNMP第二版SMI在RFC 2578之中描述
它在SNMP第一版的SMI規格資料型態上進行增加和強化，例如位元串（bit strings）、網路位址（network addresses）和計數器（counters）

第二版中指定七種核心PDU：
GET REQUEST
GET NEXT REQUEST
GET RESPONSE
SET REQUEST
TRAP

GETBULK REQUEST [SNMP第二版新加]
INFORM [SNMP第二版新加]


SNMP第二版SMI資訊模組
SNMP第二版SMI也指定了資訊模組來詳細說明一群相關連的定義。
有三種SMI資訊模組：MIB模組、回應狀態、能力狀態。
```
## SNMP v3
```
SNMP第三版由RFC 3411-RFC 3418定義

主要增加SNMP在安全性和遠端組態方面的強化。

SNMP第三版提供重要的安全性功能：
資訊完整性：保證封包在傳送中沒有被竄改。
認證：檢驗資訊來自正確的來源。
封包加密：避免被未授權的來源窺探。

第三版中指定八種核心PDU：
GET REQUEST
GET NEXT REQUEST
GET RESPONSE
SET REQUEST
TRAP

GETBULK REQUEST [SNMP第二版新加]
INFORM [SNMP第二版新加]

Report [SNMP第三版新加]
```
## OpenNMS

- [OpenNMS](https://en.wikipedia.org/wiki/OpenNMS)
- [OpenNMS Documentation](https://docs.opennms.com/start-page/1.0.0/index.html)
- [Quick Introduction to OpenNMS](https://www.youtube.com/watch?v=9ksCJiIAv-k)
- [OpenNMS](https://www.youtube.com/channel/UCuNoze7QQ9aqoR6ZxLhPqFA)
- [OpenNMS 101 video series](https://www.youtube.com/watch?v=GJzmkshdjiI&list=PLsXgBGH3nG7iZSlssmZB3xWsAJlst2j2z)

## [openSNMP](https://sourceforge.net/projects/opensnmp/) 
```
openSNMP is a multi-threaded SNMPv3 engine. This project supports the
Simple Network Management Protocol version 3. In particular, it is
designed to match the architecture of the Internet Engineering Task Force SNMPv3 standard (RFCs 3410-15).
```
## 網路監控系統
```
Prometheus 雲端監控系統
Nagios
Cacti
Graphite
Ganglia
Zabbix
OpenFalcon

ELK/EFK
```
- [Zabbix 監控系統入門與實戰 胡楊男爵2020](https://www.tenlong.com.tw/products/9787302556299)
- [下世代超前佈署：用 Zabbix 全面監管巨量伺服器 吳兆松 深智數位 2019/2020](https://www.tenlong.com.tw/products/9789865501471)
- [異形般強大的監控系統：Prometheus 掌控主機、VM、容器及 K8S 陳曉宇、 楊川胡、陳嘯 深智數位 2020](https://www.tenlong.com.tw/products/9789865501167)


## 網路監控實作
```
Day 2:
Page-182 ==> 安裝Cacti Server@Ubuntu
Page-213 ==> 設定Windows可以被Cacti Server監控
```
- [免費網絡監控 Cacti 一步一步](https://www.youtube.com/watch?v=u6-Y7AEI1MQ)
- [How to Install Cacti Server on WINDOWS | All SOLVED Error while Cacti Installation Wizard](https://www.youtube.com/watch?v=XTKuOmfs-PE)
- [How to network monitoring on Windows for free | Cacti | NETVN](https://www.youtube.com/watch?v=tfbttqvp1E4)

- [Install and Configure Cacti on Ubuntu 20.04|18.04](https://computingforgeeks.com/install-and-configure-cacti-on-ubuntu/)
- [How to install Cacti SNMP Monitor on Ubuntu](https://www.techrepublic.com/article/how-to-install-cacti-snmp-monitor-on-ubuntu/)

- [設定Windows可以被Cacti Server監控](https://a84923977.blogspot.com/2016/07/windowscacti-server.html)
