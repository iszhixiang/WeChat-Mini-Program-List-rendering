分享一下我今天学习的 微信小程序列表渲染功能
## 学习b站 up主软件大道的方法<br>

# 项目使用步骤
<br>
<hr>
<h2>1,启动本地服务器</h2><br>
首先需要用命令打开本地服务器，打开这个服务器需要下载   <em>node js</em>     这个软件,这个软件我下载之后使用的时候还显示缺失了一些模块没有安装，如 express ，安装 node js 之后出现错误可以把错误代码在浏览器中查一下，网上有解决方案<br><br>
这样就可以实现本地服务器的网络申请了，毕竟如果想要申请域名的话会很麻烦。<br>

打开终端，定位到  <strong>服务器端</strong>   所在的位置，然后用命令  <pre>node index.js</pre> 

来开启本地服务器<br>
如下图<br><br>
![image](https://github.com/iszhixiang/WeChat-Mini-Program-List-rendering/blob/main/images/minling.png)
<br><br><br>
成功之后会提示打开了本地服务器的地址<br><br>
![image](https://github.com/iszhixiang/WeChat-Mini-Program-List-rendering/blob/main/images/Start%20the%20server.png)
<hr>

<h2>2,导入项目</h2>
<br>
将项目 <strong>xiaoli</strong>   导入 微信小程序开发者工具


<br>
<br>

<strong>值得注意的是，项目编译的时候可能会出现 本地地址 为不合法的域名，这种情况点击右上角的详情，将选项 不校验合法域名，web-view..... 给勾选就好了</strong><br><br>
![image](https://github.com/iszhixiang/WeChat-Mini-Program-List-rendering/blob/main/images/Mini%20Program%20settings.png)

