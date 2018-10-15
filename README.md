2018.10月成功搭好：用搬瓦工搭梯子的教程——小白教程（只需一天）

不知道怎么放图片，但是没关系，没有图片你一样能看懂~


1. 在搬瓦工网站注册购买https://bwh1.net/

      初学者买$19.99/年的即可；

      选Plan的时候注意选择“order KVM”，不要买成了OVZ！！

      接下来，机房地址选择洛杉矶；

      使用折扣码BWH26FXH3HIQ - 优惠6.25%（目前最大的优惠）；优惠码来自搬瓦工中文网：https://www.bwgblog.org/youhuima.html
      

2. 买完了，现在登录，进入"My Services"页面，能够看到你有一个服务器是绿色的Active。现在开始配置后台：

      点击进入“KiwiVM Control Panel”页面，在Main Control页面点击"Stop"按钮，让服务器暂停运行才能安装新系统；

      然后点击左边栏的“Install New OS”，配置系统啦：此处不要配置CentOS7!! 我装的是“Centos 6 x86_64”。一定要装64位系统！
      

3. 现在开始配置Shadowsocks：

      还是左边栏，在KiwiVM Extras下面有一键配置Shadowsocks Server；然鹅我比较悲剧，没有一键配置。但是没关系！

      待在KiwiVM后台页面，在地址栏复制以下网址（不要在新的标签页输入！在后台直接跳转！！）：https://kiwivm.64clouds.com/preloader.php?load=/main-exec.php?mode=extras_shadowsocks 就可以一键配置啦！

      然后你会得到密码和端口，复制下来！
      

4. 测试服务器是否可用：

      先测一下IP是否被封: http://ping.pe/66.112.218.241 全绿说明IP正常。

      再测一下端口是否被封。

5. 下载Shadowsocks或ShadowsocksR！将配置信息输入，就可以登高远眺了！

      PC端：安装Shadowsocks:https://github.com/shadowsocks/shadowsocks-windows/releases

      ios设备：我买了一个￥12元的ShadowRocket，速度挺快。

      安卓设备：直接搜索安装一个shadowsocks。
