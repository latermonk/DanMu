# DanMu


##  网页展示slide + 实时弹幕评论系统   
https://github.com/liu946/danmuSlideServer

###  dokcer环境搭建弹幕
```
docker run -d -p 32768:22  -p 32767:3000  --name test_sshd rastasheep/ubuntu-sshd:18.04

apt update && apt install wget curl vim git  -y

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash

source ~/.bashrc  

nvm install node 

git clone https://github.com/liu946/danmuSlideServer.git

cd danmuSlideServer
npm install
node index.js

```


http://localhost:32767/danmuup

发射弹幕， Go  go  go ！！！

```
docker volume create portainer_data

docker run -d -p 8000:8000 -p 9000:9000 --name=portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer
 
```





------

#  一个基于canvas的弹幕系统     
https://github.com/zhaofinger/canvas-barrage

https://zhaofinger.github.io/canvas-barrage/index.html   


