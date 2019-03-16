## 基于 node unblocker 的通用 web 代理

能通过此代理网站在墙内访问任何网站. 此网站做一个转发的作用.

### 使用方法

1. 下载 heroku CLI 客户端: https://devcenter.heroku.com/articles/getting-started-with-php#set-up <br>
2. 部署 <br>
$ heroku login<br>
$ git clone https://github.com/justsweetpotato/web-proxy-heroku.git <br>
$ cd web-proxy-heroku <br>
$ heroku create [You APP Name]<br>
$ heroku git:remote -a [You APP Name]<br>
$ git add .<br>
$ git commit -am "make it better"<br>
$ git push heroku master<br>
 
<br>

### 关于

原项目地址: https://github.com/nfriedly/node-unblocker
<br>
有位作者进行了修改以适合 heroku 部署: https://github.com/gfw-breaker/heroku-node-proxy
<br>
本项目基于修改版的基础上仅仅是修改了主页, 通过本地 push 到远程的方式部署到 heroku.
