## git bash配置代理bash

找到项目文件夹.git/config 文件，增加下面几行，地址具体根据自己情况配置代理服务器


````
[http]
	proxy = http://10.45.40.148:8080
[https]
	proxy = https://10.45.40.148:8080

[remote "origin"]
	url = https://github.com/coolnameismy/crumbs.git
	fetch = +refs/heads/*:refs/remotes/origin/*

````