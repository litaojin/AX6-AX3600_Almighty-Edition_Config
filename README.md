## 适用于AX6  
只适用于已经刷入OpenWRT固件后的AX6   
下载[最新build](https://github.com/litaojin/AX6_OpenWRT_Build/releases/tag/2021.12.05-2217)  
如果是初次安装，需要执行以下命令来恢复出厂配置
~~~
firstboot
reboot
~~~

2021-12-5更新配置文件，删除冲突及多余的插件  
## 插件：  
* OpenAppFilter  
* 简单mesh  
* smartdns  

* 流控  
* ttyd  
* zerotier  
* Turbo ACC  

* openclash   
* passwall   
* ShadowSocksRPlus+  

关于插件说明大家可参考恩山[这个帖子](https://www.right.com.cn/forum/thread-344825-1-3.html) 

驱动：默认NSS加速和sfe加速
