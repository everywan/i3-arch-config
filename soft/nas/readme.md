# NAS
NAS, Network Attached Storage, 网络附属存储

搭建NAS有两种方法
1. 现有的成品方案, 如 群晖.
2. 购买服务器, 安装Linux以及相关软件

nas实现的功能如下
1. 文件存储: 文件的上传与下载
  - 文件安全(可选): 上传下载过程中的安全, 访问的安全, 以及数据可靠性.
2. 外网访问
3. 下载功能: 支持从网络下载到nas
4. 影视功能: 支持通过各种协议直接在 Mobile/PC/TV 上播放, 4k解码(终端/服务器端均可)
5. 服务器(可选): 可以运行一些自己的服务, docker 等

如上功能群晖本身已经支持.

## 实现方案
群晖
1. 文件中心, 支持多平台同步
2. QuickConnect, 支持外网访问局域网.
3. 4k解码等可选功能
4. 功耗低, 但性能弱.

DIY
1. 硬件配置: [nas硬件配置](./hardware.md)
2. 软件安装: [nas软件配置](./soft.md)

## 其他
- [集群配置方案](/setup/readme.md)
- [集群配置-硬件选择](/setup/pc.md)