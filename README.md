luci-app-njitclient
===================

LuCI configuration pages for <a href="https://github.com/liuqun/njit8021xclient/" target="_blank">njit8021xclient</a> (NJIT 802.1X Client)

适用于<a href="https://github.com/liuqun/njit8021xclient" target="_blank">njit8021xclient</a> (NJIT 802.1X Client) 的LuCI网页管理界面，支持设置是否自启动NJIT Client、保存用户配置信息等。

luci-app-njitclient 1.0 编译后的文件：<a href="http://pan.baidu.com/s/1CbPal" target="_blank">http://pan.baidu.com/s/1CbPal</a>

可以通过 opkg install luci-app-njitclient_1.0-1_all.ipk 没有设定依赖包，可以直接安装。
安装后请访问LuCI中的“系统”->“启动项”，并将“njitclient”设置为启用。
