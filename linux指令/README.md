# Linux指令


1.&& => And

2.|| => Or

3.ls (list)

```
a.ls aaa && ls => (前面執行成功後面才能執行)

b.ls aaa || ls => (前面執行成功後面不會執行)

c.ls aaa ; ls  => (前面不管有沒有成功後面都會執行）

d.ls /home => (列出home資料夾有什麼東西)

指令可以一直串下去

ex: ls /home/xxx/yyy/zzz

```

4.cd(change directory)

```
cd ~ => 回家目錄
cd . => 目前所在目錄
cd - => 回上一目錄所在位置
cd .. => 上一層目錄

```

5.pwd(print working directory)

6.ssh管理遠端連線（跑在22port)

7.改變port

```
a.打gedit sshd_config &

b.跑出頁面

c.去掉#後就可以改port

```

8.關機指令

```
reboot(重新開機)

halt -p

poweroff

shutdown

```

9.ifconfig在linux上查找ip

![GITHUB]( https://github.com/syuan0327/Linux-note/blob/master/user%20%26%20root/%E6%93%B7%E5%8F%962.JPG)

10.yum install：在linux 安裝東西


