# 20210906

```
0.課程內容簡介
1.通訊協定與拓樸簡介
2.網路設備及功能簡介

3.網路架構技術
4.網路架構部署原則
5.網路架構安全技術
6.網路架構管理程序


7.機關實際導入案例分享
```
# Day 1

## 1.通訊協定與拓樸簡介
```
路由協定(Routing Protocol):RIP OSPF  IS-IS IGRP/EIGRP  BGP
網路管理協定: SNMP NetFlow  sFlow

網路拓樸型態

基礎網路連線安全辨識
利用瀏覽器找到的電腦網際網路IP為何？
利用控制台找到的電腦本機IP為何？
利用控制台找到的DNS為何？
利用控制台找到的Gateway為何？
瀏覽器找到的電腦IP與控制台找到的電腦IP是否一致？
嘗試進行遠端桌面連線。
嘗試列出電腦開啟的服務埠號。
與Wiki TCP/UDP埠列表對找，了解服務內容。


實作：查找自己的網路設定
開啟網路服務-遠端桌面
實作：了解已開啟的網路服務

Windows防火牆與實測
實作 Ping
防火牆規則撰寫

連線安全常用技術: 
SSL/TLS
http vs https
FTP vs sftp  vs ftps
Telnet vs ssh

本次實作中，自己電腦的IP為何？
本次實作中，對方電腦的IP為何？
作為伺服器，如何確認自己的檔案有沒有被下載？
是否有看到 226 Transfer OK之字眼？
下載一個檔案的速率為何？
如何使用Windows防火牆阻擋連線？ 

HTTP File Server  ==> HFS  IIS

1. 安裝封包擷取程式
2. 選擇被監聽的網卡
3. 進行Telnet連線操作
4. 封包過濾，找出Telnet 流量
5. 找出連線帳號密碼及操作過程
6. 以SSH進行連線
7. 重複相同動作，顯示加密內容
```
## 第2單元 網路設備及功能簡介
```
交換器與路由器(Switch and Router)

防火牆(Firewall)
入侵偵測防禦系統(IDS/IPS)
防毒牆(Antivirus Wall)

網域名稱伺服器(DNS)

無線網路(Wi-Fi)
機關(構)適用的無線網路平台
```

```
網路架構與設備組成

攻擊型態：網路釣魚(Phishing)
商業電子郵件詐騙（Business E-mail Compromise，BEC）
攻擊型態：惡意程式(Malware)
攻擊模式： DNS放大(反射)攻擊
攻擊模式： SQL Injection

網域名稱伺服器(DNS)
攻擊手法

無線網路(Wi-Fi)
無線網路安全技術
無線網路攻擊手法

無線網路基礎操作與設定
Switch/Router 基礎操作與設定
在 Windows 系統內構建防火牆
Linux 防火牆
```
# 第三單元 網路架構 技術
```
網路OSI參考模型(ISO於1983年發布ISO/IEC 7498)
TCP/IP與DoD四層模型
IPv6協定攻擊手法分析

乙太網路
光纖通道(Fiber Channel)
設備規格與辨識
```
# 第四單元 網路架構  部署原則  ==> 機關網路 規劃與設計
```
網路設備之組成
網路區域劃分
VLAN劃分
路由劃分

核心系統資料流程圖
機關區域間存取控制設定
機關網路架構圖

網路架構探查的呈現與監控
比對檢核表，稽核檢測狀況

常見錯誤樣態與架構歸納
探查現存網路用戶之能力

LAB: 實作 – 取得教室內設備數量及MAC位置

探查現存網路用戶提供之服務 ==> nmap
```
## 第五單元 網路架構  安全技術
```
防火牆安全技術
IP 控管技術
DDoS防禦技術
防毒牆安全技術
DNS安全性設定
無線網路安全機制:WEP WPA/WPA2/WPA3
Linux 防火牆
SNMP安全性
SNMP管理協定
```
```
https://www.techrepublic.com/article/how-to-install-cacti-snmp-monitor-on-ubuntu/
安裝cacti@ubuntu
設定Windows可以被Cacti Server監控
情境討論、示範與實作
用Weathermap強化Cacti
```
# Day 3
## 第六單元 網路架構 管理程序 ==> PDCA
```
PDCA
規劃：VLAN與路由規劃
規劃：機關(構)資料流程圖繪製
規劃：網路區域間存取控制
規劃：檢測項目 vs 查檢表
網路架構檢核項目
路由檢核表
DNS安全性檢測
防火牆檢核表
網路設備定期設定備份檢核表
無線網路檢核項目
無線網路架構確認 
無線網路管理狀態確認 
無線網路使用者存取確認

管理程序 – 執行
管理程序 – 檢查
管理程序 – 行動
```

## 第七單元 機關(構)實際導入案例分享
```
資通安全責任等級分級辦法規定要求
指引實務導入報告：A機關(1/51)
指引實務導入報告：B機關(1/23)
```

```
未來網路架構與安全趨勢發展
SD-WAN
CORD
vEPC ==> 將傳統電信核心網路（EPC）布建在虛擬化平台

開源專案範例
ONF project
OPNFV and more
```

###
```
vEPC (Virtual Evolved Packet Core)
```

###
```
CORD == 『Central Office Re-architected as a Datacenter』 == ONLAB(ONF) 所提出的一個新的電信網路機房的概念設計
結合三大技術：SDN(Software-Defined Networking), NFV(Network Functions Virtualization), elastic cloud services

https://bestsamina.github.io/posts/2018-02-08-cord-init/
```






