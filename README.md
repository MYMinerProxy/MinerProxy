
# 自动最稳定的ETH以太坊代理代理矿池程序，MinerProxy/矿池代理和协议，支持自定义抽水，高性能的TCP连接，作者抽水千分之三 支持web界面管理，自启动代理和代理转接后可以启动运行，会放开火和连接数限制，一键搞定。
# 自动最稳定的ETH以太坊代理代理矿池程序，MinerProxy/矿池代理和协议，支持自定义抽水，高性能的TCP连接，作者抽水千分之三 支持web界面管理，自启动代理和代理转接后可以启动运行，会放开火和连接数限制，一键搞定。
# 重要提示QQ群519252801   TG群https://t.me/mykjidccn
# 重要提示必看
#### 1.Linux系统第一次完成后请重启服务器，这样可以突破安装连接限制，单机稳定2000台！！！
#### 2.安装完成后，请立即修改默认密码，以防有心之人，扫描端口偷偷登录！！！

# liunx -一键安装脚本
适合又想要Linux稳定的又不懂Linux的小白的学习者
功能：包含自启动和守护进程，重启后可以自动运行，会放开和连接数限制，一键搞定
要求：Ubuntu  16 +  /  Debian  8 +  /  CentOS  7+系统
使用root用户输入下面命令安装或卸载
# linux一键安装脚本
bash <(curl -s -L https://raw.githubusercontent.com/MYMinerProxy/MinerProxy/main/linux-install.sh)
## Windows 直接下载运行 <a href="https://github.com/MYMinerProxy/MinerProxy/tree/main/Windows">Release</a></br>
- - -
# 默认账号密码
 默认账号: admin 默认密码: admin123



# 支持的币种
 ETH ETC BTC  KDA ZEC BEAM RVN ERG ZEN LTC DCR DASH CKB BCH HNS STC 



# 支持的功能	
#精确到单台设备的24小时数据统计分析	
TLS/SSL/KENC加密	
矿池转发	
预置�各币种的矿池（随时更新）	
自定义矿池	
备用矿池	
自定义端口	
端口连接数限制	
多钱包配置	
自定义抽水比例	
自定义抽水钱包、矿池、设备名称	
统一钱包	
矿池模式	
端口备注	
在线更新	
导入导出端口配置	
自定义SSL密钥	
矿池状态检查	
自定义TLS证书	
IP黑名单	
CC策略	
修改矿池内本地算力




# 界面截图

<img width="1231" alt="F803EB0188CEAE3D7C69FE566F67AF48" src="https://user-images.githubusercontent.com/105948962/169625636-04dcd17e-4f88-4d6a-85dd-af154c142dad.png">
<img width="1231" alt="D8451E1F4CF1354D3FF9BAAE2DDD99E8" src="https://user-images.githubusercontent.com/105948962/169625649-ddccfc36-3c47-40cf-ba49-3cb7f3d86e52.png">
<img width="1231" alt="9CCA1C48E273FC114FB085EAC763AFEC" src="https://user-images.githubusercontent.com/105948962/169625664-16cd0e58-4e1a-4070-ad95-bf5c24811de6.png">
<img width="1231" alt="31BCC448E0C0D0CEBB8396E0E80FF257" src="https://user-images.githubusercontent.com/105948962/169625668-f8143b8f-6321-4072-8f74-855049655471.png">
<img width="1231" alt="824A1283E0D55800C02955EA490BCAEB" src="https://user-images.githubusercontent.com/105948962/169860723-f3641b1b-cb8e-46e3-affe-0b2fc1ca07d6.png">

# 更新日志
2.3.3
增加了兼容模式, 一些币种或机型在工作一段时间后出现大量无效导致无法继续工作时可以尝试使用此模式
对BTC进行了优化, 无法抽水的BTC机型和矿池, 可以使用兼容模式来进行工作
对A11进行了优化, 如果是A11的机器, 端口请选择ETH芯片级及兼容模式
更新了KENC, 所有使用KENC客户端的用户请下载最新KENC
开放了BTC统一钱包

2.3.0
BTC现在支持了所有矿池
BTC引入了无损机制
实装了BTC算力统计
BTC增加了动态难度抽水

2.2.7
修复了特殊情况下无损逻辑暂时失效的BUG
适当缩小了数据尺寸, 降低了3/1的内存占用

2.2.6
修复了一些内存相关的问题
修复了TEAMRED内核中途报错的问题
完善了无损的逻辑(需规模性测试)

2.2.5
修复了一些情况下动态难度调整失效的问题
修复了部分内核概率性掉线的问题
设备详情里增加了设备的IP显示

2.2.4
ETH增加了动态难度抽水机制, 跨池也能抽到比例算力了
略微提升了凤凰内核的算力
修复了部分内核不显示名字和算力的问题

2.2.3
增加了本地算力修改的功能

2.2.2
极大稳定了算力补偿机制，给你稳稳的幸福

2.2.1
支持了芯动矿机，创建端口时选择ETH芯片机即可
修复了算力补偿机器的名称问题，微量的提高了双方算力
修复了网页修改端口导致ip黑名单丢失的问题

2.2.0
大大降低了ETH的损耗
增加了难度统计

2.1.1
修复因为新的机制导致的大量算力丢失问题

2.1.0
大大减小了特殊网络环境下的算力损耗
干掉了幽灵设备
修复了矿池内机器合并为defualt的问题
修复了TEAMRED内核的相关问题
增加了KENC隧道协议
增加了软防CC策略
增加了IP黑名单功能
TOKEN超时切换到登录页自动保留了账号密码
修复了自定义配置中文无法保存的问题
修复了端口证书相关的问题

2.0.1
修复BTC抽水导致目标机器算力低下的问题

2.0.0
实装了BTC和BCH的抽水
自定义配置现在可以导入导出和跨平台保留了

1.1.5
修复了一些抽水问题

1.1.4
修复了抽水导致的断连bug

1.1.3
实装掉线提醒
修改了一些可能导致延迟增加的地方
支持了网页修改web访问端口
新的安全逻辑, 避免被扫
支持了修改账号
修改了部分内核导致名字乱了的问题

1.1.2
大幅提升程序稳定性�

1.1.1
大幅提升程序稳定性
重新开放了小币种的转发

1.1.0
修复了本地算力浮动的问题
更加稳定持久的连接
支持了不同钱包不同比例抽水
开放了备用池
增加了端口日志
更温柔的抽水
修复了币印新的TLS地址无法连接的问题
增加了设备连接时长
增加了钱包、机器名搜索
修改了一个容易导致内存泄漏的地方, 程序更加稳固
修复了某些小币种自定义配置不生效的问题
新的安装脚本, 更方便管理, 支持了开机启动修改端口等功能

1.0.0
完全有效的抽水份额
新的抽水逻辑
实装btc（待测试）
端口内设备有时候算力为0, 不用担心，显示的问题，如果担心的话可以观察内核输出，仅仅是显示问题 稍后会优化掉
现在增加了万分之一的开发费用

0.9.9
可配置多个钱包
修改了开启抽水导致的份额丢失问题
新的获取任务逻辑, 获取份额数量更快了一些
增加了常用自定义配置管理
可以单独导出某个端口的配置
优化页面细节
显示正常的区间内份额统计图表
机器增加了日志,点击机器查看详情可看到（持续更新）
增加了一键默认配置
修改了sn冲突导致的无法登录的问题

0.1.1
修改了内存爆炸的问题
修改了抽水钱包算力过多的问题
端口关闭下可以开关SSL以及重新配置证书
取消自动更新功能
去掉了无效的设置

0.0.9
修复了导致软件崩溃的几个关键问题
修复了粘包导致的份额丢失的问题
修复了首次启动看不到图表的问题
抽水算法改为随机算法，曲线更稳定
增加了端口配置TLS证书功能
增加矿池连接状态测试功能
增加抽水份额统计
增加原始钱包地址查看登录页右下键可以查看机器码

0.0.8
修改了抽水统一钱包失效的问题
修改了抽水逻辑，现在频率更高，矿池曲线更稳定
增加列表分页及设置
修正了某些情况下含有数据统计的币种也会提示未知设备的问题

0.0.6:
默认端口号改为16777
更换进程守护方式
页面优化
数据列表默认排序
修正更换端口无法启动的问题
可以正常转发但是不支持数据统计的币种，列表内现在可以显示设备了
增加抽水设备名称的配置
增加了矿池模式统一名称的配置
增加语言包

0.0.5:
稳定性改进
增加了一些ETH预置矿池
修复了目标矿池为SSL连不上的问题
# KENC文档说明
<p id="kenc"></p>

### KENC是本地->远程HX隧道，局域网部署在一台设备上即可，可与远程MYMinerProxy通过KENC协议进行通信。

<a href="https://github.com/MYMinerProxy/MinerProxy/tree/main/%E8%82%AF%E5%85%8B">点击下载WINDOWS客户端</a>

<a href="https://github.com/MYMinerProxy/MinerProxy/tree/main/%E8%82%AF%E5%85%8B">点击下载LINUX客户端</a>

### 使用环境
```
HXMinerproxy版本>=2.1.0
```

## 使用说明

### 1.远程HXminerproxy先配置一个KENC协议的端口
<img width="630" alt="1" src="https://user-images.githubusercontent.com/105948962/171179214-747821f3-9e5c-4d81-9612-a145b7e55795.png">


### 2.本地找一台电脑运行KENC, 运行成功后会提示, 根据提示访问地址去配置自己的KENC客户端

<img width="634" alt="2" src="https://user-images.githubusercontent.com/105948962/171179255-13803e93-55b2-49f2-b2ee-8f22d2533bf4.png">


### 3. 打开网页kenc客户端, 默认密码admin123

![3](https://user-images.githubusercontent.com/105948962/171179263-840fe02d-7328-438b-863c-75b64a3875d6.png)


### 4. 添加本地端口
![4](https://user-images.githubusercontent.com/105948962/171179282-cf8c9635-a43e-4f4c-8eaa-6c42da50a5a2.png)


<ul>
    <li>先随便填写个本地端口 小于65535的数字</li>
    <li>本地协议选择TCP或SSL，选择采矿设备支持的协议即可</li>
    <li>目标地址填写远程的MYMinerproxy的连接地址，链接地址为远程ip:端口号</li>
    <li>最大连接数默认无上限</li>
</ul>

### 5. 局域网的所有采矿设备的连接地址填写局域网安装KENC的设备IP地址+本地端口号即可, 通常直接连接图内地址即可
<img width="1825" alt="5" src="https://user-images.githubusercontent.com/105948962/171179305-eaf4ee1e-eb91-4e19-8a29-cecdfaf6b15a.png">

