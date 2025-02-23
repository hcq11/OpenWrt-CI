## 自定义插件主题代码
```yaml
- name: 自定义插件主题。
        run: |
          cd package
          mkdir openwrt-packages
          cd openwrt-packages
          git clone https://github.com/openwrt-develop/luci-theme-atmaterial.git
          git clone https://github.com/immortalwrt/luci-app-koolproxyR.git
          git clone https://github.com/rosywrt/luci-theme-rosy
```

## LuCi Applications软件包说明
```
LuCI —> Applications —> luci-app-accesscontrol #访问时间控制
LuCI —> Applications —> luci-app-adblock #ADB广告过滤
LuCI —> Applications —> luci-app-adbyby-plus #广告屏蔽大师Plus +
LuCI —> Applications —> luci-app-adbyby #广告过滤大师（已弃）
LuCI —> Applications —> luci-app-adkill #广告过滤（已弃）
LuCI —> Applications —> luci-app-advanced-reboot #Linksys高级重启
LuCI —> Applications —> luci-app-ahcp #支持AHCPd
LuCI —> Applications —> luci-app-aliddns #阿里DDNS客户端
LuCI —> Applications —> luci-app-amule #aMule下载工具
LuCI —> Applications —> luci-app-aria2 # Aria2下载工具
LuCI —> Applications —> luci-app-arpbind #IP/MAC绑定
LuCI —> Applications —> luci-app-asterisk #支持Asterisk电话服务器
LuCI —> Applications —> luci-app-attendedsysupgrade #固件更新升级相关
LuCI —> Applications —> luci-app-autoreboot #支持计划重启
LuCI —> Applications —> luci-app-bcp38 #BCP38网络入口过滤(不确定)
LuCI —> Applications —> luci-app-bird4 #Bird 4(未知)
LuCI —> Applications —> luci-app-bird6 #Bird 6(未知)
LuCI —> Applications —> luci-app-bmx6 #BMX6路由协议
LuCI —> Applications —> luci-app-bmx7 #BMX7路由协议
LuCI —> Applications —> luci-app-caldav #联系人
LuCI —> Applications —> luci-app-cjdns #加密IPV6网络相关
LuCI —> Applications —> luci-app-clamav #ClamAV杀毒软件
LuCI —> Applications —> luci-app-commands #Shell命令模块
LuCI —> Applications —> luci-app-cshark #CloudShark捕获工具
LuCI —> Applications —> luci-app-ddns #动态域名 DNS
LuCI —> Applications —> luci-app-diag-core #core诊断工具
LuCI —> Applications —> luci-app-dnscrypt-proxy #DNSCrypt解决DNS污染
LuCI —> Applications —> luci-app-dnscrypt-dnsforwarder #DNSForwarder防DNS污染
LuCI —> Applications —> luci-app-dnspod #DNSPod
LuCI —> Applications —> luci-app-dump1090 #民航无线频率(不确定)
LuCI —> Applications —> luci-app-dynapoint #DynaPoint(未知)
LuCI —> Applications —> luci-app-e2guardian #Web内容过滤器
LuCI —> Applications —> luci-app-filetransfer #文件传输
LuCI —> Applications —> luci-app-firewall #添加防火墙
LuCI —> Applications —> luci-app-flowoffload #Turbo ACC FLOW转发加速
LuCI —> Applications —> luci-app-freifunk-diagnostics #freifunk组件 诊断(未知)
LuCI —> Applications —> luci-app-freifunk-policyrouting #freifunk组件 策略路由(未知)
LuCI —> Applications —> luci-app-freifunk-widgets #freifunk组件 索引(未知)
LuCI —> Applications —> luci-app-frpc #内网穿透 Frp
LuCI —> Applications —> luci-app-fwknopd #Firewall Knock Operator服务器
LuCI —> Applications —> luci-app-guest-wifi #WiFi访客网络
LuCI —> Applications —> luci-app-hd-idle #硬盘休眠
LuCI —> Applications —> luci-app-hnet #Homenet Status家庭网络控制协议
LuCI —> Applications —> luci-app-kooldns #virtual服务器 ddns替代方案（已弃）
LuCI —> Applications —> luci-app-koolproxy #KP去广告（已弃）
LuCI —> Applications —> luci-app-lxc #LXC容器管理
LuCI —> Applications —> luci-app-meshwizard #网络设置向导
LuCI —> Applications —> luci-app-minidlna #完全兼容DLNA / UPnP-AV客户端的服务器软件
LuCI —> Applications —> luci-app-mjpg-streamer #兼容Linux-UVC的摄像头程序
LuCI —> Applications —> luci-app-mmc-over-gpio #添加SD卡操作界面（已弃）
LuCI —> Applications —> luci-app-multiwan #多拨虚拟网卡（已弃）
LuCI —> Applications —> luci-app-mwan #MWAN负载均衡
LuCI —> Applications —> luci-app-mwan3 #MWAN3分流助手
LuCI —> Applications —> luci-app-n2n_v2 #N2N内网穿透 N2N v2 virtual服务
LuCI —> Applications —> luci-app-nft-qos #QOS流控 Nftables版（已弃）
LuCI —> Applications —> luci-app-ngrokc #Ngrok 内网穿透（已弃）
LuCI —> Applications —> luci-app-nlbwmon #网络带宽监视器
LuCI —> Applications —> luci-app-noddos #NodDOS Clients 阻止DDoS攻击
LuCI —> Applications —> luci-app-ntpc #NTP时间同步服务器
LuCI —> Applications —> luci-app-ocserv #OpenConnect virtual服务
LuCI —> Applications —> luci-app-olsr #OLSR配置和状态模块
LuCI —> Applications —> luci-app-olsr-services #OLSR服务器
LuCI —> Applications —> luci-app-olsr-viz #OLSR可视化
LuCI —> Applications —> luci-app-ocserv #OpenConnect virtual服务（已弃）
LuCI —> Applications —> luci-app-openvirtual #Openvirtual客户端
LuCI —> Applications —> luci-app-openvirtual-server #易于使用的Openvirtual服务器 Web-UI
LuCI —> Applications —> luci-app-oscam #OSCAM服务器（已弃）
LuCI —> Applications —> luci-app-p910nd #打印服务器模块
LuCI —> Applications —> luci-app-pagekitee #Pagekite内网穿透客户端
LuCI —> Applications —> luci-app-polipo #Polipo代理(是一个小型且快速的网页缓存代理)
LuCI —> Applications —> luci-app-pppoe-relay #PPPoE NAT穿透 点对点协议(PPP)
LuCI —> Applications —> luci-app-p p t p-server #virtual服务器 p p t p
LuCI —> Applications —> luci-app-privoxy #Privoxy网络代理(带过滤无缓存)
LuCI —> Applications —> luci-app-qos #流量服务质量(QoS)流控
LuCI —> Applications —> luci-app-radicale #CalDAV/CardDAV同步工具
LuCI —> Applications —> luci-app-ramfree #释放内存
LuCI —> Applications —> luci-app-rp-pppoe-server #Roaring Penguin PPPoE Server 服务器
LuCI —> Applications —> luci-app-samba #网络共享(Samba)
LuCI —> Applications —> luci-app-samba4 #网络共享(Samba4)
LuCI —> Applications —> luci-app-sfe #Turbo ACC网络加速(开启Fast Path转发加速)
LuCI —> Applications —> luci-app-s-s #SS兲朝上网（已弃）
LuCI —> Applications —> luci-app-s-s-libes #SS-libev服务端
LuCI —> Applications —> luci-app-shairplay #支持AirPlay功能
LuCI —> Applications —> luci-app-siitwizard #SIIT配置向导 SIIT-Wizzard
LuCI —> Applications —> luci-app-simple-adblock #简单的广告拦截
LuCI —> Applications —> luci-app-simple-softethervirtual #SoftEther virtual服务器 NAT穿透（已弃）
LuCI —> Applications —> luci-app-splash #Client-Splash是无线MESH网络的一个热点认证系统
LuCI —> Applications —> luci-app-sqm #流量智能队列管理(QOS)
LuCI —> Applications —> luci-app-squid #Squid代理服务器
——————————————————————————————-
LuCI —> Applications —> luci-app-S-S R-plus #S-S R兲朝上网Plus+
LuCI —> Applications —> luci-app-S-S R-plus —> Include s-s New Versiong #新SS代理
LuCI —> Applications —> luci-app-S-S R-plus —> Include V2ray #V2Ray透明代理
LuCI —> Applications —> luci-app-S-S R-plus —> Include Kcptun #Kcptun代理
LuCI —> Applications —> luci-app-S-S R-plus —> Include s-sR Server #S-S R客户端
LuCI —> Applications —> luci-app-S-S R-plus —> Include s-sR Socks and Tunnel #S-S R代理
——————————————————————————————-
LuCI —> Applications —> luci-app-S-S R-pro #S-S R-Pro
LuCI —> Applications —> luci-app-S-S Rserver-python #s-sR Python服务器
LuCI —> Applications —> luci-app-statistics #流量监控工具
LuCI —> Applications —> luci-app-syncdial #多拨虚拟网卡(原macvlan)
LuCI —> Applications —> luci-app-tinyproxy #Tinyproxy是 HTTP(S)代理服务器
LuCI —> Applications —> luci-app-transmission #BT下载工具
LuCI —> Applications —> luci-app-travelmate #旅行路由器
LuCI —> Applications —> luci-app-ttyd #网页终端命令行
LuCI —> Applications —> luci-app-udpxy #udpxy做组播服务器
LuCI —> Applications —> luci-app-uhttpd #uHTTPd Web服务器
LuCI —> Applications —> luci-app-unbound #Unbound DNS解析器
LuCI —> Applications —> luci-app-upnp #通用即插即用UPnP(端口自动转发)
LuCI —> Applications —> luci-app-usb-printer #USB 打印服务器
LuCI —> Applications —> luci-app-v2ray-pro #V2Ray透明代理
LuCI —> Applications —> luci-app-vlmcsd #KMS服务器设置
LuCI —> Applications —> luci-app-vnstat #vnStat网络监控(图表)
LuCI —> Applications —> luci-app-virtualbypass #virtual BypassWebUI 绕过virtual设置
LuCI —> Applications —> luci-app-vsftpd #FTP服务器
LuCI —> Applications —> luci-app-watchcat #断网检测功能与定时重启
LuCI —> Applications —> luci-app-webadmin #Web管理页面设置
LuCI —> Applications —> luci-app-webshell #网页命令行终端（已弃）
LuCI —> Applications —> luci-app-wifischedule #WiFi 计划
LuCI —> Applications —> luci-app-wireguard #virtual**服务器 WireGuard状态
LuCI —> Applications —> luci-app-wireless-regdb #WiFi无线
LuCI —> Applications —> luci-app-wol #WOL网络唤醒
LuCI —> Applications —> luci-app-wrtbwmon #实时流量监测
LuCI —> Applications —> luci-app-xlnetacc #迅雷快鸟
LuCI —> Applications —> luci-app-zerotier #ZeroTier内网穿透
```
