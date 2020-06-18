# 連上Putty
###### 一、進入最高權限使者
```
su
輸入密碼：******
```
###### 二、開啟sshd
systemctl start httpd
###### 三、確認是否開啟sshd
systemctl status httpd
<img src="https://github.com/syuan0327/Linux-note/blob/master/%E9%80%A3%E4%B8%8Aputty/1.JPG" width="80%" height="80%">
顯示綠色代表成功

netstat -tulnp |grep 80(查詢port 80 的語法)
<img src="https://github.com/syuan0327/Linux-note/blob/master/%E9%80%A3%E4%B8%8Aputty/2.JPG" width="80%" height="80%">

echo “hi” > /var/www/html/syuan.htm(將hi寫入syuan.htm)

systemctl start sshd 

systemctl status sshd

顯示綠色代表可以(同上一張圖片）

ifconfig

查看ip=192.168.90.***(每個人有可能不一樣）


如果不成功要記得關防火牆：
```
systemctl stop firewalls
```
#### 四、putty部分
打開putty輸入剛剛找到的ip 

輸入帳號密碼
<img src="https://github.com/syuan0327/Linux-note/blob/master/%E9%80%A3%E4%B8%8Aputty/3.JPG" width="80%" height="80%">
#### 五、google部分
輸入剛剛的"ip"+/syuan.htm
<img src="https://github.com/syuan0327/Linux-note/blob/master/%E9%80%A3%E4%B8%8Aputty/4.JPG" width="80%" height="80%">
