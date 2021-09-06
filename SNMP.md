# SNMP




```
SNMP主要分為
管理端（Manager）
利用SNMP通訊協定向代理者（Agent）查詢所需的相關資訊
如網路設備運作狀態、CPU使用率、硬碟利用率等。 
代理者（Agent）
管理資訊庫（Management Information Base，MIB）
```
```
SNMP所定義的五種Manager與Agent溝通指令
GET REQUEST ，用來得到一條管理資訊
GET NEXT REQUEST ，用來反覆得到管理資訊的序列
GET RESPONSE，讀取回應
SET REQUEST，設定值，主動管理系統
TRAP ，主動通知管理端，警告一個異常事件
```
## SNMP v1
## SNMP v2
```
針對SNMP v1 改進許多安全缺陷，提供基礎的認證程序
```
## SNMP v3
```
在SNMP v2 的基礎上增強安全功能
應用加密標準(Data Encryption Standard, DES)與MD5等編碼技術對資料進行編碼
透過對資料進行鑑別與加密，提供以下安全特性：
確保資料是合法的
對傳輸的資料加密
確保傳輸資料正確
```
## 網路監控


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
