# processes & thread
process 行程：a running program


<img src="https://github.com/syuan0327/Linux-note/blob/master/processes%20%26%20thread/1.JPG" width = 50% height=50%>

<img src="https://github.com/syuan0327/Linux-note/blob/master/processes%20%26%20thread/5.jpg" width = 50% height=50%>

#### [多工]

1.processes => 開很多行程，每個行程做不同事

2.thead(線程or執行緒) => 一程式裡面已很多線程 

*thread較有效率

<img src="https://github.com/syuan0327/Linux-note/blob/master/processes%20%26%20thread/2.JPG" width = 50% height=50%>

UID = 誰執行後面的程式(CMD)

PID = parent process id

user的ps -f

<img src="https://github.com/syuan0327/Linux-note/blob/master/processes%20%26%20thread/6.jpg" width = 50% height=50%>

root的ps -f

<img src="https://github.com/syuan0327/Linux-note/blob/master/processes%20%26%20thread/3.JPG" width = 50% height=50%>

<img src="https://github.com/syuan0327/Linux-note/blob/master/processes%20%26%20thread/7.jpg" width = 50% height=50%>

活用行程列表ps

<img src="https://github.com/syuan0327/Linux-note/blob/master/processes%20%26%20thread/4.JPG" width = 50% height=50%>

python -m SimpleHTTPServer 80 => 建立一網頁伺服器

如果要從建一個必須先kill前一個

<img src="https://github.com/syuan0327/Linux-note/blob/master/processes%20%26%20thread/8.JPG" width = 50% height=50%>
