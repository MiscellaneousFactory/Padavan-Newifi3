# Padavan-Newifi3精简版固件
固件基于Padavan源码精简，适合不爱折腾固件的NEWIFI3路由器用户

默认wifi名称PDCN及PDCN_5G  
wifi密码1234567890  
管理地址192.168.123.1  
管理账号admin
管理密码admin 

固件下载  
https://www.lanzouw.com/i6pguwe3eud

***

- 20211111更新
>- 移除失效的定时重启选项，可在[系统管理>服务>调度任务]中设置定时重启
```shell
#示例：
#分 时 日 月 周 reboot &
#每天的三点半重启
30 3 * * * reboot &
#每星期一的三点半重启
#30 3 * * 1 reboot &
```
- 20211109更新
>- 精简插件，仅保留路由器常用功能  
>- 优化科学上网插件中的DNS选项，加入对SmartDNS的支持
>- 移除VPN界面选项
>- 修复部分系统编译skipdbv2插件报错的问题

***

### 源码说明 ###
在keke1023整合的固件版本上做了精简和优化

主要特点如下：  
1.采用padavanonly源码的5.0.4.0无线驱动，支持kvr  
2.添加了chongshengB源码的所有插件  
3.其他部分等同于hanwckf的源码，有少量优化来自immortalwrt的padavan源码
  
相关源码供参考：  
https://github.com/keke1023/Padavan  
https://github.com/hanwckf/rt-n56u  
https://github.com/chongshengB/rt-n56u  
https://github.com/padavanonly/rt-n56u  
https://github.com/immortalwrt/padavan  

***

### 固件编译 ###
推荐使用云编译脚本进行固件编译  
https://github.com/pmkol/Padavan-build-Newifi3

***

### 请参阅 ###
- https://www.jianshu.com/p/c31b58728778
