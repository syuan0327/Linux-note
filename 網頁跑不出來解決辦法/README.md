# 網頁跑不出來解決辦法

#### 1.ping 127.0.0.1(Lookback位址)

** 目的為址為127.0.0.1 的封包不會送到網路上，而是送至 本機的Lookback 驅動程式。 此一動作是用來測試本機的TCP/IP 協定是否正常運作
#### 2.ping 自己的ip位址
先用ifconfig找出自己的位址

#### 3.ip route show:查看內定路由位址
￼
a.內定路由位置：

b.Ping 內定路由位址
#### 4.ping 外面提供的dns伺服器ip位址
goole的 => ping 8.8.8.8

或著直接ping tw.yahoo.com

#### 5.新增nameserver
a.開啟gedit /etc/resolv.conf

**補充：gedit=圖形化介面

然後可以自己加nameserver

Ex:nameserver 4.4.4.4
