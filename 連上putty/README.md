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

顯示綠色代表成功

netstat -tulnp |grep 80(查詢port 80 的語法)

echo “hi” > /var/www/html/hi.htm

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

進入黑色頁面

輸入帳號密碼
￼
#### 五、google部分
輸入剛剛的ip/hi.htm
￼



