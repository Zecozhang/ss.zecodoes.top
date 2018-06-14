# Windows上最“简单”的Shadowsocks使用教程 #
>Shadowsocks是一个安全的socks5代理，旨在保护您的互联网流量。

>但据不可靠消息透露，中国大陆当局及受管控的运营商已经可以嗅探道Socks5协议

>更高级别的混淆请考虑ShadowsocksR

首先去Github下载一份Windows版的SS，然后解压到你的工作文件夹。

启动它，右键托盘图标在服务器选单中通过扫描二维码的方式添加您的服务器。

## 如果您使用的是Chrome浏览器 ##
1. 在”`控制面板-Internet选项`“中，选中“`连接`”选项卡，在选项卡中打开“`局域网设置(L)`”
2. 勾选“`为 LAN 使用代理服务器(这些设置不用于拨号或 VPN 连接)(X)`”
3. 在“`地址(E)`”中填入`127.0.0.1`，`端口(T)`中填入您在Shadowsocks客户端中设置的本地端口（一般是1080）
4. 启动Google Chrome浏览器，登陆您的[Chrome网上应用店](https://chrome.google.com/webstore/category/extensions?hl=zh-CN)
5. 安装Proxy SwitchyOmega，或[点此进行安装](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif?hl=zh-CN)
7. 回到”`控制面板-Internet选项`“中，选中“`连接`”选项卡，在选项卡中打开“`局域网设置(L)`”
8.  取消勾选“`为 LAN 使用代理服务器(这些设置不用于拨号或 VPN 连接)(X)`”
6. 安装Proxy SwitchyOmega后，启动它，通常它在浏览器地址栏左侧或在附加菜单内，您也可以通过在Chrome的地址栏输入`chrome-extension://padekgcemlokbadohgkifijomclgjgif/options.html`来访问
9. 在Proxy SwitchyOmega新建一个情景模式，或修改一个情景模式
10. 代理协议选择HTTP或sock5，代理服务器填写`127.0.0.1`，代理端口填写`1080`，单击应用选项
11. 在左侧单击自动切换或auto switch
12. 在规则列表设置中选中AutoProxy，网址填`https://raw.githubusercontent.com/gfwlist/gfwlist/master/gfwlist.txt`
13. 点击立即更新情景模式
14. 在上方勾选默认情景模式，右侧下拉菜单选择您刚刚手动新建的情景模式
15. 点击应用选项

## 如果您需要针对个别应用的代理 ##
参考Proxifier的用法，在此不再赘述。

# Enjoy it! #


