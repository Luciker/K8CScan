<p><span style="font-size: 15px;"><strong><span style="font-size: 18px;">前言:</span><br /></strong>无论内网还是外网渗透信息收集都是非常关键，信息收集越多越准确渗透的成功率就越高<br />但成功率还受到漏洞影响，漏洞受时效性影响，对于大型内网扫描速度直接影响着成功率<br />漏洞时效性1-2天，扫描内网或外网需1周时间，是否会因此错过很多或许可成功的漏洞？<br />对于那些拥有几百上千域名的大站来说，你发现越快成功率就越高，慢管理员就打补丁了<br />因此我们需要一个支持批量C段/B段甚至A段的扫描器，添加自定义模块快速检测新出漏洞<br /></span></p>
<p><span style="font-size: 18px;"><strong>Cscan</strong></span><span style="font-size: 15px;"><span class="flex-auto mb-2"><span class="text-gray-dark mr-2"><span style="font-size: 18px;"><strong>简介:</strong></span><br /><span style="font-size: 14px;">何为自定义扫描器？其实也是插件化，但Cscan不需要编程同样可实现自定义功能，这比单纯插件化更容易实现插件功能</span><br /><span style="font-size: 14px;">Cscan旨在为用户提供一个高度灵活、简单易用、多线程、多网段的插件化扫描框架，减少大量重复性工作提高工作效率</span><br /><span style="font-size: 14px;">3.3及以上版本分为检测存活和不检测存活主机模式 程序采用多线程批量扫描大型内网IP段C段存活主机(支持上万个C段)</span><br /><span style="font-size: 14px;">插件含C段旁注扫描、子域名扫描、Ftp密码爆破、Mysql密码爆、系统密码爆破、存活主机扫描、Web信息探测、端口扫描</span><br /><span style="font-size: 14px;">支持调用任意外部程序或脚本，支持自定义模块，当然也可用于外网扫描（如子域名、C段旁注、FTP破、MYSQL爆破等）</span><br /><br /><span style="font-size: 18px;"><strong>使用场景：</strong></span></span></span></span></p>
<p><span style="font-size: 15px;"><span class="flex-auto mb-2"><span class="text-gray-dark mr-2"><span style="font-size: 14px;">企业批量漏洞检测，比方说新出了一个漏洞POC，只需配置Cscan.ini即可批量调用POC测试企业内部或外部站点漏洞检测<br />红队可快速找到对应漏洞进行利用，蓝队也可快速找到对应漏洞并修复。无需每次暴出漏洞都去写个批量检测或利用程序<br />当然懂编程的可使用C#编译(EXE或DLL）、Powershell脚本、Delphi编译的DLL、VC编译的DLL等插件供程序动态调用。</span></span></span></span></p>
<p><span style="font-size: 18px;"><strong>主程序功能：</strong></span></p>
<p><span style="font-size: 18px;"><span style="font-size: 15px;"><span style="font-size: 15px;"><span style="font-size: 15px;"><span style="font-size: 15px;">1.支持指定IP扫描<br />2.支持指定C段扫描(ip/24)<br />3.支持指定B段扫描(ip/16)<br />4.支持指定A段扫描(ip/8)<br />5.支持指定URL扫描<br />6.支持批量IP扫描(ip.txt)<br />7.支持批量C段扫描(ip24.txt)<br />8.支持批量B段扫描(ip16.txt)<br />9.支持批量URL扫描(url.txt)<br />10.支持批量字符串列表(str.txt)<br />11.支持指定范围C段扫描<br />12.支持调用自定义程序(系统命令或第三方程序即任意语言开发的程序或脚本)<br />13.支持自定义模块(支持多种语言编写的DLL、C#的EXE以及PowerShell脚本)</span></span></span></span></span></p>
<p><span style="font-size: 18px;"><strong>程序&amp;插件:</strong></span><span style="font-size: 15px;">[+] 主程序&nbsp;&nbsp; K8Cscan 4.0.rar 大型内网渗透扫描器<br />[+] 模块插件 K8Cscan Moudle WeblogicScan &amp; Exploit.rar Weblogic漏洞扫描&amp;GetShell<br />[+] 模块插件 K8Cscan Moudle OSScan.rar 系统版本探测<br />[+] 模块插件 K8Cscan Moudle FtpScan.rar Ftp密码扫描<br />[+] 模块插件 K8Cscan Moudle MysqlScan.rar Mysql密码扫描<br />[+] 模块插件 K8Cscan Moudle OnlinePC.rar 存活主机扫描<br />[+] 模块插件 K8Cscan Moudle WebBanner.rar 内网Web信息扫描<br />[+] 模块插件 K8Cscan Moudle WmiScan.rar Wmi扫描Win系统密码<br />[+] 独立工具 K8Cscan for SameWeb.rar C段旁站扫描工具<br />[+] 独立工具 K8Cscan for SubDomain.rar 子域名扫描工具<br />[+] Demo源码 支持自定义插件、EXE、脚本等（附C#/VC/Delphi/Python源码)<br />[+] 模块插件 K8Cscan Moudle PortScan.cs&nbsp; 端口扫描插件成品&amp;源码<br />[+] 模块插件 K8Cscan Moudle Host2IP.rar 域名解析/主机名转IP<br />[+] 模块插件 C# netscan 存活主机 &amp; Web信息插件成品&amp;源码<br />[+] 模块插件 K8Cscan Moudle Base64Enc(C#EXE) Base64加密<br />[+] 模块插件 K8Cscan Moudle Base64Dec(C#EXE) Base64解密<br />[+] 模块插件 K8Cscan Moudle HexDec(PSH)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Hex解密<br />[+] 模块插件 K8Cscan Moudle Base64Dec(PSH)&nbsp;&nbsp;&nbsp;&nbsp; Base64解密</span></p>
<p>&nbsp;</p>
<p><span style="font-size: 16px;"><strong>4.0用法:</strong></span><br />检测存活(目标内外网均可使用)<br />cscan (直接运行)<br />cscan 192.168.1.108 (单个IP)<br />cscan 192.168.1.108/24 (C段)<br />cscan 192.168.1.108/16 (B段)<br />cscan 192.168.1.108/8&nbsp; (A段)<br />cscan 192.168.1.0 192.168.5.0 (C段范围)<br />不存测存活(代理或禁ICMP时用)<br />cscan nocheck (直接运行)<br />cscan nocheck 192.168.1.108 (单个IP)<br />cscan nocheck 192.168.1.108/24 (C段)<br />cscan nocheck 192.168.1.108/16 (B段)<br />cscan nocheck 192.168.1.108/8&nbsp; (A段)<br />cscan nocheck 192.168.1.0 192.168.5.0 (C段范围)<br /><br />支持URL或IP端口参数<br />cscan.exe http://192.168.1.106:7001<br />cscan.exe 192.168.1.106:7001</p>
<p>PS:直接运行默认扫描当前机器C段，批量C段(ip24.txt)，批量B段(ip16.txt),批量A段(不支持)<br />&nbsp;&nbsp; 批量IP(ip.txt),批量URL使用url.txt,调用优先级ip24.txt&gt;&gt;ip16.txt&gt;&gt;ip.txt&gt;&gt;str.txt&gt;&gt;url.txt，<br />&nbsp;&nbsp; 文件名中的20、30、35、40、45等为.NET版本，根据环境选择,主程序与DLL均需对应，<br />&nbsp;&nbsp; 理论上动态加载的只要EXE可运行即可，插件是DLL还是EXE还是PSH都不会有影响<br />&nbsp;&nbsp; 建议：为了兼容C#的exe或dll建议3.5，PowerShell建议2.0即Win7自带版本编写<br /><br /><strong><span style="font-size: 16px;">演示教程:</span></strong></p>
<p><strong><span style="font-size: 16px;"><strong><span style="font-size: 16px;"><strong><span style="font-size: 16px;">教程15:</span></strong></span></strong>K8Cscan4.0之Base64/HEX密码批量加密解密<br /></span></strong><a href="https://www.cnblogs.com/k8gege/p/11329574.html" target="_blank"><span style="font-size: 16px;">https://www.cnblogs.com/k8gege/p/11329574.html</span></a><strong><span style="font-size: 16px;"><br /><img src="https://img2018.cnblogs.com/blog/1463611/201908/1463611-20190809212710385-1784458315.png" alt="" /><br /><strong><span style="font-size: 16px;">教程14:</span></strong>K8Cscan插件之Host2IP(批量域名解析/主机名转IP)<br /></span></strong><a href="https://www.cnblogs.com/k8gege/p/11324741.html" target="_blank"><span style="font-size: 16px;">https://www.cnblogs.com/k8gege/p/11324741.html</span></a></p>
<p><span style="font-size: 16px;"><img src="https://img2018.cnblogs.com/blog/1463611/201908/1463611-20190809212600395-520529138.png" alt="" /></span></p>
<p>&nbsp;</p>
<p><strong><span style="font-size: 16px;">教程13:K8Cscan调用外部程序例子(Win/Linux批量上控)</span></strong></p>
<p><a href="https://www.cnblogs.com/k8gege/p/11161242.html" target="_blank">https://www.cnblogs.com/k8gege/p/11161242.html</a></p>
<p><strong><span style="font-size: 16px;">教程12: Python版主要用于Linux,当然也可用于Win<br /></span></strong></p>
<p><a href="https://www.cnblogs.com/k8gege/p/10852832.html" target="_blank">https://www.cnblogs.com/k8gege/p/10852832.html</a></p>
<p><img src="https://img2018.cnblogs.com/blog/1463611/201907/1463611-20190710223325301-554278351.png" alt="" /></p>
<p><strong><span style="font-size: 16px;">教程11: GUI版方便本地使用(被调用exe或dll请使用.net 2.0版本)</span></strong></p>
<p><a href="https://github.com/k8gege/K8CScan/blob/master/CscanGui.exe" target="_blank">https://github.com/k8gege/K8CScan/blob/master/CscanGui.exe</a></p>
<p><strong><span style="font-size: 16px;"><img src="https://img2018.cnblogs.com/blog/1463611/201905/1463611-20190512173558994-1162950396.png" alt="" /></span></strong></p>
<p>&nbsp;</p>
<p><strong><span style="font-size: 16px;">教程10: 配置Cscan.ini批量Zimbra远程代码执行漏洞利用</span></strong></p>
<p><a href="https://www.cnblogs.com/k8gege/p/10822908.html" target="_blank"><span style="font-size: 16px;">https://www.cnblogs.com/k8gege/p/10822908.html</span></a></p>
<p><strong><span style="font-size: 16px;"><img src="https://img2018.cnblogs.com/blog/1463611/201905/1463611-20190506232757516-1871320882.png" alt="" /></span></strong></p>
<p><span style="font-size: 16px;"><strong>插件9: Weblogic漏洞扫描&amp;GetShell Exploit<strong><br /></strong></strong></span></p>
<p><span style="font-size: 16px;"><a href="https://www.cnblogs.com/k8gege/p/10779728.html" target="_blank">https://www.cnblogs.com/k8gege/p/10779728.html</a></span></p>
<p><img src="https://img2018.cnblogs.com/blog/1463611/201904/1463611-20190427184635043-2096938770.png" alt="" /></p>
<p><strong><span style="font-size: 16px;"><span style="font-size: 16px;"><strong>插件8: Cisco思科设备扫描(IP、设备型号、主机名、Boot、硬件版本)</strong></span></span></strong></p>
<p><a href="https://www.cnblogs.com/k8gege/p/10679491.html" target="_blank"><span style="font-size: 16px;"><span style="font-size: 16px;">https://www.cnblogs.com/k8gege/p/10679491.html</span></span></a></p>
<p><strong><span style="font-size: 16px;"><span style="font-size: 16px;"><strong><img src="https://img2018.cnblogs.com/blog/1463611/201904/1463611-20190409202556554-1537901617.png" alt="" /></strong></span></span></strong></p>
<p>&nbsp;</p>
<p><strong><span style="font-size: 16px;">主程序: 3.3指定C段范围扫描(暂不支持B段,需要可自行写个程序传参调用即可)</span></strong></p>
<p><strong><span style="font-size: 16px;"><img src="https://img2018.cnblogs.com/blog/1463611/201904/1463611-20190409200207667-129491964.png" alt="" /></span></strong></p>
<p><span style="font-size: 16px;"><strong>主程序: 3.2以上版本独立EXE默认扫描机器所处内网C段存活机器</strong></span></p>
<p><strong><span style="font-size: 15px;"><img src="https://img2018.cnblogs.com/blog/1463611/201904/1463611-20190407010530040-1494779713.png" alt="" /></span></strong></p>
<p><span style="font-size: 16px;"><strong>插件7: 操作系统版本探测</strong></span></p>
<p><span style="font-size: 16px;">URL: <a href="https://www.cnblogs.com/k8gege/p/10673707.html" target="_blank">https://www.cnblogs.com/k8gege/p/10673707.html</a></span></p>
<p><span style="font-size: 16px;"><img src="https://img2018.cnblogs.com/blog/1463611/201904/1463611-20190408214856413-1373122600.png" alt="" /></span></p>
<p><span style="font-size: 16px;"><strong>插件6: Windows密码爆破<br /></strong></span></p>
<div><span style="font-size: 16px;"><strong><a href="https://www.cnblogs.com/k8gege/p/10650659.html%20" target="_blank">https://www.cnblogs.com/k8gege/p/10650659.html </a></strong></span></div>
<div><img src="https://img2018.cnblogs.com/blog/1463611/201904/1463611-20190403183752920-1000441903.png" alt="" /></div>
<div>
<div>
<div><span style="font-size: 16px;"><strong> 插件5:&nbsp; Mysql密码爆破</strong><br /><a href="https://www.cnblogs.com/k8gege/p/10650642.html%20" target="_blank"><span style="font-size: 16px;"><strong>https://www.cnblogs.com/k8gege/p/10650642.html
</strong></span></a></span></div>




































































</div>
<p><img src="https://img2018.cnblogs.com/blog/1463611/201904/1463611-20190403183709383-1787739211.png" alt="" /></p>
<p><strong><span style="font-size: 16px;">插件4: FTP密码爆破</span></strong></p>
<div><strong><span style="font-size: 16px;"><a href="https://www.cnblogs.com/k8gege/p/10650630.html%20" target="_blank">https://www.cnblogs.com/k8gege/p/10650630.html </a></span></strong></div>
<div><img src="https://img2018.cnblogs.com/blog/1463611/201904/1463611-20190403183627098-963540691.png" alt="" /></div>




















































</div>
<p><span style="font-size: 16px;"><strong>插件3: C段旁站扫描插件、子域名扫描插件</strong></span></p>
<p><span style="font-size: 16px;">&nbsp;<a href="https://www.cnblogs.com/k8gege/p/10626465.html" target="_blank">https://www.cnblogs.com/k8gege/p/10626465.html</a></span></p>
<p><img src="https://img2018.cnblogs.com/blog/1463611/201903/1463611-20190330123634041-483117211.png" alt="" /></p>
<p><strong><span style="font-size: 16px;">插件2: 内网WEB主机探测获取Banner、标题信息</span></strong></p>
<p>DLL源码 <a href="https://www.cnblogs.com/k8gege/p/10519512.html" target="_blank">https://www.cnblogs.com/k8gege/p/10519512.html</a></p>
<p>已编译：<a href="https://www.cnblogs.com/k8gege/p/10650610.html" target="_blank">https://www.cnblogs.com/k8gege/p/10650610.html</a></p>
<p><img src="https://img2018.cnblogs.com/blog/1463611/201903/1463611-20190312200408983-358773201.jpg" alt="" /></p>
<p><span style="font-size: 16px;"><strong>插件1:调用外部程序</strong></span></p>
<p><span style="font-size: 16px;"><strong>0x001 调用系统ping命令(不是非要完整路径)</strong></span></p>
<p><span style="font-size: 16px;"><strong><img src="https://img2018.cnblogs.com/blog/1463611/201904/1463611-20190408220224539-1459196056.png" alt="" /></strong></span></p>
<p><span style="font-size: 16px;"><strong>0x002 配置Cscan.ini 调用S扫描器扫描C段主机开放端口</strong></span></p>
<p><img src="https://img2018.cnblogs.com/blog/1463611/201903/1463611-20190312200210710-22698312.png" alt="" /></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong><span style="font-size: 18px;">更新历史</span> </strong></p>
<p>&nbsp;</p>
<p><span style="font-size: 16px;"><span style="font-size: 15px;"><span style="font-size: 16px;"><strong>4.0 暂未更新</strong> </span><br />若更新可能会将相关插件集成到主程序<br /><br /><span style="font-size: 16px;"><strong>3.5 支持IP列表、C段列表</strong></span><br />ipc.txt C段列表<br />ip.txt&nbsp; IP列表<br />优先级 ipc.txt &gt; ip.txt &gt; 自动获取IP段<br /><br /><span style="font-size: 16px;"><strong>3.4 支持指定C段</strong></span><br />cscan 192.168.1.108/24<br />cscan nocheck 192.168.1.108/24<br /><br /><span style="font-size: 16px;"><strong>3.3 新增nocheck参数不检测存活PC</strong></span> <br />cscan nocheck<br />cscan nocheck 192.168.1.108<br />修复获取当前IP段重扫的问题</span></span></p>
<p>&nbsp;</p>
<p><strong><span style="font-size: 16px;">3.2 独立EXE默认扫描C段存活主机<br /></span></strong><span style="font-size: 16px;"><span style="font-size: 15px;">即无cscan.ini或相关DLL时，程序相当于Cping，自动扫描当前机器所处C段存活主机。<span style="font-size: 16px;"><br /><span style="font-size: 15px;">端口扫描插件例子源码</span></span></span></span></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong><span style="font-size: 16px;">3.1 支持单个IP扫描</span></strong><br />例子：Cscan.exe 192.11.22.8</p>
<p><br /><span style="font-size: 16px;"><strong>3.0 DLL调用（支持C# DLL \ VC DLL \Delphi DLL）</strong></span><br /><br />Demo<br />C# DLL 名称必须为netscan.dll &nbsp;&nbsp; &nbsp; （源码例子为获取IP对应机器名，其它功能自己写）<br />VC DLL 名称必须为vcscan.dll &nbsp;&nbsp;&nbsp; &nbsp; （源码例子为打印在线主机IP，其它功能自己写）<br />Delphi DLL 名称必须为descan.dll&nbsp; （源码例子为打印在线主机IP，其它功能自己写）<br /><br />EXE (非scan.exe或多参数需配置cscan.ini)<br />scan.py&nbsp;&nbsp; 使用pyinstaller打包成exe（源码例子为打印在线主机IP，其它功能自己写）<br />scan.cs&nbsp; （源码例子为打印在线主机IP，其它功能自己写）<br />scan.cpp （源码例子为打印在线主机IP，其它功能自己写）<br /><br /><span style="font-size: 16px;">调用优先级</span><br /><span style="font-size: 16px;">为 netscan.dll &gt;&gt; vcscan.dll &gt;&gt; descan.dll &gt;&gt; Cscan.ini &gt;&gt; scan.exe 同目录下同时含以下多个文件时，仅会调用一个。</span><br /><span style="font-size: 16px;">Cscan.ini 支持exe自定义参数，其它均只支持IP。</span><br /><br /><span style="font-size: 16px;"><strong>注意：</strong></span></p>
<p><span style="font-size: 16px;"><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>调用EXE可能会在运行机器上产生30个exe进程,所以建议将功能写成DLL比较好。</span><br /><span style="font-size: 16px;">&nbsp;&nbsp; &nbsp;&nbsp; 不懂代码的或实在无法实现功能的可使用exe或配置cscan.ini文件（如批量ping，WMI批量种马等）</span><br /><br />&nbsp;&nbsp; &nbsp; &nbsp;<br /><span style="font-size: 16px;"><strong>其它：</strong></span></p>
<p><span style="font-size: 16px;"><strong>&nbsp;&nbsp;&nbsp;&nbsp; </strong></span>由于python编译后的DLL还是需要python相关依赖实在太大，就不提供DLL例子了,不会以上3种语言就exe吧。<br />&nbsp;&nbsp; &nbsp;&nbsp; Python、Perl或其它类似脚本可配置Cscan.ini当成EXE来调用,如python.exe scan.py 192.168.1.1<br />&nbsp;&nbsp; &nbsp;&nbsp; 但你并不能保证目标一定安装有对应python依赖包，所以还是得编译成EXE比较好，<br />&nbsp;&nbsp; &nbsp;&nbsp; 如果不编译也会产生30个Python.exe进程，因为py脚本是靠python.exe来执行的。<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Bat也会产生一堆被执行系统命令的EXE进程，最佳方案把相关命令写成一个EXE。<br />&nbsp;&nbsp; &nbsp;&nbsp; 最主要是多线程不好同时监视BAT调用的命令是否执行完成，无法准确获取回显。<br />&nbsp;&nbsp; &nbsp; &nbsp;<br />&nbsp;&nbsp; &nbsp; &nbsp;<br />build 20190312 by K8哥哥<br /><br />=======================================================================<br /><br /></p>
<p><span style="font-size: 16px; color: #ff00ff;"><strong>下载:</strong></span></p>
<p><a href="https://github.com/k8gege/K8CScan" target="_blank">https://github.com/k8gege/K8CScan</a><br /><a href="https://github.com/k8gege/K8tools/blob/master/K8Cscan4.0.rar" target="_blank">https://github.com/k8gege/K8tools/blob/master/K8Cscan4.0.rar</a></p>
