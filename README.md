# test_jingdong01

## 项目介绍

	### 此项目与学期末这几天内制作，项目主要由Vue2 + vue-router + element-ui + axios制作

### 项目环境为 node.js 14 版本，vue-cli  ，npm 6.14.18 。  由于后端知识不足，用了json-server插件在本地搭建数据接口，后期会加入Springboot作为后端。

### 主要是练手为主，新手很好练的一个项目 

```
分为游客登陆，普通用户，管理员(管理员账号在  本地接口/db.json里找得到，管理员账号：AKAYWJ，密码：123456)

只有管理员用户可以进入后台管理，但在网址加路由也可以，原因是我没做权限，时间来不及
```



***

## 项目开始前注意事项： 必须先开启json-server项目，否则前端不会出现数据



## 第一种方法



### 第一步

		安装node环境（这里不多说） 最好是node 14版本

### 第二步

```
下载项目，解压后，将整个项目部署到PhpStudy或者宝塔或者你会的部署方式
```

```
进入“本地接口”目录，打开cmd，输入 npm i  -g json-server  全局安装json-server
```

```
运行 npm i 
运行 npm run dev (可以在package.json中修改运行方式)
出现 ：
	 \{^_^}/ hi!

  Loading db.json
  Done
说明json-server服务运行成功---------不要关闭cmd窗口
```

### 第三步

```
打开你部署项目的地方，不要关闭json-server服务即可正常使用
```

## 第二种方式

### 第一步

```
	安装node环境（这里不多说） 最好是node 14版本
```

```
进入“本地接口”目录，打开cmd，输入 npm i  -g json-server  全局安装json-server

运行 npm i 
运行 npm run dev (可以在package.json中修改运行方式)
出现 ：
	 \{^_^}/ hi!

  Loading db.json
  Done
说明json-server服务运行成功---------不要关闭cmd窗口
```

### 第二步

```
浏览器输入 https://akaywj.github.io/ 即可线上访问（这个是部署到GitHub服务器，网速慢或者/没有魔法，请用下面的）
第二个网址 ：https://71l95066r3.yicp.fun/#/


```

## 结尾

以上两种方式都必须先开启json-server服务，否则体验不好



