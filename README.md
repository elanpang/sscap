﻿<p>
	SSCap是一个Windows下C++版的Shadowsocks客户端. 相比其它的客户端更稳定更快速,不会出现其它版本中常现的接收数据错误.<br />
<br />
2016.03.09 2.1<br />
1, 修正在最新版的libev服务器端下有可能打不开网站的问题.<br />
2, 增加测试所有节点的功能(主界面右键菜单中).<br />
3, 修正在系统托盘菜单中切换节点后托盘图标提示的当前节点仍未改变的BUG.<br />
4, 修正主界面中通过右键菜单禁用一个节点后再启用节点无法启用的BUG.<br />
5, 修正被禁用的节点仍然可以被使用的问题.<br />
6, 修正被禁用的节点在系统托盘右键菜单中仍然可以使用的问题.<br />
7, 修正主界面中的节点被排序后更新状态时会错乱的问题.<br />
<br />
2016.03.06 1.9<br />
1, 修正WIN 10系统下 PAC模式下不能正确代理网站的问题.<br />
2, 增加结束某个节点的所有连接的功能. ( 切换代理后希望将之前代理的连接全断开)<br />
3, 主界面中SS节点信息动态更新时加以颜色区分.<br />
4, 修正按扭禁止时状态不对的BUG<br />
5, 升级时可以选择下载源.<br />
<br />
2016.01.03 1.8<br />
1, 修改主界面连接数不会变动的BUG.<br />
2, 系统托盘菜单添加: 切换全局模式/PAC模式.<br />
3, 系统托盘菜单添加: 更新线上PAC文件功能.<br />
4, 系统托盘菜单添加: 编辑本地PAC文件功能.<br />
5, 加入功能: 增加用户PAC文件, 可以实时将希望通过代理的域名添加到用户PAC文件并立即生效.<br />
6, 一些小bug修改<br />
<br />
2015.12.24 1.7<br />
/////////////////////////////////////////////////////<br />
1, 二维码截图方式修改.<br />
2, 修正SOCKS 5的帐号密码的验证时的BUG.<br />
3, 修正系统代理PAC模式下的BUG: SSCAP绑定了1080外的其它端口,但是系统代理中PAC地址端口仍然是1080.<br />
4, 切换当前代理后,系统托盘中的当前代理信息不会改变.<br />
5, 修改本地SOCKS 5代理端口后,系统设置中的代理端口不会改变.<br />
6, 修改本地SOCKS 5代理端口后,privoxy中转端口未修改.<br />
<br />
2015.12.15 1.6<br />
/////////////////////////////////////////////////////<br />
1, 应网友要求: 增加启动时最小化到系统托盘功能. (请在系统设置中启用此功能)<br />
<br />
2015.12.12 1.5<br />
/////////////////////////////////////////////////////<br />
1, 增加端口被占用时自动搜索端口功能.<br />
<br />
2015.12.08 1.4<br />
/////////////////////////////////////////////////////<br />
1, 增加'复制到'功能,可以将一个SS节点复制到二维码/JSON/SS链接<br />
2, 可以手动修改本地SOCKS监听端口.<br />
3, 可以通过将SSCap拷贝到新目录来实现运行多份SSCap实例.<br />
<br />
2015.11.30 1.3<br />
/////////////////////////////////////////////////////<br />
1, 修正在rc4-md5,salsa20兩種加密方式下的嚴重BUG導至無法工作.<br />
2, 修改系統代理的工作方式.<br />
<br />
2015.11.28 1.2<br />
/////////////////////////////////////////////////////<br />
first issue, Key Features:<br />
1, Support aes-256-cfb/aes-192-cfb/aes-128-cfb,md5,rc-md5,chacha20,salsa20 encryption.<br />
2, Test shadowsocks node in sscap<br />
3, Show speed and traffic of every ss node.<br />
4, support from win xp to win 10 windows os.
</p>
<p>
	<br />
</p>