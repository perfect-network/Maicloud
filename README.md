# Maicloud Network
## 1.最新官网地址
https://www.maicloud.ml 

https://maicloud.ml 

http://sub.maicloud.ml/

## 2.使用帮助
### PC

1.  [点击此处](http://pd6jw15xn.bkt.clouddn.com/Shadow5ocksR-4.7.0.7z)下载并解压缩ShadowsocksR-4.x.x-win.7z
    ![image](http://upload-images.jianshu.io/upload_images/5833359-e7410adcf1970021.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2.  运行ShadowsocksR-dotnet4.0.exe
    （XP以及老版win7请使用ShadowsocksR-dotnet2.0.exe）
    这时任务栏会出现小飞机图标
    ![image](http://upload-images.jianshu.io/upload_images/5833359-187d84928000357f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3.  导入配置
  ![pc1.gif](https://upload-images.jianshu.io/upload_images/5833359-e9a1628e41c110aa.gif?imageMogr2/auto-orient/strip)
    方式一：复制SSR链接，右键小飞机，选择剪切板批量导入链接，点击确定保存
    方式二：将二维码图片打开，不要被桌面其他窗口覆盖，右键小飞机，点击二维码扫描

4.  运行方法
    右键小飞机->服务器->选择刚刚导入的链接
    ![image](http://upload-images.jianshu.io/upload_images/5833359-e0cc2af3c8a3b1e7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

    “系统代理模式”选择”PAC”->”代理规则”选择”全局”->取消”负载均衡”前的勾选
    ![pc2.gif](https://upload-images.jianshu.io/upload_images/5833359-ea2df9365ec04fba.gif?imageMogr2/auto-orient/strip)
    
5.  此时小飞机应为绿色，打开[谷歌](https://google.com/)测试

### IOS

1.  下载App
    使用AppStore海外账号，购买Shadowrocket（付费线提供下载账号）

2.  添加配置
    导入链接（推荐）：
    先复制以SSR链接，然后打开ShadowRocket，按照提示导入即可
    如果是二维码：
    进入APP，点击扫码按钮扫描二维码
    手动添加：
    进入APP，点击+号手动添加一条SS或者SSR线路，按照提供的参数填入即可

3.  选择代理模式为自动代理（配置）
    点击运行，VPN权限弹窗中选择Allow（仅初次需要），任务栏出现VPN图标表示成功

4.  此时手机左上角出现VPN标志，打开[谷歌](https://google.com/)测试

### Android

1.  [点击此处下载](https://github.com/shadowsocksrr/shadowsocksr-android/releases/download/3.5.4/shadowsocksr-android-3.5.4.apk)shadowsocksr-release.apk并安装

2.  导入配置
    ![image](http://upload-images.jianshu.io/upload_images/5833359-897c3c156965e89f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

    复制SSR链接，点击左上角shadowsocksR，先删除默认配置，+号中选择[从剪贴板导入] 如果是二维码：
    点击左上角shadowsocksR，+号中选择[扫描二维码] 手动添加：
    点击左上角shadowsocksR，+号中选择[手动设置]，按照提供的参数填入即可

3.  下拉到[路由]选择[仅代理中国大陆无法访问的]或[绕过局域网及中国大陆]，然后点右上角运行
    ![image](http://upload-images.jianshu.io/upload_images/5833359-33c09af6d6e39c31.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4.  打开[谷歌](https://google.com/)测试

### Mac

1.  [点击此处](http://pd6jw15xn.bkt.clouddn.com/ShadowsocksX-NG-R8.dmg)下载ShadowsocksX-NG-R8.dmg并安装

2.  打开程序后，打开Safari，复制SSR链接到Safari地址栏回车即可导入配置
    或者右键小飞机，点击服务器，点击扫描屏幕上的二维码导入

3.  右键程序，勾选PAC模式，点击顶部的运行

4.  打开[谷歌](https://google.com/)测试

### 名词解释

*   PAC模式：
    自动代理国外网站，国内网站访问不受影响。

*   全局模式：
    代理所有的网络连接（包括运行的软件），所以访问国内网站会变慢，建议只在网站实在打不开的时候使用全局模式。

*   代理规则：
    一般使用“大陆白名单”或“绕过局域网或大陆”即可，网站实在打不开就用”全局“
