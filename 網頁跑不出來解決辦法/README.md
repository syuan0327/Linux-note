# 網頁跑不出來解決辦法

#### 1.ping 127.0.0.1(Lookback位址)

** 目的位址為127.0.0.1 的封包不會送到網路上，而是送至本機的Lookback 驅動程式。 此一動作是用來測試本機的TCP/IP 協定是否正常運作
#### 2.ping 自己的ip位址
a.先用ifconfig找出自己的位址

b.在ping自己的ip位址
#### 3.ip route show:查看內定路由位址
a.內定路由位置：

<img src="https://github.com/syuan0327/Linux-note/blob/master/%E7%B6%B2%E9%A0%81%E8%B7%91%E4%B8%8D%E5%87%BA%E4%BE%86%E8%A7%A3%E6%B1%BA%E8%BE%A6%E6%B3%95/1.JPG" width="60%" height="60%">

b.Ping 內定路由位址
#### 4.ping 外面提供的dns伺服器ip位址
goole的 => ping 8.8.8.8

或著直接ping tw.yahoo.com

<img src="https://github.com/syuan0327/Linux-note/blob/master/%E7%B6%B2%E9%A0%81%E8%B7%91%E4%B8%8D%E5%87%BA%E4%BE%86%E8%A7%A3%E6%B1%BA%E8%BE%A6%E6%B3%95/2.JPG" width="60%" height="60%">

#### 5.新增nameserver
a.開啟gedit /etc/resolv.conf

**補充：gedit=圖形化介面

b.然後可以自己加nameserver

Ex:nameserver 4.4.4.4

<img src="https://github.com/syuan0327/Linux-note/blob/master/%E7%B6%B2%E9%A0%81%E8%B7%91%E4%B8%8D%E5%87%BA%E4%BE%86%E8%A7%A3%E6%B1%BA%E8%BE%A6%E6%B3%95/3.JPG" width="60%" height="60%">
