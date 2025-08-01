## iStore软件包 iStore .run Packages

* 本页面所下载的软件包插件仅适用于x86_64平台的机器。

* 仅适用于KoolCenter iStoreOS 22.03.X的软件包

#### 常用代理软件包 Commonly Used Proxy Packages
|插件名|功能|下载|编译日期|
| :----: | :----: | :----: | :----: |
| [PassWall](https://github.com/xiaorouji/openwrt-passwall) | 科学工具 | [PassWall_25.7.15](https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/PassWall_25.7.15_x86_64_all_sdk_22.03.7.run) |2025-07-16|
| [PassWall2](https://github.com/xiaorouji/openwrt-passwall2) | 科学工具 | [PassWall2_25.7.15](https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/PassWall2_25.7.15_x86_64_all_sdk_22.03.7.run) |2025-07-16|
| [SSR-Plus](https://github.com/fw876/helloworld) | 科学工具 | [SSR-Plus_189](https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/SSR-Plus_189_x86_64_all_sdk_22.03.7.run) |2025-05-12|
| [OpenClash](https://github.com/vernesong/OpenClash) | 科学工具 | [OpenClash_0.46.133](https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/OpenClash_0.46.133+x86_64_core.run) |2025-07-15|
* 不推荐passwall系列和ssr-plus一同安装，因为部分软件包可能存在冲突影响使用
* 如果你在安装此包前尝试通过第三方软件源安装，可能导致意外的错误。推荐你删除所有自行添加的第三方软件源。
* **注意，上述软件包安装，部分依赖依然要通过opkg软件源在线安装。如果安装失败，检查路由器自身的网络情况，特别是旁路由模式下最容易出现网络问题。**
* **再三注意需要路由器自身联网正常**

#### 其它软件包 Other Packages
|插件名|功能|下载|编译日期|
| :----: | :----: | :----: | :----: |
| [AdGuardHome](https://github.com/sirpdboy/sirpdboy-package) | DNS/拦截 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/adguardhome.run) |2024-06-30|
| [MosDNS](https://github.com/sbwml/luci-app-mosdns) | DNS 转发/分流器 | [mosdns_5.3.3-4](https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/mosdns_5.3.3-4_x86_64_luci_1.6.11_all.run) |2025-05-16|
| [UnblockNeteaseMusic](https://github.com/UnblockNeteaseMusic/luci-app-unblockneteasemusic) | 解锁网易云灰色歌曲 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/unblockneteasemusic.run) |2024-12-24|
| KMS | KMS服务器 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/KMS_x86.run) |N/A|
| OpenVPN | OpenVPN客户端 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/OpenVPN_x86.run) |N/A|
| OpenVPN-Server | OpenVPN服务端 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/OpenVPN-Server_x86.run) |N/A|
| NPS | Nps内网穿透 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/NPS_x86.run) |N/A|

#### 如何安装
* 下载后，来到iStore应用商店页面，点击手动安装，点击选择上传或者直接拖放文件
![png](https://cdn.jsdelivr.net/gh/AUK9527/Are-u-ok@master/apps/install.png)

* 对于没有iStore应用商店的OpenWrt也可以使用以下方法。

将 .run 文件上传到路由器上，然后在终端环境执行
```console
sh 包名.run
```
例
```console
sh PassWall_24.11.23_x86_64_all_sdk_22.03.6.run
```
如果文件不在当前路径记得填写路径，下例
```console
sh /tmp/upload/PassWall_24.11.23_x86_64_all_sdk_22.03.6.run
```













