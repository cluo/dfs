# 分布式文件服务器
[![Build Status](https://api.travis-ci.org/qieangel2013/dfs.svg)](https://travis-ci.org/qieangel2013/dfs)
[![Packagist](https://img.shields.io/badge/packagist-passing-ff69b4.svg)](https://packagist.org/packages/qieangel2013/dfs)
![Supported PHP versions: >=5.5](https://img.shields.io/badge/php-%3E%3D5.5-blue.svg)
![License](https://img.shields.io/badge/license-Apache%202-yellow.svg)
### 核心特性
    1.基于swoole和inotify实现分布式文件服务
    2.采用协议包来实时同步文件、性能很高，采用sendfile传送文件，内存、cpu占有率很少
    3.文件实时监控及监控子目录服务
    4.自动断线重连服务
    5.自动扫描本地已存在的文件目录实时同步服务
### 服务启动
    需要php以cli模式运行/server.php
      php server.php start
      php server.php stop
      php server.php restart
### composer 安装
	{
    		"require": {
        		"qieangel2013/dfs": "0.1.6"
		 }
	}
### 使用介绍
    安装swoole扩展和inotify扩展
    修改/config/config.php文件相应的配置
    交流群：337937322
### wiki介绍
https://github.com/qieangel2013/dfs/wiki
### liveim是一款直播平台，内置im聊天功能
	由于未开源，需要授权可以获取源代码
http://www.weivq.com:88/ (演示地址)<br/>
http://www.weivq.com:88/public/uploads/LiveIm.apk (安卓演示)<br/>
http://www.weivq.com:88/public/uploads/LiveImInstall.exe (pc端演示)
![](https://github.com/qieangel2013/yaf/blob/master/public/images/windowspc.png)
![](https://github.com/qieangel2013/yaf/blob/master/public/images/jt.png)
![](https://github.com/qieangel2013/yaf/blob/master/public/images/jtmobilet.png)
### License
    Apache License Version 2.0 see http://www.apache.org/licenses/LICENSE-2.0.html
### 如果你对我的辛勤劳动给予肯定，请给我捐赠，你的捐赠是我最大的动力
![](https://github.com/qieangel2013/zys/blob/master/public/images/pw.jpg)
![](https://github.com/qieangel2013/zys/blob/master/public/images/pay.png)
[项目捐赠列表](https://github.com/qieangel2013/zys/wiki/%E9%A1%B9%E7%9B%AE%E6%8D%90%E8%B5%A0)
