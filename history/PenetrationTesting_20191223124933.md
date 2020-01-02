# 所有收集类项目:
- [收集的所有开源工具](https://github.com/alphaSeclab/sec-tool-list): 超过18K, 包括Markdown和Json两种格式
- [逆向资源](https://github.com/alphaSeclab/awesome-reverse-engineering): IDA/Ghidra/x64dbg/OllDbg/WinDBG/CuckooSandbox/Radare2/BinaryNinja/DynamoRIO/IntelPin/Frida/QEMU/Android安全/iOS安全/Window安全/Linux安全/macOS安全/游戏Hacking/Bootkit/Rootkit/Angr/Shellcode/进程注入/代码注入/DLL注入/WSL/Sysmon/...
- [网络相关的安全资源](https://github.com/alphaSeclab/awesome-network-stuff): 代理/GFW/反向代理/隧道/VPN/Tor/I2P，以及中间人/PortKnocking/嗅探/网络分析/网络诊断等
- [攻击性网络安全资源](https://github.com/alphaSeclab/awesome-cyber-security): 漏洞/渗透/物联网安全/数据渗透/Metasploit/BurpSuite/KaliLinux/C&C/OWASP/免杀/CobaltStrike/侦查/OSINT/社工/密码/凭证/威胁狩猎/Payload/WifiHacking/无线攻击/后渗透/提权/UAC绕过/...


# PenetrationTesting


[English Version](https://github.com/alphaSeclab/awesome-cyber-security/blob/master/Readme_en.md)

Github的Readme显示不会超过4000行，而此Repo添加的工具和文章近万行，默认显示不全。当前页面是减配版：工具星数少于200且500天内没更新的不在此文档中显示。

点击这里查看完整版：[中文-完整版](https://github.com/alphaSeclab/awesome-cyber-security/blob/master/Readme_full.md)


# 目录
- [新添加的](#94ca60d12e210fdd7fd9e387339b293e)
    - [工具](#9eee96404f868f372a6cbc6769ccb7f8)
        - [(1103) 新添加的](#31185b925d5152c7469b963809ceb22d)
        - [未分类](#f34b4da04f2a77a185729b5af752efc5)
        - [新添加1](#b9dc08e7e118fc7af41df5e0ef9ddc3c)
        - [新添加2](#efb2cfb167e34b03243547cfb3a662ac)
        - [未分类3](#f04dd1be8e552b074dde7cb33ae6c84c)
        - [未分类4](#cbb37de8d70e314ce905d78c566ef384)
        - [未分类5](#bb7173c3a2ea52d046c8abe3c57e3291)
        - [(1) 其他](#f7654997cf8b691617b89c5e523a942f)
    - [(3) 古老的&&有新的替代版本的](#d5e869a870d6e2c14911de2bc527a6ef)
    - [文章](#8603294b7c1f136b866b6402d63a9978)
        - [新添加的](#f110da0bf67359d3abc62b27d717e55e)
- [收集&&集合](#a4ee2f4d4a944b54b2246c72c037cd2e)
    - [(222) 未分类](#e97d183e67fa3f530e7d0e7e8c33ee62)
    - [(9) 混合型收集](#664ff1dbdafefd7d856c88112948a65b)
    - [(12) 无工具类收集](#67acc04b20c99f87ee625b073330d8c2)
    - [(1) 收集类的收集](#24707dd322098f73c7e450d6b1eddf12)
    - [(7) 教育资源&&课程&&教程&&书籍](#9101434a896f20263d09c25ace65f398)
    - [笔记&&Tips&&Tricks](#8088e46fc533286d88b945f1d472bf57)
        - [(12) 未分类](#f57ccaab4279b60c17a03f90d96b815c)
        - [(1) blog](#0476f6b97e87176da0a0d7328f8747e7)
    - [Talk&&Conference ](#df8ec4a66ef5027bbcc591c94f8de1e5)
    - [(1) 文档&&Documentation&&规则说明&&RFC](#4be58a3a00f83975b0321425db3b9b68)
- [特定目标](#7e840ca27f1ff222fd25bc61a79b07ba)
    - [(4) 未分类-XxTarget](#eb2d1ffb231cee014ed24d59ca987da2)
    - [(113) AWS](#c71ad1932bbf9c908af83917fe1fd5da)
    - [(1) Phoenix](#88716f4591b1df2149c2b7778d15d04e)
    - [(4) Kubernetes](#4fd96686a470ff4e9e974f1503d735a2)
    - [(1) Azure](#786201db0bcc40fdf486cee406fdad31)
    - [(1) Nginx](#40dbffa18ec695a618eef96d6fd09176)
    - [(1) ELK](#6b90a3993f9846922396ec85713dc760)
    - [(1) GoogleCloud&&谷歌云](#6730dabeca61fcf64d4f7631abae6734)
- [物联网(IoT)&&嵌入式设备&&路由器&&交换机&&智能设备&&打印机](#d55d9dfd081aa2a02e636b97ca1bad0b)
    - [工具](#9a20a70f58ea7946f24224c5d73fac15)
        - [(46) 未分类-IoT](#cda63179d132f43441f8844c5df10024)
        - [(1) 打印机 ](#72bffacc109d51ea286797a7d5079392)
        - [(4) 路由器&&交换机](#c9fd442ecac4e22d142731165b06b3fe)
        - [(1) 嵌入式设备](#3d345feb9fee1c101aea3838da8cbaca)
    - [文章](#01e638f09e44280ae9a1a95fc376edc5)
        - [新添加](#a4a3bcead86d9f9f7977479dfe94797d)
- [渗透&&offensive&&渗透框架&&后渗透框架](#1233584261c0cd5224b6e90a98cc9a94)
    - [工具](#5dd93fbc2f2ebc8d98672b2d95782af3)
        - [(310) 未分类-Pentest](#2e40f2f1df5d7f93a7de47bf49c24a0e)
        - [(13) 渗透多合一&&渗透框架](#2051fd9e171f2698d8e7486e3dd35d87)
        - [(4) 自动化](#fc8737aef0f59c3952d11749fe582dac)
        - [(4) 收集](#9081db81f6f4b78d5c263723a3f7bd6d)
        - [Burp](#39e9a0fe929fffe5721f7d7bb2dae547)
            - [(2) 收集](#6366edc293f25b57bf688570b11d6584)
            - [(425) 未分类-Burp](#5b761419863bc686be12c76451f49532)
        - [(4) 数据渗透&&DataExfiltration](#3ae4408f4ab03f99bab9ef9ee69642a8)
        - [Metasploit](#8e7a6a74ff322cbf2bad59092598de77)
            - [(178) 未分类-metasploit](#01be61d5bb9f6f7199208ff0fba86b5d)
        - [横向渗透](#adfa06d452147ebacd35981ce56f916b)
        - [(36) 免杀&&躲避AV检测](#b1161d6c4cb520d0cd574347cd18342e)
        - [(107) C&C](#98a851c8e6744850efcb27b8e93dff73)
        - [(96) DDOS](#a0897294e74a0863ea8b83d11994fad6)
        - [(148) Kali](#7667f6a0381b6cded2014a0d279b5722)
        - [(163) OWASP](#8e1069b2bce90b87eea762ee3d0935d8)
        - [(76) CobaltStrike](#0b8e79b79094082d0906153445d6ef9a)
        - [CMS](#fb821e664950df22549557cb8cc54afe)
        - [日志](#53f3011d262d2554156afe18d7ad6a43)
        - [劫持&&各种劫持](#b0233cd346f5ee456ee04bf653b12ae2)
            - [(51) 未分类-Hijack](#b087f1741bcf7c449d2910d052a7f312)
            - [点击劫持](#ecdeb90ce9bd347ca7f9d366d157689d)
        - [(31) RedTeam](#8afafc25f4fb0805556003864cce90e2)
        - [(15) BlueTeam](#4c42a9cc007de389f975cb0ce146c0ed)
    - [文章](#f21aa1088a437dbb001a137f6f885530)
        - [新添加的](#7229723a22769af40b96ab31fb09dcc7)
        - [Metasploit](#6280e13d236b0f18c75894d304309416)
        - [BurpSuite](#082a9e72817adcf2f824767e3e2ce597)
        - [CobaltStrike ](#6710d6fe61cbbc36b2ba75de156eda8a)
- [扫描器&&安全扫描&&App扫描&&漏洞扫描](#8f92ead9997a4b68d06a9acf9b01ef63)
    - [工具](#132036452bfacf61471e3ea0b7bf7a55)
        - [(291) 未分类-Scanner](#de63a029bda6a7e429af272f291bb769)
        - [(20) 隐私&&Secret&&Privacy扫描](#58d8b993ffc34f7ded7f4a0077129eb2)
        - [隐私存储](#1927ed0a77ff4f176b0b7f7abc551e4a)
            - [(1) 未分类](#1af1c4f9dba1db2a4137be9c441778b8)
            - [(26) 隐写](#362dfd9c1f530dd20f922fd4e0faf0e3)
    - [文章](#1d8298e4ee4ad3c3028a1e157f85f27b)
        - [新添加的](#7669ebab00d00c744abc35195fbaa833)
- [侦察&&信息收集&&子域名发现与枚举&&OSINT](#a76463feb91d09b3d024fae798b92be6)
    - [工具](#170048b7d8668c50681c0ab1e92c679a)
        - [(210) 未分类-OSINT](#05ab1b75266fddafc7195f5b395e4d99)
        - [(81) 子域名枚举&&爆破](#e945721056c78a53003e01c3d2f3b8fe)
        - [(183) 信息收集&&侦查&&Recon&&InfoGather](#375a8baa06f24de1b67398c1ac74ed24)
        - [(75) 指纹&&Fingerprinting](#016bb6bd00f1e0f8451f779fe09766db)
        - [(1) 收集](#6ea9006a5325dd21d246359329a3ede2)
        - [社交网络](#dc74ad2dd53aa8c8bf3a3097ad1f12b7)
            - [(2) Twitter](#de93515e77c0ca100bbf92c83f82dc2a)
            - [(5) 其他-SocialNetwork](#6d36e9623aadaf40085ef5af89c8d698)
            - [(13) Github](#8d1ae776898748b8249132e822f6c919)
        - [(71) DNS](#a695111d8e30d645354c414cb27b7843)
        - [(68) Shodan](#18c7c1df2e6ae5e9135dfa2e4eb1d4db)
        - [(187) nmap](#94c01f488096fafc194b9a07f065594c)
    - [文章](#b0ca6c8512a268e8438d5e5247a88c2f)
        - [新添加](#5a855113503106950acff4d7dbb2403e)
- [社工(SET)&&钓鱼&&鱼叉攻击](#546f4fe70faa2236c0fbc2d486a83391)
    - [工具](#3e622bff3199cf22fe89db026b765cd4)
        - [(11) 未分类-SET](#ce734598055ad3885d45d0b35d2bf0d7)
        - [(2) 社工](#f30507893511f89b19934e082a54023e)
        - [(156) 钓鱼&&Phish](#290e9ae48108d21d6d8b9ea9e74d077d)
        - [鱼叉攻击](#ab3e6e6526d058e35c7091d8801ebf3a)
    - [文章](#8f6c7489870c7358c39c920c83fa2b6b)
        - [新添加的](#d7e332e9e235fd5a60687800f5ce184c)
- [环境配置&&分析系统](#dc89c90b80529c1f62f413288bca89c4)
    - [工具](#9763d00cbe773aa10502dbe258f9c385)
        - [(10) 未分类-Env](#f5a7a43f964b2c50825f3e2fee5078c8)
        - [(5) Linux-Distro](#cf07b04dd2db1deedcf9ea18c05c83e0)
        - [(3) 环境自动配置&&自动安装](#4709b10a8bb691204c0564a3067a0004)
    - [文章](#6454949c0d580904537643b8f4cd5a6b)
        - [新添加的](#873294ea77bc292b6fc4cfb2f9b40049)
- [密码&&凭证&&认证](#c49aef477cf3397f97f8b72185c3d100)
    - [工具](#862af330f45f21fbb0d495837fc7e879)
        - [(98) 未分类-Password](#20bf2e2fefd6de7aadbf0774f4921824)
        - [(43) 密码](#86dc226ae8a71db10e4136f4b82ccd06)
        - [(15) 认证&&Authenticate](#764122f9a7cf936cd9bce316b09df5aa)
    - [文章](#5fda419e854b390c8361d347f48607ce)
        - [新添加的](#776c034543a65be69c061d1aafce3127)
- [辅助周边](#43b0310ac54c147a62c545a2b0f4bce2)
    - [(12) 未分类-Assist](#569887799ee0148230cc5d7bf98e96d0)
    - [(34) TLS&&SSL&&HTTPS](#86d5daccb4ed597e85a0ec9c87f3c66f)
- [防护&&Defense](#946d766c6a0fb23b480ff59d4029ec71)
    - [工具](#0abd611fc3e9a4d9744865ca6e47a6b2)
        - [(101) WAF](#784ea32a3f4edde1cd424b58b17e7269)
        - [(119) 防火墙&&FireWall](#ce6532938f729d4c9d66a5c75d1676d3)
        - [(39) IDS&&IPS](#ff3e0b52a1477704b5f6a94ccf784b9a)
        - [(43) 未分类-Defense](#7a277f8b0e75533e0b50d93c902fb351)
        - [(3) 隐私保护&&Privacy](#6543c237786d1f334d375f4d9acdeee4)
    - [文章](#5aac7367edfef7c63fc95afd6762b773)
        - [新添加的](#04aac0e81b87788343930e9dbf01ba9c)
- [SoftwareDefinedRadio](#52b481533d065d9e80cfd3cca9d91c7f)
    - [(6) 工具](#015984b1dae0c9aa03b3aa74ea449f3f)
    - [文章](#043e62cc373eb3e7b3910b622cf220d8)
- [LOLBin&&LOLScript](#507f1a48f4709abb1c6b0d2689fd15e6)
    - [(2) 工具](#ec32edc7b3e441f29c70f6e9bca0174a)
    - [文章](#9bffad3ac781090ab31d4013bf858dd9)
- [日志&&Log](#e25d233159b1dc40898ff0c74574f790)
    - [(1) 工具](#13df0f4d5c7a1386b329fd9e43d8fc15)
    - [文章](#06e7d46942d5159d19aa5c36f66f174a)
- [威胁狩猎&&ThreatHunt](#9b026a07fdf243c6870ce91f00191214)
    - [工具](#b911aad7512e253660092942e06d00ad)
        - [(1) 未分类](#0b27f97199330c4945572a1f9c229000)
    - [文章](#f613271a55b177f626b42b8c728a0b1c)
        - [新添加的](#3828e67170e5db714c9c16f663b42a5e)
- [Crypto&&加密&&密码学](#d6b02213a74372407371f77dd6e39c99)
    - [(13) 工具](#41d260119ad54db2739a9ae393bd87a5)
    - [文章](#cc043f672c90d4b834cdae80bfbe8851)
- [恶意代码&&Malware&&APT](#8cb1c42a29fa3e8825a0f8fca780c481)
    - [(12) 工具](#e2fd0947924229d7de24b9902e1f54a0)
    - [文章](#cfffc63a6302bd3aa79a0305ed7afd55)
- [REST_API&&RESTFUL ](#7d5d2d22121ed8456f0c79098f5012bb)
    - [(3) 工具](#3b127f2a89bc8d18b4ecb0d9c61f1d58)
    - [文章](#b16baff7e1b11133efecf1b5b6e10aab)
- [蓝牙&&Bluetooth](#ceb90405292daed9bb32ac20836c219a)
    - [(3) 工具](#c72811e491c68f75ac2e7eb7afd3b01f)
    - [文章](#97e1bdced96fc7fcd502174d6eecee36)
- [浏览器&&browser](#76df273beb09f6732b37a6420649179c)
    - [(21) 工具](#47a03071becd6df66b469df7c2c6f9b5)
    - [文章](#ca0c0694dc0aa87534e9bb19be4ee4d5)
- [MitreATT&CK](#249c9d207ed6743e412c8c8bcd8a2927)
    - [工具](#a88c0c355b342b835fb42abee283bd71)
        - [(27) 未分类的](#6ab6835b55cf5c8462c4229a4a0ee94c)
    - [文章](#8512ba6c3855733a1474ca2f16153906)
        - [新添加的](#4b17464da487fbdf719e9a1482abf8f1)
- [破解&&Crack&&爆破&&BruteForce](#de81f9dd79c219c876c1313cd97852ce)
    - [工具](#73c3c9225523cbb05333246f23342846)
        - [(255) 未分类的](#53084c21ff85ffad3dd9ce445684978b)
    - [文章](#171e396a8965775c27602762c6638694)
        - [新添加的](#fc3c73849911ede2ce0d6d02f1f5b0b9)
- [泄漏&&Breach&&Leak](#96171a80e158b8752595329dd42e8bcf)
    - [工具](#602bb9759b0b2ba5555b05b7218a2d6f)
        - [(15) 未分类](#dc507c5be7c09e1e88af7a1ad91e2703)
    - [文章](#fb3bccf80281e11fdf4ef06ddaa34566)
        - [新添加的](#339727dd5a006d7a5bd8f0173dc80bb9)
- [爬虫](#785ad72c95e857273dce41842f5e8873)
    - [工具](#0f931c85ab54698d0bcfaf9a3e6dac73)
        - [(1) 未分类](#442f9390fd56008def077a21ab65d4aa)
    - [文章](#23b008498c8b41ec3128bd9855660b7d)
        - [新添加的](#37ca6907aa42dfd32db5973ff9eec83d)
- [无线&&WiFi&&AP&&802.11](#39931e776c23e80229368dfc6fd54770)
    - [(184) 未分类-WiFi](#d4efda1853b2cb0909727188116a2a8c)
    - [(7) WPS&&WPA&&WPA2](#8d233e2d068cce2b36fd0cf44d10f5d8)
    - [(2) 802.11](#8863b7ba27658d687a85585e43b23245)
- [Payload&&远控&&RAT](#80301821d0f5d8ec2dd3754ebb1b4b10)
    - [工具](#783f861b9f822127dba99acb55687cbb)
        - [(134) 未分类-payload](#6602e118e0245c83b13ff0db872c3723)
        - [(20) Payload收集](#b5d99a78ddb383c208aae474fc2cb002)
        - [(44) 远控&&RAT](#b318465d0d415e35fc0883e9894261d1)
        - [(58) Payload生成](#ad92f6b801a18934f1971e2512f5ae4f)
        - [(34) Botnet&&僵尸网络](#c45a90ab810d536a889e4e2dd45132f8)
        - [(70) 后门&&添加后门](#b6efee85bca01cde45faa45a92ece37f)
        - [(105) 混淆器&&Obfuscate](#85bb0c28850ffa2b4fd44f70816db306)
        - [(1) Payload管理](#78d0ac450a56c542e109c07a3b0225ae)
        - [(32) 勒索软件](#d08b7bd562a4bf18275c63ffe7d8fc91)
        - [(32) 键盘记录器&&Keylogger](#82f546c7277db7919986ecf47f3c9495)
        - [(13) Meterpreter](#8f99087478f596139922cd1ad9ec961b)
        - [(6) Payload投递](#63e0393e375e008af46651a3515072d8)
    - [文章](#0b644b2d8119abf6643755ef455fcf2c)
        - [新添加](#27962a7633b86d43cae2dd2d4c32f1b6)
- [后渗透](#a9494547a9359c60f09aea89f96a2c83)
    - [工具](#3ed50213c2818f1455eff4e30372c542)
        - [(49) 未分类-post-exp](#12abc279c69d1fcf10692b9cb89bcdf7)
        - [(53) 提权&&PrivilegeEscalation](#4c2095e7e192ac56f6ae17c8fc045c51)
        - [Windows](#caab36bba7fa8bb931a9133e37d397f6)
            - [(19) UAC](#58f3044f11a31d0371daa91486d3694e)
            - [(72) 未分类-Windows](#7ed8ee71c4a733d5e5e5d239f0e8b9e0)
            - [(3) AppLocker](#b84c84a853416b37582c3b7f13eabb51)
            - [(10) ActiveDirectory](#e3c4c83dfed529ceee65040e565003c4)
            - [域渗透](#25697cca32bd8c9492b8e2c8a3a93bfe)
            - [WET](#a5c1d88a8e35b6c6223a6d64dbfb5358)
        - [(10) 驻留&&Persistence](#2dd40db455d3c6f1f53f8a9c25bbe63e)
        - [Linux&&Xnix](#4fc56d3dd1977b882ba14a9fd820f8e2)
    - [文章](#c86567da7d4004149912383575be3b45)
        - [新添加](#fdf10af493284be94033d1350f1e9b5c)


# <a id="94ca60d12e210fdd7fd9e387339b293e"></a>新添加的


***


## <a id="9eee96404f868f372a6cbc6769ccb7f8"></a>工具


### <a id="31185b925d5152c7469b963809ceb22d"></a>新添加的


- [**825**星][2m] [Py] [corelan/mona](https://github.com/corelan/mona) 用于Immunity Debugger的mona.py
- [**813**星][26d] [JS] [sindresorhus/is-online](https://github.com/sindresorhus/is-online) 检查互联网连接是否正常
- [**810**星][2m] [Shell] [andreyvit/create-dmg](https://github.com/andreyvit/create-dmg) 用于构建精美DMG的Shell脚本
- [**793**星][2m] [Go] [dreddsa5dies/gohacktools](https://github.com/dreddsa5dies/gohacktools) Golang编写的多款Hacking工具
- [**786**星][1y] [PS] [kevin-robertson/invoke-thehash](https://github.com/kevin-robertson/invoke-thehash) 执行 pass the hash WMI 和 SMB 任务的PowerShell函数
- [**783**星][26d] [Go] [bishopfox/sliver](https://github.com/bishopfox/sliver) 一个通用的跨平台植入程序框架，该框架C3支持Mutual-TLS，HTTP（S）和DNS
- [**770**星][13d] [C++] [shekyan/slowhttptest](https://github.com/shekyan/slowhttptest) 应用层DoS攻击模拟器
- [**770**星][18d] [C++] [snort3/snort3](https://github.com/snort3/snort3) 下一代Snort IPS（入侵防御系统）。
- [**761**星][1y] [Py] [greatsct/greatsct](https://github.com/greatsct/greatsct) 生成绕过常见防病毒解决方案和应用程序白名单解决方案的metasploit payload
- [**760**星][11d] [HTML] [m4cs/babysploit](https://github.com/m4cs/babysploit) 渗透测试工具包，旨在使您轻松学习如何使用更大，更复杂的框架（例如Metasploit）
- [**743**星][1y] [C#] [eladshamir/internal-monologue](https://github.com/eladshamir/internal-monologue) 在不接触LSASS的情况下提取NTLM hash
- [**742**星][6m] [Go] [talkingdata/owl](https://github.com/talkingdata/owl) 企业级分布式监控告警系
- [**731**星][2d] [Go] [gruntwork-io/cloud-nuke](https://github.com/gruntwork-io/cloud-nuke) 通过检查（删除）其中的所有资源来清理云帐户
- [**731**星][1m] [C] [iaik/zombieload](https://github.com/iaik/zombieload) ZombieLoad攻击PoC
- [**729**星][2m] [Py] [shawndevans/smbmap](https://github.com/shawndevans/smbmap) SMB枚举
- [**728**星][6m] [Go] [anshumanbh/git-all-secrets](https://github.com/anshumanbh/git-all-secrets) 结合多个开源 git 搜索工具实现的代码审计工具
- [**723**星][6d] [Py] [skelsec/pypykatz](https://github.com/skelsec/pypykatz) 纯Python实现的Mimikatz
- [**720**星][1y] [C#] [p3nt4/powershdll](https://github.com/p3nt4/powershdll) 使用rundll32执行PowerShell，绕过软件限制
- [**716**星][6m] [Py] [adamlaurie/rfidiot](https://github.com/adamlaurie/rfidiot) python RFID / NFC library & tools
- [**715**星][21d] [Py] [f-secure/see](https://github.com/f-secure/see) 在安全环境中构建测试自动化的框架
- [**703**星][2m] [Py] [mjg59/python-broadlink](https://github.com/mjg59/python-broadlink) Python模块，用于控制Broadlink RM2 / 3（Pro）遥控器、A1传感器平台和SP2 / 3智能插头
- [**695**星][3m] [netflix/security-bulletins](https://github.com/netflix/security-bulletins) Security Bulletins that relate to Netflix Open Source
- [**693**星][7m] [Py] [mr-un1k0d3r/powerlessshell](https://github.com/mr-un1k0d3r/powerlessshell) 依靠MSBuild.exe远程执行PowerShell脚本和命令
- [**686**星][3m] [Go] [pquerna/otp](https://github.com/pquerna/otp) 一次性密码工具，Golang编写
- [**683**星][1y] [PS] [arvanaghi/sessiongopher](https://github.com/Arvanaghi/SessionGopher) 使用WMI为远程访问工具（如WinSCP，PuTTY，SuperPuTTY，FileZilla和Microsoft远程桌面）提取保存的会话信息。PowerShell编写
- [**682**星][1m] [ptresearch/attackdetection](https://github.com/ptresearch/attackdetection) 搜索新的漏洞和0day，进行服现并创建PoC exp，以了解这些安全漏洞的工作方式，以及如何在网络层上检测到相关的攻击
- [**679**星][1y] [Py] [endgameinc/rta](https://github.com/endgameinc/rta) 根据MITER ATT＆CK进行建模，针对恶意tradecraft测试其检测功能。脚本框架
- [**679**星][5d] [C#] [ghostpack/rubeus](https://github.com/ghostpack/rubeus) 原始Kerberos交互和滥用，C＃编写
- [**665**星][6m] [Py] [golismero/golismero](https://github.com/golismero/golismero) 安全测试框架，当前主要是Web安全，可轻松扩展到其他扫描
- [**665**星][12m] [C#] [wwillv/godofhacker](https://github.com/wwillv/godofhacker) 由各种顶级黑客技术结合而成，基本功能覆盖面广，可满足大多数人的基本需求
- [**656**星][6m] [PHP] [l3m0n/bypass_disable_functions_shell](https://github.com/l3m0n/bypass_disable_functions_shell) 一个各种方式突破Disable_functions达到命令执行的shell
- [**647**星][3m] [Py] [gquere/pwn_jenkins](https://github.com/gquere/pwn_jenkins) 有关攻击Jenkins服务器的笔记
- [**639**星][10m] [Py] [dirkjanm/privexchange](https://github.com/dirkjanm/privexchange) 通过滥用Exchange交换您对Domain Admin privs的特权
- [**635**星][1y] [JS] [alcuadrado/hieroglyphy](https://github.com/alcuadrado/hieroglyphy) 将所有JavaScript代码转换为等价的（）[] {}！+字符序列！，可在浏览器中运行
- [**630**星][5m] [ankane/secure_rails](https://github.com/ankane/secure_rails) Rails安全最佳实战
- [**621**星][1m] [Go] [evilsocket/arc](https://github.com/evilsocket/arc) 可用于管理私密数据的工具. 后端是 Go 语言编写的 RESTful 服务器,  前台是Html + JavaScript
- [**605**星][30d] [Py] [webrecorder/pywb](https://github.com/webrecorder/pywb) 重放和记录Web存档
- [**601**星][4d] [YARA] [didierstevens/didierstevenssuite](https://github.com/didierstevens/didierstevenssuite) 工具、脚本列表
- [**601**星][17d] [C] [mrexodia/titanhide](https://github.com/mrexodia/titanhide) 用于隐藏某些进程调试器的驱动程序
- [**599**星][2m] [PS] [ramblingcookiemonster/powershell](https://github.com/ramblingcookiemonster/powershell) 各种PowerShell函数和脚本
- [**588**星][11m] [C] [justinsteven/dostackbufferoverflowgood](https://github.com/justinsteven/dostackbufferoverflowgood) 跨站点脚本编写者的演示和教程，这些站点编写者不能很好地堆积缓冲区溢出，并且也想做其他事情
- [**583**星][10m] [Py] [romanz/amodem](https://github.com/romanz/amodem) 使用简单的耳机在两台计算机之间传输文件，实现真正的气密通信（通过扬声器和麦克风）或音频电缆（以提高传输速度）
- [**582**星][1y] [C#] [tyranid/dotnettojscript](https://github.com/tyranid/dotnettojscript) 创建从内存中加载.NET v2程序集的JScript文件
- [**580**星][5m] [Py] [nidem/kerberoast](https://github.com/nidem/kerberoast) 一系列用于攻击MS Kerberos实现的工具
- [**570**星][1y] [Solidity] [crytic/not-so-smart-contracts](https://github.com/crytic/not-so-smart-contracts) 常见的以太坊智能合约漏洞示例，包括来自真实智能合约的代码。
- [**567**星][4m] [Py] [its-a-feature/apfell](https://github.com/its-a-feature/apfell) 利用python3，docker，docker-compose和Web浏览器UI构建的跨平台，后渗透的Red Team框架。
- [**557**星][1m] [C] [vanhauser-thc/thc-ipv6](https://github.com/vanhauser-thc/thc-ipv6) IPv6攻击工具包
- [**550**星][6m] [HCL] [coalfire-research/red-baron](https://github.com/coalfire-research/red-baron) 为Red Teams自动创建有弹性，disposable，安全和敏捷的基础架构。
- [**542**星][9m] [C] [hfiref0x/upgdsed](https://github.com/hfiref0x/upgdsed) 通用PG和DSE禁用工具
- [**539**星][3m] [C] [eliasoenal/multimon-ng](https://github.com/EliasOenal/multimon-ng) multimon-ng是multimon的继承者。解码多种数字传输模式
- [**537**星][1y] [C#] [ghostpack/safetykatz](https://github.com/ghostpack/safetykatz) Mimikatz和 .NET PE Loader的结合
- [**531**星][13d] [Go] [sensepost/gowitness](https://github.com/sensepost/gowitness) Go 语言编写的网站快照工具
- [**526**星][5d] [Ruby] [hdm/mac-ages](https://github.com/hdm/mac-ages) 确定IEEE分配的硬件地址范围的大概发布日期
- [**520**星][2m] [Shell] [trailofbits/twa](https://github.com/trailofbits/twa) 小型网页审计工具，可灵活设置参数
- [**517**星][2m] [JS] [mr-un1k0d3r/thundershell](https://github.com/mr-un1k0d3r/thundershell) 通过HTTP请求进行通信的C＃RAT
- [**517**星][5m] [C++] [shuax/greenchrome](https://github.com/shuax/greenchrome) 超好用的Chrome浏览器增强软件
- [**516**星][8m] [Visual Basic .NET] [mr-un1k0d3r/maliciousmacrogenerator](https://github.com/mr-un1k0d3r/maliciousmacrogenerator) 生成混淆的宏，可进行AV /沙箱逃逸
- [**510**星][12m] [Go] [mthbernardes/gtrs](https://github.com/mthbernardes/gtrs) 使用Google翻译器作为代理将任意命令发送到受感染的计算机
- [**505**星][12m] [C] [google/ktsan](https://github.com/google/ktsan) 用于Linux内核的快速数据竞赛检测器
- [**503**星][1m] [JS] [sindresorhus/public-ip](https://github.com/sindresorhus/public-ip) 快速获取外网IP地址
- [**501**星][2m] [C] [m0nad/diamorphine](https://github.com/m0nad/diamorphine) 适用于Linux Kernels 2.6.x / 3.x / 4.x（x86和x86_64）的LKM rootkit
- [**500**星][11m] [C] [yangyangwithgnu/bypass_disablefunc_via_ld_preload](https://github.com/yangyangwithgnu/bypass_disablefunc_via_ld_preload) 通过LD_PRELOA绕过disable_functions（不需要/ usr / sbin / sendmail）
- [**495**星][3m] [PHP] [nzedb/nzedb](https://github.com/nzedb/nzedb) 自动扫描Usenet，类似于爬虫扫描互联网的方式
- [**492**星][3m] [Go] [gen2brain/cam2ip](https://github.com/gen2brain/cam2ip) 将任何网络摄像头转换为IP 摄像机
- [**488**星][2m] [Py] [aoii103/darknet_chinesetrading](https://github.com/aoii103/darknet_chinesetrading) 暗网中文网监控实时爬虫
- [**488**星][3m] [Go] [gorilla/csrf](https://github.com/gorilla/csrf) 为Go Web应用程序和服务提供CSRF预防中间件
- [**487**星][12m] [Go] [evanmiller/hecate](https://github.com/evanmiller/hecate) Hex编辑器
- [**486**星][11m] [Shell] [craigz28/firmwalker](https://github.com/craigz28/firmwalker) 一个简单的bash脚本，用于搜索提取或安装的固件文件系统。
- [**478**星][1m] [xiangpasama/jdsrc-small-classroom](https://github.com/xiangpasama/jdsrc-small-classroom) 京东SRC小课堂系列文章
- [**478**星][2m] [TS] [mitre-attack/attack-navigator](https://github.com/mitre-attack/attack-navigator) 提供ATT＆CK矩阵的基本导航和注释的Web App
- [**472**星][2m] [Py] [bit4woo/teemo](https://github.com/bit4woo/teemo) 域名和电子邮件地址收集工具
- [**469**星][20d] [Py] [fportantier/habu](https://github.com/fportantier/habu) Python 编写的网络工具工具包，主要用于教学/理解网络攻击中的一些概念
- [**468**星][2m] [Py] [coleifer/micawber](https://github.com/coleifer/micawber) 用于从URL中提取丰富的内容库
- [**467**星][1m] [Shell] [wireghoul/graudit](https://github.com/wireghoul/graudit) 简单的脚本和签名集，进行源代码审计
- [**465**星][2m] [Go] [gen0cide/gscript](https://github.com/gen0cide/gscript) 基于运行时参数，动态安装恶意软件
- [**462**星][5m] [C] [phoenhex/files](https://github.com/phoenhex/files) Phoenhex 团队的exploits/POCs/presentation
- [**461**星][3m] [PS] [rvrsh3ll/misc-powershell-scripts](https://github.com/rvrsh3ll/misc-powershell-scripts) PowerShell工具集
- [**454**星][19d] [PS] [mr-un1k0d3r/redteampowershellscripts](https://github.com/mr-un1k0d3r/redteampowershellscripts) 在红队练习中可能会有用的各种PowerShell脚本
- [**454**星][2m] [Py] [super-l/superl-url](https://github.com/super-l/superl-url) 根据关键词，对搜索引擎内容检索结果的网址内容进行采集的一款轻量级软程序。 程序主要运用于安全渗透测试项目，以及批量评估各类CMS系统0DAY的影响程度，同时也是批量采集自己获取感兴趣的网站的一个小程序~~ 可自动从搜索引擎采集相关网站的真实地址与标题等信息，可保存为文件，自动去除重复URL。同时，也可以自定义忽略多条域名等。
- [**450**星][4m] [C++] [omerya/invisi-shell](https://github.com/omerya/invisi-shell) 隐藏您的Powershell脚本。绕过所有Powershell安全功能
- [**431**星][7m] [Pascal] [mojtabatajik/robber](https://github.com/mojtabatajik/robber) 查找易于发生DLL劫持的可执行文件
- [**431**星][11d] [C++] [tenable/routeros](https://github.com/tenable/routeros) 对 MikroTik的RouterOS进行安全性研究时使用的各种工具和漏洞
- [**421**星][8m] [7kbstorm/7kbscan-webpathbrute](https://github.com/7kbstorm/7kbscan-webpathbrute) 路径暴力探测工具
- [**420**星][11m] [Py] [powerscript/katanaframework](https://github.com/powerscript/katanaframework) 用于进行渗透测试的框架，基于一个简单而全面的结构，任何人都可以使用，修改和共享。Python编写
- [**411**星][5d] [HTML] [w3c/webappsec](https://github.com/w3c/webappsec) Web App安全工作组
- [**411**星][15d] [Py] [ytisf/pyexfil](https://github.com/ytisf/pyexfil) 用于数据渗透的Python包
- [**409**星][10m] [Py] [linklayer/pyvit](https://github.com/linklayer/pyvit) 与汽车接口的工具包。它旨在实现汽车系统中使用的通用硬件接口和协议。
- [**408**星][2d] [Go] [cloudfoundry/gorouter](https://github.com/cloudfoundry/gorouter) CF Router
- [**401**星][1m] [Py] [fbngrm/matroschka](https://github.com/fbngrm/Matroschka) Python隐写术工具，可在图像中红隐藏文本或图像
- [**391**星][12d] [C++] [simsong/bulk_extractor](https://github.com/simsong/bulk_extractor) 取证工具
- [**389**星][24d] [Ruby] [david942j/seccomp-tools](https://github.com/david942j/seccomp-tools) 用于seccomp分析
- [**386**星][4m] [PHP] [msurguy/honeypot](https://github.com/msurguy/honeypot) 一种简单有效的方法，来阻止某些进入您网站的垃圾邮件机器人
- [**384**星][11d] [C#] [bloodhoundad/sharphound](https://github.com/bloodhoundad/sharphound) C＃重写BloodHound Ingestor
- [**383**星][1y] [JS] [empireproject/empire-gui](https://github.com/empireproject/empire-gui) Empire开渗透框架的图形界面
- [**383**星][1m] [JS] [nccgroup/tracy](https://github.com/nccgroup/tracy) 查找web app中所有的sinks and sources, 并以易于理解的方式显示这些结果
- [**381**星][1m] [Py] [fox-it/bloodhound.py](https://github.com/fox-it/bloodhound.py) 基于Python的BloodHound Ingestor，基于Impacket
- [**379**星][9m] [Py] [k4m4/onioff](https://github.com/k4m4/onioff) url检测器，深度检测网页链接
- [**376**星][2d] [Ruby] [dradis/dradis-ce](https://github.com/dradis/dradis-ce) 面向信息安全团队的协作框架
- [**376**星][7m] [Py] [tidesec/tidefinger](https://github.com/tidesec/tidefinger) 指纹识别小工具，汲取整合了多个web指纹库，结合了多种指纹检测方法，让指纹检测更快捷、准确。
- [**375**星][] [C] [vanhauser-thc/aflplusplus](https://github.com/vanhauser-thc/aflplusplus) 带社区补丁的afl 2.56b
- [**375**星][6m] [Py] [vysecurity/domlink](https://github.com/vysecurity/DomLink) 一种将具有注册组织名称和电子邮件的域链接到其他域的工具。
- [**369**星][2m] [Py] [emtunc/slackpirate](https://github.com/emtunc/slackpirate) Slack枚举和提取工具-从Slack工作区中提取敏感信息
- [**367**星][20d] [Shell] [trimstray/otseca](https://github.com/trimstray/otseca) 安全审计工具, 搜索并转储系统配置
- [**364**星][1m] [Py] [tenable/poc](https://github.com/tenable/poc) 漏洞PoC
- [**363**星][2m] [Py] [codingo/interlace](https://github.com/codingo/interlace) 轻松将单线程命令行应用程序转换为具有CIDR和glob支持的快速，多线程应用程序。
- [**363**星][11m] [Py] [secynic/ipwhois](https://github.com/secynic/ipwhois) 检索和解析IPv4和IPv6地址的Whois数据
- [**359**星][4d] [C#] [sonarsource/sonar-dotnet](https://github.com/sonarsource/sonar-dotnet) 用于C＃和VB.NET语言的静态代码分析器，用作SonarQube和SonarCloud平台的扩展。
- [**356**星][7d] [TeX] [vlsergey/infosec](https://github.com/vlsergey/infosec) MIPT无线电工程与控制系统部信息保护教科书
- [**356**星][21d] [hackerschoice/thc-tesla-powerwall2-hack](https://github.com/hackerschoice/thc-tesla-powerwall2-hack) TESLA PowerWall 2安全雪茄
- [**355**星][19d] [Py] [lockgit/hacking](https://github.com/lockgit/hacking) Hacking工具收集
- [**355**星][5m] [Makefile] [xdite/internet-security](https://github.com/xdite/internet-security) 互联网资安风控实战
- [**347**星][7d] [Ruby] [sunitparekh/data-anonymization](https://github.com/sunitparekh/data-anonymization) 帮助您构建匿名的生产数据转储，可用于性能测试，安全性测试，调试和开发。
- [**346**星][19d] [Perl] [keydet89/regripper2.8](https://github.com/keydet89/regripper2.8) 从注册表中提取/解析信息（键，值，数据）并将其呈现出来进行分析。
- [**344**星][1y] [Assembly] [egebalci/amber](https://github.com/egebalci/amber) 反射式PE加壳器，用于绕过安全产品和缓解措施
- [**343**星][2m] [veracode-research/solr-injection](https://github.com/veracode-research/solr-injection) Apache Solr注入研究
- [**342**星][9m] [Py] [skorov/ridrelay](https://github.com/skorov/ridrelay) 通过使用具有低priv的SMB中继来枚举您没有信誉的域上的用户名。
- [**340**星][11d] [C#] [mr-un1k0d3r/scshell](https://github.com/mr-un1k0d3r/scshell) Fileless lateral movement tool that relies on ChangeServiceConfigA to run command
- [**339**星][4d] [JS] [meituan-dianping/lyrebird](https://github.com/meituan-dianping/lyrebird) 基于拦截以及模拟HTTP/HTTPS网络请求的面向移动应用的插件化测试工作台
- [**339**星][1y] [Ruby] [srcclr/commit-watcher](https://github.com/srcclr/commit-watcher) Find interesting and potentially hazardous commits in git projects
- [**335**星][4m] [C] [csete/gpredict](https://github.com/csete/gpredict) a real time satellite tracking and orbit prediction program
for the Linux desktop
- [**332**星][11m] [C#] [ghostpack/sharpdump](https://github.com/ghostpack/sharpdump) SharpDump is a C# port of PowerSploit's Out-Minidump.ps1 functionality.
- [**332**星][1y] [Py] [leapsecurity/inspy](https://github.com/leapsecurity/InSpy) A python based LinkedIn enumeration tool
- [**331**星][1y] [Shell] [1n3/goohak](https://github.com/1n3/goohak) Automatically Launch Google Hacking Queries Against A Target Domain
- [**328**星][1y] [Java] [ysrc/liudao](https://github.com/ysrc/liudao) “六道”实时业务风控系统
- [**327**星][3m] [Py] [defaultnamehere/cookie_crimes](https://github.com/defaultnamehere/cookie_crimes) Read local Chrome cookies without root or decrypting
- [**326**星][2m] [PS] [joelgmsec/autordpwn](https://github.com/joelgmsec/autordpwn) The Shadow Attack Framework
- [**326**星][1y] [JS] [nccgroup/wssip](https://github.com/nccgroup/wssip) 服务器和客户端之间通信时自定义 WebSocket 数据的捕获、修改和发送。
- [**326**星][1m] [Go] [wangyihang/platypus](https://github.com/wangyihang/platypus)  A modern multiple reverse shell sessions/clients manager via terminal written in go
- [**325**星][21d] [Shell] [al0ne/linuxcheck](https://github.com/al0ne/linuxcheck) linux信息收集/应急响应/常见后门检测脚本
- [**324**星][12d] [JS] [privacypass/challenge-bypass-extension](https://github.com/privacypass/challenge-bypass-extension) 用于匿名认证的浏览器扩展
- [**323**星][1m] [trustedsec/physical-docs](https://github.com/trustedsec/physical-docs) This is a collection of legal wording and documentation used for physical security assessments. The goal is to hopefully allow this as a template for other companies to use and to protect themselves when conducting physical security assessments.
- [**322**星][1y] [crazywa1ker/darthsidious-chinese](https://github.com/crazywa1ker/darthsidious-chinese) 从0开始你的域渗透之旅
- [**318**星][2m] [Visual Basic .NET] [nccgroup/vcg](https://github.com/nccgroup/vcg) Code security scanning tool.
- [**317**星][5d] [Py] [circl/lookyloo](https://github.com/circl/lookyloo) Lookyloo is a web interface allowing to scrape a website and then displays a tree of domains calling each other.
- [**316**星][22d] [HTML] [vanhauser-thc/thc-archive](https://github.com/vanhauser-thc/thc-archive) All releases of the security research group (a.k.a. hackers) The Hacker's Choice
- [**315**星][6d] [VBA] [itm4n/vba-runpe](https://github.com/itm4n/vba-runpe) A VBA implementation of the RunPE technique or how to bypass application whitelisting.
- [**315**星][8m] [C] [tomac/yersinia](https://github.com/tomac/yersinia) layer 2 攻击框架
- [**315**星][1y] [Go] [benjojo/bgp-battleships](https://github.com/benjojo/bgp-battleships) Play battleships using BGP
- [**313**星][2m] [Py] [coalfire-research/slackor](https://github.com/coalfire-research/slackor) A Golang implant that uses Slack as a command and control server
- [**312**星][7m] [C] [pmem/syscall_intercept](https://github.com/pmem/syscall_intercept) Linux系统调用拦截框架，通过 hotpatching 进程标准C库的机器码实现。
- [**312**星][5m] [Java] [shengqi158/fastjson-remote-code-execute-poc](https://github.com/shengqi158/fastjson-remote-code-execute-poc) 直接用intellij IDEA打开即可 首先编译得到Test.class，然后运行Poc.java
- [**311**星][7m] [HTML] [nccgroup/crosssitecontenthijacking](https://github.com/nccgroup/crosssitecontenthijacking) Content hijacking proof-of-concept using Flash, PDF and Silverlight
- [**311**星][1m] [YARA] [needmorecowbell/hamburglar](https://github.com/needmorecowbell/hamburglar)  collect useful information from urls, directories, and files
- [**310**星][2m] [PS] [darkoperator/posh-secmod](https://github.com/darkoperator/posh-secmod) PowerShell Module with Security cmdlets for security work
- [**309**星][4m] [PS] [enigma0x3/misc-powershell-stuff](https://github.com/enigma0x3/misc-powershell-stuff) random powershell goodness
- [**305**星][3m] [C] [9176324/shark](https://github.com/9176324/shark) Turn off PatchGuard in real time for win7 (7600) ~ win10 (18950).
- [**305**星][7d] [ugvf2009/miles](https://github.com/ugvf2009/miles) 二爷翻墙，专注翻墙30年，但没有掌握核心科技^_^
- [**305**星][11d] [Py] [xinsss/conf-for-surge-shadowrocket](https://github.com/xinsss/conf-for-surge-shadowrocket) Surge Shadowrocket conf
- [**304**星][2m] [JS] [doyensec/electronegativity](https://github.com/doyensec/electronegativity) Electronegativity is a tool to identify misconfigurations and security anti-patterns in Electron applications.
- [**300**星][] [C++] [squalr/squally](https://github.com/squalr/squally) 2D Platformer Game for Teaching Game Hacking - C++/cocos2d-x
- [**300**星][1m] [C] [tarsnap/scrypt](https://github.com/tarsnap/scrypt) The scrypt key derivation function was originally developed for use in the Tarsnap online backup system and is designed to be far more secure against hardware brute-force attacks than alternative functions such as PBKDF2 or bcrypt.
- [**299**星][10m] [C++] [anhkgg/superdllhijack](https://github.com/anhkgg/superdllhijack) SuperDllHijack：A general DLL hijack technology, don't need to manually export the same function interface of the DLL, so easy! 一种通用Dll劫持技术，不再需要手工导出Dll的函数接口了
- [**299**星][1y] [C#] [ghostpack/sharpup](https://github.com/ghostpack/sharpup) SharpUp is a C# port of various PowerUp functionality.
- [**298**星][7m] [Py] [edent/bmw-i-remote](https://github.com/edent/bmw-i-remote) A reverse engineered interface for the BMW i3 Electric Car
- [**298**星][14d] [Shell] [fdiskyou/zines](https://github.com/fdiskyou/zines) Mirror of my favourite hacking Zines for the lulz, nostalgy, and reference
- [**297**星][10d] [JS] [jesusprubio/strong-node](https://github.com/jesusprubio/strong-node) 
- [**297**星][1y] [JS] [xxxily/fiddler-plus](https://github.com/xxxily/fiddler-plus) 自定义的Fiddler规则，多环境切换、解决跨域开发、快速调试线上代码必备|高效调试分析利器
- [**296**星][9m] [C] [gianlucaborello/libprocesshider](https://github.com/gianlucaborello/libprocesshider) Hide a process under Linux using the ld preloader (
- [**295**星][2m] [Go] [mdsecactivebreach/o365-attack-toolkit](https://github.com/mdsecactivebreach/o365-attack-toolkit) A toolkit to attack Office365
- [**295**星][9m] [C] [rhboot/shim](https://github.com/rhboot/shim) a trivial EFI application that, when run, attempts to open and execute another application
- [**292**星][9d] [Go] [cruise-automation/fwanalyzer](https://github.com/cruise-automation/fwanalyzer) a tool to analyze filesystem images for security
- [**292**星][2m] [C] [mboehme/aflfast](https://github.com/mboehme/aflfast) AFLFast (extends AFL with Power Schedules)
- [**292**星][2d] [Py] [vulnerscom/api](https://github.com/vulnerscom/api) Python 2/3 library for the Vulners Database
- [**290**星][20d] [C#] [matterpreter/offensivecsharp](https://github.com/matterpreter/offensivecsharp) Collection of Offensive C# Tooling
- [**290**星][5m] [Py] [opsdisk/pagodo](https://github.com/opsdisk/pagodo) pagodo (Passive Google Dork) - Automate Google Hacking Database scraping
- [**288**星][12m] [Py] [justicerage/ffm](https://github.com/justicerage/ffm) Freedom Fighting Mode: open source hacking harness
- [**287**星][3m] [Py] [apache/incubator-spot](https://github.com/apache/incubator-spot) Mirror of Apache Spot
- [**283**星][16d] [PS] [nullbind/powershellery](https://github.com/nullbind/powershellery) This repo contains Powershell scripts used for general hackery.
- [**282**星][3m] [Py] [hacktoolspack/hack-tools](https://github.com/hacktoolspack/hack-tools) hack tools
- [**282**星][4m] [Py] [joxeankoret/pyew](https://github.com/joxeankoret/pyew) Official repository for Pyew.
- [**282**星][13d] [PHP] [nico3333fr/csp-useful](https://github.com/nico3333fr/csp-useful) Collection of scripts, thoughts about CSP (Content Security Policy)
- [**282**星][1y] [HTML] [googleprojectzero/p0tools](https://github.com/googleprojectzero/p0tools) Project Zero Docs and Tools
- [**278**星][5d] [geerlingguy/ansible-role-security](https://github.com/geerlingguy/ansible-role-security) Ansible Role - Security
- [**277**星][5m] [Py] [18f/domain-scan](https://github.com/18f/domain-scan) A lightweight pipeline, locally or in Lambda, for scanning things like HTTPS, third party service use, and web accessibility.
- [**277**星][8m] [s0md3v/mypapers](https://github.com/s0md3v/mypapers) Repository for hosting my research papers
- [**276**星][28d] [C#] [mkaring/confuserex](https://github.com/mkaring/confuserex) An open-source, free protector for .NET applications
- [**274**星][4m] [Py] [invernizzi/scapy-http](https://github.com/invernizzi/scapy-http) Support for HTTP in Scapy
- [**273**星][15d] [Py] [den1al/jsshell](https://github.com/den1al/jsshell) An interactive multi-user web JS shell
- [**271**星][8m] [offensive-security/nethunter-lrt](https://github.com/offensive-security/nethunter-lrt) The Nethunter Linux Root Toolkit is a collection of bash scripts which install Nethunter onto a supported device.
- [**271**星][8m] [Py] [s0md3v/breacher](https://github.com/s0md3v/Breacher) An advanced multithreaded admin panel finder written in python.
- [**269**星][18d] [Py] [ledger-donjon/lascar](https://github.com/ledger-donjon/lascar) Ledger's Advanced Side-Channel Analysis Repository
- [**269**星][5d] [JS] [nodejs/security-wg](https://github.com/nodejs/security-wg) Node.js Security Working Group
- [**265**星][5d] [C] [eua/wxhexeditor](https://github.com/eua/wxhexeditor) wxHexEditor official GIT repo
- [**265**星][1y] [PS] [fox-it/invoke-aclpwn](https://github.com/fox-it/invoke-aclpwn) 
- [**264**星][11m] [Py] [ant4g0nist/susanoo](https://github.com/ant4g0nist/susanoo) A REST API security testing framework.
- [**264**星][t] [C++] [fransbouma/injectablegenericcamerasystem](https://github.com/fransbouma/injectablegenericcamerasystem) This is a generic camera system to be used as the base for cameras for taking screenshots within games. The main purpose of the system is to hijack the in-game 3D camera by overwriting values in its camera structure with our own values so we can control where the camera is located, it's pitch/yaw/roll values, its FoV and the camera's look vector.
- [**264**星][9m] [C] [landhb/hideprocess](https://github.com/landhb/hideprocess) A basic Direct Kernel Object Manipulation rootkit that removes a process from the EPROCESS list, hiding it from the Task Manager
- [**264**星][1y] [JS] [roccomuso/netcat](https://github.com/roccomuso/netcat) Netcat client and server modules written in pure Javascript for Node.j
- [**263**星][25d] [Py] [guimaizi/get_domain](https://github.com/guimaizi/get_domain) 域名收集与监测
- [**263**星][1m] [Ruby] [rapid7/recog](https://github.com/rapid7/recog) Pattern recognition for hosts, services, and content
- [**262**星][4m] [C] [portcullislabs/linikatz](https://github.com/portcullislabs/linikatz) UNIX版本的Mimikatz
- [**262**星][] [rustsec/advisory-db](https://github.com/rustsec/advisory-db) Security advisory database for Rust crates published through crates.io
- [**262**星][6d] [Py] [sofianehamlaoui/lockdoor-framework](https://github.com/sofianehamlaoui/lockdoor-framework) 
- [**260**星][12m] [Py] [hysnsec/devsecops-studio](https://github.com/hysnsec/DevSecOps-Studio) DevSecOps Distribution - Virtual Environment to learn DevSecOps
- [**259**星][10d] [C++] [poweradminllc/paexec](https://github.com/poweradminllc/paexec) Remote execution, like PsExec
- [**258**星][1y] [Py] [m4ll0k/galileo](https://github.com/m4ll0k/galileo) Galileo - Web Application Audit Framework
- [**257**星][1m] [Py] [frint0/email-enum](https://github.com/frint0/email-enum) Email-Enum searches mainstream websites and tells you if an email is registered! #DEPRECATED
- [**257**星][10m] [C] [p0f/p0f](https://github.com/p0f/p0f) p0f unofficial git repo
- [**255**星][1m] [Py] [cloudflare/python-cloudflare](https://github.com/cloudflare/python-cloudflare) Python wrapper for the Cloudflare Client API v4
- [**254**星][7m] [Go] [lavalamp-/ipv666](https://github.com/lavalamp-/ipv666) IPV6地址枚举工具. Go编写
- [**254**星][10m] [Py] [wh0ale/src-experience](https://github.com/wh0ale/src-experience) 工欲善其事，必先利其器
- [**252**星][3m] [Py] [cvandeplas/pystemon](https://github.com/cvandeplas/pystemon) Monitoring tool for PasteBin-alike sites written in Python. Inspired by pastemon
- [**252**星][7m] [Py] [itskindred/procspy](https://github.com/itskindred/procspy) Python tool that monitors and logs user-run commands on a Linux system for either offensive or defensive purposes..
- [**252**星][1m] [Py] [rvrsh3ll/findfrontabledomains](https://github.com/rvrsh3ll/findfrontabledomains) Search for potential frontable domains
- [**250**星][9m] [C] [jakeajames/rootlessjb](https://github.com/jakeajames/rootlessjb) 
- [**249**星][19d] [Py] [cisco-config-analysis-tool/ccat](https://github.com/cisco-config-analysis-tool/ccat) Cisco Config Analysis Tool
- [**248**星][8d] [Py] [susmithkrishnan/torghost](https://github.com/SusmithKrishnan/torghost) Tor anonimizer
- [**246**星][8m] [ethicalhack3r/wordpress_plugin_security_testing_cheat_sheet](https://github.com/ethicalhack3r/wordpress_plugin_security_testing_cheat_sheet) WordPress插件安全测试备忘录。
- [**246**星][1y] [xcsh/unity-game-hacking](https://github.com/xcsh/unity-game-hacking) A guide for hacking unity games
- [**244**星][9m] [Py] [mazen160/bfac](https://github.com/mazen160/bfac) 自动化 web app 备份文件测试工具，可检测备份文件是否会泄露 web  app 源代码
- [**244**星][8m] [Py] [openstack/syntribos](https://github.com/openstack/syntribos) 自动化的 API 安全测试工具
- [**242**星][19d] [Rust] [hirrolot/anevicon](https://github.com/Hirrolot/anevicon) 
- [**239**星][1y] [Py] [matthewclarkmay/geoip-attack-map](https://github.com/matthewclarkmay/geoip-attack-map) Cyber security geoip attack map that follows syslog and parses IPs/port numbers to visualize attackers in real time.
- [**238**星][2m] [JS] [martinzhou2015/srcms](https://github.com/martinzhou2015/srcms) SRCMS企业应急响应与缺陷管理系统
- [**238**星][2m] [Py] [timlib/webxray](https://github.com/timlib/webxray) webxray is a tool for analyzing third-party content on webpages and identifying the companies which collect user data.
- [**237**星][11m] [duoergun0729/2book](https://github.com/duoergun0729/2book) 《Web安全之深度学习实战》
- [**236**星][10m] [Py] [cryin/javaid](https://github.com/cryin/javaid) java source code static code analysis and danger function identify prog
- [**236**星][8m] [Py] [xhak9x/fbi](https://github.com/xhak9x/fbi) Facebook Information
- [**231**星][18d] [o-mg/demonseed](https://github.com/o-mg/demonseed) minimal malicious USB cabl
- [**231**星][3d] [Py] [webbreacher/whatsmyname](https://github.com/webbreacher/whatsmyname) This repository has the unified data required to perform user enumeration on various websites. Content is in a JSON file and can easily be used in other projects.
- [**230**星][2m] [Java] [commonsguy/cwac-netsecurity](https://github.com/commonsguy/cwac-netsecurity) CWAC-NetSecurity: Simplifying Secure Internet Access
- [**230**星][2m] [PS] [miriamxyra/eventlist](https://github.com/miriamxyra/eventlist) help improving your Audit capabilities and to help to build your Security Operation Center.
- [**229**星][1m] [C] [vusec/ridl](https://github.com/vusec/ridl) RIDL test suite and exploits
- [**226**星][1y] [Go] [netxfly/sec_check](https://github.com/netxfly/sec_check) 服务器安全检测的辅助工具
- [**226**星][1y] [lanjelot/kb](https://github.com/lanjelot/kb) Respositoy of all my notes on infosec I have been building up over the years
- [**224**星][1y] [basilfx/tradfri-hacking](https://github.com/basilfx/tradfri-hacking) Hacking the IKEA TRÅDFRI light bulbs and accessories.
- [**223**星][1y] [Py] [tkcert/mail-security-tester](https://github.com/tkcert/mail-security-tester) A testing framework for mail security and filtering solutions.
- [**221**星][7m] [bhdresh/dejavu](https://github.com/bhdresh/dejavu) deception framework which can be used to deploy decoys across the infrastructure
- [**220**星][5m] [Shell] [vedetta-com/vedetta](https://github.com/vedetta-com/vedetta) OpenBSD Router Boilerplate
- [**220**星][15d] [Py] [wazuh/wazuh-ruleset](https://github.com/wazuh/wazuh-ruleset) ruleset is used to detect attacks, intrusions, software misuse, configuration problems, application errors, malware, rootkits, system anomalies or security policy violations.
- [**219**星][9m] [JS] [zhuyingda/veneno](https://github.com/zhuyingda/veneno) 用Node.js编写的Web安全测试框架
- [**218**星][10m] [C] [feexd/pocs](https://github.com/feexd/pocs) 
- [**218**星][10m] [JS] [jopyth/mmm-remote-control](https://github.com/jopyth/mmm-remote-control) Magic Mirror Module to shutdown or configure your mirror
- [**217**星][10m] [Py] [mckinsey666/vocabs](https://github.com/Mckinsey666/vocabs) A lightweight online dictionary integration to the command line
- [**216**星][3m] [Py] [jordanpotti/cloudscraper](https://github.com/jordanpotti/cloudscraper) Tool to enumerate targets in search of cloud resources. S3 Buckets, Azure Blobs, Digital Ocean Storage Space.
- [**216**星][9m] [C] [sleinen/samplicator](https://github.com/sleinen/samplicator) Send copies of (UDP) datagrams to multiple receivers, with optional sampling and spoofing
- [**215**星][6m] [C#] [erfg12/memory.dll](https://github.com/erfg12/memory.dll) C# Hacking library for making PC game trainers.
- [**214**星][5m] [Py] [infosecn1nja/maliciousmacromsbuild](https://github.com/infosecn1nja/maliciousmacromsbuild) Generates Malicious Macro and Execute Powershell or Shellcode via MSBuild Application Whitelisting Bypass.
- [**213**星][6m] [Py] [dirkjanm/krbrelayx](https://github.com/dirkjanm/krbrelayx) Kerberos unconstrained delegation abuse toolkit
- [**213**星][27d] [Py] [nyxgeek/lyncsmash](https://github.com/nyxgeek/lyncsmash) locate and attack Lync/Skype for Business
- [**210**星][5m] [Java] [dschanoeh/kayak](https://github.com/dschanoeh/kayak) Kayak is a CAN bus analysis tool based on SocketCAN
- [**210**星][3m] [Py] [si9int/cc.py](https://github.com/si9int/cc.py) Extracting URLs of a specific target based on the results of "commoncrawl.org"
- [**210**星][2m] [Shell] [hak5/lanturtle-modules](https://github.com/hak5/lanturtle-modules) The Official LAN Turtle Module Repository
- [**209**星][5m] [PS] [harmj0y/damp](https://github.com/harmj0y/damp) The Discretionary ACL Modification Project: Persistence Through Host-based Security Descriptor Modification
- [**208**星][11d] [C#] [b4rtik/redpeanut](https://github.com/b4rtik/redpeanut) RedPeanut is a small RAT developed in .Net Core 2 and its agent in .Net 3.5 / 4.0.
- [**208**星][1m] [Py] [seahoh/gotox](https://github.com/seahoh/gotox) 本地自动代理，修改自 goagent。
- [**207**星][8m] [1hack0/facebook-bug-bounty-write-ups](https://github.com/1hack0/facebook-bug-bounty-write-ups) Hunting Bugs for Fun and Profit
- [**207**星][4m] [HCL] [byt3bl33d3r/red-baron](https://github.com/byt3bl33d3r/red-baron) Automate creating resilient, disposable, secure and agile infrastructure for Red Teams
- [**207**星][5m] [YARA] [th3hurrican3/pepper](https://github.com/th3hurrican3/pepper) An open source script to perform malware static analysis on Portable Executable
- [**206**星][1y] [JS] [jpcertcc/sysmonsearch](https://github.com/jpcertcc/sysmonsearch) Investigate suspicious activity by visualizing Sysmon's event log
- [**206**星][1y] [Py] [orf/xcat](https://github.com/orf/xcat) 辅助盲 Xpath 注入，检索正在由 Xpath 查询处理的整个 XML 文档，读取主机文件系统上的任意文件，并使用出站 HTTP 请求，使服务器将数据直接发送到xcat
- [**206**星][9m] [Py] [openstack/hacking](https://github.com/openstack/hacking) OpenStack Hacking Style Checks
- [**204**星][1m] [Jupyter Notebook] [hunters-forge/attack-python-client](https://github.com/hunters-forge/ATTACK-Python-Client) Python Script to access ATT&CK content available in STIX via a public TAXII server
- [**203**星][2m] [TS] [helmetjs/csp](https://github.com/helmetjs/csp) Content Security Policy middleware
- [**203**星][7m] [JS] [wingleung/save-page-state](https://github.com/wingleung/save-page-state) A chrome extension to save the state of a page for further analysis
- [**202**星][10d] [C++] [oisf/libhtp](https://github.com/oisf/libhtp) LibHTP is a security-aware parser for the HTTP protocol and the related bits and pieces.


### <a id="f34b4da04f2a77a185729b5af752efc5"></a>未分类




### <a id="b9dc08e7e118fc7af41df5e0ef9ddc3c"></a>新添加1




### <a id="efb2cfb167e34b03243547cfb3a662ac"></a>新添加2




### <a id="f04dd1be8e552b074dde7cb33ae6c84c"></a>未分类3




### <a id="cbb37de8d70e314ce905d78c566ef384"></a>未分类4




### <a id="bb7173c3a2ea52d046c8abe3c57e3291"></a>未分类5




### <a id="f7654997cf8b691617b89c5e523a942f"></a>其他


- [**923**星][3d] [C] [arm-software/arm-trusted-firmware](https://github.com/arm-software/arm-trusted-firmware) Arm A-Profile体系结构（Armv8-A和Armv7-A）的安全世界软件的参考实现，其中包括Exception Level 3（EL3）安全监视器。




***


## <a id="d5e869a870d6e2c14911de2bc527a6ef"></a>古老的&&有新的替代版本的


- [**1605**星][3m] [Py] [knownsec/pocsuite](https://github.com/knownsec/pocsuite) This project has stopped to maintenance, please to


***


## <a id="8603294b7c1f136b866b6402d63a9978"></a>文章


### <a id="f110da0bf67359d3abc62b27d717e55e"></a>新添加的






# <a id="a4ee2f4d4a944b54b2246c72c037cd2e"></a>收集&&集合


***


## <a id="e97d183e67fa3f530e7d0e7e8c33ee62"></a>未分类


- [**4252**星][22d] [qazbnm456/awesome-web-security](https://github.com/qazbnm456/awesome-web-security) web 安全资源列表
- [**3168**星][8d] [CSS] [juliocesarfort/public-pentesting-reports](https://github.com/juliocesarfort/public-pentesting-reports) Curated list of public penetration test reports released by several consulting firms and academic security groups
- [**2904**星][3m] [infosecn1nja/red-teaming-toolkit](https://github.com/infosecn1nja/red-teaming-toolkit) A collection of open source and commercial tools that aid in red team operations.
- [**2680**星][4d] [rmusser01/infosec_reference](https://github.com/rmusser01/infosec_reference) An Information Security Reference That Doesn't Suck
- [**2529**星][3m] [kbandla/aptnotes](https://github.com/kbandla/aptnotes) Various public documents, whitepapers and articles about APT campaigns
- [**2474**星][2m] [Py] [0xinfection/awesome-waf](https://github.com/0xinfection/awesome-waf) 
- [**2345**星][12d] [yeyintminthuhtut/awesome-red-teaming](https://github.com/yeyintminthuhtut/awesome-red-teaming) List of Awesome Red Teaming Resources
- [**2161**星][10m] [exakat/php-static-analysis-tools](https://github.com/exakat/php-static-analysis-tools) A reviewed list of useful PHP static analysis tools
- [**2116**星][1m] [infoslack/awesome-web-hacking](https://github.com/infoslack/awesome-web-hacking) A list of web application security
- [**2067**星][2d] [tanprathan/mobileapp-pentest-cheatsheet](https://github.com/tanprathan/mobileapp-pentest-cheatsheet) The Mobile App Pentest cheat sheet was created to provide concise collection of high value information on specific mobile application penetration testing topics.
- [**2066**星][1y] [bluscreenofjeff/red-team-infrastructure-wiki](https://github.com/bluscreenofjeff/red-team-infrastructure-wiki) Wiki to collect Red Team infrastructure hardening resources
- [**1930**星][3m] [toolswatch/blackhat-arsenal-tools](https://github.com/toolswatch/blackhat-arsenal-tools) Black Hat 武器库
- [**1845**星][2m] [djadmin/awesome-bug-bounty](https://github.com/djadmin/awesome-bug-bounty) A comprehensive curated list of available Bug Bounty & Disclosure Programs and Write-ups.
- [**1760**星][1y] [coreb1t/awesome-pentest-cheat-sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) Collection of the cheat sheets useful for pentesting
- [**1752**星][1m] [ngalongc/bug-bounty-reference](https://github.com/ngalongc/bug-bounty-reference) Inspired by
- [**1716**星][4m] [R] [briatte/awesome-network-analysis](https://github.com/briatte/awesome-network-analysis) A curated list of awesome network analysis resources.
- [**1602**星][7m] [Py] [w1109790800/penetration](https://github.com/w1109790800/penetration) 渗透 超全面的渗透资料
- [**1585**星][7m] [Ruby] [brunofacca/zen-rails-security-checklist](https://github.com/brunofacca/zen-rails-security-checklist) Checklist of security precautions for Ruby on Rails applications.
- [**1546**星][9d] [emijrp/awesome-awesome](https://github.com/emijrp/awesome-awesome) A curated list of awesome curated lists of many topics.
- [**1534**星][6m] [snowming04/the-hacker-playbook-3-translation](https://github.com/snowming04/the-hacker-playbook-3-translation) 对 The Hacker Playbook 3 的翻译。
- [**1376**星][2m] [grrrdog/java-deserialization-cheat-sheet](https://github.com/grrrdog/java-deserialization-cheat-sheet) The cheat sheet about Java Deserialization vulnerabilities
- [**1242**星][1y] [Ruby] [eliotsykes/rails-security-checklist](https://github.com/eliotsykes/rails-security-checklist) 
- [**1207**星][8m] [joe-shenouda/awesome-cyber-skills](https://github.com/joe-shenouda/awesome-cyber-skills) A curated list of hacking environments where you can train your cyber skills legally and safely
- [**1197**星][1m] [Py] [cujanovic/ssrf-testing](https://github.com/cujanovic/ssrf-testing) SSRF (Server Side Request Forgery) testing resources
- [**1172**星][7d] [m4ll0k/awesome-hacking-tools](https://github.com/m4ll0k/awesome-hacking-tools) Awesome Hacking Tools
- [**1164**星][4d] [w00t3k/awesome-cellular-hacking](https://github.com/w00t3k/awesome-cellular-hacking) Awesome-Cellular-Hacking
- [**1145**星][1m] [Batchfile] [ckjbug/hacking](https://github.com/ckjbug/hacking) 
- [**1116**星][11d] [slowmist/knowledge-base](https://github.com/slowmist/knowledge-base) Knowledge Base 慢雾安全团队知识库
- [**1115**星][1y] [paulsec/awesome-windows-domain-hardening](https://github.com/PaulSec/awesome-windows-domain-hardening) A curated list of awesome Security Hardening techniques for Windows.
- [**1110**星][5m] [zbetcheckin/security_list](https://github.com/zbetcheckin/security_list) Great security list for fun and profit
- [**1080**星][1m] [guardrailsio/awesome-golang-security](https://github.com/guardrailsio/awesome-golang-security) Awesome Golang Security resources
- [**1030**星][7m] [stephenturner/oneliners](https://github.com/stephenturner/oneliners) Useful bash one-liners for bioinformatics.
- [**1026**星][7d] [sundowndev/hacker-roadmap](https://github.com/sundowndev/hacker-roadmap) 
- [**1013**星][1y] [JS] [0xsobky/hackvault](https://github.com/0xsobky/hackvault) A container repository for my public web hacks!
- [**993**星][9d] [Py] [jekil/awesome-hacking](https://github.com/jekil/awesome-hacking) Awesome hacking is an awesome collection of hacking tools.
- [**986**星][7m] [0x4d31/awesome-threat-detection](https://github.com/0x4d31/awesome-threat-detection) A curated list of awesome threat detection and hunting resources
- [**959**星][9m] [wtsxdev/penetration-testing](https://github.com/wtsxdev/penetration-testing) List of awesome penetration testing resources, tools and other shiny things
- [**929**星][2m] [tom0li/collection-document](https://github.com/tom0li/collection-document) Collection of quality safety articles
- [**921**星][7m] [PS] [api0cradle/ultimateapplockerbypasslist](https://github.com/api0cradle/ultimateapplockerbypasslist) The goal of this repository is to document the most common techniques to bypass AppLocker.
- [**917**星][7m] [cn0xroot/rfsec-toolkit](https://github.com/cn0xroot/rfsec-toolkit) RFSec-ToolKit is a collection of Radio Frequency Communication Protocol Hacktools.无线通信协议相关的工具集，可借助SDR硬件+相关工具对无线通信进行研究。Collect with ♥ by HackSmith
- [**906**星][24d] [Shell] [dominicbreuker/stego-toolkit](https://github.com/dominicbreuker/stego-toolkit) Collection of steganography tools - helps with CTF challenges
- [**871**星][3d] [explife0011/awesome-windows-kernel-security-development](https://github.com/explife0011/awesome-windows-kernel-security-development) windows kernel security development
- [**829**星][5m] [Shell] [danielmiessler/robotsdisallowed](https://github.com/danielmiessler/robotsdisallowed) A curated list of the most common and most interesting robots.txt disallowed directories.
- [**823**星][3m] [feeicn/security-ppt](https://github.com/feeicn/security-ppt) 大安全各领域各公司各会议分享的PPT
- [**788**星][11m] [v2-dev/awesome-social-engineering](https://github.com/v2-dev/awesome-social-engineering) 社会工程学资源集合
- [**766**星][2m] [daviddias/awesome-hacking-locations](https://github.com/daviddias/awesome-hacking-locations) 
- [**736**星][1y] [Py] [averagesecurityguy/scripts](https://github.com/averagesecurityguy/scripts) Scripts I use during pentest engagements.
- [**728**星][3m] [C#] [harleyqu1nn/aggressorscripts](https://github.com/harleyqu1nn/aggressorscripts) Collection of Aggressor scripts for Cobalt Strike 3.0+ pulled from multiple sources
- [**714**星][1y] [snifer/security-cheatsheets](https://github.com/snifer/security-cheatsheets) A collection of cheatsheets for various infosec tools and topics.
- [**712**星][5m] [bit4woo/python_sec](https://github.com/bit4woo/python_sec) python安全和代码审计相关资料收集 resource collection of python security and code review
- [**685**星][24d] [XSLT] [adon90/pentest_compilation](https://github.com/adon90/pentest_compilation) Compilation of commands, tips and scripts that helped me throughout Vulnhub, Hackthebox, OSCP and real scenarios
- [**684**星][2m] [andrewjkerr/security-cheatsheets](https://github.com/andrewjkerr/security-cheatsheets) 
- [**671**星][1y] [dsasmblr/hacking-online-games](https://github.com/dsasmblr/hacking-online-games) A curated list of tutorials/resources for hacking online games.
- [**665**星][1m] [redhuntlabs/awesome-asset-discovery](https://github.com/redhuntlabs/awesome-asset-discovery) List of Awesome Asset Discovery Resources
- [**633**星][4m] [3gstudent/pentest-and-development-tips](https://github.com/3gstudent/pentest-and-development-tips) A collection of pentest and development tips
- [**632**星][10m] [webbreacher/offensiveinterview](https://github.com/webbreacher/offensiveinterview) Interview questions to screen offensive (red team/pentest) candidates
- [**629**星][4m] [bypass007/safety-project-collection](https://github.com/bypass007/safety-project-collection) 收集一些比较优秀的开源安全项目，以帮助甲方安全从业人员构建企业安全能力。
- [**619**星][1y] [jiangsir404/audit-learning](https://github.com/jiangsir404/audit-learning) 记录自己对《代码审计》的理解和总结，对危险函数的深入分析以及在p牛的博客和代码审计圈的收获
- [**613**星][3m] [Shell] [ashishb/osx-and-ios-security-awesome](https://github.com/ashishb/osx-and-ios-security-awesome) OSX and iOS related security tools
- [**601**星][1m] [Py] [hslatman/awesome-industrial-control-system-security](https://github.com/hslatman/awesome-industrial-control-system-security) 工控系统安全资源列表
- [**593**星][23d] [lirantal/awesome-nodejs-security](https://github.com/lirantal/awesome-nodejs-security) Awesome Node.js Security resources
- [**592**星][12m] [pandazheng/ioshackstudy](https://github.com/pandazheng/ioshackstudy) IOS安全学习资料汇总
- [**571**星][3m] [r35tart/penetration_testing_case](https://github.com/r35tart/penetration_testing_case) 用于记录分享一些有趣的案例
- [**560**星][9m] [guardrailsio/awesome-python-security](https://github.com/guardrailsio/awesome-python-security) Awesome Python Security resources
- [**558**星][10m] [guardrailsio/awesome-php-security](https://github.com/guardrailsio/awesome-php-security) Awesome PHP Security Resources
- [**530**星][20d] [a13xp0p0v/linux-kernel-defence-map](https://github.com/a13xp0p0v/linux-kernel-defence-map) Linux内核防御地图
- [**477**星][1y] [hack-with-github/powerful-plugins](https://github.com/hack-with-github/powerful-plugins) Powerful plugins and add-ons for hackers
- [**468**星][19d] [meitar/awesome-cybersecurity-blueteam](https://github.com/meitar/awesome-cybersecurity-blueteam) 
- [**465**星][26d] [gradiuscypher/infosec_getting_started](https://github.com/gradiuscypher/infosec_getting_started) A collection of resources/documentation/links/etc to help people learn about Infosec and break into the field.
- [**460**星][4m] [C++] [comaeio/opcde](https://github.com/comaeio/opcde) OPCDE Cybersecurity Conference Materials
- [**448**星][7m] [jnusimba/miscsecnotes](https://github.com/jnusimba/miscsecnotes) some learning notes about Web/Cloud/Docker Security、 Penetration Test、 Security Building
- [**438**星][1y] [meitar/awesome-lockpicking](https://github.com/meitar/awesome-lockpicking) 有关锁、保险箱、钥匙的指南、工具及其他资源的列表
- [**437**星][4m] [re4lity/hacking-with-golang](https://github.com/re4lity/hacking-with-golang) Golang安全资源合集
- [**426**星][21d] [dropsofzut/awesome-security-weixin-official-accounts](https://github.com/dropsofzut/awesome-security-weixin-official-accounts) 网络安全类公众号推荐，欢迎大家推荐
- [**423**星][12m] [Lua] [w3h/icsmaster](https://github.com/w3h/icsmaster) 整合工控安全相关资源
- [**411**星][5d] [Py] [bl4de/security-tools](https://github.com/bl4de/security-tools) Collection of small security tools created mostly in Python. CTFs, pentests and so on
- [**411**星][1m] [husnainfareed/awesome-ethical-hacking-resources](https://github.com/husnainfareed/Awesome-Ethical-Hacking-Resources) 
- [**407**星][8m] [kai5263499/osx-security-awesome](https://github.com/kai5263499/osx-security-awesome) A collection of OSX and iOS security resources
- [**397**星][7m] [HTML] [gexos/hacking-tools-repository](https://github.com/gexos/hacking-tools-repository) A list of security/hacking tools that have been collected from the internet. Suggestions are welcomed.
- [**392**星][2m] [dsopas/assessment-mindset](https://github.com/dsopas/assessment-mindset) 安全相关的思维导图, 可用于pentesting, bug bounty, red-teamassessments
- [**383**星][2m] [thejambo/awesome-testing](https://github.com/thejambo/awesome-testing) A curated list of testing resources
- [**375**星][8m] [opencybertranslationproject/linux-basics-for-hackers](https://github.com/opencybertranslationproject/linux-basics-for-hackers) 书籍《Linux Basics for Hackers》2019版中文翻译版
- [**369**星][20d] [fkromer/awesome-ros2](https://github.com/fkromer/awesome-ros2) The Robot Operating System Version 2.0 is awesome!
- [**363**星][3d] [hongrisec/web-security-attack](https://github.com/hongrisec/web-security-attack) Web安全相关内容
- [**345**星][2m] [softwareunderground/awesome-open-geoscience](https://github.com/softwareunderground/awesome-open-geoscience) Curated from repositories that make our lives as geoscientists, hackers and data wranglers easier or just more awesome
- [**335**星][t] [stamparm/ipsum](https://github.com/stamparm/ipsum) Daily feed of bad IPs (with blacklist hit scores)
- [**334**星][5d] [PS] [mgeeky/penetration-testing-tools](https://github.com/mgeeky/penetration-testing-tools) A collection of my Penetration Testing scripts, tools, cheatsheets collected over years, used during real-world assignments or collected from various good quality sources.
- [**327**星][9m] [pxlpnk/awesome-ruby-security](https://github.com/pxlpnk/awesome-ruby-security) Awesome Ruby Security resources
- [**321**星][2m] [HTML] [eugenekolo/sec-tools](https://github.com/eugenekolo/sec-tools) A set of security related tools
- [**318**星][3d] [cryptax/confsec](https://github.com/cryptax/confsec) Security, hacking conferences (list)
- [**315**星][22d] [trimstray/technical-whitepapers](https://github.com/trimstray/technical-whitepapers) 收集：IT白皮书、PPT、PDF、Hacking、Web应用程序安全性、数据库、逆向等
- [**312**星][10m] [Shell] [swoodford/aws](https://github.com/swoodford/aws) A collection of bash shell scripts for automating various tasks with Amazon Web Services using the AWS CLI and jq.
- [**310**星][1y] [1522402210/2018-blackhat-tools-list](https://github.com/1522402210/2018-blackhat-tools-list) 2018 BlackHat Tools List
- [**309**星][2m] [no-github/dork-admin](https://github.com/no-github/dork-admin) 盘点近年来的数据泄露、供应链污染事件
- [**299**星][15d] [JS] [aws-samples/aws-serverless-security-workshop](https://github.com/aws-samples/aws-serverless-security-workshop) In this workshop, you will learn techniques to secure a serverless application built with AWS Lambda, Amazon API Gateway and RDS Aurora. We will cover AWS services and features you can leverage to improve the security of a serverless applications in 5 domains: identity & access management, code, data, infrastructure, logging & monitoring.
- [**295**星][1y] [findneo/newbie-security-list](https://github.com/findneo/newbie-security-list) 网络安全学习资料，欢迎补充
- [**294**星][7m] [JS] [ma3k4h3d/papers](https://github.com/ma3k4h3d/papers) Some papers about cyber security
- [**287**星][10m] [wallarm/awesome-nginx-security](https://github.com/wallarm/awesome-nginx-security) 
- [**276**星][4m] [mattnotmax/cyberchef-recipes](https://github.com/mattnotmax/cyberchef-recipes) A list of cyber-chef recipes
- [**272**星][8d] [JS] [ropnop/serverless_toolkit](https://github.com/ropnop/serverless_toolkit) A collection of useful Serverless functions I use when pentesting
- [**260**星][5m] [zhaoweiho/web-sec-interview](https://github.com/zhaoweiho/web-sec-interview) Information Security (Web Security/Penetration Testing Direction) Interview Questions/Solutions 信息安全(Web安全/渗透测试方向)面试题/解题思路
- [**260**星][27d] [thelsa/cs-checklist](https://github.com/thelsa/cs-checklist) PC客户端（C-S架构）渗透测试checklist / Client side(C-S) penestration checklist
- [**243**星][7d] [euphrat1ca/security_w1k1](https://github.com/euphrat1ca/security_w1k1) collect
- [**239**星][6d] [pe3zx/my-infosec-awesome](https://github.com/pe3zx/my-infosec-awesome) My curated list of awesome links, resources and tools on infosec related topics
- [**228**星][6m] [guardrailsio/awesome-dotnet-security](https://github.com/guardrailsio/awesome-dotnet-security) Awesome .NET Security Resources
- [**223**星][5d] [decalage2/awesome-security-hardening](https://github.com/decalage2/awesome-security-hardening) A collection of awesome security hardening guides, tools and other resources
- [**222**星][9m] [jesusprubio/awesome-nodejs-pentest](https://github.com/jesusprubio/awesome-nodejs-pentest) 
- [**221**星][4m] [security-checklist/php-security-check-list](https://github.com/security-checklist/php-security-check-list) PHP Security Check List [ EN ]
- [**216**星][10m] [puresec/awesome-serverless-security](https://github.com/puresec/awesome-serverless-security) A curated list of awesome serverless security resources such as (e)books, articles, whitepapers, blogs and research papers.
- [**214**星][3d] [shogunlab/awesome-hyper-v-exploitation](https://github.com/shogunlab/awesome-hyper-v-exploitation) A curated list of Hyper-V exploitation resources, fuzzing and vulnerability research.
- [**213**星][10m] [jeansgit/redteam](https://github.com/jeansgit/redteam) RedTeam资料收集整理
- [**213**星][3m] [Shell] [xu-jian/vps](https://github.com/xu-jian/vps) 个人笔记汇总
- [**209**星][28d] [sigp/solidity-security-blog](https://github.com/sigp/solidity-security-blog) Comprehensive list of known attack vectors and common anti-patterns
- [**207**星][1y] [faizann24/resources-for-learning-hacking](https://github.com/faizann24/resources-for-learning-hacking) All the resources I could find for learning Ethical Hacking and penetration testing.


***


## <a id="664ff1dbdafefd7d856c88112948a65b"></a>混合型收集


- [**24868**星][8d] [trimstray/the-book-of-secret-knowledge](https://github.com/trimstray/the-book-of-secret-knowledge) A collection of inspiring lists, manuals, cheatsheets, blogs, hacks, one-liners, cli/web tools and more.
- [**10920**星][26d] [enaqx/awesome-pentest](https://github.com/enaqx/awesome-pentest) 渗透测试资源/工具集
- [**5513**星][9m] [carpedm20/awesome-hacking](https://github.com/carpedm20/awesome-hacking) Hacking教程、工具和资源
- [**5121**星][2m] [sbilly/awesome-security](https://github.com/sbilly/awesome-security) 与安全相关的软件、库、文档、书籍、资源和工具等收集
- [**3230**星][6d] [Rich Text Format] [the-art-of-hacking/h4cker](https://github.com/The-Art-of-Hacking/h4cker) 资源收集：hacking、渗透、数字取证、事件响应、漏洞研究、漏洞开发、逆向
- [**1904**星][20d] [olivierlaflamme/cheatsheet-god](https://github.com/olivierlaflamme/cheatsheet-god) Penetration Testing Reference Bank - OSCP / PTP & PTX Cheatsheet
- [**591**星][6d] [Perl] [bollwarm/sectoolset](https://github.com/bollwarm/sectoolset) 安全项目工具集合
- [**587**星][6m] [d30sa1/rootkits-list-download](https://github.com/d30sa1/rootkits-list-download) Rootkit收集


***


## <a id="67acc04b20c99f87ee625b073330d8c2"></a>无工具类收集


- [**34045**星][21d] [Py] [minimaxir/big-list-of-naughty-strings](https://github.com/minimaxir/big-list-of-naughty-strings) “淘气”的字符串列表，当作为用户输入时很容易引发问题
- [**9042**星][3m] [vitalysim/awesome-hacking-resources](https://github.com/vitalysim/awesome-hacking-resources) A collection of hacking / penetration testing resources to make you better!
- [**3616**星][9d] [blacckhathaceekr/pentesting-bible](https://github.com/blacckhathaceekr/pentesting-bible) links reaches 10000 links & 10000 pdf files .Learn Ethical Hacking and penetration testing .hundreds of ethical hacking & penetration testing & red team & cyber security & computer science resources.
- [**2800**星][2m] [secwiki/sec-chart](https://github.com/secwiki/sec-chart) 安全思维导图集合
- [**2671**星][1y] [HTML] [chybeta/web-security-learning](https://github.com/chybeta/web-security-learning) Web-Security-Learning
- [**2519**星][17d] [onlurking/awesome-infosec](https://github.com/onlurking/awesome-infosec) A curated list of awesome infosec courses and training resources.
- [**2356**星][11m] [hack-with-github/free-security-ebooks](https://github.com/hack-with-github/free-security-ebooks) Free Security and Hacking eBooks
- [**2118**星][3m] [yeahhub/hacking-security-ebooks](https://github.com/yeahhub/hacking-security-ebooks) Top 100 Hacking & Security E-Books (Free Download)
- [**1956**星][1m] [Py] [nixawk/pentest-wiki](https://github.com/nixawk/pentest-wiki) PENTEST-WIKI is a free online security knowledge library for pentesters / researchers. If you have a good idea, please share it with others.
- [**1955**星][1m] [hmaverickadams/beginner-network-pentesting](https://github.com/hmaverickadams/beginner-network-pentesting) Notes for Beginner Network Pentesting Course


***


## <a id="24707dd322098f73c7e450d6b1eddf12"></a>收集类的收集


- [**33101**星][3m] [hack-with-github/awesome-hacking](https://github.com/hack-with-github/awesome-hacking) A collection of various awesome lists for hackers, pentesters and security researchers


***


## <a id="9101434a896f20263d09c25ace65f398"></a>教育资源&&课程&&教程&&书籍


- [**10944**星][2m] [CSS] [hacker0x01/hacker101](https://github.com/hacker0x01/hacker101) Hacker101
- [**3945**星][4m] [PHP] [paragonie/awesome-appsec](https://github.com/paragonie/awesome-appsec) A curated list of resources for learning about application security
- [**959**星][5m] [bugcrowd/bugcrowd_university](https://github.com/bugcrowd/bugcrowd_university) 研究者社区的教育内容
- [**936**星][7m] [Py] [osirislab/hack-night](https://github.com/osirislab/Hack-Night) a sobering introduction to offensive security


***


## <a id="8088e46fc533286d88b945f1d472bf57"></a>笔记&&Tips&&Tricks


### <a id="f57ccaab4279b60c17a03f90d96b815c"></a>未分类


- [**2816**星][2m] [paulsec/awesome-sec-talks](https://github.com/paulsec/awesome-sec-talks) A collected list of awesome security talks
- [**864**星][2d] [Py] [lylemi/learn-web-hacking](https://github.com/lylemi/learn-web-hacking) Web安全学习笔记
- [**723**星][3m] [uknowsec/active-directory-pentest-notes](https://github.com/uknowsec/active-directory-pentest-notes) 个人域渗透学习笔记
- [**593**星][1m] [PS] [threatexpress/red-team-scripts](https://github.com/threatexpress/red-team-scripts) A collection of Red Team focused tools, scripts, and notes


### <a id="0476f6b97e87176da0a0d7328f8747e7"></a>blog


- [**1229**星][5m] [chalker/notes](https://github.com/chalker/notes) Some public notes




***


## <a id="df8ec4a66ef5027bbcc591c94f8de1e5"></a>Talk&&Conference 




***


## <a id="4be58a3a00f83975b0321425db3b9b68"></a>文档&&Documentation&&规则说明&&RFC


- [**1705**星][10m] [CSS] [bagder/http2-explained](https://github.com/bagder/http2-explained) A detailed document explaining and documenting HTTP/2, the successor to the widely popular HTTP/1.1 protocol


# <a id="7e840ca27f1ff222fd25bc61a79b07ba"></a>特定目标


***


## <a id="eb2d1ffb231cee014ed24d59ca987da2"></a>未分类-XxTarget


- [**4177**星][4d] [Java] [spring-projects/spring-security](https://github.com/spring-projects/spring-security) Spring Security
- [**2942**星][6d] [Go] [securego/gosec](https://github.com/securego/gosec) Golang security checker
- [**1906**星][2m] [Py] [pycqa/bandit](https://github.com/pycqa/bandit) 在Python代码中查找常见的安全问题


***


## <a id="c71ad1932bbf9c908af83917fe1fd5da"></a>AWS


- [**4471**星][1y] [Go] [wallix/awless](https://github.com/wallix/awless) A Mighty CLI for AWS
- [**4271**星][4m] [Py] [dxa4481/trufflehog](https://github.com/dxa4481/trufflehog) Searches through git repositories for high entropy strings and secrets, digging deep into commit history
- [**3301**星][5d] [Shell] [toniblyx/my-arsenal-of-aws-security-tools](https://github.com/toniblyx/my-arsenal-of-aws-security-tools) List of open source tools for AWS security: defensive, offensive, auditing, DFIR, etc.
- [**3154**星][5d] [JS] [duo-labs/cloudmapper](https://github.com/duo-labs/cloudmapper) 生成AWS环境的网络拓扑图
- [**2895**星][3d] [Go] [99designs/aws-vault](https://github.com/99designs/aws-vault) A vault for securely storing and accessing AWS credentials in development environments
- [**2645**星][4m] [Java] [teevity/ice](https://github.com/teevity/ice) AWS Usage Tool
- [**2374**星][5m] [Go] [mlabouardy/komiser](https://github.com/mlabouardy/komiser) 
- [**1912**星][6d] [Shell] [toniblyx/prowler](https://github.com/toniblyx/prowler) AWS Security Best Practices Assessment, Auditing, Hardening and Forensics Readiness Tool. It follows guidelines of the CIS Amazon Web Services Foundations Benchmark and DOZENS of additional checks including GDPR and HIPAA (+100). Official CIS for AWS guide:
- [**1895**星][3d] [Py] [mozilla/mozdef](https://github.com/mozilla/mozdef) Mozilla Enterprise Defense Platform
- [**1604**星][1y] [Py] [nccgroup/scout2](https://github.com/nccgroup/Scout2) Security auditing tool for AWS environments
- [**1386**星][12m] [Py] [eth0izzle/bucket-stream](https://github.com/eth0izzle/bucket-stream) 通过certstream 监控多种证书 transparency 日志, 进而查找有趣的 Amazon S3 Buckets
- [**1198**星][17d] [Py] [lyft/cartography](https://github.com/lyft/cartography) Cartography is a Python tool that consolidates infrastructure assets and the relationships between them in an intuitive graph view powered by a Neo4j database.
- [**1149**星][4m] [Py] [rhinosecuritylabs/pacu](https://github.com/rhinosecuritylabs/pacu) The AWS exploitation framework, designed for testing the security of Amazon Web Services environments.
- [**938**星][3m] [Py] [sa7mon/s3scanner](https://github.com/sa7mon/s3scanner) Scan for open AWS S3 buckets and dump the contents
- [**844**星][26d] [Py] [jordanpotti/awsbucketdump](https://github.com/jordanpotti/awsbucketdump) 快速枚举 AWS S3 Buckets，查找感兴趣的文件。类似于子域名爆破，但针对S3 Bucket，有额外功能，例如下载文件等
- [**814**星][7d] [Go] [rebuy-de/aws-nuke](https://github.com/rebuy-de/aws-nuke) Nuke a whole AWS account and delete all its resources.
- [**804**星][2d] [Py] [awslabs/aws-config-rules](https://github.com/awslabs/aws-config-rules) [Node, Python, Java] Repository of sample Custom Rules for AWS Config.
- [**786**星][11d] [Go] [liamg/tfsec](https://github.com/liamg/tfsec) 
- [**774**星][13d] [Java] [tmobile/pacbot](https://github.com/tmobile/pacbot) PacBot (Policy as Code Bot)
- [**613**星][3m] [Py] [netflix/repokid](https://github.com/netflix/repokid) AWS Least Privilege for Distributed, High-Velocity Deployment
- [**609**星][21d] [Shell] [securityftw/cs-suite](https://github.com/securityftw/cs-suite) Cloud Security Suite - One stop tool for auditing the security posture of AWS/GCP/Azure infrastructure.
- [**563**星][3m] [Shell] [denizparlak/zeus](https://github.com/denizparlak/zeus) AWS Auditing & Hardening Tool
- [**548**星][9d] [Ruby] [stelligent/cfn_nag](https://github.com/stelligent/cfn_nag) Linting tool for CloudFormation templates
- [**539**星][4d] [Py] [salesforce/policy_sentry](https://github.com/salesforce/policy_sentry) IAM Least Privilege Policy Generator
- [**505**星][3m] [Py] [awslabs/aws-security-benchmark](https://github.com/awslabs/aws-security-benchmark) Open source demos, concept and guidance related to the AWS CIS Foundation framework.
- [**485**星][19d] [Py] [netflix-skunkworks/diffy](https://github.com/netflix-skunkworks/diffy) Diffy is a triage tool used during cloud-centric security incidents, to help digital forensics and incident response (DFIR) teams quickly identify suspicious hosts on which to focus their response.
- [**462**星][8m] [Py] [ustayready/fireprox](https://github.com/ustayready/fireprox) AWS API Gateway management tool for creating on the fly HTTP pass-through proxies for unique IP rotation
- [**409**星][2m] [Ruby] [arkadiyt/aws_public_ips](https://github.com/arkadiyt/aws_public_ips) Fetch all public IP addresses tied to your AWS account. Works with IPv4/IPv6, Classic/VPC networking, and across all AWS services
- [**400**星][4m] [Py] [duo-labs/cloudtracker](https://github.com/duo-labs/cloudtracker) CloudTracker helps you find over-privileged IAM users and roles by comparing CloudTrail logs with current IAM policies.
- [**389**星][2m] [Py] [riotgames/cloud-inquisitor](https://github.com/riotgames/cloud-inquisitor) Enforce ownership and data security within AWS
- [**370**星][11m] [Py] [awslabs/aws-security-automation](https://github.com/awslabs/aws-security-automation) Collection of scripts and resources for DevSecOps and Automated Incident Response Security
- [**365**星][7m] [Py] [carnal0wnage/weirdaal](https://github.com/carnal0wnage/weirdaal) WeirdAAL (AWS Attack Library)
- [**343**星][2m] [Ruby] [anaynayak/aws-security-viz](https://github.com/anaynayak/aws-security-viz) Visualize your aws security groups.
- [**321**星][1y] [Py] [securing/dumpsterdiver](https://github.com/securing/dumpsterdiver) Tool to search secrets in various filetypes.
- [**292**星][8m] [Py] [cesar-rodriguez/terrascan](https://github.com/cesar-rodriguez/terrascan) Collection of security and best practice test for static code analysis of terraform templates
- [**289**星][1y] [Py] [nccgroup/aws-inventory](https://github.com/nccgroup/aws-inventory) 发现在AWS账户中创建的资源
- [**274**星][2m] [Py] [nccgroup/pmapper](https://github.com/nccgroup/pmapper) A tool for quickly evaluating IAM permissions in AWS.
- [**260**星][11d] [Py] [voulnet/barq](https://github.com/voulnet/barq) The AWS Cloud Post Exploitation framework!
- [**258**星][14d] [Jupyter Notebook] [aws-samples/aws-security-workshops](https://github.com/aws-samples/aws-security-workshops) A collection of the latest AWS Security workshops
- [**242**星][6d] [HCL] [nozaq/terraform-aws-secure-baseline](https://github.com/nozaq/terraform-aws-secure-baseline) Terraform module to set up your AWS account with the secure baseline configuration based on CIS Amazon Web Services Foundations.
- [**224**星][10d] [Dockerfile] [thinkst/canarytokens-docker](https://github.com/thinkst/canarytokens-docker) Docker configuration to quickly setup your own Canarytokens.
- [**204**星][17d] [stuhirst/awssecurity](https://github.com/stuhirst/awssecurity) for AWS Security material
- [**203**星][6m] [Py] [dowjones/hammer](https://github.com/dowjones/hammer) Dow Jones Hammer : Protect the cloud with the power of the cloud(AWS)


***


## <a id="88716f4591b1df2149c2b7778d15d04e"></a>Phoenix


- [**820**星][5d] [Elixir] [nccgroup/sobelow](https://github.com/nccgroup/sobelow) Phoenix 框架安全方面的静态分析工具（Phoenix  框架：支持对webUI,接口, web性能,mobile app 或 mobile browser 进行自动化测试和监控的平台）


***


## <a id="4fd96686a470ff4e9e974f1503d735a2"></a>Kubernetes


- [**1895**星][23d] [Py] [aquasecurity/kube-hunter](https://github.com/aquasecurity/kube-hunter) Hunt for security weaknesses in Kubernetes clusters
- [**582**星][2m] [Go] [shopify/kubeaudit](https://github.com/shopify/kubeaudit) kubeaudit helps you audit your Kubernetes clusters against common security controls
- [**385**星][2m] [Shell] [kabachook/k8s-security](https://github.com/kabachook/k8s-security) Kubernetes security notes and best practices
- [**211**星][9m] [Go] [cloudflare/cloudflare-ingress-controller](https://github.com/cloudflare/cloudflare-ingress-controller) A Kubernetes ingress controller for Cloudflare's Argo Tunnels


***


## <a id="786201db0bcc40fdf486cee406fdad31"></a>Azure




***


## <a id="40dbffa18ec695a618eef96d6fd09176"></a>Nginx


- [**6211**星][2m] [Py] [yandex/gixy](https://github.com/yandex/gixy) Nginx 配置静态分析工具，防止配置错误导致安全问题，自动化错误配置检测


***


## <a id="6b90a3993f9846922396ec85713dc760"></a>ELK


- [**1945**星][4d] [CSS] [cyb3rward0g/helk](https://github.com/cyb3rward0g/helk) 对ELK栈进行分析，具备多种高级功能，例如SQL声明性语言，图形，结构化流，机器学习等


***


## <a id="6730dabeca61fcf64d4f7631abae6734"></a>GoogleCloud&&谷歌云


- [**1066**星][2d] [Py] [forseti-security/forseti-security](https://github.com/forseti-security/forseti-security)  A community-driven collection of open source tools to improve the security of your Google Cloud Platform environments


# <a id="d55d9dfd081aa2a02e636b97ca1bad0b"></a>物联网(IoT)&&嵌入式设备&&路由器&&交换机&&智能设备&&打印机


***


## <a id="9a20a70f58ea7946f24224c5d73fac15"></a>工具


### <a id="cda63179d132f43441f8844c5df10024"></a>未分类-IoT


- [**1218**星][] [C] [dgiese/dustcloud](https://github.com/dgiese/dustcloud) Xiaomi Smart Home Device Reverse Engineering and Hacking
- [**1145**星][7m] [nebgnahz/awesome-iot-hacks](https://github.com/nebgnahz/awesome-iot-hacks) A Collection of Hacks in IoT Space so that we can address them (hopefully).
- [**1049**星][29d] [Py] [ct-open-source/tuya-convert](https://github.com/ct-open-source/tuya-convert) A collection of scripts to flash Tuya IoT devices to alternative firmwares
- [**836**星][5d] [v33ru/iotsecurity101](https://github.com/v33ru/iotsecurity101) From IoT Pentesting to IoT Security
- [**587**星][9m] [Py] [woj-ciech/danger-zone](https://github.com/woj-ciech/danger-zone) Correlate data between domains, IPs and email addresses, present it as a graph and store everything into Elasticsearch and JSON files.
- [**491**星][18d] [Py] [iti/ics-security-tools](https://github.com/iti/ics-security-tools) Tools, tips, tricks, and more for exploring ICS Security.
- [**461**星][5d] [Py] [rabobank-cdc/dettect](https://github.com/rabobank-cdc/dettect) Detect Tactics, Techniques & Combat Threats
- [**330**星][1y] [Py] [vmware/liota](https://github.com/vmware/liota) 
- [**315**星][16d] [Java] [erudika/para](https://github.com/erudika/para) Open source back-end server for web, mobile and IoT. The backend for busy developers. (self-hosted or hosted)


### <a id="72bffacc109d51ea286797a7d5079392"></a>打印机 




### <a id="c9fd442ecac4e22d142731165b06b3fe"></a>路由器&&交换机




### <a id="3d345feb9fee1c101aea3838da8cbaca"></a>嵌入式设备


- [**7547**星][8d] [Py] [threat9/routersploit](https://github.com/threat9/routersploit) Exploitation Framework for Embedded Devices




***


## <a id="01e638f09e44280ae9a1a95fc376edc5"></a>文章


### <a id="a4a3bcead86d9f9f7977479dfe94797d"></a>新添加






# <a id="1233584261c0cd5224b6e90a98cc9a94"></a>渗透&&offensive&&渗透框架&&后渗透框架


***


## <a id="5dd93fbc2f2ebc8d98672b2d95782af3"></a>工具


### <a id="2e40f2f1df5d7f93a7de47bf49c24a0e"></a>未分类-Pentest


- [**3051**星][4m] [Py] [spiderlabs/responder](https://github.com/spiderlabs/responder) LLMNR/NBT-NS/MDNS投毒，内置HTTP/SMB/MSSQL/FTP/LDAP认证服务器, 支持NTLMv1/NTLMv2/LMv2
- [**2058**星][2m] [C++] [lordnoteworthy/al-khaser](https://github.com/lordnoteworthy/al-khaser) 在野恶意软件使用的技术：虚拟机，仿真，调试器，沙盒检测。
    - 重复区段: [恶意代码->工具](#e2fd0947924229d7de24b9902e1f54a0) |
- [**1957**星][5d] [chaitin/xray](https://github.com/chaitin/xray) xray 安全评估工具 | 使用之前务必先阅读文档
- [**1468**星][6d] [C] [ufrisk/pcileech](https://github.com/ufrisk/pcileech) DMA攻击工具。通过 PCIe 硬件设备使用 DMA，直接读写目标系统的内存。目标系统不需要安装驱动。
- [**1421**星][5m] [yadox666/the-hackers-hardware-toolkit](https://github.com/yadox666/the-hackers-hardware-toolkit) 用于Red Team、渗透、安全研究的最佳硬件产品集合
- [**1398**星][4d] [Py] [ekultek/whatwaf](https://github.com/ekultek/whatwaf) 检测并绕过WAF和保护系统
- [**1223**星][4m] [Py] [owtf/owtf](https://github.com/owtf/owtf) 进攻性 Web 测试框架。着重于 OWASP + PTES，尝试统合强大的工具，提高渗透测试的效率。大部分以Python 编写
- [**1020**星][1m] [C] [bt3gl/pentesting-toolkit](https://github.com/bt3gl/Pentesting-Toolkit) 渗透测试，CTF和战争游戏的工具收集
- [**952**星][4m] [Py] [hatriot/zarp](https://github.com/hatriot/zarp) 网络攻击工具，主要是本地网络攻击
- [**938**星][2m] [Py] [d4vinci/one-lin3r](https://github.com/d4vinci/one-lin3r) 轻量级框架，提供在渗透测试中需要的所有one-liners
- [**850**星][8m] [JS] [serpicoproject/serpico](https://github.com/serpicoproject/serpico) 渗透测试报告生成和协作工具
- [**820**星][2m] [Py] [jeffzh3ng/fuxi](https://github.com/jeffzh3ng/fuxi) 渗透测试平台
- [**809**星][17d] [Py] [jivoi/pentest](https://github.com/jivoi/pentest) 渗透测试工具
- [**775**星][8m] [Py] [gkbrk/slowloris](https://github.com/gkbrk/slowloris) HTTP DoS 服务攻击，主要影响多线程服务器
- [**722**星][19d] [voorivex/pentest-guide](https://github.com/voorivex/pentest-guide) 基于OWASP的渗透测试指南，包括测试案例，资源和示例。
- [**713**星][6m] [leezj9671/pentest_interview](https://github.com/leezj9671/pentest_interview) 个人准备渗透测试和安全面试的经验之谈，和去部分厂商的面试题，干货真的满满~
- [**685**星][4d] [Py] [gwen001/pentest-tools](https://github.com/gwen001/pentest-tools) 日常使用的渗透工具集合
- [**624**星][10m] [Py] [epsylon/ufonet](https://github.com/epsylon/ufonet) 用于发起DDoS和DoS攻击的工具包。
- [**613**星][1m] [Ruby] [hackplayers/evil-winrm](https://github.com/hackplayers/evil-winrm) 用户Hacking/渗透的终极WinRM shell
- [**545**星][t] [C++] [danielkrupinski/osiris](https://github.com/danielkrupinski/osiris) 开源培训软件/“反恐精英：全球攻势”游戏作弊工具。设计为内部作弊-可将动态链接库（DLL）加载到游戏过程中
- [**514**星][25d] [PS] [s3cur3th1ssh1t/winpwn](https://github.com/S3cur3Th1sSh1t/WinPwn) 内部Windows渗透测试/与安全的自动化
- [**502**星][7d] [netbiosx/checklists](https://github.com/netbiosx/checklists) 参与的各种渗透测试的清单
- [**491**星][1y] [Shell] [leonteale/pentestpackage](https://github.com/leonteale/pentestpackage) 一整套我已经制作或经常使用的渗透脚本
- [**489**星][11m] [Ruby] [sidaf/homebrew-pentest](https://github.com/sidaf/homebrew-pentest) 一个包含一些Homebrew formulas的Tap，包含与渗透测试相关的工具。
- [**474**星][8m] [Java] [alpha1e0/pentestdb](https://github.com/alpha1e0/pentestdb) WEB渗透测试数据库
- [**472**星][11m] [PHP] [l3m0n/pentest_tools](https://github.com/l3m0n/pentest_tools) 收集一些小型实用的工具
- [**464**星][3m] [C++] [fsecurelabs/c3](https://github.com/FSecureLABS/C3) 一个用于快速定制C2通道原型的框架，同时仍提供与现有攻击性工具包的集成。
- [**463**星][4m] [mel0day/redteam-bcs](https://github.com/mel0day/redteam-bcs) BCS（北京网络安全大会）2019 红队行动会议重点内容

- [**451**星][8m] [C++] [rek7/mxtract](https://github.com/rek7/mxtract) 一个基于linux的开源工具，用于分析和转储内存。
- [**440**星][2m] [Py] [admintony/prepare-for-awd](https://github.com/admintony/prepare-for-awd) AWD攻防赛脚本集合
- [**435**星][10m] [Go] [amyangxyz/assassingo](https://github.com/amyangxyz/assassingo) 一个可扩展的并发信息收集和漏洞扫描框架，具有基于WebSocket的Web GUI。
- [**403**星][2d] [Py] [christruncer/pentestscripts](https://github.com/christruncer/pentestscripts) 渗透脚本
- [**401**星][2m] [Py] [clr2of8/dpat](https://github.com/clr2of8/dpat) 域密码审核工具
- [**396**星][4m] [ansjdnakjdnajkd/ios](https://github.com/ansjdnakjdnajkd/ios) iOS渗透测试最有用的工具
- [**395**星][8d] [PS] [d0nkeys/redteam](https://github.com/d0nkeys/redteam) Red Team 脚本
- [**394**星][1y] [Py] [cr4shcod3/pureblood](https://github.com/cr4shcod3/pureblood) 为黑客/渗透测试/漏洞赏金创建的渗透测试框架
- [**392**星][4m] [Py] [xuanhun/pythonhackingbook1](https://github.com/xuanhun/pythonhackingbook1) Python黑客编程之极速入门

- [**387**星][5m] [C#] [bitsadmin/nopowershell](https://github.com/bitsadmin/nopowershell) 使用C#"重写"的PowerShell, 支持执行与PowerShell类似的命令, 然而对所有的PowerShell日志机制都不可见
- [**381**星][9m] [C] [ridter/pentest](https://github.com/ridter/pentest) 渗透工具
- [**379**星][7m] [unprovable/pentesthardware](https://github.com/unprovable/pentesthardware) 公开笔记整理
- [**353**星][1y] [PS] [rootclay/powershell-attack-guide](https://github.com/rootclay/powershell-attack-guide) Powershell攻击指南----黑客后渗透之道

- [**351**星][3m] [Shell] [maldevel/pentestkit](https://github.com/maldevel/pentestkit) 渗透脚本和工具
- [**347**星][1m] [Py] [ym2011/pest](https://github.com/ym2011/PEST) 渗透脚本
- [**346**星][11m] [Py] [darkspiritz/darkspiritz](https://github.com/darkspiritz/darkspiritz) 适用于Linux，MacOS和Windows系统的渗透测试框架。
- [**344**星][1m] [stardustsky/saidict](https://github.com/stardustsky/saidict) 弱口令,敏感目录,敏感文件等渗透测试常用攻击字典

- [**340**星][1y] [Java] [rub-nds/ws-attacker](https://github.com/rub-nds/ws-attacker) Web服务渗透测试框架，模块化。
- [**331**星][1m] [Py] [m8r0wn/nullinux](https://github.com/m8r0wn/nullinux) SMB null 会话识别和枚举工具
- [**323**星][3m] [PS] [kmkz/pentesting](https://github.com/kmkz/pentesting) 渗透测试技巧
- [**322**星][4m] [HTML] [koutto/jok3r](https://github.com/koutto/jok3r) 一个Python3 CLI应用程序，旨在帮助渗透测试人员进行网络基础结构和Web黑盒安全性测试。
- [**310**星][7m] [ring04h/pentest](https://github.com/ring04h/pentest) 渗透测试用到的东东

- [**305**星][3m] [Ruby] [fozavci/viproy-voipkit](https://github.com/fozavci/viproy-voipkit) VoIP渗透测试工具和 Metasploit 框架
    - 重复区段: [渗透->工具->Metasploit->未分类-metasploit](#01be61d5bb9f6f7199208ff0fba86b5d) |
- [**297**星][2m] [Py] [bishopfox/eyeballer](https://github.com/bishopfox/eyeballer) 用于大型网络渗透测试中需要从大量基于Web的主机中找到“有趣的”目标
- [**295**星][2m] [Lua] [pentesteracademy/patoolkit](https://github.com/pentesteracademy/patoolkit) 一组流量分析插件，用于将Wireshark的功能从微分析工具和协议解析器扩展到宏分析器和威胁猎人。
- [**289**星][5d] [Java] [mr-xn/penetration_testing_poc](https://github.com/mr-xn/penetration_testing_poc) 渗透测试有关的POC、EXP、脚本、提权、小工具等
- [**287**星][1y] [C++] [paranoidninja/pandoras-box](https://github.com/paranoidninja/pandoras-box) 渗透和Red Team脚本
- [**280**星][12d] [Go] [rmikehodges/hidensneak](https://github.com/rmikehodges/hidensneak) 通过提供快速部署，管理和关闭各种云服务的界面，协助管理渗透测试人员的攻击基础架构
- [**273**星][19d] [Py] [elevenpaths/homepwn](https://github.com/elevenpaths/homepwn) HomePwn - Swiss Army Knife for Pentesting of IoT Devices
- [**262**星][4m] [Py] [giantbranch/python-hacker-code](https://github.com/giantbranch/python-hacker-code) 《python黑帽子：黑客与渗透测试编程之道》代码及实验文件，字典等

- [**259**星][1m] [anyeduke/enterprise-security-skill](https://github.com/anyeduke/enterprise-security-skill) 用于记录企业安全规划，建设，运营，攻防的相关资源

- [**250**星][5d] [PS] [sdcampbell/internal-pentest-playbook](https://github.com/sdcampbell/internal-pentest-playbook) Internal Network Penetration Test Playbook
- [**246**星][3m] [Shell] [leviathan36/kaboom](https://github.com/leviathan36/kaboom) An automated pentest tool
- [**231**星][9m] [Go] [stevenaldinger/decker](https://github.com/stevenaldinger/decker) Declarative penetration testing orchestration framework
- [**220**星][] [JS] [giper45/dockersecurityplayground](https://github.com/giper45/dockersecurityplayground) A Microservices-based framework for the study of Network Security and Penetration Test techniques
- [**219**星][6m] [Py] [mgeeky/tomcatwardeployer](https://github.com/mgeeky/tomcatwardeployer) Apache Tomcat auto WAR deployment & pwning penetration testing tool.
- [**206**星][3m] [Shell] [keepwannabe/remot3d](https://github.com/keepwannabe/remot3d) is a simple tool created for large pentesters as well as just for the pleasure of defacers to control server by backdoors
- [**203**星][2m] [Ruby] [vonahisec/leprechaun](https://github.com/vonahisec/leprechaun) This tool is used to map out the network data flow to help penetration testers identify potentially valuable targets.
- [**200**星][11m] [Py] [infamoussyn/rogue](https://github.com/infamoussyn/rogue) An extensible toolkit providing penetration testers an easy-to-use platform to deploy Access Points during penetration testing and red team engagements.


### <a id="9081db81f6f4b78d5c263723a3f7bd6d"></a>收集


- [**923**星][9m] [C] [0x90/wifi-arsenal](https://github.com/0x90/wifi-arsenal) WiFi arsenal
- [**822**星][3m] [Shell] [shr3ddersec/shr3dkit](https://github.com/shr3ddersec/shr3dkit) Red Team Tool Kit
- [**540**星][7m] [Py] [0xdea/tactical-exploitation](https://github.com/0xdea/tactical-exploitation) 渗透测试辅助工具包. Python/PowerShell脚本


### <a id="2051fd9e171f2698d8e7486e3dd35d87"></a>渗透多合一&&渗透框架


- [**5062**星][5m] [PS] [empireproject/empire](https://github.com/EmpireProject/Empire) 后渗透框架. Windows客户端用PowerShell, Linux/OSX用Python. 之前PowerShell Empire和Python EmPyre的组合
- [**4752**星][13d] [Py] [manisso/fsociety](https://github.com/manisso/fsociety) fsociety Hacking Tools Pack – A Penetration Testing Framework
- [**3427**星][1m] [PS] [samratashok/nishang](https://github.com/samratashok/nishang) 渗透框架，脚本和Payload收集，主要是PowerShell，涵盖渗透的各个阶段
- [**3154**星][t] [Shell] [1n3/sn1per](https://github.com/1n3/sn1per) 自动化渗透测试框架
- [**3136**星][2m] [Py] [byt3bl33d3r/crackmapexec](https://github.com/byt3bl33d3r/crackmapexec) 后渗透工具，自动化评估大型Active Directory网络的安全性
- [**2995**星][18d] [Py] [guardicore/monkey](https://github.com/guardicore/monkey) 自动化渗透测试工具, 测试数据中心的弹性, 以防范周边(perimeter)泄漏和内部服务器感染
- [**2840**星][8m] [C#] [quasar/quasarrat](https://github.com/quasar/quasarrat) Remote Administration Tool for Windows
- [**2421**星][5d] [Py] [infobyte/faraday](https://github.com/infobyte/faraday) 渗透测试和漏洞管理平台
- [**1527**星][19d] [Py] [zerosum0x0/koadic](https://github.com/zerosum0x0/koadic) 类似于Meterpreter、Powershell Empire 的post-exploitation rootkit，区别在于其大多数操作都是由 Windows 脚本主机 JScript/VBScript 执行
- [**1096**星][11m] [Py] [secforce/sparta](https://github.com/secforce/sparta) 网络基础架构渗透测试
- [**961**星][4m] [Py] [0xinfection/tidos-framework](https://github.com/0xInfection/TIDoS-Framework) Web App渗透测试框架, 攻击性, 手动
- [**928**星][1y] [Py] [m4n3dw0lf/pythem](https://github.com/m4n3dw0lf/pythem) 多功能渗透测试框架
- [**521**星][t] [Py] [gyoisamurai/gyoithon](https://github.com/gyoisamurai/gyoithon) 使用机器学习的成长型渗透测试工具


### <a id="fc8737aef0f59c3952d11749fe582dac"></a>自动化


- [**1881**星][5m] [Shell] [arismelachroinos/lscript](https://github.com/arismelachroinos/lscript) 自动化无线渗透和Hacking 任务的脚本
    - 重复区段: [无线->未分类-WiFi](#d4efda1853b2cb0909727188116a2a8c) |
- [**1792**星][t] [Shell] [leebaird/discover](https://github.com/leebaird/discover) 自定义的bash脚本, 用于自动化多个渗透测试任务, 包括: 侦查、扫描、解析、在Metasploit中创建恶意Payload和Listener
    - 重复区段: [渗透->工具->Metasploit->未分类-metasploit](#01be61d5bb9f6f7199208ff0fba86b5d) |[侦察->工具->未分类-OSINT](#05ab1b75266fddafc7195f5b395e4d99) |[Payload->工具->Payload生成](#ad92f6b801a18934f1971e2512f5ae4f) |
- [**1688**星][3m] [Py] [rootm0s/winpwnage](https://github.com/rootm0s/winpwnage) UAC bypass, Elevate, Persistence and Execution methods


### <a id="3ae4408f4ab03f99bab9ef9ee69642a8"></a>数据渗透&&DataExfiltration


- [**1065**星][1m] [C] [quiet/quiet](https://github.com/quiet/quiet) Transmit data with sound. Includes binaries for soundcards and .wav files.
- [**469**星][4m] [Py] [viralmaniar/powershell-rat](https://github.com/viralmaniar/powershell-rat) Python based backdoor that uses Gmail to exfiltrate data through attachment. This RAT will help during red team engagements to backdoor any Windows machines. It tracks the user activity using screen capture and sends it to an attacker as an e-mail attachment.


### <a id="adfa06d452147ebacd35981ce56f916b"></a>横向渗透




### <a id="39e9a0fe929fffe5721f7d7bb2dae547"></a>Burp


#### <a id="6366edc293f25b57bf688570b11d6584"></a>收集


- [**1982**星][1y] [BitBake] [1n3/intruderpayloads](https://github.com/1n3/intruderpayloads) A collection of Burpsuite Intruder payloads, BurpBounty payloads, fuzz lists, malicious file uploads and web pentesting methodologies and checklists.
- [**1108**星][2m] [snoopysecurity/awesome-burp-extensions](https://github.com/snoopysecurity/awesome-burp-extensions) Burp扩展收集


#### <a id="5b761419863bc686be12c76451f49532"></a>未分类-Burp


- [**1112**星][1y] [Py] [bugcrowd/hunt](https://github.com/bugcrowd/HUNT) Burp和ZAP的扩展收集
- [**917**星][5d] [Batchfile] [mr-xn/burpsuite-collections](https://github.com/mr-xn/burpsuite-collections) BurpSuite收集：包括不限于 Burp 文章、破解版、插件(非BApp Store)、汉化等相关教程，欢迎添砖加瓦---burpsuite-pro burpsuite-extender burpsuite cracked-version hackbar hacktools fuzzing fuzz-testing burp-plugin burp-extensions bapp-store brute-force-attacks brute-force-passwords waf sqlmap jar
- [**715**星][1y] [Java] [d3vilbug/hackbar](https://github.com/d3vilbug/hackbar) HackBar plugin for Burpsuite
- [**663**星][9m] [Java] [vulnerscom/burp-vulners-scanner](https://github.com/vulnerscom/burp-vulners-scanner) Vulnerability scanner based on vulners.com search API
- [**605**星][9m] [Java] [c0ny1/chunked-coding-converter](https://github.com/c0ny1/chunked-coding-converter) Burp suite 分块传输辅助插件
- [**584**星][1y] [Java] [federicodotta/brida](https://github.com/federicodotta/brida) The new bridge between Burp Suite and Frida!
- [**510**星][2m] [Java] [wagiro/burpbounty](https://github.com/wagiro/burpbounty) Burp Bounty (Scan Check Builder in BApp Store) is a extension of Burp Suite that allows you, in a quick and simple way, to improve the active and passive scanner by means of personalized rules through a very intuitive graphical interface.
- [**496**星][2m] [Py] [romanzaikin/burpextension-whatsapp-decryption-checkpoint](https://github.com/romanzaikin/burpextension-whatsapp-decryption-checkpoint) This tool was created during our research at Checkpoint Software Technologies on Whatsapp Protocol (This repository will be updated after BlackHat 2019)
- [**445**星][6m] [Py] [albinowax/activescanplusplus](https://github.com/albinowax/activescanplusplus) ActiveScan++ Burp Suite Plugin
- [**423**星][5m] [Java] [bit4woo/recaptcha](https://github.com/bit4woo/recaptcha) reCAPTCHA = REcognize CAPTCHA: A Burp Suite Extender that recognize CAPTCHA and use for intruder payload 自动识别图形验证码并用于burp intruder爆破模块的插件
- [**410**星][8m] [Java] [nccgroup/burpsuitehttpsmuggler](https://github.com/nccgroup/burpsuitehttpsmuggler) A Burp Suite extension to help pentesters to bypass WAFs or test their effectiveness using a number of techniques
- [**381**星][1y] [Py] [rhinosecuritylabs/sleuthql](https://github.com/rhinosecuritylabs/sleuthql) Python3 Burp History parsing tool to discover potential SQL injection points. To be used in tandem with SQLmap.
- [**378**星][3m] [Java] [nccgroup/autorepeater](https://github.com/nccgroup/autorepeater) Automated HTTP Request Repeating With Burp Suite
- [**366**星][13d] [Java] [portswigger/http-request-smuggler](https://github.com/PortSwigger/http-request-smuggler) an extension for Burp Suite designed to help you launch HTTP Request Smuggling attack
- [**364**星][4d] [Kotlin] [portswigger/turbo-intruder](https://github.com/portswigger/turbo-intruder) Turbo Intruder is a Burp Suite extension for sending large numbers of HTTP requests and analyzing the results.
- [**359**星][5m] [Java] [bit4woo/domain_hunter](https://github.com/bit4woo/domain_hunter) A Burp Suite Extender that try to find sub-domain, similar-domain and related-domain of an organization, not only a domain! 利用burp收集整个企业、组织的域名（不仅仅是单个主域名）的插件
- [**336**星][13d] [Java] [bit4woo/knife](https://github.com/bit4woo/knife) A burp extension that add some useful function to Context Menu 添加一些右键菜单让burp用起来更顺畅
- [**310**星][1y] [Java] [ebryx/aes-killer](https://github.com/ebryx/aes-killer) Burp plugin to decrypt AES Encrypted traffic of mobile apps on the fly
- [**303**星][6d] [Java] [ilmila/j2eescan](https://github.com/ilmila/j2eescan) J2EEScan is a plugin for Burp Suite Proxy. The goal of this plugin is to improve the test coverage during web application penetration tests on J2EE applications.
- [**301**星][1y] [Java] [elkokc/reflector](https://github.com/elkokc/reflector) Burp 插件，浏览网页时实时查找反射 XSS
- [**299**星][1y] [Java] [vmware/burp-rest-api](https://github.com/vmware/burp-rest-api) REST/JSON API to the Burp Suite security tool.
- [**298**星][12m] [Shell] [yw9381/burp_suite_doc_zh_cn](https://github.com/yw9381/burp_suite_doc_zh_cn) 这是基于Burp Suite官方文档翻译而来的中文版文档
- [**273**星][2m] [Py] [quitten/autorize](https://github.com/quitten/autorize) Automatic authorization enforcement detection extension for burp suite written in Jython developed by Barak Tawily in order to ease application security people work and allow them perform an automatic authorization tests
- [**257**星][3m] [Py] [rhinosecuritylabs/iprotate_burp_extension](https://github.com/rhinosecuritylabs/iprotate_burp_extension) Extension for Burp Suite which uses AWS API Gateway to rotate your IP on every request.
- [**250**星][30d] [Java] [c0ny1/jsencrypter](https://github.com/c0ny1/jsencrypter) 一个用于加密传输爆破的Burp Suite插件
- [**246**星][5m] [Py] [initroot/burpjslinkfinder](https://github.com/initroot/burpjslinkfinder) Burp Extension for a passive scanning JS files for endpoint links.
- [**244**星][3m] [Java] [c0ny1/passive-scan-client](https://github.com/c0ny1/passive-scan-client) Burp被动扫描流量转发插件
- [**238**星][2m] [Java] [samlraider/samlraider](https://github.com/samlraider/samlraider) SAML2 Burp Extension
- [**235**星][1y] [Java] [difcareer/sqlmap4burp](https://github.com/difcareer/sqlmap4burp) sqlmap embed in burpsuite
- [**230**星][1y] [Py] [audibleblink/doxycannon](https://github.com/audibleblink/doxycannon) 为一堆OpenVPN文件分别创建Docker容器, 每个容器开启SOCKS5代理服务器并绑定至Docker主机端口, 再结合使用Burp或ProxyChains, 构建私有的Botnet
- [**225**星][6m] [Perl] [modzero/mod0burpuploadscanner](https://github.com/modzero/mod0burpuploadscanner) HTTP file upload scanner for Burp Proxy
- [**219**星][9m] [Py] [teag1e/burpcollector](https://github.com/teag1e/burpcollector) 通过BurpSuite来构建自己的爆破字典，可以通过字典爆破来发现隐藏资产。
- [**209**星][3m] [Java] [h3xstream/http-script-generator](https://github.com/h3xstream/http-script-generator) ZAP/Burp plugin that generate script to reproduce a specific HTTP request (Intended for fuzzing or scripted attacks)




### <a id="8e7a6a74ff322cbf2bad59092598de77"></a>Metasploit


#### <a id="01be61d5bb9f6f7199208ff0fba86b5d"></a>未分类-metasploit


- [**19127**星][4d] [Ruby] [rapid7/metasploit-framework](https://github.com/rapid7/metasploit-framework) Metasploit Framework
- [**1792**星][t] [Shell] [leebaird/discover](https://github.com/leebaird/discover) 自定义的bash脚本, 用于自动化多个渗透测试任务, 包括: 侦查、扫描、解析、在Metasploit中创建恶意Payload和Listener
    - 重复区段: [渗透->工具->自动化](#fc8737aef0f59c3952d11749fe582dac) |[侦察->工具->未分类-OSINT](#05ab1b75266fddafc7195f5b395e4d99) |[Payload->工具->Payload生成](#ad92f6b801a18934f1971e2512f5ae4f) |
- [**1302**星][1y] [Shell] [dana-at-cp/backdoor-apk](https://github.com/dana-at-cp/backdoor-apk) backdoor-apk is a shell script that simplifies the process of adding a backdoor to any Android APK file. Users of this shell script should have working knowledge of Linux, Bash, Metasploit, Apktool, the Android SDK, smali, etc. This shell script is provided as-is without warranty of any kind and is intended for educational purposes only.
- [**742**星][16d] [C] [rapid7/metasploit-payloads](https://github.com/rapid7/metasploit-payloads) Unified repository for different Metasploit Framework payloads
- [**732**星][3m] [Java] [isafeblue/trackray](https://github.com/isafeblue/trackray) 溯光 (TrackRay) 3 beta⚡渗透测试框架（资产扫描|指纹识别|暴力破解|网页爬虫|端口扫描|漏洞扫描|代码审计|AWVS|NMAP|Metasploit|SQLMap）
- [**534**星][4d] [Shell] [r00t-3xp10it/venom](https://github.com/r00t-3xp10it/venom) venom - shellcode generator/compiler/handler (metasploit)
- [**456**星][5m] [Py] [cchio/deep-pwning](https://github.com/cchio/deep-pwning) 一个轻量级的框架，用于试验机器学习模型，目的是评估其对主动攻击者的鲁棒性
- [**413**星][6m] [Ruby] [praetorian-code/purple-team-attack-automation](https://github.com/praetorian-code/purple-team-attack-automation) Praetorian's public release of our Metasploit automation of MITRE ATT&CK™ TTPs
- [**310**星][2m] [Py] [3ndg4me/autoblue-ms17-010](https://github.com/3ndg4me/autoblue-ms17-010) This is just an semi-automated fully working, no-bs, non-metasploit version of the public exploit code for MS17-010
- [**310**星][11m] [Ruby] [darkoperator/metasploit-plugins](https://github.com/darkoperator/metasploit-plugins) Plugins for Metasploit Framework
- [**305**星][3m] [Ruby] [fozavci/viproy-voipkit](https://github.com/fozavci/viproy-voipkit) VoIP渗透测试工具和 Metasploit 框架
    - 重复区段: [渗透->工具->未分类-Pentest](#2e40f2f1df5d7f93a7de47bf49c24a0e) |
- [**279**星][3m] [Vue] [zerx0r/kage](https://github.com/Zerx0r/Kage) Kage is Graphical User Interface for Metasploit Meterpreter and Session Handler




### <a id="b1161d6c4cb520d0cd574347cd18342e"></a>免杀&&躲避AV检测


- [**1032**星][5m] [C] [govolution/avet](https://github.com/govolution/avet) 免杀工具
- [**733**星][10m] [Py] [mr-un1k0d3r/dkmc](https://github.com/mr-un1k0d3r/dkmc) DKMC - Dont kill my cat - Malicious payload evasion tool
- [**686**星][7m] [Py] [paranoidninja/carboncopy](https://github.com/paranoidninja/carboncopy) A tool which creates a spoofed certificate of any online website and signs an Executable for AV Evasion. Works for both Windows and Linux
- [**472**星][18d] [Go] [arvanaghi/checkplease](https://github.com/arvanaghi/checkplease) Sandbox evasion modules written in PowerShell, Python, Go, Ruby, C, C#, Perl, and Rust.
- [**316**星][1m] [C#] [ch0pin/aviator](https://github.com/ch0pin/aviator) Antivirus evasion project
- [**302**星][1y] [Py] [two06/inception](https://github.com/two06/inception) Provides In-memory compilation and reflective loading of C# apps for AV evasion.
- [**276**星][2m] [C#] [hackplayers/salsa-tools](https://github.com/hackplayers/salsa-tools) Salsa Tools - ShellReverse TCP/UDP/ICMP/DNS/SSL/BINDTCP/Shellcode/SILENTTRINITY and AV bypass, AMSI patched


### <a id="98a851c8e6744850efcb27b8e93dff73"></a>C&C


- [**2490**星][4m] [Go] [ne0nd0g/merlin](https://github.com/ne0nd0g/merlin) Merlin is a cross-platform post-exploitation HTTP/2 Command & Control server and agent written in golang.
- [**1826**星][6m] [C++] [iagox86/dnscat2](https://github.com/iagox86/dnscat2) 在 DNS 协议上创建加密的 C&C channel
- [**1110**星][1y] [Py] [byt3bl33d3r/gcat](https://github.com/byt3bl33d3r/gcat) A PoC backdoor that uses Gmail as a C&C server
- [**994**星][2m] [C#] [cobbr/covenant](https://github.com/cobbr/covenant) Covenant is a collaborative .NET C2 framework for red teamers.
- [**633**星][11m] [Py] [mehulj94/braindamage](https://github.com/mehulj94/braindamage) Remote administration tool which uses Telegram as a C&C server
- [**596**星][19d] [Py] [trustedsec/trevorc2](https://github.com/trustedsec/trevorc2) 通过正常的可浏览的网站隐藏 C&C 指令的客户端/服务器模型，因为时间间隔不同，检测变得更加困难，并且获取主机数据时不会使用 POST 请求
- [**320**星][1y] [C#] [spiderlabs/dohc2](https://github.com/spiderlabs/dohc2) DoHC2 allows the ExternalC2 library from Ryan Hanson (
- [**283**星][t] [PS] [nettitude/poshc2](https://github.com/nettitude/poshc2) Python Server for PoshC2
- [**280**星][4d] [PS] [nettitude/poshc2](https://github.com/nettitude/PoshC2) Python Server for PoshC2
- [**207**星][1y] [C#] [damonmohammadbagher/nativepayload_dns](https://github.com/damonmohammadbagher/nativepayload_dns) 使用DNS流量传输Payload，绕过杀软。C#编写
- [**201**星][1y] [Py] [sec-bit/awesome-buggy-erc20-tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) A Collection of Vulnerabilities in ERC20 Smart Contracts With Tokens Affected


### <a id="a0897294e74a0863ea8b83d11994fad6"></a>DDOS


- [**2466**星][1m] [C++] [pavel-odintsov/fastnetmon](https://github.com/pavel-odintsov/fastnetmon) 快速 DDoS 检测/分析工具，支持 sflow/netflow/mirror
- [**1268**星][4d] [Shell] [mitchellkrogza/nginx-ultimate-bad-bot-blocker](https://github.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker) Nginx Block Bad Bots, Spam Referrer Blocker, Vulnerability Scanners, User-Agents, Malware, Adware, Ransomware, Malicious Sites, with anti-DDOS, Wordpress Theme Detector Blocking and Fail2Ban Jail for Repeat Offenders
- [**858**星][3m] [Py] [649/memcrashed-ddos-exploit](https://github.com/649/memcrashed-ddos-exploit) DDoS attack tool for sending forged UDP packets to vulnerable Memcached servers obtained using Shodan API
    - 重复区段: [侦察->工具->Shodan](#18c7c1df2e6ae5e9135dfa2e4eb1d4db) |
- [**510**星][3m] [JS] [acmesec/pocbox](https://github.com/Acmesec/PoCBox) 赏金猎人的脆弱性测试辅助平台
- [**476**星][16d] [JS] [codemanki/cloudscraper](https://github.com/codemanki/cloudscraper) Node.js library to bypass cloudflare's anti-ddos page
- [**468**星][7m] [Shell] [jgmdev/ddos-deflate](https://github.com/jgmdev/ddos-deflate) Fork of DDoS Deflate with fixes, improvements and new features.
- [**385**星][1y] [C] [markus-go/bonesi](https://github.com/markus-go/bonesi) BoNeSi - the DDoS Botnet Simulator
- [**301**星][4m] [Shell] [anti-ddos/anti-ddos](https://github.com/anti-ddos/Anti-DDOS) 
- [**265**星][1y] [Py] [wenfengshi/ddos-dos-tools](https://github.com/wenfengshi/ddos-dos-tools) some sort of ddos-tools


### <a id="8e1069b2bce90b87eea762ee3d0935d8"></a>OWASP


- [**11306**星][2d] [Py] [owasp/cheatsheetseries](https://github.com/owasp/cheatsheetseries) The OWASP Cheat Sheet Series was created to provide a concise collection of high value information on specific application security topics.
- [**5084**星][7d] [HTML] [owasp/owasp-mstg](https://github.com/owasp/owasp-mstg) 关于移动App安全开发、测试和逆向的相近手册
- [**2434**星][13d] [Go] [owasp/amass](https://github.com/owasp/amass) In-depth Attack Surface Mapping and Asset Discovery
- [**1964**星][10d] [Perl] [spiderlabs/owasp-modsecurity-crs](https://github.com/spiderlabs/owasp-modsecurity-crs) OWASP ModSecurity Core Rule Set (CRS) Project (Official Repository)
- [**1417**星][3m] [HTML] [owasp/top10](https://github.com/owasp/top10) Official OWASP Top 10 Document Repository
- [**1056**星][3m] [HTML] [owasp/nodegoat](https://github.com/owasp/nodegoat) 学习OWASP安全威胁Top10如何应用到Web App的，以及如何处理
- [**752**星][2d] [Java] [owasp/securityshepherd](https://github.com/owasp/securityshepherd) Web and mobile application security training platform
- [**698**星][7d] [HTML] [owasp/asvs](https://github.com/owasp/asvs) Application Security Verification Standard
- [**625**星][9d] [Py] [zdresearch/owasp-nettacker](https://github.com/zdresearch/OWASP-Nettacker) Automated Penetration Testing Framework
- [**559**星][6d] [Shell] [owasp/owasp-masvs](https://github.com/owasp/owasp-masvs) OWASP 移动App安全标准
- [**503**星][10d] [owasp/wstg](https://github.com/OWASP/wstg) The OWASP Web Security Testing Guide includes a "best practice" penetration testing framework which users can implement in their own organizations and a "low level" penetration testing guide that describes techniques for testing most common web application and web service security issues.
- [**503**星][10d] [owasp/wstg](https://github.com/owasp/wstg) The OWASP Web Security Testing Guide includes a "best practice" penetration testing framework which users can implement in their own organizations and a "low level" penetration testing guide that describes techniques for testing most common web application and web service security issues.
- [**466**星][8m] [Java] [owasp/owasp-webscarab](https://github.com/owasp/owasp-webscarab) OWASP WebScarab
- [**422**星][5m] [Py] [stanislav-web/opendoor](https://github.com/stanislav-web/opendoor) OWASP WEB Directory Scanner
- [**370**星][4d] [Java] [zaproxy/zap-extensions](https://github.com/zaproxy/zap-extensions) OWASP ZAP Add-ons
- [**348**星][2m] [Java] [esapi/esapi-java-legacy](https://github.com/esapi/esapi-java-legacy) ESAPI (The OWASP Enterprise Security API) is a free, open source, web application security control library that makes it easier for programmers to write lower-risk applications.
- [**305**星][5m] [0xradi/owasp-web-checklist](https://github.com/0xradi/owasp-web-checklist) OWASP Web Application Security Testing Checklist
- [**297**星][5m] [tanprathan/owasp-testing-checklist](https://github.com/tanprathan/owasp-testing-checklist) OWASP based Web Application Security Testing Checklist is an Excel based checklist which helps you to track the status of completed and pending test cases.
- [**286**星][5m] [JS] [mike-goodwin/owasp-threat-dragon](https://github.com/mike-goodwin/owasp-threat-dragon) An open source, online threat modelling tool from OWASP
- [**258**星][2m] [owasp/api-security](https://github.com/owasp/api-security) OWASP API Security Project
- [**255**星][12m] [Java] [owasp/owasp-java-encoder](https://github.com/owasp/owasp-java-encoder) The OWASP Java Encoder is a Java 1.5+ simple-to-use drop-in high-performance encoder class with no dependencies and little baggage. This project will help Java web developers defend against Cross Site Scripting!
- [**208**星][17d] [Java] [owasp/benchmark](https://github.com/owasp/benchmark) OWASP Benchmark is a test suite designed to verify the speed and accuracy of software vulnerability detection tools. A fully runnable web app written in Java, it supports analysis by Static (SAST), Dynamic (DAST), and Runtime (IAST) tools that support Java. The idea is that since it is fully runnable and all the vulnerabilities are actually expl…


### <a id="7667f6a0381b6cded2014a0d279b5722"></a>Kali


- [**2538**星][8m] [offensive-security/kali-nethunter](https://github.com/offensive-security/kali-nethunter) The Kali NetHunter Project
- [**2436**星][8m] [Py] [lionsec/katoolin](https://github.com/lionsec/katoolin) Automatically install all Kali linux tools
- [**1699**星][3m] [PHP] [xtr4nge/fruitywifi](https://github.com/xtr4nge/fruitywifi) FruityWiFi is a wireless network auditing tool. The application can be installed in any Debian based system (Jessie) adding the extra packages. Tested in Debian, Kali Linux, Kali Linux ARM (Raspberry Pi), Raspbian (Raspberry Pi), Pwnpi (Raspberry Pi), Bugtraq, NetHunter.
- [**879**星][11m] [Shell] [esc0rtd3w/wifi-hacker](https://github.com/esc0rtd3w/wifi-hacker) Shell Script For Attacking Wireless Connections Using Built-In Kali Tools. Supports All Securities (WEP, WPS, WPA, WPA2)
- [**769**星][13d] [Py] [rajkumrdusad/tool-x](https://github.com/rajkumrdusad/tool-x) Tool-X is a kali linux hacking Tool installer. Tool-X developed for termux and other android terminals. using Tool-X you can install almost 370+ hacking tools in termux app and other linux based distributions.
- [**675**星][8m] [offensive-security/kali-arm-build-scripts](https://github.com/offensive-security/kali-arm-build-scripts) Kali Linux ARM build scripts
- [**556**星][2m] [Shell] [offensive-security/kali-linux-docker](https://github.com/offensive-security/kali-linux-docker) PLEASE USE GITLAB
- [**425**星][4m] [jack-liang/kalitools](https://github.com/jack-liang/kalitools) Kali Linux工具清单
- [**336**星][8m] [offensive-security/kali-linux-recipes](https://github.com/offensive-security/kali-linux-recipes) Kali Linux Recipes
- [**316**星][2m] [Shell] [brainfucksec/kalitorify](https://github.com/brainfucksec/kalitorify) 用于Kali的shell脚本，使用iptables创建通过Tor网络的透明代理。可以执行各种检查：检查Tor出口节点（即在Tor代理下时的公共IP），或者Tor已正确配置，可以检查服务和网络设置。
- [**273**星][27d] [C++] [steve-m/kalibrate-rtl](https://github.com/steve-m/kalibrate-rtl) fork of
- [**203**星][5m] [jiansiting/kali-windows](https://github.com/jiansiting/kali-windows) Kali Windows


### <a id="0b8e79b79094082d0906153445d6ef9a"></a>CobaltStrike


- [**1072**星][9d] [C#] [k8gege/ladon](https://github.com/k8gege/ladon) 大型内网渗透扫描器&Cobalt Strike，包含信息收集/端口扫描/服务识别/网络资产/密码爆破/漏洞检测/漏洞利用。漏洞检测含MS17010、Weblogic、ActiveMQ、Tomcat等，密码口令爆破含(Mysql、Oracle、MSSQL)、FTP、SSH(Linux)、VNC、Windows(IPC、WMI、SMB)等,可高度自定义插件支持.NET程序集、DLL(C#/Delphi/VC)、PowerShell等语言编写的插件,支持通过配置INI批量调用任意外部程序或命令,EXP生成器一键生成Web漏洞POC,可快速扩展扫描或利用能力。支持Cobalt Strike插件化直接内存加载Ladon扫描快速拓展内网横向移动
- [**770**星][5m] [aleenzz/cobalt_strike_wiki](https://github.com/aleenzz/cobalt_strike_wiki) Cobalt Strike系列
- [**474**星][1m] [Py] [k8gege/k8cscan](https://github.com/k8gege/k8cscan) 大型内网渗透自定义插件化扫描神器，包含信息收集、网络资产、漏洞扫描、密码爆破、漏洞利用，程序采用多线程批量扫描大型内网多个IP段C段主机，目前插件包含: C段旁注扫描、子域名扫描、Ftp密码爆破、Mysql密码爆破、Oracle密码爆破、MSSQL密码爆破、Windows/Linux系统密码爆破、存活主机扫描、端口扫描、Web信息探测、操作系统版本探测、Cisco思科设备扫描等,支持调用任意外部程序或脚本，支持Cobalt Strike联动
- [**397**星][1y] [Shell] [killswitch-gui/cobaltstrike-toolkit](https://github.com/killswitch-gui/cobaltstrike-toolkit) Some useful scripts for CobaltStrike
- [**287**星][7m] [JS] [joshuaferrara/node-csgo](https://github.com/joshuaferrara/node-csgo) A node-steam plugin for Counter-Strike: Global Offensive.
- [**217**星][12d] [JS] [saul/demofile](https://github.com/saul/demofile) Node.js library for parsing Counter-Strike: Global Offensive demo files
- [**215**星][9m] [PS] [outflanknl/excel4-dcom](https://github.com/outflanknl/excel4-dcom) PowerShell and Cobalt Strike scripts for lateral movement using Excel 4.0 / XLM macros via DCOM (direct shellcode injection in Excel.exe)
- [**207**星][1y] [C#] [spiderlabs/sharpcompile](https://github.com/spiderlabs/sharpcompile) SharpCompile is an aggressor script for Cobalt Strike which allows you to compile and execute C# in realtime. This is a more slick approach than manually compiling an .NET assembly and loading it into Cobalt Strike. The project aims to make it easier to move away from adhoc PowerShell execution instead creating a temporary assembly and executing…


### <a id="fb821e664950df22549557cb8cc54afe"></a>CMS




### <a id="53f3011d262d2554156afe18d7ad6a43"></a>日志




### <a id="b0233cd346f5ee456ee04bf653b12ae2"></a>劫持&&各种劫持


#### <a id="b087f1741bcf7c449d2910d052a7f312"></a>未分类-Hijack


- [**1417**星][1m] [Java] [chrisk44/hijacker](https://github.com/chrisk44/hijacker) Aircrack, Airodump, Aireplay, MDK3 and Reaver GUI Application for Android
- [**554**星][6m] [Py] [owasp/qrljacking](https://github.com/owasp/qrljacking) 一个简单的能够进行会话劫持的社会工程攻击向量，影响所有使用“使用 QR 码登录”作为安全登录方式的应用程序。（ Quick Response CodeLogin Jacking）


#### <a id="ecdeb90ce9bd347ca7f9d366d157689d"></a>点击劫持






### <a id="8afafc25f4fb0805556003864cce90e2"></a>RedTeam


- [**617**星][19d] [Py] [facebookincubator/weasel](https://github.com/facebookincubator/weasel) DNS covert channel implant for Red Teams.
- [**542**星][8m] [Py] [wyatu/perun](https://github.com/wyatu/perun) 主要适用于乙方安服、渗透测试人员和甲方RedTeam红队人员的网络资产漏洞扫描器/扫描框架
- [**476**星][13d] [PS] [mantvydasb/redteam-tactics-and-techniques](https://github.com/mantvydasb/RedTeam-Tactics-and-Techniques) Red Teaming Tactics and Techniques
- [**357**星][2m] [C] [nccgroup/phantap](https://github.com/nccgroup/phantap) Phantom Tap (PhanTap) - an ‘invisible’ network tap aimed at red teams
- [**221**星][2m] [Py] [khast3x/redcloud](https://github.com/khast3x/redcloud) Comfy & powerful Red Team Infrastructure deployement using Docker
- [**220**星][9m] [Py] [coalfire-research/deathmetal](https://github.com/coalfire-research/deathmetal) Red team & penetration testing tools to exploit the capabilities of Intel AMT
- [**217**星][1y] [foobarto/redteam-notebook](https://github.com/foobarto/redteam-notebook) Collection of commands, tips and tricks and references I found useful during preparation for OSCP exam.


### <a id="4c42a9cc007de389f975cb0ce146c0ed"></a>BlueTeam


- [**883**星][4m] [CSS] [outflanknl/redelk](https://github.com/outflanknl/redelk) 跟踪和警告Blue Team活动以及长期运营中的更高可用性
- [**639**星][5m] [smgorelik/windows-rce-exploits](https://github.com/smgorelik/windows-rce-exploits) The exploit samples database is a repository for **RCE** (remote code execution) exploits and Proof-of-Concepts for **WINDOWS**, the samples are uploaded for education purposes for red and blue teams.
- [**409**星][1y] [C] [ww9210/linux_kernel_exploits](https://github.com/ww9210/linux_kernel_exploits) Repo for FUZE project. I will also publish some Linux kernel LPE exploits for various real world kernel vulnerabilities here. the samples are uploaded for education purposes for red and blue teams.
- [**261**星][11d] [Ruby] [evait-security/envizon](https://github.com/evait-security/envizon) 网络可视化工具, 在渗透测试中快速识别最可能的目标




***


## <a id="f21aa1088a437dbb001a137f6f885530"></a>文章


### <a id="7229723a22769af40b96ab31fb09dcc7"></a>新添加的




### <a id="6280e13d236b0f18c75894d304309416"></a>Metasploit




### <a id="082a9e72817adcf2f824767e3e2ce597"></a>BurpSuite




### <a id="6710d6fe61cbbc36b2ba75de156eda8a"></a>CobaltStrike 






# <a id="8f92ead9997a4b68d06a9acf9b01ef63"></a>扫描器&&安全扫描&&App扫描&&漏洞扫描


***


## <a id="132036452bfacf61471e3ea0b7bf7a55"></a>工具


### <a id="de63a029bda6a7e429af272f291bb769"></a>未分类-Scanner


- [**11486**星][3m] [C] [robertdavidgraham/masscan](https://github.com/robertdavidgraham/masscan) masscan：世界上最快的互联网端口扫描器，号称可6分钟内扫描整个互联网
- [**7449**星][3d] [Py] [s0md3v/xsstrike](https://github.com/s0md3v/XSStrike) Most advanced XSS scanner.
- [**5351**星][15d] [Go] [zricethezav/gitleaks](https://github.com/zricethezav/gitleaks) Audit git repos for secrets
- [**4563**星][8d] [Ruby] [wpscanteam/wpscan](https://github.com/wpscanteam/wpscan) WPScan is a free, for non-commercial use, black box WordPress Vulnerability Scanner written for security professionals and blog maintainers to test the security of their WordPress websites.
- [**4215**星][24d] [we5ter/scanners-box](https://github.com/we5ter/scanners-box)  安全行业从业者自研开源扫描器合辑
- [**3455**星][26d] [Perl] [sullo/nikto](https://github.com/sullo/nikto) Nikto web server scanner
- [**3279**星][20d] [Go] [mozilla/sops](https://github.com/mozilla/sops) Simple and flexible tool for managing secrets
- [**3252**星][26d] [Py] [maurosoria/dirsearch](https://github.com/maurosoria/dirsearch) Web path scanner
- [**3092**星][3m] [C] [zmap/zmap](https://github.com/zmap/zmap) ZMap is a fast single packet network scanner designed for Internet-wide network surveys.
- [**2960**星][2m] [Py] [andresriancho/w3af](https://github.com/andresriancho/w3af) Web App安全扫描器, 辅助开发者和渗透测试人员识别和利用Web App中的漏洞
- [**2669**星][20d] [Py] [cloudflare/flan](https://github.com/cloudflare/flan) A pretty sweet vulnerability scanner
- [**2287**星][4m] [JS] [retirejs/retire.js](https://github.com/retirejs/retire.js) scanner detecting the use of JavaScript libraries with known vulnerabilities
- [**2113**星][12d] [Ruby] [urbanadventurer/whatweb](https://github.com/urbanadventurer/whatweb) Next generation web scanner
- [**2050**星][23d] [Py] [nabla-c0d3/sslyze](https://github.com/nabla-c0d3/sslyze) SSL/TLS服务器扫描
- [**1682**星][2m] [NSIS] [angryip/ipscan](https://github.com/angryip/ipscan) Angry IP Scanner - fast and friendly network scanner
- [**1560**星][8m] [Py] [m4ll0k/wascan](https://github.com/m4ll0k/WAScan) WAScan - Web Application Scanner
- [**1511**星][9d] [Py] [hannob/snallygaster](https://github.com/hannob/snallygaster) Python脚本, 扫描HTTP服务器"秘密文件"
- [**1139**星][24d] [Py] [gerbenjavado/linkfinder](https://github.com/gerbenjavado/linkfinder) A python script that finds endpoints in JavaScript files
- [**1102**星][3m] [PHP] [tuhinshubhra/red_hawk](https://github.com/tuhinshubhra/red_hawk) 信息收集、漏洞扫描、爬虫多合一
    - 重复区段: [侦察->工具->未分类-OSINT](#05ab1b75266fddafc7195f5b395e4d99) |
- [**1076**星][8m] [Py] [lucifer1993/struts-scan](https://github.com/lucifer1993/struts-scan) struts2漏洞全版本检测和利用工具
- [**1062**星][4m] [Py] [h4ckforjob/dirmap](https://github.com/h4ckforjob/dirmap) 一个高级web目录、文件扫描工具，功能将会强于DirBuster、Dirsearch、cansina、御剑。
- [**935**星][6m] [PHP] [tidesec/wdscanner](https://github.com/tidesec/wdscanner) 分布式web漏洞扫描、客户管理、漏洞定期扫描、子域名枚举、端口扫描、网站爬虫、暗链检测、坏链检测、网站指纹搜集、专项漏洞检测、代理搜集及部署等功能。
- [**933**星][3m] [Py] [tuhinshubhra/cmseek](https://github.com/tuhinshubhra/cmseek) CMS Detection and Exploitation suite - Scan WordPress, Joomla, Drupal and over 170 other CMSs
- [**896**星][20d] [Py] [ajinabraham/nodejsscan](https://github.com/ajinabraham/nodejsscan) NodeJsScan is a static security code scanner for Node.js applications.
- [**855**星][12d] [JS] [cloudsploit/scans](https://github.com/cloudsploit/scans) Cloud security configuration checks
- [**767**星][2m] [Py] [vesche/scanless](https://github.com/vesche/scanless) 端口扫描器
- [**758**星][2m] [Py] [nekmo/dirhunt](https://github.com/nekmo/dirhunt) Web爬虫, 针对搜索和分析路径做了优化
    - 重复区段: [爬虫->工具->未分类](#442f9390fd56008def077a21ab65d4aa) |
- [**734**星][7m] [Py] [ztgrace/changeme](https://github.com/ztgrace/changeme) 默认证书扫描器
- [**725**星][14d] [CSS] [w-digital-scanner/w12scan](https://github.com/w-digital-scanner/w12scan) a network asset discovery engine that can automatically aggregate related assets for analysis and use
- [**704**星][23d] [Py] [grayddq/gscan](https://github.com/grayddq/gscan) 本程序旨在为安全应急响应人员对Linux主机排查时提供便利，实现主机侧Checklist的自动全面化检测，根据检测结果自动数据聚合，进行黑客攻击路径溯源。
- [**703**星][5m] [CSS] [ajinabraham/cmsscan](https://github.com/ajinabraham/cmsscan) Scan Wordpress, Drupal, Joomla, vBulletin websites for Security issues
- [**702**星][1m] [C] [scanmem/scanmem](https://github.com/scanmem/scanmem) memory scanner for Linux
- [**686**星][14d] [Py] [kevthehermit/pastehunter](https://github.com/kevthehermit/pastehunter) Scanning pastebin with yara rules
- [**671**星][8m] [Py] [m4ll0k/wpseku](https://github.com/m4ll0k/wpseku) WPSeku - Wordpress Security Scanner
- [**671**星][2m] [Ruby] [mozilla/ssh_scan](https://github.com/mozilla/ssh_scan) A prototype SSH configuration and policy scanner (Blog:
- [**669**星][6m] [Py] [droope/droopescan](https://github.com/droope/droopescan) A plugin-based scanner that aids security researchers in identifying issues with several CMSs, mainly Drupal & Silverstripe.
- [**665**星][6m] [Py] [rabbitmask/weblogicscan](https://github.com/rabbitmask/weblogicscan) Weblogic一键漏洞检测工具，V1.3
- [**641**星][1y] [Py] [lmco/laikaboss](https://github.com/lmco/laikaboss) Laika BOSS: Object Scanning System
- [**618**星][5m] [Py] [faizann24/xsspy](https://github.com/faizann24/xsspy) Web Application XSS Scanner
- [**610**星][1y] [Ruby] [thesp0nge/dawnscanner](https://github.com/thesp0nge/dawnscanner) Dawn is a static analysis security scanner for ruby written web applications. It supports Sinatra, Padrino and Ruby on Rails frameworks.
- [**578**星][8d] [Py] [codingo/vhostscan](https://github.com/codingo/vhostscan) A virtual host scanner that performs reverse lookups, can be used with pivot tools, detect catch-all scenarios, work around wildcards, aliases and dynamic default pages.
- [**576**星][3m] [Perl] [alisamtechnology/atscan](https://github.com/alisamtechnology/atscan) Advanced dork Search & Mass Exploit Scanner
- [**574**星][2m] [HTML] [gwillem/magento-malware-scanner](https://github.com/gwillem/magento-malware-scanner) 用于检测 Magento 恶意软件的规则/样本集合
- [**563**星][8m] [Go] [marco-lancini/goscan](https://github.com/marco-lancini/goscan) Interactive Network Scanner
- [**539**星][5m] [Py] [cisagov/pshtt](https://github.com/cisagov/pshtt) Scan domains and return data based on HTTPS best practices
- [**485**星][2m] [Py] [fcavallarin/htcap](https://github.com/fcavallarin/htcap) htcap is a web application scanner able to crawl single page application (SPA) recursively by intercepting ajax calls and DOM changes.
- [**476**星][1y] [C] [nanshihui/scan-t](https://github.com/nanshihui/scan-t) a new crawler based on python with more function including Network fingerprint search
- [**442**星][11d] [Py] [w-digital-scanner/w13scan](https://github.com/w-digital-scanner/w13scan) Passive Security Scanner (被动式安全扫描器)
- [**401**星][11m] [JS] [eviltik/evilscan](https://github.com/eviltik/evilscan) 大规模 IP/端口扫描器，Node.js 编写
- [**400**星][1y] [Py] [grayddq/publicmonitors](https://github.com/grayddq/publicmonitors) 对公网IP列表进行端口服务扫描，发现周期内的端口服务变化情况和弱口令安全风险
- [**398**星][t] [C] [hasherezade/hollows_hunter](https://github.com/hasherezade/hollows_hunter) Scans all running processes. Recognizes and dumps a variety of potentially malicious implants (replaced/implanted PEs, shellcodes, hooks, in-memory patches).
- [**393**星][11m] [Py] [mitre/multiscanner](https://github.com/mitre/multiscanner) Modular file scanning/analysis framework
- [**384**星][1m] [Py] [stamparm/dsss](https://github.com/stamparm/dsss) Damn Small SQLi Scanner
- [**376**星][1m] [Py] [skavngr/rapidscan](https://github.com/skavngr/rapidscan) | The Multi-Tool Web Vulnerability Scanner.
- [**368**星][4d] [Swift] [evermeer/passportscanner](https://github.com/evermeer/passportscanner) Scan the MRZ code of a passport and extract the firstname, lastname, passport number, nationality, date of birth, expiration date and personal numer.
- [**356**星][5m] [Py] [swisskyrepo/wordpresscan](https://github.com/swisskyrepo/wordpresscan) WPScan rewritten in Python + some WPSeku ideas
- [**346**星][4m] [Java] [portswigger/backslash-powered-scanner](https://github.com/portswigger/backslash-powered-scanner) Finds unknown classes of injection vulnerabilities
- [**343**星][28d] [Py] [fgeek/pyfiscan](https://github.com/fgeek/pyfiscan) Web App 漏洞及版本扫描
- [**333**星][1y] [Py] [flipkart-incubator/rta](https://github.com/flipkart-incubator/rta) Red team Arsenal - An intelligent scanner to detect security vulnerabilities in company's layer 7 assets.
- [**330**星][2d] [C] [royhills/arp-scan](https://github.com/royhills/arp-scan) The ARP Scanner
- [**320**星][12d] [HTML] [coinbase/salus](https://github.com/coinbase/salus) Security scanner coordinator
- [**314**星][1m] [PS] [canix1/adaclscanner](https://github.com/canix1/adaclscanner) Repo for ADACLScan.ps1 - Your number one script for ACL's in Active Directory
- [**305**星][3m] [Ruby] [m0nad/hellraiser](https://github.com/m0nad/hellraiser) Vulnerability Scanner
- [**303**星][10m] [PHP] [steverobbins/magescan](https://github.com/steverobbins/magescan) Scan a Magento site for information
- [**301**星][6d] [Shell] [mitchellkrogza/apache-ultimate-bad-bot-blocker](https://github.com/mitchellkrogza/apache-ultimate-bad-bot-blocker) Apache Block Bad Bots, (Referer) Spam Referrer Blocker, Vulnerability Scanners, Malware, Adware, Ransomware, Malicious Sites, Wordpress Theme Detectors and Fail2Ban Jail for Repeat Offenders
- [**296**星][9m] [Py] [boy-hack/w8fuckcdn](https://github.com/boy-hack/w8fuckcdn) 通过扫描全网绕过CDN获取网站IP地址
- [**296**星][1y] [Shell] [cryptolok/ghostinthenet](https://github.com/cryptolok/ghostinthenet) Ultimate Network Stealther that makes Linux a Ghost In The Net and protects from MITM/DOS/scan
- [**293**星][5m] [enkomio/taipan](https://github.com/enkomio/Taipan) Web application vulnerability scanner
- [**288**星][1m] [Go] [zmap/zgrab2](https://github.com/zmap/zgrab2) Go Application Layer Scanner
- [**287**星][4d] [Py] [target/strelka](https://github.com/target/strelka) Real-time, container-based file scanning at enterprise scale
- [**287**星][2m] [Py] [xdavidhu/portspider](https://github.com/xdavidhu/portspider) A lightning fast multithreaded network scanner framework with modules.
- [**285**星][1y] [Py] [code-scan/dzscan](https://github.com/code-scan/dzscan) Dzscan
- [**282**星][4m] [Py] [shenril/sitadel](https://github.com/shenril/sitadel) Web Application Security Scanner
- [**271**星][14d] [Py] [abhisharma404/vault](https://github.com/abhisharma404/vault) swiss army knife for hackers
- [**263**星][3m] [Py] [m4ll0k/konan](https://github.com/m4ll0k/Konan) Konan - Advanced Web Application Dir Scanner
- [**252**星][24d] [Swift] [netyouli/whc_scan](https://github.com/netyouli/whc_scan) 高效强大扫描分析iOS和Android项目里没有使用的类Mac开源工具，清理项目垃圾类，让项目结构干净清爽，升级维护得心应手. Efficient and powerful scanning analysis iOS and Android project no classes used in Mac open source tools, cleaning rubbish class project, make project structure clean and relaxed, upgrade maintenance
- [**251**星][10m] [jeffzh3ng/insectsawake](https://github.com/jeffzh3ng/insectsawake) Network Vulnerability Scanner
- [**246**星][2m] [Py] [gildasio/h2t](https://github.com/gildasio/h2t) h2t (HTTP Hardening Tool) scans a website and suggests security headers to apply
- [**239**星][2m] [PHP] [psecio/versionscan](https://github.com/psecio/versionscan) A PHP version scanner for reporting possible vulnerabilities
- [**237**星][8m] [Go] [gocaio/goca](https://github.com/gocaio/goca) Goca Scanner
- [**225**星][6m] [Py] [rub-nds/corstest](https://github.com/rub-nds/corstest) A simple CORS misconfiguration scanner
- [**224**星][6m] [JS] [pavanw3b/sh00t](https://github.com/pavanw3b/sh00t) Security Testing is not as simple as right click > Scan. It's messy, a tough game. What if you had missed to test just that one thing and had to regret later? Sh00t is a highly customizable, intelligent platform that understands the life of bug hunters and emphasizes on manual security testing.
- [**220**星][1y] [Py] [dionach/cmsmap](https://github.com/dionach/cmsmap) CMSmap is a python open source CMS scanner that automates the process of detecting security flaws of the most popular CMSs.
- [**216**星][4m] [Py] [iojw/socialscan](https://github.com/iojw/socialscan) Check email address and username availability on online platforms with 100% accuracy
- [**213**星][10m] [Py] [nullarray/dorknet](https://github.com/nullarray/dorknet) Selenium powered Python script to automate searching for vulnerable web apps.
- [**208**星][4m] [Py] [lengjibo/dedecmscan](https://github.com/lengjibo/dedecmscan) 织梦全版本漏洞扫描
- [**202**星][1y] [PS] [sud0woodo/dcomrade](https://github.com/sud0woodo/dcomrade) Powershell script for enumerating vulnerable DCOM Applications


### <a id="58d8b993ffc34f7ded7f4a0077129eb2"></a>隐私&&Secret&&Privacy扫描


- [**6861**星][30d] [Shell] [awslabs/git-secrets](https://github.com/awslabs/git-secrets) Prevents you from committing secrets and credentials into git repositories
- [**4468**星][1m] [Py] [jofpin/trape](https://github.com/jofpin/trape) 学习在互联网上跟踪别人，获取其详细信息，并避免被别人跟踪
- [**3091**星][5d] [Py] [tribler/tribler](https://github.com/tribler/tribler) Privacy enhanced BitTorrent client with P2P content discovery
- [**2204**星][1m] [sobolevn/awesome-cryptography](https://github.com/sobolevn/awesome-cryptography) A curated list of cryptography resources and links.
- [**1141**星][5m] [Vue] [0xbug/hawkeye](https://github.com/0xbug/hawkeye) GitHub 泄露监控系统(GitHub Sensitive Information Leakage Monitor Spider)
- [**955**星][19d] [Py] [mozilla/openwpm](https://github.com/mozilla/OpenWPM) A web privacy measurement framework
- [**932**星][5d] [C#] [elevenpaths/foca](https://github.com/elevenpaths/foca) Tool to find metadata and hidden information in the documents.
- [**892**星][2m] [Py] [al0ne/vxscan](https://github.com/al0ne/vxscan) python3写的综合扫描工具，主要用来存活验证，敏感文件探测(目录扫描/js泄露接口/html注释泄露)，WAF/CDN识别，端口扫描，指纹/服务识别，操作系统识别，POC扫描，SQL注入，绕过CDN，查询旁站等功能，主要用来甲方自测或乙方授权测试，请勿用来搞破坏。
- [**395**星][7m] [Py] [repoog/gitprey](https://github.com/repoog/gitprey) Searching sensitive files and contents in GitHub associated to company name or other key words
- [**355**星][2m] [Py] [hell0w0rld0/github-hunter](https://github.com/hell0w0rld0/github-hunter) This tool is for sensitive information searching on Github - The Fast Version here:
- [**324**星][4d] [HTML] [tanjiti/sec_profile](https://github.com/tanjiti/sec_profile) 爬取secwiki和xuanwu.github.io/sec.today,分析安全信息站点、安全趋势、提取安全工作者账号(twitter,weixin,github等)
    - 重复区段: [侦察->工具->社交网络->Github](#8d1ae776898748b8249132e822f6c919) |


### <a id="1927ed0a77ff4f176b0b7f7abc551e4a"></a>隐私存储


#### <a id="1af1c4f9dba1db2a4137be9c441778b8"></a>未分类


- [**5082**星][3m] [Shell] [stackexchange/blackbox](https://github.com/stackexchange/blackbox) 文件使用PGP加密后隐藏在Git/Mercurial/Subversion


#### <a id="362dfd9c1f530dd20f922fd4e0faf0e3"></a>隐写


- [**583**星][2m] [Go] [dimitarpetrov/stegify](https://github.com/dimitarpetrov/stegify) Go tool for LSB steganography, capable of hiding any file within an image.
- [**358**星][7m] [Go] [lukechampine/jsteg](https://github.com/lukechampine/jsteg) JPEG steganography
- [**354**星][6m] [Java] [syvaidya/openstego](https://github.com/syvaidya/openstego) OpenStego is a steganography application that provides two functionalities: a) Data Hiding: It can hide any data within a cover file (e.g. images). b) Watermarking: Watermarking files (e.g. images) with an invisible signature. It can be used to detect unauthorized file copying.
- [**280**星][1y] [C] [abeluck/stegdetect](https://github.com/abeluck/stegdetect) UNMAINTAINED. USE AT OWN RISK. Stegdetect is an automated tool for detecting steganographic content in images.
- [**258**星][] [Py] [cedricbonhomme/stegano](https://github.com/cedricbonhomme/stegano) Stegano is a pure Python steganography module.






***


## <a id="1d8298e4ee4ad3c3028a1e157f85f27b"></a>文章


### <a id="7669ebab00d00c744abc35195fbaa833"></a>新添加的






# <a id="a76463feb91d09b3d024fae798b92be6"></a>侦察&&信息收集&&子域名发现与枚举&&OSINT


***


## <a id="170048b7d8668c50681c0ab1e92c679a"></a>工具


### <a id="05ab1b75266fddafc7195f5b395e4d99"></a>未分类-OSINT


- [**7307**星][12d] [Java] [lionsoul2014/ip2region](https://github.com/lionsoul2014/ip2region) Ip2region is a offline IP location library with accuracy rate of 99.9% and 0.0x millseconds searching performance. DB file is less then 5Mb with all ip address stored. binding for Java,PHP,C,Python,Nodejs,Golang,C#,lua. Binary,B-tree,Memory searching algorithm
- [**6964**星][22d] [greatfire/wiki](https://github.com/greatfire/wiki) 自由浏览
- [**6140**星][10m] [Py] [schollz/howmanypeoplearearound](https://github.com/schollz/howmanypeoplearearound) 检测 Wifi 信号统计你周围的人数
    - 重复区段: [无线->未分类-WiFi](#d4efda1853b2cb0909727188116a2a8c) |
- [**2224**星][1m] [C] [texane/stlink](https://github.com/texane/stlink) stm32 discovery line linux programmer
- [**2134**星][t] [Py] [fortynorthsecurity/eyewitness](https://github.com/FortyNorthSecurity/EyeWitness) 给网站做快照，提供服务器Header信息，识别默认凭证等
- [**1792**星][t] [Shell] [leebaird/discover](https://github.com/leebaird/discover) 自定义的bash脚本, 用于自动化多个渗透测试任务, 包括: 侦查、扫描、解析、在Metasploit中创建恶意Payload和Listener
    - 重复区段: [渗透->工具->自动化](#fc8737aef0f59c3952d11749fe582dac) |[渗透->工具->Metasploit->未分类-metasploit](#01be61d5bb9f6f7199208ff0fba86b5d) |[Payload->工具->Payload生成](#ad92f6b801a18934f1971e2512f5ae4f) |
- [**1666**星][] [Py] [cea-sec/ivre](https://github.com/cea-sec/ivre) Network recon framework.
- [**1642**星][25d] [Go] [awnumar/memguard](https://github.com/awnumar/memguard) 处理内存中敏感的值，纯Go语言编写。
- [**1609**星][5m] [Py] [mozilla/cipherscan](https://github.com/mozilla/cipherscan) 查找指定目标支持的SSL ciphersuites
- [**1484**星][13d] [Py] [enablesecurity/wafw00f](https://github.com/enablesecurity/wafw00f) 识别保护网站的WAF产品
- [**1401**星][13d] [JS] [lockfale/osint-framework](https://github.com/lockfale/osint-framework) OSINT Framework
- [**1363**星][2m] [CSS] [undeadsec/socialfish](https://github.com/undeadsec/socialfish) 网络钓鱼培训与信息收集
    - 重复区段: [社工(SET)->工具->未分类-SET](#ce734598055ad3885d45d0b35d2bf0d7) |
- [**1354**星][8d] [Py] [s0md3v/arjun](https://github.com/s0md3v/Arjun) HTTP parameter discovery suite.
- [**1289**星][3m] [Py] [codingo/reconnoitre](https://github.com/codingo/reconnoitre) A security tool for multithreaded information gathering and service enumeration whilst building directory structures to store results, along with writing out recommendations for further testing.
- [**1279**星][1y] [PS] [dafthack/mailsniper](https://github.com/dafthack/mailsniper) 在Microsoft Exchange环境中搜索邮件中包含的指定内容：密码、insider intel、网络架构信息等
- [**1224**星][1m] [Py] [codingo/nosqlmap](https://github.com/codingo/NoSQLMap) Automated NoSQL database enumeration and web application exploitation tool.
- [**1199**星][11m] [C] [blechschmidt/massdns](https://github.com/blechschmidt/massdns) A high-performance DNS stub resolver for bulk lookups and reconnaissance (subdomain enumeration)
- [**1108**星][t] [Py] [sundowndev/phoneinfoga](https://github.com/sundowndev/phoneinfoga) Advanced information gathering & OSINT tool for phone numbers
- [**1102**星][3m] [PHP] [tuhinshubhra/red_hawk](https://github.com/tuhinshubhra/red_hawk) 信息收集、漏洞扫描、爬虫多合一
    - 重复区段: [扫描器->工具->未分类-Scanner](#de63a029bda6a7e429af272f291bb769) |
- [**1059**星][16d] [Rust] [fgribreau/mailchecker](https://github.com/fgribreau/mailchecker) 邮件检测库，跨语言。覆盖33078虚假邮件提供者
- [**976**星][5m] [C] [rbsec/sslscan](https://github.com/rbsec/sslscan) 测试启用SSL/TLS的服务，发现其支持的cipher suites
- [**931**星][16d] [OCaml] [airbus-seclab/bincat](https://github.com/airbus-seclab/bincat) 二进制代码静态分析工具。值分析（寄存器、内存）、污点分析、类型重建和传播（propagation）、前向/后向分析
- [**906**星][5m] [derpopo/uabe](https://github.com/derpopo/uabe) Unity Assets Bundle Extractor
- [**866**星][8m] [Py] [s0md3v/recondog](https://github.com/s0md3v/ReconDog) Reconnaissance Swiss Army Knife
- [**778**星][5m] [Shell] [nahamsec/lazyrecon](https://github.com/nahamsec/lazyrecon) 侦查(reconnaissance)过程自动化脚本, 可自动使用Sublist3r/certspotter获取子域名, 调用nmap/dirsearch等
- [**778**星][1y] [HTML] [sense-of-security/adrecon](https://github.com/sense-of-security/adrecon) 收集Active Directory信息并生成报告
- [**758**星][2m] [Py] [khast3x/h8mail](https://github.com/khast3x/h8mail) Password Breach Hunting and Email OSINT tool, locally or using premium services. Supports chasing down related email
- [**754**星][4m] [Py] [threatexpress/domainhunter](https://github.com/threatexpress/domainhunter) Checks expired domains for categorization/reputation and Archive.org history to determine good candidates for phishing and C2 domain names
    - 重复区段: [社工(SET)->工具->未分类-SET](#ce734598055ad3885d45d0b35d2bf0d7) |
- [**706**星][21d] [Ruby] [intrigueio/intrigue-core](https://github.com/intrigueio/intrigue-core) 外部攻击面发现框架，自动化OSINT
- [**625**星][5m] [Py] [deibit/cansina](https://github.com/deibit/cansina) web 内容发现工具。发出各种请求并过滤回复，识别是否存在请求的资源。
- [**595**星][2m] [Py] [1n3/blackwidow](https://github.com/1n3/blackwidow) A Python based web application scanner to gather OSINT and fuzz for OWASP vulnerabilities on a target website.
- [**582**星][8m] [Py] [ekultek/zeus-scanner](https://github.com/ekultek/zeus-scanner) Advanced reconnaissance utility
- [**561**星][1m] [Py] [m4ll0k/infoga](https://github.com/m4ll0k/infoga) 邮件信息收集工具
- [**516**星][1m] [no-github/digital-privacy](https://github.com/no-github/digital-privacy) 一个关于数字隐私搜集、保护、清理集一体的方案,外加开源信息收集(OSINT)对抗
- [**492**星][29d] [Rust] [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int) Semi-automatic OSINT framework and package manager
- [**475**星][4m] [Py] [xillwillx/skiptracer](https://github.com/xillwillx/skiptracer) OSINT python webscaping framework
- [**442**星][3m] [Py] [superhedgy/attacksurfacemapper](https://github.com/superhedgy/attacksurfacemapper) AttackSurfaceMapper is a tool that aims to automate the reconnaissance process.
- [**422**星][1y] [JS] [ciscocsirt/gosint](https://github.com/ciscocsirt/gosint) 收集、处理、索引高质量IOC的框架
- [**411**星][5m] [Shell] [d4rk007/redghost](https://github.com/d4rk007/redghost) Linux post exploitation framework written in bash designed to assist red teams in persistence, reconnaissance, privilege escalation and leaving no trace.
- [**409**星][3m] [ph055a/osint-collection](https://github.com/ph055a/osint-collection) Maintained collection of OSINT related resources. (All Free & Actionable)
- [**397**星][5d] [Go] [graniet/operative-framework](https://github.com/graniet/operative-framework) operative framework is a OSINT investigation framework, you can interact with multiple targets, execute multiple modules, create links with target, export rapport to PDF file, add note to target or results, interact with RESTFul API, write your own modules.
- [**392**星][1y] [Py] [chrismaddalena/odin](https://github.com/chrismaddalena/odin) Automated network asset, email, and social media profile discovery and cataloguing.
- [**383**星][2m] [Py] [dedsecinside/torbot](https://github.com/dedsecinside/torbot) Dark Web OSINT Tool
- [**354**星][12m] [Py] [aancw/belati](https://github.com/aancw/belati) The Traditional Swiss Army Knife for OSINT
- [**353**星][18d] [Py] [depthsecurity/armory](https://github.com/depthsecurity/armory) Armory is a tool meant to take in a lot of external and discovery data from a lot of tools, add it to a database and correlate all of related information.
- [**344**星][16d] [Py] [darryllane/bluto](https://github.com/darryllane/bluto) DNS Recon | Brute Forcer | DNS Zone Transfer | DNS Wild Card Checks | DNS Wild Card Brute Forcer | Email Enumeration | Staff Enumeration | Compromised Account Checking
- [**336**星][12m] [Py] [mdsecactivebreach/linkedint](https://github.com/mdsecactivebreach/linkedint) A LinkedIn scraper for reconnaissance during adversary simulation
- [**329**星][6m] [Go] [nhoya/gosint](https://github.com/nhoya/gosint) OSINT Swiss Army Knife
- [**328**星][17d] [Py] [initstring/linkedin2username](https://github.com/initstring/linkedin2username) Generate username lists for companies on LinkedIn
- [**314**星][] [Py] [sharadkumar97/osint-spy](https://github.com/sharadkumar97/osint-spy) Performs OSINT scan on email/domain/ip_address/organization using OSINT-SPY. It can be used by Data Miners, Infosec Researchers, Penetration Testers and cyber crime investigator in order to find deep information about their target. If you want to ask something please feel free to reach out to me at robotcoder@protonmail.com
- [**313**星][1y] [Py] [twelvesec/gasmask](https://github.com/twelvesec/gasmask) Information gathering tool - OSINT
- [**307**星][1y] [Py] [r3vn/badkarma](https://github.com/r3vn/badkarma) network reconnaissance toolkit
- [**297**星][7m] [Shell] [eschultze/urlextractor](https://github.com/eschultze/urlextractor) Information gathering & website reconnaissance |
- [**292**星][3m] [JS] [pownjs/pown-recon](https://github.com/pownjs/pown-recon) A powerful target reconnaissance framework powered by graph theory.
- [**286**星][1y] [Shell] [ha71/namechk](https://github.com/ha71/namechk) Osint tool based on namechk.com for checking usernames on more than 100 websites, forums and social networks.
- [**285**星][23d] [Py] [ekultek/whatbreach](https://github.com/ekultek/whatbreach) OSINT tool to find breached emails, databases, pastes, and relevant information
- [**269**星][1y] [Go] [tomsteele/blacksheepwall](https://github.com/tomsteele/blacksheepwall) blacksheepwall is a hostname reconnaissance tool
- [**259**星][4m] [Py] [thewhiteh4t/finalrecon](https://github.com/thewhiteh4t/finalrecon) OSINT Tool for All-In-One Web Reconnaissance
- [**258**星][3m] [Shell] [solomonsklash/chomp-scan](https://github.com/solomonsklash/chomp-scan) A scripted pipeline of tools to streamline the bug bounty/penetration test reconnaissance phase, so you can focus on chomping bugs.
- [**257**星][8d] [TS] [ninoseki/mitaka](https://github.com/ninoseki/mitaka) A browser extension for OSINT search
- [**253**星][26d] [Py] [zephrfish/googd0rker](https://github.com/zephrfish/googd0rker) GoogD0rker is a tool for firing off google dorks against a target domain, it is purely for OSINT against a specific target domain. READ the readme before messaging or tweeting me.
- [**243**星][2m] [Py] [sc1341/instagramosint](https://github.com/sc1341/instagramosint) An Instagram Open Source Intelligence Tool
- [**236**星][7m] [JS] [cliqz-oss/local-sheriff](https://github.com/cliqz-oss/local-sheriff) Think of Local sheriff as a recon tool in your browser (WebExtension). While you normally browse the internet, Local Sheriff works in the background to empower you in identifying what data points (PII) are being shared / leaked to which all third-parties.
- [**233**星][2m] [Propeller Spin] [grandideastudio/jtagulator](https://github.com/grandideastudio/jtagulator) Assisted discovery of on-chip debug interfaces
- [**229**星][2m] [Py] [anon-exploiter/sitebroker](https://github.com/anon-exploiter/sitebroker) A cross-platform python based utility for information gathering and penetration testing automation!
- [**226**星][5d] [Py] [eth0izzle/the-endorser](https://github.com/eth0izzle/the-endorser) An OSINT tool that allows you to draw out relationships between people on LinkedIn via endorsements/skills.
- [**223**星][1y] [Shell] [edoverflow/megplus](https://github.com/edoverflow/megplus) Automated reconnaissance wrapper — TomNomNom's meg on steroids. [DEPRECATED]
- [**222**星][1m] [PS] [tonyphipps/meerkat](https://github.com/tonyphipps/meerkat) A collection of PowerShell modules designed for artifact gathering and reconnaisance of Windows-based endpoints.
- [**220**星][9d] [Shell] [x1mdev/reconpi](https://github.com/x1mdev/reconpi) ReconPi - A lightweight recon tool that performs extensive scanning with the latest tools.
- [**217**星][5m] [Py] [spiderlabs/hosthunter](https://github.com/spiderlabs/hosthunter) HostHunter a recon tool for discovering hostnames using OSINT techniques.
- [**211**星][2m] [Py] [inquest/omnibus](https://github.com/inquest/omnibus) The OSINT Omnibus (beta release)
- [**201**星][4m] [Py] [sham00n/buster](https://github.com/sham00n/buster) An advanced tool for email reconnaissance


### <a id="e945721056c78a53003e01c3d2f3b8fe"></a>子域名枚举&&爆破


- [**4153**星][2m] [Py] [aboul3la/sublist3r](https://github.com/aboul3la/sublist3r) Fast subdomains enumeration tool for penetration testers
- [**3270**星][27d] [Py] [laramies/theharvester](https://github.com/laramies/theharvester) E-mails, subdomains and names Harvester - OSINT
- [**3102**星][7m] [Go] [michenriksen/aquatone](https://github.com/michenriksen/aquatone) 子域名枚举工具。除了经典的爆破枚举之外，还利用多种开源工具和在线服务大幅度增加发现子域名的数量。
- [**2028**星][8d] [Go] [projectdiscovery/subfinder](https://github.com/projectdiscovery/subfinder) 使用Passive Sources, Search Engines, Pastebins, Internet Archives等查找子域名
- [**1808**星][7m] [Py] [lijiejie/subdomainsbrute](https://github.com/lijiejie/subdomainsbrute) 子域名爆破
- [**1716**星][8m] [Py] [guelfoweb/knock](https://github.com/guelfoweb/knock) 使用 Wordlist 枚举子域名
- [**1561**星][11d] [Go] [caffix/amass](https://github.com/caffix/amass) 子域名枚举, 搜索互联网数据源, 使用机器学习猜测子域名. Go语言
- [**1115**星][2m] [Py] [john-kurkowski/tldextract](https://github.com/john-kurkowski/tldextract) Accurately separate the TLD from the registered domain and subdomains of a URL, using the Public Suffix List.
- [**990**星][6d] [Py] [shmilylty/oneforall](https://github.com/shmilylty/oneforall) 子域收集工具
- [**823**星][8d] [Rust] [edu4rdshl/findomain](https://github.com/edu4rdshl/findomain) The fastest and cross-platform subdomain enumerator, don't waste your time.
- [**773**星][5m] [Go] [haccer/subjack](https://github.com/haccer/subjack) 异步多线程扫描子域列表，识别能够被劫持的子域。Go 编写
- [**649**星][1y] [Py] [simplysecurity/simplyemail](https://github.com/SimplySecurity/SimplyEmail) Email recon made fast and easy, with a framework to build on
- [**575**星][3m] [Py] [jonluca/anubis](https://github.com/jonluca/anubis) Subdomain enumeration and information gathering tool
- [**553**星][9m] [Py] [feeicn/esd](https://github.com/feeicn/esd) Enumeration sub domains(枚举子域名)
- [**499**星][3m] [Py] [yanxiu0614/subdomain3](https://github.com/yanxiu0614/subdomain3) 简单快速的子域名爆破工具。
- [**498**星][27d] [Py] [typeerror/domained](https://github.com/TypeError/domained) Multi Tool Subdomain Enumeration
- [**479**星][6m] [Py] [threezh1/jsfinder](https://github.com/threezh1/jsfinder) JSFinder is a tool for quickly extracting URLs and subdomains from JS files on a website.
- [**454**星][25d] [Py] [nsonaniya2010/subdomainizer](https://github.com/nsonaniya2010/subdomainizer) A tool to find subdomains and interesting things hidden inside, external Javascript files of page, folder, and Github.
- [**445**星][1y] [Go] [ice3man543/subover](https://github.com/ice3man543/subover) A Powerful Subdomain Takeover Tool
- [**432**星][11m] [Py] [appsecco/bugcrowd-levelup-subdomain-enumeration](https://github.com/appsecco/bugcrowd-levelup-subdomain-enumeration) This repository contains all the material from the talk "Esoteric sub-domain enumeration techniques" given at Bugcrowd LevelUp 2017 virtual conference
- [**334**星][5m] [Py] [chris408/ct-exposer](https://github.com/chris408/ct-exposer) An OSINT tool that discovers sub-domains by searching Certificate Transparency logs
- [**332**星][2m] [Go] [tomnomnom/assetfinder](https://github.com/tomnomnom/assetfinder) Find domains and subdomains related to a given domain
- [**293**星][4d] [Go] [anshumanbh/tko-subs](https://github.com/anshumanbh/tko-subs) A tool that can help detect and takeover subdomains with dead DNS records
- [**279**星][26d] [Py] [franccesco/getaltname](https://github.com/franccesco/getaltname) 直接从SSL证书中提取子域名或虚拟域名
- [**277**星][11m] [Py] [appsecco/the-art-of-subdomain-enumeration](https://github.com/appsecco/the-art-of-subdomain-enumeration) This repository contains all the supplement material for the book "The art of sub-domain enumeration"
- [**228**星][2m] [Shell] [screetsec/sudomy](https://github.com/screetsec/sudomy) Sudomy is a subdomain enumeration tool, created using a bash script, to analyze domains and collect subdomains in fast and comprehensive way . Report output in HTML or CSV format


### <a id="375a8baa06f24de1b67398c1ac74ed24"></a>信息收集&&侦查&&Recon&&InfoGather


- [**3603**星][11d] [Shell] [drwetter/testssl.sh](https://github.com/drwetter/testssl.sh) 检查服务器任意端口对 TLS/SSL 的支持、协议以及一些加密缺陷，命令行工具
- [**2489**星][1m] [Py] [smicallef/spiderfoot](https://github.com/smicallef/spiderfoot) 自动收集指定目标的信息：IP、域名、主机名、网络子网、ASN、邮件地址、用户名
- [**2021**星][7d] [Py] [j3ssie/osmedeus](https://github.com/j3ssie/osmedeus) Fully automated offensive security framework for reconnaissance and vulnerability scanning
- [**1966**星][9m] [JS] [weichiachang/stacks-cli](https://github.com/weichiachang/stacks-cli) Check website stack from the terminal
- [**1958**星][30d] [Go] [mpolden/echoip](https://github.com/mpolden/echoip) IP address lookup service
- [**1651**星][1y] [Py] [evyatarmeged/raccoon](https://github.com/evyatarmeged/raccoon) 高性能的侦查和漏洞扫描工具
- [**1486**星][6m] [Py] [oros42/imsi-catcher](https://github.com/oros42/imsi-catcher) This program show you IMSI numbers of cellphones around you.
- [**1305**星][1y] [Go] [evilsocket/xray](https://github.com/evilsocket/xray) 自动化执行一些信息收集、网络映射的初始化工作
- [**1154**星][23d] [C] [xroche/httrack](https://github.com/xroche/httrack) download a World Wide website from the Internet to a local directory, building recursively all directories, getting html, images, and other files from the server to your computer.
- [**975**星][2m] [HTML] [n0tr00t/sreg](https://github.com/n0tr00t/sreg) 可对使用者通过输入email、phone、username的返回用户注册的所有互联网护照信息。
- [**923**星][3m] [Ruby] [weppos/whois](https://github.com/weppos/whois) An intelligent — pure Ruby — WHOIS client and parser.
- [**860**星][11m] [Shell] [thelinuxchoice/userrecon](https://github.com/thelinuxchoice/userrecon) Find usernames across over 75 social networks
- [**838**星][7d] [HTML] [rewardone/oscprepo](https://github.com/rewardone/oscprepo) A list of commands, scripts, resources, and more that I have gathered and attempted to consolidate for use as OSCP (and more) study material. Commands in 'Usefulcommands' Keepnote. Bookmarks and reading material in 'BookmarkList' Keepnote. Reconscan in scripts folder.
- [**677**星][2m] [Py] [tib3rius/autorecon](https://github.com/tib3rius/autorecon) AutoRecon is a multi-threaded network reconnaissance tool which performs automated enumeration of services.
- [**512**星][10m] [Py] [fortynorthsecurity/just-metadata](https://github.com/FortyNorthSecurity/Just-Metadata) Just-Metadata is a tool that gathers and analyzes metadata about IP addresses. It attempts to find relationships between systems within a large dataset.
- [**483**星][2m] [Py] [yassineaboukir/sublert](https://github.com/yassineaboukir/sublert) Sublert is a security and reconnaissance tool which leverages certificate transparency to automatically monitor new subdomains deployed by specific organizations and issued TLS/SSL certificate.
- [**418**星][2m] [Py] [lanmaster53/recon-ng](https://github.com/lanmaster53/recon-ng) Open Source Intelligence gathering tool aimed at reducing the time spent harvesting information from open sources.
- [**394**星][11m] [Swift] [ibm/mac-ibm-enrollment-app](https://github.com/ibm/mac-ibm-enrollment-app) The Mac@IBM enrollment app makes setting up macOS with Jamf Pro more intuitive for users and easier for IT. The application offers IT admins the ability to gather additional information about their users during setup, allows users to customize their enrollment by selecting apps or bundles of apps to install during setup, and provides users with …
- [**362**星][2m] [Shell] [vitalysim/totalrecon](https://github.com/vitalysim/totalrecon) TotalRecon installs all the recon tools you need
- [**361**星][5m] [C++] [wbenny/pdbex](https://github.com/wbenny/pdbex) pdbex is a utility for reconstructing structures and unions from the PDB into compilable C headers
- [**307**星][5m] [PLpgSQL] [amachanic/sp_whoisactive](https://github.com/amachanic/sp_whoisactive) sp_whoisactive
- [**300**星][18d] [Py] [govanguard/legion](https://github.com/govanguard/legion) Legion is an open source, easy-to-use, super-extensible and semi-automated network penetration testing tool that aids in discovery, reconnaissance and exploitation of information systems.
- [**273**星][20d] [Rust] [nccgroup/dirble](https://github.com/nccgroup/dirble) Fast directory scanning and scraping tool
- [**269**星][11m] [Py] [LaNMaSteR53/recon-ng](https://bitbucket.org/lanmaster53/recon-ng) 
- [**258**星][4d] [Java] [ripe-ncc/whois](https://github.com/ripe-ncc/whois) RIPE Database whois code repository
- [**233**星][2m] [C] [elfmaster/libelfmaster](https://github.com/elfmaster/libelfmaster) Secure ELF parsing/loading library for forensics reconstruction of malware, and robust reverse engineering tools
- [**200**星][2m] [Py] [tylous/vibe](https://github.com/tylous/vibe) A framework for stealthy domain reconnaissance


### <a id="016bb6bd00f1e0f8451f779fe09766db"></a>指纹&&Fingerprinting


- [**9519**星][12d] [JS] [valve/fingerprintjs2](https://github.com/valve/fingerprintjs2) Modern & flexible browser fingerprinting library
- [**4758**星][7m] [Py] [worldveil/dejavu](https://github.com/worldveil/dejavu) Audio fingerprinting and recognition in Python
- [**3072**星][2m] [JS] [valve/fingerprintjs](https://github.com/valve/fingerprintjs) Anonymous browser fingerprint
- [**1670**星][] [JS] [ghacksuserjs/ghacks-user.js](https://github.com/ghacksuserjs/ghacks-user.js) An ongoing comprehensive user.js template for configuring and hardening Firefox privacy, security and anti-fingerprinting
- [**1618**星][10m] [C] [nmikhailov/validity90](https://github.com/nmikhailov/validity90) Reverse engineering of Validity/Synaptics 138a:0090, 138a:0094, 138a:0097, 06cb:0081, 06cb:009a fingerprint readers protocol
- [**931**星][8m] [JS] [song-li/cross_browser](https://github.com/song-li/cross_browser) cross_browser_fingerprinting
- [**831**星][1m] [Py] [salesforce/ja3](https://github.com/salesforce/ja3) SSL/TLS 客户端指纹，用于恶意代码检测
- [**380**星][2m] [Py] [0x4d31/fatt](https://github.com/0x4d31/fatt) FATT /fingerprintAllTheThings - a pyshark based script for extracting network metadata and fingerprints from pcap files and live network traffic
- [**313**星][3m] [Py] [dpwe/audfprint](https://github.com/dpwe/audfprint) Landmark-based audio fingerprinting
- [**312**星][4m] [Py] [salesforce/hassh](https://github.com/salesforce/hassh) HASSH is a network fingerprinting standard which can be used to identify specific Client and Server SSH implementations. The fingerprints can be easily stored, searched and shared in the form of a small MD5 fingerprint.
- [**282**星][1y] [CSS] [w-digital-scanner/w11scan](https://github.com/w-digital-scanner/w11scan) 分布式WEB指纹识别平台 Distributed WEB fingerprint identification platform
- [**245**星][3m] [C] [leebrotherston/tls-fingerprinting](https://github.com/leebrotherston/tls-fingerprinting) TLS Fingerprinting
- [**223**星][25d] [GLSL] [westpointltd/tls_prober](https://github.com/westpointltd/tls_prober) A tool to fingerprint SSL/TLS servers
- [**220**星][1y] [Py] [sensepost/spartan](https://github.com/sensepost/spartan) Frontpage and Sharepoint fingerprinting and attack tool.


### <a id="6ea9006a5325dd21d246359329a3ede2"></a>收集


- [**3868**星][1m] [jivoi/awesome-osint](https://github.com/jivoi/awesome-osint) OSINT资源收集


### <a id="dc74ad2dd53aa8c8bf3a3097ad1f12b7"></a>社交网络


#### <a id="6d36e9623aadaf40085ef5af89c8d698"></a>其他-SocialNetwork


- [**9767**星][4d] [Py] [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock) Find Usernames Across Social Networks
- [**2578**星][3m] [Py] [greenwolf/social_mapper](https://github.com/Greenwolf/social_mapper) 对多个社交网站的用户Profile图片进行大规模的人脸识别
- [**1131**星][3m] [Py] [thoughtfuldev/eagleeye](https://github.com/thoughtfuldev/eagleeye) Stalk your Friends. Find their Instagram, FB and Twitter Profiles using Image Recognition and Reverse Image Search.
- [**664**星][1y] [Go] [0x09al/raven](https://github.com/0x09al/raven) raven is a Linkedin information gathering tool that can be used by pentesters to gather information about an organization employees using Linkedin.


#### <a id="de93515e77c0ca100bbf92c83f82dc2a"></a>Twitter


- [**3033**星][4d] [Py] [twintproject/twint](https://github.com/twintproject/twint) An advanced Twitter scraping & OSINT tool written in Python that doesn't use Twitter's API, allowing you to scrape a user's followers, following, Tweets and more while evading most API limitations.


#### <a id="8d1ae776898748b8249132e822f6c919"></a>Github


- [**1717**星][2m] [Go] [eth0izzle/shhgit](https://github.com/eth0izzle/shhgit) 监听Github Event API，实时查找Github代码和Gist中的secret和敏感文件
- [**1636**星][2m] [Shell] [internetwache/gittools](https://github.com/internetwache/gittools) find websites with their .git repository available to the public
- [**1563**星][1y] [Py] [unkl4b/gitminer](https://github.com/unkl4b/gitminer) Github内容挖掘
- [**1352**星][7m] [Py] [feeicn/gsil](https://github.com/feeicn/gsil) GitHub敏感信息泄露监控，几乎实时监控，发送警告
- [**859**星][2m] [JS] [vksrc/github-monitor](https://github.com/vksrc/github-monitor) Github Sensitive Information Leakage Monitor(Github信息泄漏监控系统)
- [**857**星][7m] [Go] [misecurity/x-patrol](https://github.com/misecurity/x-patrol) github泄露扫描系统
- [**810**星][4m] [Py] [techgaun/github-dorks](https://github.com/techgaun/github-dorks) 快速搜索Github repo中的敏感信息
- [**789**星][2m] [Py] [bishopfox/gitgot](https://github.com/bishopfox/gitgot) Semi-automated, feedback-driven tool to rapidly search through troves of public data on GitHub for sensitive secrets.
- [**667**星][3m] [Py] [hisxo/gitgraber](https://github.com/hisxo/gitgraber) monitor GitHub to search and find sensitive data in real time for different online services such as: Google, Amazon, Paypal, Github, Mailgun, Facebook, Twitter, Heroku, Stripe...
- [**324**星][4d] [HTML] [tanjiti/sec_profile](https://github.com/tanjiti/sec_profile) 爬取secwiki和xuanwu.github.io/sec.today,分析安全信息站点、安全趋势、提取安全工作者账号(twitter,weixin,github等)
    - 重复区段: [扫描器->工具->隐私](#58d8b993ffc34f7ded7f4a0077129eb2) |
- [**294**星][8m] [Py] [s0md3v/zen](https://github.com/s0md3v/zen) 查找Github用户的邮箱地址




### <a id="a695111d8e30d645354c414cb27b7843"></a>DNS


- [**2562**星][5m] [Go] [oj/gobuster](https://github.com/oj/gobuster) Directory/File, DNS and VHost busting tool written in Go
- [**2380**星][2m] [Py] [ab77/netflix-proxy](https://github.com/ab77/netflix-proxy) Smart DNS proxy to watch Netflix
- [**2131**星][2m] [Py] [elceef/dnstwist](https://github.com/elceef/dnstwist) 域名置换引擎，用于检测打字错误，网络钓鱼和企业间谍活动
    - 重复区段: [社工(SET)->工具->钓鱼](#290e9ae48108d21d6d8b9ea9e74d077d) |
- [**1933**星][7d] [C++] [powerdns/pdns](https://github.com/powerdns/pdns) PowerDNS
- [**1735**星][4m] [Py] [lgandx/responder](https://github.com/lgandx/responder) Responder is a LLMNR, NBT-NS and MDNS poisoner, with built-in HTTP/SMB/MSSQL/FTP/LDAP rogue authentication server supporting NTLMv1/NTLMv2/LMv2, Extended Security NTLMSSP and Basic HTTP authentication.
- [**1144**星][16d] [Py] [darkoperator/dnsrecon](https://github.com/darkoperator/dnsrecon) DNS 枚举脚本
- [**1090**星][1m] [Go] [looterz/grimd](https://github.com/looterz/grimd) Fast dns proxy that can run anywhere, built to black-hole internet advertisements and malware servers.
- [**1090**星][2m] [Go] [nadoo/glider](https://github.com/nadoo/glider) 正向代理，支持若干协议
- [**1078**星][3m] [Py] [infosec-au/altdns](https://github.com/infosec-au/altdns) Generates permutations, alterations and mutations of subdomains and then resolves them
- [**977**星][7m] [Py] [m57/dnsteal](https://github.com/m57/dnsteal) DNS Exfiltration tool for stealthily sending files over DNS requests.
- [**912**星][5m] [Py] [m0rtem/cloudfail](https://github.com/m0rtem/cloudfail) 通过错误配置的DNS和老数据库，发现CloudFlare网络后面的隐藏IP
- [**908**星][30d] [Py] [mschwager/fierce](https://github.com/mschwager/fierce) A DNS reconnaissance tool for locating non-contiguous IP space.
- [**708**星][1y] [Py] [bugscanteam/dnslog](https://github.com/bugscanteam/dnslog) 监控 DNS 解析记录和 HTTP 访问记录
- [**613**星][8m] [Shell] [cokebar/gfwlist2dnsmasq](https://github.com/cokebar/gfwlist2dnsmasq) A shell script which convert gfwlist into dnsmasq rules. Python version:
- [**585**星][2m] [C] [getdnsapi/stubby](https://github.com/getdnsapi/stubby) Stubby is the name given to a mode of using getdns which enables it to act as a local DNS Privacy stub resolver (using DNS-over-TLS).
- [**461**星][9m] [C] [cofyc/dnscrypt-wrapper](https://github.com/cofyc/dnscrypt-wrapper) This is dnscrypt wrapper (server-side dnscrypt proxy), which helps to add dnscrypt support to any name resolver.
- [**415**星][6m] [Py] [dnsviz/dnsviz](https://github.com/dnsviz/dnsviz) s a tool suite for analysis and visualization of Domain Name System (DNS) behavior, including its security extensions (DNSSEC)
- [**375**星][1m] [JS] [nccgroup/singularity](https://github.com/nccgroup/singularity) A DNS rebinding attack framework.
- [**355**星][1y] [Py] [i3visio/osrframework](https://github.com/i3visio/osrframework) 开源研究框架，提供 API 和工具执行更加精确的在线研究，例如用户名检查、DNS lookup、信息泄露研究、深度 web 研究、正则表达式提取等。
- [**336**星][5m] [Py] [rbsec/dnscan](https://github.com/rbsec/dnscan) a python wordlist-based DNS subdomain scanner.
- [**267**星][1y] [Py] [trycatchhcf/packetwhisper](https://github.com/trycatchhcf/packetwhisper) Stealthily exfiltrate data and defeat attribution using DNS queries and text-based steganography. Avoid the problems associated with typical DNS exfiltration methods. Transfer data between systems without the communicating devices directly connecting to each other or to a common endpoint. No need to control a DNS Name Server.
- [**265**星][2m] [Go] [sensepost/godoh](https://github.com/sensepost/godoh)  A DNS-over-HTTPS Command & Control Proof of Concept 
- [**263**星][3m] [Go] [zmap/zdns](https://github.com/zmap/zdns) 快速DNS查找, 命令行工具
- [**258**星][7d] [Go] [erbbysam/dnsgrep](https://github.com/erbbysam/dnsgrep) Quickly Search Large DNS Datasets
- [**256**星][3m] [Py] [qunarcorp/open_dnsdb](https://github.com/qunarcorp/open_dnsdb) OpenDnsdb 是去哪儿网OPS团队开源的基于Python语言的DNS管理系统
- [**252**星][8m] [Py] [dirkjanm/adidnsdump](https://github.com/dirkjanm/adidnsdump) Active Directory Integrated DNS dumping by any authenticated user
- [**251**星][4m] [C#] [kevin-robertson/inveighzero](https://github.com/kevin-robertson/inveighzero) Windows C# LLMNR/mDNS/NBNS/DNS spoofer/man-in-the-middle tool
- [**241**星][23d] [Py] [mandatoryprogrammer/trusttrees](https://github.com/mandatoryprogrammer/trusttrees) a script to recursively follow all the possible delegation paths for a target domain and graph the relationships between various nameservers along the way.


### <a id="18c7c1df2e6ae5e9135dfa2e4eb1d4db"></a>Shodan


- [**1214**星][8d] [Py] [achillean/shodan-python](https://github.com/achillean/shodan-python) The official Python library for Shodan
- [**1052**星][5m] [Py] [woj-ciech/kamerka](https://github.com/woj-ciech/kamerka) 利用Shodan构建交互式摄像头地图
- [**890**星][3m] [jakejarvis/awesome-shodan-queries](https://github.com/jakejarvis/awesome-shodan-queries) 
- [**858**星][3m] [Py] [649/memcrashed-ddos-exploit](https://github.com/649/memcrashed-ddos-exploit) DDoS attack tool for sending forged UDP packets to vulnerable Memcached servers obtained using Shodan API
    - 重复区段: [渗透->工具->DDOS](#a0897294e74a0863ea8b83d11994fad6) |
- [**391**星][3d] [Py] [random-robbie/my-shodan-scripts](https://github.com/random-robbie/my-shodan-scripts) Collection of Scripts for shodan searching stuff.
- [**378**星][2m] [Py] [pielco11/fav-up](https://github.com/pielco11/fav-up) IP lookup from favicon using Shodan
- [**234**星][11m] [Py] [nethunteros/punter](https://github.com/nethunteros/punter) 使用 DNSDumpster, WHOIS, Reverse WHOIS 挖掘域名
- [**220**星][6d] [Py] [shodansploit/shodansploit](https://github.com/shodansploit/shodansploit) 


### <a id="94c01f488096fafc194b9a07f065594c"></a>nmap


- [**3609**星][7d] [C] [nmap/nmap](https://github.com/nmap/nmap) Nmap
- [**2116**星][7m] [Py] [calebmadrigal/trackerjacker](https://github.com/calebmadrigal/trackerjacker) 映射你没连接到的Wifi网络, 类似于NMap, 另外可以追踪设备
- [**1871**星][20d] [Lua] [vulnerscom/nmap-vulners](https://github.com/vulnerscom/nmap-vulners) NSE script based on Vulners.com API
- [**1536**星][5d] [C++] [nmap/npcap](https://github.com/nmap/npcap) Nmap项目的针对Windows系统的数据包嗅探库，基于WinPcap/Libpcap，用NDIS6和LWF做了升级
- [**1317**星][3m] [Lua] [scipag/vulscan](https://github.com/scipag/vulscan) Nmap 模块，将 Nmap 转化为高级漏洞扫描器
- [**1029**星][1m] [Shell] [trimstray/sandmap](https://github.com/trimstray/sandmap) 使用NMap引擎, 辅助网络和系统侦查(reconnaissance)
- [**887**星][12m] [Py] [rev3rsesecurity/webmap](https://github.com/rev3rsesecurity/webmap) Nmap Web Dashboard and Reporting
- [**849**星][5d] [Py] [x90skysn3k/brutespray](https://github.com/x90skysn3k/brutespray) 获取 nmapGNMAP 输出，自动调用 Medusa 使用默认证书爆破服务（brute-forces services）
- [**733**星][5m] [Lua] [cldrn/nmap-nse-scripts](https://github.com/cldrn/nmap-nse-scripts) My collection of nmap NSE scripts
- [**696**星][2m] [Py] [iceyhexman/onlinetools](https://github.com/iceyhexman/onlinetools) 在线cms识别|信息泄露|工控|系统|物联网安全|cms漏洞扫描|nmap端口扫描|子域名获取|待续..
- [**503**星][1y] [XSLT] [honze-net/nmap-bootstrap-xsl](https://github.com/honze-net/nmap-bootstrap-xsl) A Nmap XSL implementation with Bootstrap.
- [**394**星][8m] [Py] [savon-noir/python-libnmap](https://github.com/savon-noir/python-libnmap) libnmap is a python library to run nmap scans, parse and diff scan results. It supports python 2.6 up to 3.4. It's wonderful.
- [**328**星][10m] [Py] [samhaxr/hackbox](https://github.com/samhaxr/hackbox) 集合了某些Hacking工具和技巧的攻击工具
- [**308**星][1y] [Java] [s4n7h0/halcyon](https://github.com/s4n7h0/halcyon) First IDE for Nmap Script (NSE) Development.
- [**283**星][1y] [Ruby] [danmcinerney/pentest-machine](https://github.com/danmcinerney/pentest-machine) Automates some pentest jobs via nmap xml file
- [**261**星][1y] [Shell] [m4ll0k/autonse](https://github.com/m4ll0k/autonse) Massive NSE (Nmap Scripting Engine) AutoSploit and AutoScanner
- [**257**星][1y] [Java] [danicuestasuarez/nmapgui](https://github.com/danicuestasuarez/nmapgui) Advanced Graphical User Interface for NMap
- [**246**星][8m] [Lua] [rvn0xsy/nse_vuln](https://github.com/rvn0xsy/nse_vuln) Nmap扫描、漏洞利用脚本
- [**233**星][6m] [Py] [maaaaz/nmaptocsv](https://github.com/maaaaz/nmaptocsv) A simple python script to convert Nmap output to CSV
- [**223**星][12d] [Py] [rackerlabs/scantron](https://github.com/rackerlabs/scantron) A distributed nmap / masscan scanning framework
- [**204**星][6m] [Py] [hellogoldsnakeman/masnmapscan-v1.0](https://github.com/hellogoldsnakeman/masnmapscan-v1.0) 一款端口扫描器。整合了masscan和nmap两款扫描器，masscan扫描端口，nmap扫描端口对应服务，二者结合起来实现了又快又好地扫描。并且加入了防火墙的功能




***


## <a id="b0ca6c8512a268e8438d5e5247a88c2f"></a>文章


### <a id="5a855113503106950acff4d7dbb2403e"></a>新添加






# <a id="546f4fe70faa2236c0fbc2d486a83391"></a>社工(SET)&&钓鱼&&鱼叉攻击


***


## <a id="3e622bff3199cf22fe89db026b765cd4"></a>工具


### <a id="ce734598055ad3885d45d0b35d2bf0d7"></a>未分类-SET


- [**1363**星][2m] [CSS] [undeadsec/socialfish](https://github.com/undeadsec/socialfish) 网络钓鱼培训与信息收集
    - 重复区段: [侦察->工具->未分类-OSINT](#05ab1b75266fddafc7195f5b395e4d99) |
- [**754**星][4m] [Py] [threatexpress/domainhunter](https://github.com/threatexpress/domainhunter) Checks expired domains for categorization/reputation and Archive.org history to determine good candidates for phishing and C2 domain names
    - 重复区段: [侦察->工具->未分类-OSINT](#05ab1b75266fddafc7195f5b395e4d99) |
- [**658**星][18d] [Py] [thewhiteh4t/seeker](https://github.com/thewhiteh4t/seeker) Accurately Locate Smartphones using Social Engineering
- [**342**星][2m] [Py] [raikia/uhoh365](https://github.com/raikia/uhoh365) A script that can see if an email address is valid in Office365 (user/email enumeration). This does not perform any login attempts, is unthrottled, and is incredibly useful for social engineering assessments to find which emails exist and which don't.


### <a id="f30507893511f89b19934e082a54023e"></a>社工


- [**4966**星][4d] [Py] [trustedsec/social-engineer-toolkit](https://github.com/trustedsec/social-engineer-toolkit) The Social-Engineer Toolkit (SET) repository from TrustedSec - All new versions of SET will be deployed here.


### <a id="290e9ae48108d21d6d8b9ea9e74d077d"></a>钓鱼&&Phish


- [**8455**星][8d] [Py] [wifiphisher/wifiphisher](https://github.com/wifiphisher/wifiphisher) 流氓AP框架, 用于RedTeam和Wi-Fi安全测试
    - 重复区段: [无线->未分类-WiFi](#d4efda1853b2cb0909727188116a2a8c) |
- [**4242**星][4d] [Go] [gophish/gophish](https://github.com/gophish/gophish) 网络钓鱼工具包
- [**2829**星][2m] [Go] [kgretzky/evilginx2](https://github.com/kgretzky/evilginx2) 独立的MITM攻击工具，用于登录凭证钓鱼，可绕过双因素认证
- [**2131**星][2m] [Py] [elceef/dnstwist](https://github.com/elceef/dnstwist) 域名置换引擎，用于检测打字错误，网络钓鱼和企业间谍活动
    - 重复区段: [侦察->工具->DNS](#a695111d8e30d645354c414cb27b7843) |
- [**1400**星][9m] [JS] [anttiviljami/browser-autofill-phishing](https://github.com/anttiviljami/browser-autofill-phishing) A simple demo of phishing by abusing the browser autofill feature
- [**1369**星][10m] [HTML] [thelinuxchoice/blackeye](https://github.com/thelinuxchoice/blackeye) The most complete Phishing Tool, with 32 templates +1 customizable
- [**1019**星][22d] [Py] [securestate/king-phisher](https://github.com/securestate/king-phisher) Phishing Campaign Toolkit
- [**996**星][2m] [Py] [x0rz/phishing_catcher](https://github.com/x0rz/phishing_catcher) 使用Certstream 捕获钓鱼域名
- [**968**星][19d] [HTML] [darksecdevelopers/hiddeneye](https://github.com/darksecdevelopers/hiddeneye) Modern Phishing Tool With Advanced Functionality And Multiple Tunnelling Services [ Android-Support-Available ]
- [**918**星][8m] [HTML] [thelinuxchoice/shellphish](https://github.com/thelinuxchoice/shellphish) 针对18个社交媒体的钓鱼工具：Instagram, Facebook, Snapchat, Github, Twitter, Yahoo, Protonmail, Spotify, Netflix, Linkedin, Wordpress, Origin, Steam, Microsoft, InstaFollowers, Gitlab, Pinterest
- [**842**星][1m] [PHP] [raikia/fiercephish](https://github.com/Raikia/FiercePhish) FiercePhish is a full-fledged phishing framework to manage all phishing engagements. It allows you to track separate phishing campaigns, schedule sending of emails, and much more.
- [**537**星][2m] [Py] [shellphish/driller](https://github.com/shellphish/driller) augmenting AFL with symbolic execution!
- [**460**星][4d] [Py] [angr/rex](https://github.com/angr/rex) Shellphish's automated exploitation engine, originally created for the Cyber Grand Challenge.
- [**351**星][5m] [Py] [tatanus/spf](https://github.com/tatanus/spf) SpeedPhishing Framework
- [**300**星][11m] [Py] [mr-un1k0d3r/catmyphish](https://github.com/Mr-Un1k0d3r/CatMyPhish) Search for categorized domain
- [**274**星][1m] [Go] [muraenateam/muraena](https://github.com/muraenateam/muraena) Muraena is an almost-transparent reverse proxy aimed at automating phishing and post-phishing activities.
- [**242**星][3m] [Py] [atexio/mercure](https://github.com/atexio/mercure) 对员工进行网络钓鱼的培训
- [**233**星][1y] [Jupyter Notebook] [wesleyraptor/streamingphish](https://github.com/wesleyraptor/streamingphish) 使用受监督的机器学习, 从证书透明度(Certificate Transparency)日志中检测钓鱼域名
- [**228**星][4m] [Py] [duo-labs/isthislegit](https://github.com/duo-labs/isthislegit) 收集、分析和回复网络钓鱼邮件的框架
- [**218**星][9m] [Go] [joncooperworks/judas](https://github.com/joncooperworks/judas) a phishing proxy
- [**207**星][3d] [JS] [409h/etheraddresslookup](https://github.com/409h/etheraddresslookup) Adds links to strings that look like Ethereum addresses to your favourite blockchain explorer. Adds protection against private key phishing. Offers custom site bookmarks.
- [**205**星][3m] [Py] [dionach/phemail](https://github.com/dionach/phemail) PhEmail is a python open source phishing email tool that automates the process of sending phishing emails as part of a social engineering test


### <a id="ab3e6e6526d058e35c7091d8801ebf3a"></a>鱼叉攻击






***


## <a id="8f6c7489870c7358c39c920c83fa2b6b"></a>文章


### <a id="d7e332e9e235fd5a60687800f5ce184c"></a>新添加的






# <a id="dc89c90b80529c1f62f413288bca89c4"></a>环境配置&&分析系统


***


## <a id="9763d00cbe773aa10502dbe258f9c385"></a>工具


### <a id="f5a7a43f964b2c50825f3e2fee5078c8"></a>未分类-Env


- [**1678**星][2d] [HTML] [clong/detectionlab](https://github.com/clong/detectionlab) Vagrant & Packer scripts to build a lab environment complete with security tooling and logging best practices
- [**1433**星][11d] [Go] [crazy-max/windowsspyblocker](https://github.com/crazy-max/windowsspyblocker) 
- [**1308**星][18d] [C] [cisco-talos/pyrebox](https://github.com/cisco-talos/pyrebox) 逆向沙箱，基于QEMU，Python Scriptable
- [**1229**星][11m] [JS] [mame82/p4wnp1_aloa](https://github.com/mame82/p4wnp1_aloa) 将 Rapsberry Pi Zero W 转变成灵活的渗透平台
- [**827**星][1m] [redhuntlabs/redhunt-os](https://github.com/redhuntlabs/redhunt-os) Virtual Machine for Adversary Emulation and Threat Hunting
- [**800**星][3m] [sh4hin/androl4b](https://github.com/sh4hin/androl4b) 用于评估Android应用程序，逆向工程和恶意软件分析的虚拟机
- [**564**星][6m] [Ruby] [sliim/pentest-env](https://github.com/sliim/pentest-env) Pentest environment deployer (kali linux + targets) using vagrant and chef.
- [**214**星][12m] [Shell] [proxycannon/proxycannon-ng](https://github.com/proxycannon/proxycannon-ng) 使用多个云环境构建私人僵尸网络, 用于渗透测试和RedTeaming


### <a id="cf07b04dd2db1deedcf9ea18c05c83e0"></a>Linux-Distro


- [**2927**星][4d] [Py] [trustedsec/ptf](https://github.com/trustedsec/ptf) 创建基于Debian/Ubuntu/ArchLinux的渗透测试环境
- [**2375**星][18d] [security-onion-solutions/security-onion](https://github.com/security-onion-solutions/security-onion) Linux distro for intrusion detection, enterprise security monitoring, and log management
- [**1489**星][t] [Shell] [blackarch/blackarch](https://github.com/blackarch/blackarch) BlackArch Linux is an Arch Linux-based distribution for penetration testers and security researchers.
- [**347**星][t] [Shell] [archstrike/archstrike](https://github.com/archstrike/archstrike) An Arch Linux repository for security professionals and enthusiasts. Done the Arch Way and optimized for i686, x86_64, ARMv6, ARMv7 and ARMv8.


### <a id="4709b10a8bb691204c0564a3067a0004"></a>环境自动配置&&自动安装


- [**3142**星][3m] [PS] [fireeye/commando-vm](https://github.com/fireeye/commando-vm) Complete Mandiant Offensive VM (Commando VM), a fully customizable Windows-based pentesting virtual machine distribution. commandovm@fireeye.com
- [**1748**星][2m] [PS] [fireeye/flare-vm](https://github.com/fireeye/flare-vm) 火眼发布用于 Windows 恶意代码分析的虚拟机：FLARE VM




***


## <a id="6454949c0d580904537643b8f4cd5a6b"></a>文章


### <a id="873294ea77bc292b6fc4cfb2f9b40049"></a>新添加的






# <a id="c49aef477cf3397f97f8b72185c3d100"></a>密码&&凭证&&认证


***


## <a id="862af330f45f21fbb0d495837fc7e879"></a>工具


### <a id="20bf2e2fefd6de7aadbf0774f4921824"></a>未分类-Password


- [**4889**星][13d] [Py] [alessandroz/lazagne](https://github.com/alessandroz/lazagne) Credentials recovery project
- [**1457**星][1y] [Py] [d4vinci/cr3dov3r](https://github.com/d4vinci/cr3dov3r) Know the dangers of credential reuse attacks.
- [**1384**星][24d] [Shell] [drduh/pwd.sh](https://github.com/drduh/pwd.sh) GPG symmetric password manager
- [**1282**星][19d] [Py] [pyauth/pyotp](https://github.com/pyauth/pyotp) Python One-Time Password Library
- [**1034**星][1y] [PS] [danmcinerney/icebreaker](https://github.com/danmcinerney/icebreaker) Gets plaintext Active Directory credentials if you're on the internal network but outside the AD environment
- [**1000**星][10d] [Ruby] [mdp/rotp](https://github.com/mdp/rotp) Ruby One Time Password library
- [**913**星][7d] [C] [cossacklabs/themis](https://github.com/cossacklabs/themis) 用于存储或通信的加密库，可用于Swift, ObjC, Android, С++, JS, Python, Ruby, PHP, Go。
- [**814**星][9m] [Py] [nccgroup/featherduster](https://github.com/nccgroup/featherduster) 自动化的密码分析工具，模块化
- [**805**星][2m] [Py] [hellman/xortool](https://github.com/hellman/xortool) 分析多字节异或密码
- [**740**星][1m] [Py] [ricterz/genpass](https://github.com/ricterz/genpass) 中国特色的弱口令生成器
- [**523**星][3m] [Py] [unode/firefox_decrypt](https://github.com/unode/firefox_decrypt) Firefox Decrypt is a tool to extract passwords from Mozilla (Firefox/Thunderbird/SeaMonkey) profiles
- [**507**星][3m] [Py] [byt3bl33d3r/sprayingtoolkit](https://github.com/byt3bl33d3r/sprayingtoolkit) Scripts to make password spraying attacks against Lync/S4B & OWA a lot quicker, less painful and more efficient
- [**485**星][1y] [JS] [emilbayes/secure-password](https://github.com/emilbayes/secure-password) Making Password storage safer for all
- [**454**星][1y] [Go] [ncsa/ssh-auditor](https://github.com/ncsa/ssh-auditor) 扫描网络中的弱SSH密码
- [**399**星][2m] [Py] [x899/chrome_password_grabber](https://github.com/x899/chrome_password_grabber) Get unencrypted 'Saved Password' from Google Chrome
- [**391**星][1y] [Shell] [mthbernardes/sshlooter](https://github.com/mthbernardes/sshlooter) Script to steal passwords from ssh.
- [**369**星][4m] [Ruby] [digininja/pipal](https://github.com/digininja/pipal) Pipal, THE password analyser
- [**361**星][21d] [Py] [davidtavarez/pwndb](https://github.com/davidtavarez/pwndb) Search for leaked credentials
- [**341**星][11m] [C] [1clickman/3snake](https://github.com/1clickman/3snake) reads memory from sshd and sudo system calls that handle password based authentication
- [**295**星][6m] [C#] [raikia/credninja](https://github.com/raikia/credninja) A multithreaded tool designed to identify if credentials are valid, invalid, or local admin valid credentials within a network at-scale via SMB, plus now with a user hunter
- [**290**星][3m] [JS] [kspearrin/ff-password-exporter](https://github.com/kspearrin/ff-password-exporter) Easily export your passwords from Firefox.
- [**289**星][7m] [Shell] [greenwolf/spray](https://github.com/Greenwolf/Spray) A Password Spraying tool for Active Directory Credentials by Jacob Wilkin(Greenwolf)
- [**286**星][17d] [Py] [xfreed0m/rdpassspray](https://github.com/xfreed0m/rdpassspray) Python3 tool to perform password spraying using RDP
- [**256**星][5m] [C] [rub-syssec/omen](https://github.com/rub-syssec/omen) Ordered Markov ENumerator - Password Guesser
- [**212**星][4m] [Ruby] [bdmac/strong_password](https://github.com/bdmac/strong_password) Entropy-based password strength checking for Ruby and Rails.


### <a id="86dc226ae8a71db10e4136f4b82ccd06"></a>密码


- [**7035**星][t] [C] [hashcat/hashcat](https://github.com/hashcat/hashcat) 世界上最快最先进的密码恢复工具
    - 重复区段: [后渗透->工具->未分类-post-exp](#12abc279c69d1fcf10692b9cb89bcdf7) |
- [**5173**星][1y] [JS] [samyk/poisontap](https://github.com/samyk/poisontap) Exploits locked/password protected computers over USB, drops persistent WebSocket-based backdoor, exposes internal router, and siphons cookies using Raspberry Pi Zero & Node.js.
- [**3209**星][2d] [C] [magnumripper/johntheripper](https://github.com/magnumripper/johntheripper) This is the official repo for John the Ripper, "Jumbo" version. The "bleeding-jumbo" branch is based on 1.9.0-Jumbo-1 which was released on May 14, 2019. An import of the "core" version of john this jumbo was based on (or newer) is found in the "master" branch (CVS:
- [**2583**星][2m] [C] [huntergregal/mimipenguin](https://github.com/huntergregal/mimipenguin) dump 当前Linux用户的登录密码
- [**1162**星][8m] [Py] [mebus/cupp](https://github.com/mebus/cupp) Common User Passwords Profiler (CUPP)
- [**874**星][5m] [Go] [fireeye/gocrack](https://github.com/fireeye/gocrack) 火眼开源的密码破解工具，可以跨多个 GPU 服务器执行任务
- [**852**星][3m] [Go] [ukhomeoffice/repo-security-scanner](https://github.com/ukhomeoffice/repo-security-scanner) CLI tool that finds secrets accidentally committed to a git repo, eg passwords, private keys
- [**652**星][1y] [Java] [faizann24/wifi-bruteforcer-fsecurify](https://github.com/faizann24/wifi-bruteforcer-fsecurify) Android app，无需 Root 即可爆破 Wifi 密码
- [**602**星][7m] [C] [hashcat/hashcat-utils](https://github.com/hashcat/hashcat-utils) Small utilities that are useful in advanced password cracking
- [**598**星][1y] [Py] [brannondorsey/passgan](https://github.com/brannondorsey/passgan) A Deep Learning Approach for Password Guessing (
- [**593**星][4m] [Py] [thewhiteh4t/pwnedornot](https://github.com/thewhiteh4t/pwnedornot) OSINT Tool for Finding Passwords of Compromised Email Addresses
- [**493**星][1y] [PS] [dafthack/domainpasswordspray](https://github.com/dafthack/domainpasswordspray) DomainPasswordSpray is a tool written in PowerShell to perform a password spray attack against users of a domain. By default it will automatically generate the userlist from the domain. BE VERY CAREFUL NOT TO LOCKOUT ACCOUNTS!
- [**353**星][8m] [Py] [iphelix/pack](https://github.com/iphelix/pack) PACK (Password Analysis and Cracking Kit)
- [**334**星][2m] [CSS] [guyoung/captfencoder](https://github.com/guyoung/captfencoder) CaptfEncoder是一款跨平台网络安全工具套件，提供网络安全相关编码转换、古典密码、密码学、特殊编码等工具，并聚合各类在线工具。
- [**333**星][26d] [JS] [auth0/repo-supervisor](https://github.com/auth0/repo-supervisor) Serverless工具，在pull请求中扫描源码，搜索密码及其他秘密


### <a id="764122f9a7cf936cd9bce316b09df5aa"></a>认证&&Authenticate


- [**901**星][1m] [Go] [smallstep/cli](https://github.com/smallstep/cli) 🧰 A zero trust swiss army knife for working with X509, OAuth, JWT, OATH OTP, etc.
- [**665**星][9m] [C] [samdenty/wi-pwn](https://github.com/samdenty/Wi-PWN)  performs deauth attacks on cheap Arduino boards
- [**298**星][15d] [Java] [shred/acme4j](https://github.com/shred/acme4j) a protocol that a certificate authority (CA) and an applicant can use to automate the process of verification and certificate issuance
- [**281**星][4m] [Java] [ztosec/secscan-authcheck](https://github.com/ztosec/secscan-authcheck) 越权检测工具
- [**214**星][1y] [C#] [leechristensen/spoolsample](https://github.com/leechristensen/spoolsample) PoC tool to coerce Windows hosts authenticate to other machines via the MS-RPRN RPC interface. This is possible via other protocols as well.




***


## <a id="5fda419e854b390c8361d347f48607ce"></a>文章


### <a id="776c034543a65be69c061d1aafce3127"></a>新添加的






# <a id="43b0310ac54c147a62c545a2b0f4bce2"></a>辅助周边


***


## <a id="569887799ee0148230cc5d7bf98e96d0"></a>未分类-Assist


- [**26031**星][3d] [Py] [certbot/certbot](https://github.com/certbot/certbot) Certbot is EFF's tool to obtain certs from Let's Encrypt and (optionally) auto-enable HTTPS on your server. It can also act as a client for any other CA that uses the ACME protocol.
- [**7784**星][2d] [JS] [gchq/cyberchef](https://github.com/gchq/cyberchef) The Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis
- [**4909**星][3m] [Rust] [sharkdp/hexyl](https://github.com/sharkdp/hexyl) 命令行中查看hex
- [**4402**星][] [JS] [cure53/dompurify](https://github.com/cure53/dompurify) a DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG. DOMPurify works with a secure default, but offers a lot of configurability and hooks. Demo:
- [**3239**星][7m] [HTML] [leizongmin/js-xss](https://github.com/leizongmin/js-xss) Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist
- [**3097**星][8d] [Shell] [trimstray/htrace.sh](https://github.com/trimstray/htrace.sh) My simple Swiss Army knife for http/https troubleshooting and profiling.
- [**1223**星][1y] [Go] [cloudflare/redoctober](https://github.com/cloudflare/redoctober) Go server for two-man rule style file encryption and decryption.
- [**1022**星][9m] [Go] [maliceio/malice](https://github.com/maliceio/malice) 开源版的VirusTotal
- [**508**星][6d] [Py] [certtools/intelmq](https://github.com/certtools/intelmq) IntelMQ is a solution for IT security teams for collecting and processing security feeds using a message queuing protocol.
- [**481**星][5m] [JS] [ehrishirajsharma/swiftnessx](https://github.com/ehrishirajsharma/swiftnessx) A cross-platform note-taking & target-tracking app for penetration testers.


***


## <a id="86d5daccb4ed597e85a0ec9c87f3c66f"></a>TLS&&SSL&&HTTPS


- [**22020**星][23d] [Go] [filosottile/mkcert](https://github.com/filosottile/mkcert) A simple zero-config tool to make locally trusted development certificates with any names you'd like.
- [**4322**星][12d] [Py] [diafygi/acme-tiny](https://github.com/diafygi/acme-tiny) A tiny script to issue and renew TLS certs from Let's Encrypt
- [**1694**星][9d] [HTML] [chromium/badssl.com](https://github.com/chromium/badssl.com) 
- [**1230**星][1m] [Go] [jsha/minica](https://github.com/jsha/minica) minica is a small, simple CA intended for use in situations where the CA operator also operates each host where a certificate will be used.
- [**1211**星][2d] [Go] [smallstep/certificates](https://github.com/smallstep/certificates) 私有的证书颁发机构（X.509和SSH）和ACME服务器，用于安全的自动证书管理，因此您可以在SSH和SSO处使用TLS
- [**833**星][10m] [Py] [ietf-wg-acme/acme](https://github.com/ietf-wg-acme/acme) A protocol for automating certificate issuance
- [**740**星][21d] [Shell] [dokku/dokku-letsencrypt](https://github.com/dokku/dokku-letsencrypt) BETA: Automatic Let's Encrypt TLS Certificate installation for dokku
- [**691**星][5m] [C++] [google/certificate-transparency](https://github.com/google/certificate-transparency) Auditing for TLS certificates.
- [**512**星][1m] [Java] [rub-nds/tls-attacker](https://github.com/rub-nds/tls-attacker) TLS-Attacker is a Java-based framework for analyzing TLS libraries. It is developed by the Ruhr University Bochum (
- [**469**星][3m] [Go] [square/certigo](https://github.com/square/certigo) A utility to examine and validate certificates in a variety of formats
- [**279**星][1m] [Shell] [trimstray/mkchain](https://github.com/trimstray/mkchain) 建立从根证书到最终用户证书的有效的SSL证书链, 修复不完整的证书链并下载所有缺少的CA证书
- [**229**星][7m] [Shell] [r00t-3xp10it/meterpreter_paranoid_mode-ssl](https://github.com/r00t-3xp10it/meterpreter_paranoid_mode-ssl) Meterpreter Paranoid Mode - SSL/TLS connections
- [**225**星][12m] [Shell] [nviso-be/magisktrustusercerts](https://github.com/nviso-be/magisktrustusercerts) A Magisk module that automatically adds user certificates to the system root CA store


# <a id="946d766c6a0fb23b480ff59d4029ec71"></a>防护&&Defense


***


## <a id="0abd611fc3e9a4d9744865ca6e47a6b2"></a>工具


### <a id="7a277f8b0e75533e0b50d93c902fb351"></a>未分类-Defense


- [**9862**星][9m] [imthenachoman/how-to-secure-a-linux-server](https://github.com/imthenachoman/how-to-secure-a-linux-server) An evolving how-to guide for securing a Linux server.
- [**747**星][12m] [Py] [infobyte/spoilerwall](https://github.com/infobyte/spoilerwall) Spoilerwall introduces a brand new concept in the field of network hardening. Avoid being scanned by spoiling movies on all your ports!
- [**657**星][6m] [TeX] [bettercrypto/applied-crypto-hardening](https://github.com/bettercrypto/applied-crypto-hardening) Best Current Practices regarding secure online communication and configuration of services using cryptography.
- [**639**星][2d] [Py] [binarydefense/artillery](https://github.com/binarydefense/artillery) The Artillery Project is an open-source blue team tool designed to protect Linux and Windows operating systems through multiple methods.
- [**589**星][21d] [Ruby] [dev-sec/ansible-ssh-hardening](https://github.com/dev-sec/ansible-ssh-hardening) This Ansible role provides numerous security-related ssh configurations, providing all-round base protection.
- [**570**星][29d] [Py] [graphenex/graphenex](https://github.com/graphenex/graphenex) Automated System Hardening Framework
- [**499**星][8m] [ernw/hardening](https://github.com/ernw/hardening) Repository of Hardening Guides
- [**241**星][20d] [Py] [a13xp0p0v/kconfig-hardened-check](https://github.com/a13xp0p0v/kconfig-hardened-check) A script for checking the hardening options in the Linux kernel config
- [**217**星][27d] [Puppet] [dev-sec/puppet-os-hardening](https://github.com/dev-sec/puppet-os-hardening) This puppet module provides numerous security-related configurations, providing all-round base protection.


### <a id="784ea32a3f4edde1cd424b58b17e7269"></a>WAF


- [**5094**星][2m] [Lua] [alexazhou/verynginx](https://github.com/alexazhou/verynginx) A very powerful and friendly nginx base on lua-nginx-module( openresty ) which provide WAF, Control Panel, and Dashboards.
- [**3294**星][3m] [C] [nbs-system/naxsi](https://github.com/nbs-system/naxsi) NAXSI is an open-source, high performance, low rules maintenance WAF for NGINX
- [**3207**星][1m] [C++] [spiderlabs/modsecurity](https://github.com/spiderlabs/modsecurity) ModSecurity is an open source, cross platform web application firewall (WAF) engine for Apache, IIS and Nginx that is developed by Trustwave's SpiderLabs. It has a robust event-based programming language which provides protection from a range of attacks against web applications and allows for HTTP traffic monitoring, logging and real-time analys…
- [**619**星][3m] [Py] [3xp10it/xwaf](https://github.com/3xp10it/xwaf) waf 自动爆破(绕过)工具
- [**617**星][4m] [Lua] [jx-sec/jxwaf](https://github.com/jx-sec/jxwaf) JXWAF(锦衣盾)是一款基于openresty(nginx+lua)开发的web应用防火墙
- [**552**星][8m] [Py] [s0md3v/blazy](https://github.com/s0md3v/Blazy) Blazy is a modern login bruteforcer which also tests for CSRF, Clickjacking, Cloudflare and WAF .
- [**540**星][4d] [Go] [janusec/janusec](https://github.com/janusec/janusec) Janusec Application Gateway, a Golang based application security solution which provides WAF (Web Application Firewall), CC attack defense, unified web administration portal, private key protection, web routing and scalable load balancing.
- [**481**星][8m] [Java] [chengdedeng/waf](https://github.com/chengdedeng/waf) 
- [**452**星][3d] [PHP] [akaunting/firewall](https://github.com/akaunting/firewall) Web Application Firewall (WAF) package for Laravel
- [**433**星][9m] [Py] [aws-samples/aws-waf-sample](https://github.com/aws-samples/aws-waf-sample) This repository contains example scripts and sets of rules for the AWS WAF service. Please be aware that the applicability of these examples to specific workloads may vary.
- [**423**星][6d] [Py] [awslabs/aws-waf-security-automations](https://github.com/awslabs/aws-waf-security-automations) This solution automatically deploys a single web access control list (web ACL) with a set of AWS WAF rules designed to filter common web-based attacks.
- [**415**星][5d] [C#] [jbe2277/waf](https://github.com/jbe2277/waf) Win Application Framework (WAF) is a lightweight Framework that helps you to create well structured XAML Applications.
- [**412**星][11m] [C] [titansec/openwaf](https://github.com/titansec/openwaf) Web security protection system based on openresty
- [**384**星][6d] [PHP] [terrylinooo/shieldon](https://github.com/terrylinooo/shieldon) Web Application Firewall (WAF) for PHP.
- [**248**星][1y] [Py] [warflop/cloudbunny](https://github.com/warflop/cloudbunny) CloudBunny is a tool to capture the real IP of the server that uses a WAF as a proxy or protection. In this tool we used three search engines to search domain information: Shodan, Censys and Zoomeye.
- [**216**星][1m] [Py] [stamparm/identywaf](https://github.com/stamparm/identywaf) Blind WAF identification tool
- [**209**星][7m] [C] [coolervoid/raptor_waf](https://github.com/coolervoid/raptor_waf) Raptor - WAF - Web application firewall using DFA [ Current version ] - Beta


### <a id="ce6532938f729d4c9d66a5c75d1676d3"></a>防火墙&&FireWall


- [**4209**星][2m] [Py] [evilsocket/opensnitch](https://github.com/evilsocket/opensnitch) opensnitch：Little Snitch 应用程序防火墙的 GNU/Linux 版本。（Little Snitch：Mac操作系统的应用程序防火墙，能防止应用程序在你不知道的情况下自动访问网络）
- [**3283**星][11d] [ObjC] [objective-see/lulu](https://github.com/objective-see/lulu) LuLu is the free macOS firewall
- [**1542**星][6d] [Java] [ukanth/afwall](https://github.com/ukanth/afwall) AFWall+ (Android Firewall +) - iptables based firewall for Android
- [**1095**星][3m] [PHP] [antonioribeiro/firewall](https://github.com/antonioribeiro/firewall) Firewall package for Laravel applications
- [**1049**星][8d] [Shell] [firehol/firehol](https://github.com/firehol/firehol) A firewall for humans...
- [**852**星][20d] [trimstray/iptables-essentials](https://github.com/trimstray/iptables-essentials) Common Firewall Rules and Commands.
- [**567**星][7m] [Go] [sysdream/chashell](https://github.com/sysdream/chashell) Chashell is a Go reverse shell that communicates over DNS. It can be used to bypass firewalls or tightly restricted networks.
- [**468**星][6m] [Shell] [vincentcox/bypass-firewalls-by-dns-history](https://github.com/vincentcox/bypass-firewalls-by-dns-history) Firewall bypass script based on DNS history records. This script will search for DNS A history records and check if the server replies for that domain. Handy for bugbounty hunters.
- [**279**星][11d] [Shell] [geerlingguy/ansible-role-firewall](https://github.com/geerlingguy/ansible-role-firewall) Ansible Role - iptables Firewall configuration.
- [**261**星][2m] [C#] [wokhansoft/wfn](https://github.com/wokhansoft/wfn) Windows Firewall Notifier extends the default Windows embedded firewall by allowing to handle and notify about outgoing connections, offers real time connections monitoring, connections map, bandwidth usage monitoring and more...
- [**260**星][4d] [Ruby] [puppetlabs/puppetlabs-firewall](https://github.com/puppetlabs/puppetlabs-firewall) Puppet Firewall Module
- [**240**星][7d] [Shell] [essandess/macos-fortress](https://github.com/essandess/macos-fortress) Firewall and Privatizing Proxy for Trackers, Attackers, Malware, Adware, and Spammers with Anti-Virus On-Demand and On-Access Scanning (PF, squid, privoxy, hphosts, dshield, emergingthreats, hostsfile, PAC file, clamav)
- [**220**星][1y] [Go] [maksadbek/tcpovericmp](https://github.com/maksadbek/tcpovericmp) TCP implementation over ICMP protocol to bypass firewalls


### <a id="ff3e0b52a1477704b5f6a94ccf784b9a"></a>IDS&&IPS


- [**2938**星][4d] [Zeek] [zeek/zeek](https://github.com/zeek/zeek) Zeek is a powerful network analysis framework that is much different from the typical IDS you may know.
- [**2852**星][10d] [C] [ossec/ossec-hids](https://github.com/ossec/ossec-hids) 入侵检测系统
- [**1622**星][2m] [Go] [ysrc/yulong-hids](https://github.com/ysrc/yulong-hids) 一款由 YSRC 开源的主机入侵检测系统
- [**1325**星][9d] [C] [oisf/suricata](https://github.com/OISF/suricata) a network IDS, IPS and NSM engine
- [**581**星][5d] [Py] [0kee-team/watchad](https://github.com/0kee-team/watchad) AD Security Intrusion Detection System
- [**512**星][5m] [C] [decaf-project/decaf](https://github.com/decaf-project/DECAF) DECAF (short for Dynamic Executable Code Analysis Framework) is a binary analysis platform based on QEMU. This is also the home of the DroidScope dynamic Android malware analysis platform. DroidScope is now an extension to DECAF.
- [**499**星][8m] [Shell] [stamusnetworks/selks](https://github.com/stamusnetworks/selks) A Suricata based IDS/IPS distro
- [**383**星][7m] [jnusimba/androidsecnotes](https://github.com/jnusimba/androidsecnotes) some learning notes about Android Security
- [**298**星][4d] [C] [ebwi11/agentsmith-hids](https://github.com/EBWi11/AgentSmith-HIDS) By Kprobe technology Open Source Host-based Intrusion Detection System(HIDS), from E_Bwill.
- [**248**星][1y] [Perl] [mrash/psad](https://github.com/mrash/psad) iptables 的入侵检测和日志分析
- [**225**星][1m] [Py] [secureworks/dalton](https://github.com/secureworks/dalton) 使用预定义/指定的规则, 针对IDS传感器(例如Snort/Suricata)进行网络数据包捕获


### <a id="6543c237786d1f334d375f4d9acdeee4"></a>隐私保护&&Privacy


- [**3236**星][5m] [Go] [meshbird/meshbird](https://github.com/meshbird/meshbird) cloud-native multi-region multi-cloud decentralized private networking
- [**1069**星][20d] [Py] [yelp/detect-secrets](https://github.com/yelp/detect-secrets) An enterprise friendly way of detecting and preventing secrets in code.




***


## <a id="5aac7367edfef7c63fc95afd6762b773"></a>文章


### <a id="04aac0e81b87788343930e9dbf01ba9c"></a>新添加的






# <a id="52b481533d065d9e80cfd3cca9d91c7f"></a>SoftwareDefinedRadio


***


## <a id="015984b1dae0c9aa03b3aa74ea449f3f"></a>工具


- [**934**星][1y] [C++] [miek/inspectrum](https://github.com/miek/inspectrum) analysing captured signals, primarily from software-defined radio receivers.
- [**454**星][10m] [C] [martinmarinov/tempestsdr](https://github.com/martinmarinov/tempestsdr) Remote video eavesdropping using a software-defined radio platform
- [**369**星][4d] [Py] [p1sec/qcsuper](https://github.com/p1sec/qcsuper) QCSuper is a tool communicating with Qualcomm-based phones and modems, allowing to capture raw 2G/3G/4G radio frames, among other things.


***


## <a id="043e62cc373eb3e7b3910b622cf220d8"></a>文章




# <a id="507f1a48f4709abb1c6b0d2689fd15e6"></a>LOLBin&&LOLScript


***


## <a id="ec32edc7b3e441f29c70f6e9bca0174a"></a>工具


- [**1433**星][1m] [XSLT] [lolbas-project/lolbas](https://github.com/lolbas-project/lolbas) Living Off The Land Binaries And Scripts - (LOLBins and LOLScripts)
- [**1349**星][1y] [XSLT] [api0cradle/lolbas](https://github.com/api0cradle/lolbas) Living Off The Land Binaries And Scripts - (LOLBins and LOLScripts)


***


## <a id="9bffad3ac781090ab31d4013bf858dd9"></a>文章




# <a id="e25d233159b1dc40898ff0c74574f790"></a>日志&&Log


***


## <a id="13df0f4d5c7a1386b329fd9e43d8fc15"></a>工具




***


## <a id="06e7d46942d5159d19aa5c36f66f174a"></a>文章




# <a id="9b026a07fdf243c6870ce91f00191214"></a>威胁狩猎&&ThreatHunt


***


## <a id="b911aad7512e253660092942e06d00ad"></a>工具


### <a id="0b27f97199330c4945572a1f9c229000"></a>未分类


- [**1998**星][10d] [Py] [momosecurity/aswan](https://github.com/momosecurity/aswan) 陌陌风控系统静态规则引擎，零基础简易便捷的配置多种复杂规则，实时高效管控用户异常行为。




***


## <a id="f613271a55b177f626b42b8c728a0b1c"></a>文章


### <a id="3828e67170e5db714c9c16f663b42a5e"></a>新添加的






# <a id="d6b02213a74372407371f77dd6e39c99"></a>Crypto&&加密&&密码学


***


## <a id="41d260119ad54db2739a9ae393bd87a5"></a>工具


- [**2151**星][5d] [Java] [google/wycheproof](https://github.com/google/wycheproof) Project Wycheproof tests crypto libraries against known attacks.
- [**1077**星][3m] [C] [tpruvot/cpuminer-multi](https://github.com/tpruvot/cpuminer-multi) crypto cpuminer (linux + windows)
- [**448**星][14d] [Py] [sidechannelmarvels/deadpool](https://github.com/sidechannelmarvels/deadpool) Repository of various public white-box cryptographic implementations and their practical attacks.
- [**378**星][2m] [C++] [crypto2011/idr](https://github.com/crypto2011/idr) Interactive Delphi Reconstructor
- [**214**星][5m] [Shell] [cryptolok/crykex](https://github.com/cryptolok/crykex) Linux Memory Cryptographic Keys Extractor


***


## <a id="cc043f672c90d4b834cdae80bfbe8851"></a>文章




# <a id="8cb1c42a29fa3e8825a0f8fca780c481"></a>恶意代码&&Malware&&APT


***


## <a id="e2fd0947924229d7de24b9902e1f54a0"></a>工具


- [**2058**星][2m] [C++] [lordnoteworthy/al-khaser](https://github.com/lordnoteworthy/al-khaser) 在野恶意软件使用的技术：虚拟机，仿真，调试器，沙盒检测。
    - 重复区段: [渗透->工具->未分类-Pentest](#2e40f2f1df5d7f93a7de47bf49c24a0e) |
- [**893**星][1m] [aptnotes/data](https://github.com/aptnotes/data) APTnotes data
- [**219**星][8d] [JS] [strangerealintel/cyberthreatintel](https://github.com/strangerealintel/cyberthreatintel) Analysis of malware and Cyber Threat Intel of APT and cybercriminals groups
- [**203**星][4m] [Py] [thesph1nx/absolutezero](https://github.com/thesph1nx/absolutezero) Python APT Backdoor 1.0.0.1


***


## <a id="cfffc63a6302bd3aa79a0305ed7afd55"></a>文章




# <a id="7d5d2d22121ed8456f0c79098f5012bb"></a>REST_API&&RESTFUL 


***


## <a id="3b127f2a89bc8d18b4ecb0d9c61f1d58"></a>工具


- [**1233**星][9m] [Py] [flipkart-incubator/astra](https://github.com/flipkart-incubator/astra) 自动化的REST API安全测试脚本


***


## <a id="b16baff7e1b11133efecf1b5b6e10aab"></a>文章




# <a id="ceb90405292daed9bb32ac20836c219a"></a>蓝牙&&Bluetooth


***


## <a id="c72811e491c68f75ac2e7eb7afd3b01f"></a>工具


- [**274**星][19d] [Py] [ghostop14/sparrow-wifi](https://github.com/ghostop14/sparrow-wifi) Next-Gen GUI-based WiFi and Bluetooth Analyzer for Linux
    - 重复区段: [无线->未分类-WiFi](#d4efda1853b2cb0909727188116a2a8c) |
- [**201**星][t] [Py] [seemoo-lab/internalblue](https://github.com/seemoo-lab/internalblue) Bluetooth experimentation framework for Broadcom and Cypress chips.


***


## <a id="97e1bdced96fc7fcd502174d6eecee36"></a>文章




# <a id="76df273beb09f6732b37a6420649179c"></a>浏览器&&browser


***


## <a id="47a03071becd6df66b469df7c2c6f9b5"></a>工具


- [**4672**星][5d] [JS] [beefproject/beef](https://github.com/beefproject/beef) The Browser Exploitation Framework Project
- [**970**星][9m] [Py] [selwin/python-user-agents](https://github.com/selwin/python-user-agents) A Python library that provides an easy way to identify devices like mobile phones, tablets and their capabilities by parsing (browser) user agent strings.
- [**883**星][3m] [escapingbug/awesome-browser-exploit](https://github.com/escapingbug/awesome-browser-exploit) awesome list of browser exploitation tutorials
- [**459**星][2m] [Py] [globaleaks/tor2web](https://github.com/globaleaks/tor2web) Tor2web is an HTTP proxy software that enables access to Tor Hidden Services by mean of common web browsers
- [**455**星][12d] [m1ghtym0/browser-pwn](https://github.com/m1ghtym0/browser-pwn) An updated collection of resources targeting browser-exploitation.
- [**411**星][3m] [Pascal] [felipedaragon/sandcat](https://github.com/felipedaragon/sandcat) 为渗透测试和开发者准备的轻量级浏览器, 基于Chromium和Lua
- [**320**星][3m] [xsleaks/xsleaks](https://github.com/xsleaks/xsleaks) A collection of browser-based side channel attack vectors.
- [**232**星][1y] [C#] [djhohnstein/sharpweb](https://github.com/djhohnstein/sharpweb) .NET 2.0 CLR project to retrieve saved browser credentials from Google Chrome, Mozilla Firefox and Microsoft Internet Explorer/Edge.
- [**217**星][3m] [Py] [icsec/airpwn-ng](https://github.com/icsec/airpwn-ng) force the target's browser to do what we want 


***


## <a id="ca0c0694dc0aa87534e9bb19be4ee4d5"></a>文章




# <a id="249c9d207ed6743e412c8c8bcd8a2927"></a>MitreATT&CK


***


## <a id="a88c0c355b342b835fb42abee283bd71"></a>工具


### <a id="6ab6835b55cf5c8462c4229a4a0ee94c"></a>未分类的


- [**2758**星][] [PS] [redcanaryco/atomic-red-team](https://github.com/redcanaryco/atomic-red-team) Small and highly portable detection tests based on MITRE's ATT&CK.
- [**1396**星][2d] [Py] [mitre/caldera](https://github.com/mitre/caldera) 自动化 adversary emulation 系统
- [**568**星][6m] [HTML] [nshalabi/attack-tools](https://github.com/nshalabi/attack-tools) Utilities for MITRE™ ATT&CK
- [**491**星][1y] [bfuzzy/auditd-attack](https://github.com/bfuzzy/auditd-attack) A Linux Auditd rule set mapped to MITRE's Attack Framework
- [**478**星][3m] [Py] [olafhartong/threathunting](https://github.com/olafhartong/threathunting) A Splunk app mapped to MITRE ATT&CK to guide your threat hunts
- [**344**星][6m] [teoseller/osquery-attck](https://github.com/teoseller/osquery-attck) Mapping the MITRE ATT&CK Matrix with Osquery
- [**333**星][t] [Py] [atc-project/atomic-threat-coverage](https://github.com/atc-project/atomic-threat-coverage) Actionable analytics designed to combat threats based on MITRE's ATT&CK.
- [**312**星][11m] [PS] [cyb3rward0g/invoke-attackapi](https://github.com/cyb3rward0g/invoke-attackapi) A PowerShell script to interact with the MITRE ATT&CK Framework via its own API
- [**201**星][3m] [infosecn1nja/awesome-mitre-attack](https://github.com/infosecn1nja/awesome-mitre-attack) A curated list of awesome resources related to Mitre ATT&CK™ Framework




***


## <a id="8512ba6c3855733a1474ca2f16153906"></a>文章


### <a id="4b17464da487fbdf719e9a1482abf8f1"></a>新添加的






# <a id="de81f9dd79c219c876c1313cd97852ce"></a>破解&&Crack&&爆破&&BruteForce


***


## <a id="73c3c9225523cbb05333246f23342846"></a>工具


### <a id="53084c21ff85ffad3dd9ce445684978b"></a>未分类的


- [**3325**星][1m] [C] [vanhauser-thc/thc-hydra](https://github.com/vanhauser-thc/thc-hydra) 网络登录破解，支持多种服务
- [**1925**星][29d] [Py] [lanjelot/patator](https://github.com/lanjelot/patator) Patator is a multi-purpose brute-forcer, with a modular design and a flexible usage.
- [**1096**星][4m] [Py] [landgrey/pydictor](https://github.com/landgrey/pydictor) A powerful and useful hacker dictionary builder for a brute-force attack
- [**898**星][3m] [Py] [trustedsec/hate_crack](https://github.com/trustedsec/hate_crack) 使用HashCat 的自动哈希破解工具
- [**894**星][29d] [Py] [ticarpi/jwt_tool](https://github.com/ticarpi/jwt_tool) 测试，调整和破解JSON Web Token 的工具包
- [**857**星][7m] [C] [brendan-rius/c-jwt-cracker](https://github.com/brendan-rius/c-jwt-cracker) C 语言编写的 JWT 爆破工具
- [**803**星][11m] [Py] [mak-/parameth](https://github.com/mak-/parameth) 在文件中(例如PHP 文件)暴力搜索GET 和 POST 请求的参数
- [**763**星][5m] [Py] [s0md3v/hash-buster](https://github.com/s0md3v/Hash-Buster) Crack hashes in seconds.
- [**690**星][8m] [Shell] [1n3/brutex](https://github.com/1n3/brutex) Automatically brute force all services running on a target.
- [**687**星][9d] [JS] [animir/node-rate-limiter-flexible](https://github.com/animir/node-rate-limiter-flexible) Node.js rate limit requests by key with atomic increments. Protection from DDoS and Brute-Force attacks in process Memory, Redis, MongoDb, Memcached, MySQL, PostgreSQL, Cluster or PM
- [**659**星][5m] [C#] [shack2/snetcracker](https://github.com/shack2/snetcracker) 超级弱口令检查工具是一款Windows平台的弱口令审计工具，支持批量多线程检查，可快速发现弱密码、弱口令账号，密码支持和用户名结合进行检查，大大提高成功率，支持自定义服务端口和字典。
- [**588**星][6m] [PHP] [s3inlc/hashtopolis](https://github.com/s3inlc/hashtopolis) Hashcat wrapper, 用于跨平台分布式Hash破解
- [**563**星][2m] [Py] [pure-l0g1c/instagram](https://github.com/pure-l0g1c/instagram) Bruteforce attack for Instagram
- [**559**星][1y] [CSS] [hashview/hashview](https://github.com/hashview/hashview) 密码破解和分析工具
- [**538**星][27d] [C] [nmap/ncrack](https://github.com/nmap/ncrack) Ncrack network authentication tool
- [**528**星][3m] [Py] [ypeleg/hungabunga](https://github.com/ypeleg/hungabunga) HungaBunga: Brute-Force all sklearn models with all parameters using .fit .predict!
- [**520**星][4m] [duyetdev/bruteforce-database](https://github.com/duyetdev/bruteforce-database) Bruteforce database
- [**490**星][1y] [C] [mikeryan/crackle](https://github.com/mikeryan/crackle) Crack and decrypt BLE encryption
- [**451**星][6m] [JS] [coalfire-research/npk](https://github.com/coalfire-research/npk) A mostly-serverless distributed hash cracking platform
- [**442**星][1y] [C] [ryancdotorg/brainflayer](https://github.com/ryancdotorg/brainflayer) A proof-of-concept cracker for cryptocurrency brainwallets and other low entropy key alogrithms.
- [**358**星][2m] [Py] [denyhosts/denyhosts](https://github.com/denyhosts/denyhosts) Automated host blocking from SSH brute force attacks
- [**356**星][28d] [Java] [wycm/selenium-geetest-crack](https://github.com/wycm/selenium-geetest-crack) selenium破解滑动验证码
- [**332**星][11m] [C] [e-ago/bitcracker](https://github.com/e-ago/bitcracker) BitLocker密码破解器
- [**309**星][8d] [Go] [ropnop/kerbrute](https://github.com/ropnop/kerbrute) A tool to perform Kerberos pre-auth bruteforcing
- [**304**星][2m] [Py] [yzddmr6/webcrack](https://github.com/yzddmr6/webcrack) 网站后台弱口令/万能密码批量检测工具
- [**292**星][12m] [Shell] [cyb0r9/socialbox](https://github.com/Cyb0r9/SocialBox) SocialBox is a Bruteforce Attack Framework [ Facebook , Gmail , Instagram ,Twitter ] , Coded By Belahsan Ouerghi
- [**286**星][9d] [Shell] [wuseman/emagnet](https://github.com/wuseman/emagnet) Emagnet is a tool for find leaked databases with 97.1% accurate to grab mail + password together from pastebin leaks. Support for brute forcing spotify accounts, instagram accounts, ssh servers, microsoft rdp clients and gmail accounts
- [**275**星][1y] [C] [jmk-foofus/medusa](https://github.com/jmk-foofus/medusa) Medusa is a speedy, parallel, and modular, login brute-forcer.
- [**274**星][1y] [Shell] [thelinuxchoice/instainsane](https://github.com/thelinuxchoice/instainsane) Multi-threaded Instagram Brute Forcer (100 attemps at once)
- [**250**星][1y] [Py] [avramit/instahack](https://github.com/avramit/instahack) Instagram bruteforce tool
- [**250**星][1y] [Py] [hsury/geetest3-crack](https://github.com/hsury/geetest3-crack) 
- [**248**星][11d] [Py] [evilmog/ntlmv1-multi](https://github.com/evilmog/ntlmv1-multi) 修改NTLMv1/NTLMv1-ESS/MSCHAPv1 Hask, 使其可以在hashcat中用DES模式14000破解
- [**235**星][7m] [Py] [blark/aiodnsbrute](https://github.com/blark/aiodnsbrute) Python 3.5+ DNS asynchronous brute force utility
- [**233**星][8m] [Py] [paradoxis/stegcracker](https://github.com/paradoxis/stegcracker) Steganography brute-force utility to uncover hidden data inside files
- [**221**星][12m] [Py] [chris408/known_hosts-hashcat](https://github.com/chris408/known_hosts-hashcat) A guide and tool for cracking ssh known_hosts files with hashcat
- [**219**星][4m] [Py] [isaacdelly/plutus](https://github.com/isaacdelly/plutus) An automated bitcoin wallet collider that brute forces random wallet addresses
- [**215**星][2m] [C] [hyc/fcrackzip](https://github.com/hyc/fcrackzip) A braindead program for cracking encrypted ZIP archives. Forked from
- [**207**星][27d] [Py] [m4ll0k/smbrute](https://github.com/m4ll0k/smbrute) SMB Protocol Bruteforce
- [**206**星][5m] [Shell] [anshumanbh/brutesubs](https://github.com/anshumanbh/brutesubs) An automation framework for running multiple open sourced subdomain bruteforcing tools (in parallel) using your own wordlists via Docker Compose
- [**204**星][1y] [JS] [lmammino/jwt-cracker](https://github.com/lmammino/jwt-cracker) jwt-cracker：HS256JWT 令牌暴力破解工具，只对弱密码有效
- [**200**星][1y] [ObjC] [sunweiliang/neteasemusiccrack](https://github.com/sunweiliang/neteasemusiccrack) iOS网易云音乐 免VIP下载、去广告、去更新 无需越狱...




***


## <a id="171e396a8965775c27602762c6638694"></a>文章


### <a id="fc3c73849911ede2ce0d6d02f1f5b0b9"></a>新添加的






# <a id="96171a80e158b8752595329dd42e8bcf"></a>泄漏&&Breach&&Leak


***


## <a id="602bb9759b0b2ba5555b05b7218a2d6f"></a>工具


### <a id="dc507c5be7c09e1e88af7a1ad91e2703"></a>未分类


- [**1437**星][6m] [gitguardian/apisecuritybestpractices](https://github.com/gitguardian/apisecuritybestpractices) Resources to help you keep secrets (API keys, database credentials, certificates, ...) out of source code and remediate the issue in case of a leaked API key. Made available by GitGuardian.
- [**1398**星][1y] [Go] [filosottile/whosthere](https://github.com/filosottile/whosthere) A ssh server that knows who you are
- [**1147**星][3m] [HTML] [cure53/httpleaks](https://github.com/cure53/httpleaks) HTTPLeaks - All possible ways, a website can leak HTTP requests
- [**906**星][2m] [Py] [woj-ciech/leaklooker](https://github.com/woj-ciech/leaklooker) Find open databases - Powered by Binaryedge.io
- [**862**星][3d] [Py] [circl/ail-framework](https://github.com/circl/ail-framework) AIL framework - Analysis Information Leak framework
- [**728**星][2m] [streaak/keyhacks](https://github.com/streaak/keyhacks) Keyhacks is a repository which shows quick ways in which API keys leaked by a bug bounty program can be checked to see if they're valid.
- [**726**星][3d] [Py] [globaleaks/globaleaks](https://github.com/globaleaks/globaleaks) The Open-Source Whistleblowing Software
- [**301**星][5m] [Py] [wangyihang/githacker](https://github.com/wangyihang/githacker) a multiple threads tool to detect whether a site has git source leaks,   and has the ability to download the site source to the local




***


## <a id="fb3bccf80281e11fdf4ef06ddaa34566"></a>文章


### <a id="339727dd5a006d7a5bd8f0173dc80bb9"></a>新添加的






# <a id="785ad72c95e857273dce41842f5e8873"></a>爬虫


***


## <a id="0f931c85ab54698d0bcfaf9a3e6dac73"></a>工具


### <a id="442f9390fd56008def077a21ab65d4aa"></a>未分类


- [**758**星][2m] [Py] [nekmo/dirhunt](https://github.com/nekmo/dirhunt) Web爬虫, 针对搜索和分析路径做了优化
    - 重复区段: [扫描器->工具->未分类-Scanner](#de63a029bda6a7e429af272f291bb769) |




***


## <a id="23b008498c8b41ec3128bd9855660b7d"></a>文章


### <a id="37ca6907aa42dfd32db5973ff9eec83d"></a>新添加的






# <a id="39931e776c23e80229368dfc6fd54770"></a>无线&&WiFi&&AP&&802.11


***


## <a id="d4efda1853b2cb0909727188116a2a8c"></a>未分类-WiFi


- [**8455**星][8d] [Py] [wifiphisher/wifiphisher](https://github.com/wifiphisher/wifiphisher) 流氓AP框架, 用于RedTeam和Wi-Fi安全测试
    - 重复区段: [社工(SET)->工具->钓鱼](#290e9ae48108d21d6d8b9ea9e74d077d) |
- [**6140**星][10m] [Py] [schollz/howmanypeoplearearound](https://github.com/schollz/howmanypeoplearearound) 检测 Wifi 信号统计你周围的人数
    - 重复区段: [侦察->工具->未分类-OSINT](#05ab1b75266fddafc7195f5b395e4d99) |
- [**5824**星][2m] [C] [spacehuhn/esp8266_deauther](https://github.com/spacehuhn/esp8266_deauther) 使用ESP8266 制作Wifi干扰器
- [**4494**星][19d] [Py] [jopohl/urh](https://github.com/jopohl/urh) Universal Radio Hacker: investigate wireless protocols like a boss
- [**2989**星][5d] [JS] [evilsocket/pwnagotchi](https://github.com/evilsocket/pwnagotchi) 深度学习+Bettercap，基于A2C，从周围的WiFi环境中学习，以最大程度地利用捕获的WPA关键信息
- [**2939**星][4d] [Py] [danmcinerney/wifijammer](https://github.com/danmcinerney/wifijammer) 持续劫持范围内的Wifi客户端和AP
- [**2756**星][9m] [Py] [p0cl4bs/wifi-pumpkin](https://github.com/P0cL4bs/WiFi-Pumpkin) AP攻击框架, 创建虚假网络, 取消验证攻击、请求和凭证监控、透明代理、Windows更新攻击、钓鱼管理、ARP投毒、DNS嗅探、Pumpkin代理、动态图片捕获等
- [**2745**星][1y] [C] [vanhoefm/krackattacks-scripts](https://github.com/vanhoefm/krackattacks-scripts) 检测客户端和AP是否受KRACK漏洞影响
- [**2476**星][3m] [C] [martin-ger/esp_wifi_repeater](https://github.com/martin-ger/esp_wifi_repeater) A full functional WiFi Repeater (correctly: a WiFi NAT Router)
- [**2378**星][1y] [Py] [danmcinerney/lans.py](https://github.com/danmcinerney/lans.py) Inject code and spy on wifi users
- [**2303**星][2m] [Shell] [v1s1t0r1sh3r3/airgeddon](https://github.com/v1s1t0r1sh3r3/airgeddon) This is a multi-use bash script for Linux systems to audit wireless networks.
- [**1924**星][1y] [Py] [derv82/wifite2](https://github.com/derv82/wifite2) 无线网络审计工具wifite 的升级版/重制版
- [**1881**星][5m] [Shell] [arismelachroinos/lscript](https://github.com/arismelachroinos/lscript) 自动化无线渗透和Hacking 任务的脚本
    - 重复区段: [渗透->工具->自动化](#fc8737aef0f59c3952d11749fe582dac) |
- [**1567**星][25d] [Py] [k4m4/kickthemout](https://github.com/k4m4/kickthemout) 使用ARP欺骗，将设备从网络中踢出去
- [**1424**星][19d] [C] [ettercap/ettercap](https://github.com/ettercap/ettercap) Ettercap Project
- [**1286**星][4d] [C] [aircrack-ng/aircrack-ng](https://github.com/aircrack-ng/aircrack-ng) WiFi security auditing tools suite
- [**1280**星][2m] [C] [seemoo-lab/nexmon](https://github.com/seemoo-lab/nexmon) The C-based Firmware Patching Framework for Broadcom/Cypress WiFi Chips that enables Monitor Mode, Frame Injection and much more
- [**1057**星][2d] [C] [s0lst1c3/eaphammer](https://github.com/s0lst1c3/eaphammer) 针对WPA2-Enterprise 网络的定向双重攻击（evil twin attacks）
- [**1038**星][2m] [C] [t6x/reaver-wps-fork-t6x](https://github.com/t6x/reaver-wps-fork-t6x) 攻击 Wi-Fi Protected Setup (WPS)， 恢复 WPA/WPA2 密码
- [**1007**星][1y] [Py] [entropy1337/infernal-twin](https://github.com/entropy1337/infernal-twin) 自动化无线Hack 工具
- [**994**星][1y] [Py] [tylous/sniffair](https://github.com/tylous/sniffair) 无线渗透框架. 解析被动收集的无线数据, 执行复杂的无线攻击
- [**991**星][2m] [C] [wiire-a/pixiewps](https://github.com/wiire-a/pixiewps) An offline Wi-Fi Protected Setup brute-force utility
- [**985**星][1y] [HTML] [sensepost/mana](https://github.com/sensepost/mana) *DEPRECATED* mana toolkit for wifi rogue AP attacks and MitM
- [**916**星][2m] [TeX] [ethereum/yellowpaper](https://github.com/ethereum/yellowpaper) The "Yellow Paper": Ethereum's formal specification
- [**854**星][2m] [C] [spacehuhn/wifi_ducky](https://github.com/spacehuhn/wifi_ducky) Upload, save and run keystroke injection payloads with an ESP8266 + ATMEGA32U4
- [**799**星][1y] [ObjC] [igrsoft/kismac2](https://github.com/igrsoft/kismac2) KisMAC is a free, open source wireless stumbling and security tool for Mac OS X.
- [**781**星][2m] [Py] [konradit/gopro-py-api](https://github.com/konradit/gopro-py-api) Unofficial GoPro API Library for Python - connect to GoPro via WiFi.
- [**761**星][8m] [Py] [misterbianco/boopsuite](https://github.com/MisterBianco/BoopSuite) 无线审计与安全测试
- [**685**星][11m] [ObjC] [unixpickle/jamwifi](https://github.com/unixpickle/jamwifi) A GUI, easy to use WiFi network jammer for Mac OS X
- [**654**星][8m] [C] [wifidog/wifidog-gateway](https://github.com/wifidog/wifidog-gateway) Repository for the wifidog-gateway captive portal designed for embedded systems
- [**617**星][4m] [C] [matheus-garbelini/esp32_esp8266_attacks](https://github.com/matheus-garbelini/esp32_esp8266_attacks) Proof of Concept of ESP32/8266 Wi-Fi vulnerabilties (CVE-2019-12586, CVE-2019-12587, CVE-2019-12588)
- [**527**星][] [C++] [cyberman54/esp32-paxcounter](https://github.com/cyberman54/esp32-paxcounter) Wifi & BLE driven passenger flow metering with cheap ESP32 boards
- [**477**星][3m] [Shell] [staz0t/hashcatch](https://github.com/staz0t/hashcatch) Capture handshakes of nearby WiFi networks automatically
- [**467**星][2m] [Py] [savio-code/fern-wifi-cracker](https://github.com/savio-code/fern-wifi-cracker) 无线安全审计和攻击工具, 能破解/恢复 WEP/WPA/WPSkey等
- [**462**星][21d] [Java] [lennartkoopmann/nzyme](https://github.com/lennartkoopmann/nzyme) 直接收集空中的802.11 管理帧，并将其发送到 Graylog，用于WiFi IDS, 监控, 及事件响应。（Graylog：开源的日志管理系统）
- [**419**星][9d] [Py] [jpaulmora/pyrit](https://github.com/jpaulmora/pyrit) The famous WPA precomputed cracker, Migrated from Google.
- [**397**星][4d] [C] [freifunk-gluon/gluon](https://github.com/freifunk-gluon/gluon) a modular framework for creating OpenWrt-based firmwares for wireless mesh nodes
- [**384**星][5d] [C++] [bastibl/gr-ieee802-11](https://github.com/bastibl/gr-ieee802-11) IEEE 802.11 a/g/p Transceiver
- [**327**星][3m] [Shell] [vanhoefm/modwifi](https://github.com/vanhoefm/modwifi) 
- [**321**星][4d] [Java] [wiglenet/wigle-wifi-wardriving](https://github.com/wiglenet/wigle-wifi-wardriving) Nethugging client for Android, from wigle.net
- [**313**星][4m] [TeX] [chronaeon/beigepaper](https://github.com/chronaeon/beigepaper) Rewrite of the Yellowpaper in non-Yellowpaper syntax.
- [**278**星][3m] [C] [sensepost/hostapd-mana](https://github.com/sensepost/hostapd-mana) SensePost's modified hostapd for wifi attacks.
- [**277**星][18d] [C] [br101/horst](https://github.com/br101/horst) “horst” - lightweight IEEE802.11 wireless LAN analyzer with a text interface
- [**274**星][19d] [Py] [ghostop14/sparrow-wifi](https://github.com/ghostop14/sparrow-wifi) Next-Gen GUI-based WiFi and Bluetooth Analyzer for Linux
    - 重复区段: [蓝牙->工具](#c72811e491c68f75ac2e7eb7afd3b01f) |
- [**260**星][1y] [Py] [wipi-hunter/pidense](https://github.com/wipi-hunter/pidense) Monitor illegal wireless network activities.
- [**255**星][1m] [C] [mame82/logitacker](https://github.com/mame82/logitacker) Enumerate and test Logitech wireless input devices for vulnerabilities with a nRF52840 radio dongle.
- [**240**星][8m] [Py] [lionsec/wifresti](https://github.com/lionsec/wifresti) Find your wireless network password in Windows , Linux and Mac OS
- [**212**星][1m] [Shell] [aress31/wirespy](https://github.com/aress31/wirespy) Framework designed to automate various wireless networks attacks (the project was presented on Pentester Academy TV's toolbox in 2017).


***


## <a id="8d233e2d068cce2b36fd0cf44d10f5d8"></a>WPS&&WPA&&WPA2


- [**319**星][4m] [Py] [hash3lizer/wifibroot](https://github.com/hash3lizer/wifibroot) A WiFi Pentest Cracking tool for WPA/WPA2 (Handshake, PMKID, Cracking, EAPOL, Deauthentication)


***


## <a id="8863b7ba27658d687a85585e43b23245"></a>802.11




# <a id="80301821d0f5d8ec2dd3754ebb1b4b10"></a>Payload&&远控&&RAT


***


## <a id="783f861b9f822127dba99acb55687cbb"></a>工具


### <a id="6602e118e0245c83b13ff0db872c3723"></a>未分类-payload


- [**1829**星][6m] [Py] [veil-framework/veil](https://github.com/veil-framework/veil) generate metasploit payloads that bypass common anti-virus solutions
- [**1258**星][2m] [PS] [hak5/bashbunny-payloads](https://github.com/hak5/bashbunny-payloads) The Official Bash Bunny Payload Repository
- [**982**星][2m] [C] [zardus/preeny](https://github.com/zardus/preeny) Some helpful preload libraries for pwning stuff.
- [**569**星][11m] [Py] [genetic-malware/ebowla](https://github.com/genetic-malware/ebowla) Framework for Making Environmental Keyed Payloads (NO LONGER SUPPORTED)
- [**546**星][3m] [C++] [screetsec/brutal](https://github.com/screetsec/brutal) Payload for teensy like a rubber ducky but the syntax is different. this Human interfaes device ( HID attacks ). Penetration With Teensy . Brutal is a toolkit to quickly create various payload,powershell attack , virus attack and launch listener for a Human Interface Device ( Payload Teensy )
- [**493**星][5d] [Py] [ctxis/cape](https://github.com/ctxis/cape) Malware Configuration And Payload Extraction
- [**343**星][8m] [Java] [portswigger/param-miner](https://github.com/portswigger/param-miner) identifies hidden, unlinked parameters. It's particularly useful for finding web cache poisoning vulnerabilities
- [**339**星][12m] [JS] [gabemarshall/brosec](https://github.com/gabemarshall/brosec) Brosec - An interactive reference tool to help security professionals utilize useful payloads and commands.
- [**288**星][1m] [Shell] [petit-miner/blueberry-pi](https://github.com/petit-miner/blueberry-pi) Blueberry PI
- [**262**星][2m] [Py] [felixweyne/imaginaryc2](https://github.com/felixweyne/imaginaryc2) Imaginary C2 is a python tool which aims to help in the behavioral (network) analysis of malware. Imaginary C2 hosts a HTTP server which captures HTTP requests towards selectively chosen domains/IPs. Additionally, the tool aims to make it easy to replay captured Command-and-Control responses/served payloads.
- [**246**星][13d] [C] [shchmue/lockpick_rcm](https://github.com/shchmue/lockpick_rcm) Nintendo Switch encryption key derivation bare metal RCM payload
- [**244**星][7d] [cujanovic/open-redirect-payloads](https://github.com/cujanovic/open-redirect-payloads) Open Redirect Payloads
- [**238**星][6d] [cujanovic/markdown-xss-payloads](https://github.com/cujanovic/markdown-xss-payloads) XSS payloads for exploiting Markdown syntax
- [**235**星][5m] [Shell] [hak5/packetsquirrel-payloads](https://github.com/hak5/packetsquirrel-payloads) The Official Packet Squirrel Payload Repository
- [**233**星][6m] [cr0hn/nosqlinjection_wordlists](https://github.com/cr0hn/nosqlinjection_wordlists) This repository contains payload to test NoSQL Injections
- [**232**星][18d] [PS] [rsmudge/elevatekit](https://github.com/rsmudge/elevatekit) The Elevate Kit demonstrates how to use third-party privilege escalation attacks with Cobalt Strike's Beacon payload.
- [**229**星][3m] [Py] [whitel1st/docem](https://github.com/whitel1st/docem) Uility to embed XXE and XSS payloads in docx,odt,pptx,etc (OXML_XEE on steroids)
- [**227**星][2m] [Py] [brent-stone/can_reverse_engineering](https://github.com/brent-stone/can_reverse_engineering) Automated Payload Reverse Engineering Pipeline for the Controller Area Network (CAN) protocol
- [**217**星][2m] [PHP] [zigoo0/jsonbee](https://github.com/zigoo0/jsonbee) A ready to use JSONP endpoints/payloads to help bypass content security policy (CSP) of different websites.
- [**210**星][4d] [Py] [danmcinerney/msf-autoshell](https://github.com/danmcinerney/msf-autoshell) Feed the tool a .nessus file and it will automatically get you MSF shell


### <a id="b5d99a78ddb383c208aae474fc2cb002"></a>Payload收集


- [**22055**星][20d] [PHP] [danielmiessler/seclists](https://github.com/danielmiessler/seclists) 多种类型资源收集：用户名、密码、URL、敏感数据类型、Fuzzing  Payload、WebShell等
- [**11389**星][3d] [Py] [swisskyrepo/payloadsallthethings](https://github.com/swisskyrepo/payloadsallthethings) A list of useful payloads and bypass for Web Application Security and Pentest/CTF
- [**2078**星][2m] [edoverflow/bugbounty-cheatsheet](https://github.com/edoverflow/bugbounty-cheatsheet) A list of interesting payloads, tips and tricks for bug bounty hunters.
- [**2057**星][9m] [Shell] [foospidy/payloads](https://github.com/foospidy/payloads) web 攻击 Payload 集合
- [**1870**星][11m] [PHP] [bartblaze/php-backdoors](https://github.com/bartblaze/php-backdoors) A collection of PHP backdoors. For educational or testing purposes only.
- [**783**星][19d] [payloadbox/xss-payload-list](https://github.com/payloadbox/xss-payload-list) XSS 漏洞Payload列表
- [**373**星][3m] [renwax23/xss-payloads](https://github.com/renwax23/xss-payloads) List of XSS Vectors/Payloads
- [**298**星][4m] [Py] [thekingofduck/easyxsspayload](https://github.com/thekingofduck/easyxsspayload) XssPayload List . Usage:
- [**262**星][4m] [payloadbox/command-injection-payload-list](https://github.com/payloadbox/command-injection-payload-list) 


### <a id="b318465d0d415e35fc0883e9894261d1"></a>远控&&RAT


- [**5131**星][4m] [Py] [n1nj4sec/pupy](https://github.com/n1nj4sec/pupy) Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) remote administration and post-exploitation tool mainly written in python
- [**1745**星][7m] [Smali] [ahmyth/ahmyth-android-rat](https://github.com/ahmyth/ahmyth-android-rat) Android Remote Administration Tool
- [**1335**星][1y] [Py] [marten4n6/evilosx](https://github.com/marten4n6/evilosx) An evil RAT (Remote Administration Tool) for macOS / OS X.
- [**780**星][2m] [Py] [kevthehermit/ratdecoders](https://github.com/kevthehermit/ratdecoders) Python Decoders for Common Remote Access Trojans
- [**599**星][1y] [PS] [fortynorthsecurity/wmimplant](https://github.com/FortyNorthSecurity/WMImplant) This is a PowerShell based tool that is designed to act like a RAT. Its interface is that of a shell where any command that is supported is translated into a WMI-equivalent for use on a network/remote machine. WMImplant is WMI based.
- [**500**星][6m] [Visual Basic .NET] [nyan-x-cat/lime-rat](https://github.com/nyan-x-cat/lime-rat) LimeRAT | Simple, yet powerful remote administration tool for Windows (RAT)
- [**372**星][3m] [C++] [werkamsus/lilith](https://github.com/werkamsus/lilith) Lilith, The Open Source C++ Remote Administration Tool (RAT)
- [**323**星][3d] [C#] [nyan-x-cat/asyncrat-c-sharp](https://github.com/nyan-x-cat/asyncrat-c-sharp) Open-Source Remote Administration Tool For Windows C# (RAT)
- [**317**星][6m] [Py] [mvrozanti/rat-via-telegram](https://github.com/mvrozanti/rat-via-telegram) Windows Remote Administration Tool via Telegram
- [**293**星][4m] [C++] [yuanyuanxiang/simpleremoter](https://github.com/yuanyuanxiang/simpleremoter) 基于gh0st的远程控制器：实现了终端管理、进程管理、窗口管理、远程桌面、文件管理、语音管理、视频管理、服务管理、注册表管理等功能，优化全部代码及整理排版，修复内存泄漏缺陷，程序运行稳定。此项目初版见：


### <a id="ad92f6b801a18934f1971e2512f5ae4f"></a>Payload生成


- [**3369**星][8d] [C] [screetsec/thefatrat](https://github.com/screetsec/thefatrat) Thefatrat a massive exploiting tool : Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack and etc . This tool compiles a malware with popular payload and then the compiled malware can be execute on windows, android, mac . The malware that created with this tool also have an ability to bypass most AV softw…
    - 重复区段: [后渗透->工具->未分类-post-exp](#12abc279c69d1fcf10692b9cb89bcdf7) |
- [**2678**星][4m] [Java] [frohoff/ysoserial](https://github.com/frohoff/ysoserial) 生成会利用不安全的Java对象反序列化的Payload
- [**1792**星][t] [Shell] [leebaird/discover](https://github.com/leebaird/discover) 自定义的bash脚本, 用于自动化多个渗透测试任务, 包括: 侦查、扫描、解析、在Metasploit中创建恶意Payload和Listener
    - 重复区段: [渗透->工具->自动化](#fc8737aef0f59c3952d11749fe582dac) |[渗透->工具->Metasploit->未分类-metasploit](#01be61d5bb9f6f7199208ff0fba86b5d) |[侦察->工具->未分类-OSINT](#05ab1b75266fddafc7195f5b395e4d99) |
- [**1339**星][3m] [PS] [peewpw/invoke-psimage](https://github.com/peewpw/invoke-psimage) Encodes a PowerShell script in the pixels of a PNG file and generates a oneliner to execute
- [**1075**星][5m] [Py] [nccgroup/winpayloads](https://github.com/nccgroup/winpayloads) Undetectable Windows Payload Generation
- [**1016**星][1y] [Py] [d4vinci/dr0p1t-framework](https://github.com/d4vinci/dr0p1t-framework) 创建免杀的Dropper
- [**884**星][19d] [PHP] [ambionics/phpggc](https://github.com/ambionics/phpggc) PHPGGC is a library of PHP unserialize() payloads along with a tool to generate them, from command line or programmatically.
- [**872**星][10m] [Visual Basic .NET] [mdsecactivebreach/sharpshooter](https://github.com/mdsecactivebreach/sharpshooter) Payload Generation Framework
- [**836**星][28d] [C#] [pwntester/ysoserial.net](https://github.com/pwntester/ysoserial.net) 生成Payload，恶意利用不安全的 .NET 对象反序列化
- [**832**星][7m] [Go] [tiagorlampert/chaos](https://github.com/tiagorlampert/chaos) a PoC that allow generate payloads and control remote operating system
- [**752**星][1y] [Py] [oddcod3/phantom-evasion](https://github.com/oddcod3/phantom-evasion) Python AV evasion tool capable to generate FUD executable even with the most common 32 bit metasploit payload(exe/elf/dmg/apk)
- [**713**星][6d] [Py] [sevagas/macro_pack](https://github.com/sevagas/macro_pack) 自动生成并混淆MS 文档, 用于渗透测试、演示、社会工程评估等
- [**634**星][2d] [C] [thewover/donut](https://github.com/thewover/donut) Generates x86, x64, or AMD64+x86 position-independent shellcode that loads .NET Assemblies, PE files, and other Windows payloads from memory and runs them with parameters
- [**633**星][8m] [Shell] [g0tmi1k/msfpc](https://github.com/g0tmi1k/msfpc) MSFvenom Payload Creator (MSFPC)
- [**419**星][27d] [Perl] [chinarulezzz/pixload](https://github.com/chinarulezzz/pixload) Image Payload Creating/Injecting tools
- [**301**星][8m] [Py] [0xacb/viewgen](https://github.com/0xacb/viewgen) viewgen is a ViewState tool capable of generating both signed and encrypted payloads with leaked validation keys
- [**278**星][1y] [Java] [ewilded/shelling](https://github.com/ewilded/shelling) SHELLING - a comprehensive OS command injection payload generator
- [**268**星][1y] [Shell] [abedalqaderswedan1/aswcrypter](https://github.com/abedalqaderswedan1/aswcrypter) An Bash&Python Script For Generating Payloads that Bypasses All Antivirus so far [FUD]


### <a id="c45a90ab810d536a889e4e2dd45132f8"></a>Botnet&&僵尸网络


- [**3747**星][4m] [Py] [malwaredllc/byob](https://github.com/malwaredllc/byob) BYOB (Build Your Own Botnet)
- [**2163**星][1y] [C++] [maestron/botnets](https://github.com/maestron/botnets) This is a collection of #botnet source codes, unorganized. For EDUCATIONAL PURPOSES ONLY
- [**412**星][1m] [C++] [souhardya/uboat](https://github.com/souhardya/uboat) HTTP Botnet Project
- [**328**星][6m] [Go] [saturnsvoid/gobot2](https://github.com/saturnsvoid/gobot2) Second Version of The GoBot Botnet, But more advanced.


### <a id="b6efee85bca01cde45faa45a92ece37f"></a>后门&&添加后门


- [**386**星][8m] [C] [zerosum0x0/smbdoor](https://github.com/zerosum0x0/smbdoor) Windows kernel backdoor via registering a malicious SMB handler
- [**378**星][3m] [Shell] [screetsec/vegile](https://github.com/screetsec/vegile) This tool will setting up your backdoor/rootkits when backdoor already setup it will be hidden your spesisifc process,unlimited your session in metasploit and transparent. Even when it killed, it will re-run again. There always be a procces which while run another process,So we can assume that this procces is unstopable like a Ghost in The Shell
- [**370**星][8m] [Py] [s0md3v/cloak](https://github.com/s0md3v/Cloak) Cloak can backdoor any python script with some tricks.
- [**349**星][15d] [Shell] [r00t-3xp10it/backdoorppt](https://github.com/r00t-3xp10it/backdoorppt) 将Exe格式Payload伪装成Doc（.ppt）
- [**348**星][9d] [C] [cr4sh/smmbackdoor](https://github.com/cr4sh/smmbackdoor) System Management Mode backdoor for UEFI
- [**318**星][1y] [Ruby] [carletonstuberg/browser-backdoor](https://github.com/CarletonStuberg/browser-backdoor) BrowserBackdoor is an Electron Application with a JavaScript WebSocket Backdoor and a Ruby Command-Line Listener
- [**301**星][4m] [C#] [mvelazc0/defcon27_csharp_workshop](https://github.com/mvelazc0/defcon27_csharp_workshop) Writing custom backdoor payloads with C# - Defcon 27
- [**205**星][9m] [C] [paradoxis/php-backdoor](https://github.com/Paradoxis/PHP-Backdoor) Your interpreter isn’t safe anymore  —  The PHP module backdoor


### <a id="85bb0c28850ffa2b4fd44f70816db306"></a>混淆器&&Obfuscate


- [**3676**星][3d] [TS] [javascript-obfuscator/javascript-obfuscator](https://github.com/javascript-obfuscator/javascript-obfuscator) A powerful obfuscator for JavaScript and Node.js
- [**2477**星][11m] [C#] [yck1509/confuserex](https://github.com/yck1509/confuserex) An open-source, free protector for .NET applications
- [**1397**星][9m] [PS] [danielbohannon/invoke-obfuscation](https://github.com/danielbohannon/invoke-obfuscation) PowerShell Obfuscator
- [**1147**星][8m] [hikariobfuscator/hikari](https://github.com/HikariObfuscator/Hikari) LLVM Obfuscator
- [**1021**星][1m] [Swift] [rockbruno/swiftshield](https://github.com/rockbruno/swiftshield) wift/OBJ-C Obfuscator
- [**676**星][1m] [C#] [obfuscar/obfuscar](https://github.com/obfuscar/obfuscar) Open source obfuscation tool for .NET assemblies
- [**675**星][7m] [C++] [gossip-sjtu/armariris](https://github.com/gossip-sjtu/armariris) 孤挺花（Armariris） -- 由上海交通大学密码与计算机安全实验室维护的LLVM混淆框架
- [**653**星][6m] [Go] [yawning/obfs4](https://github.com/yawning/obfs4) The obfourscator (Courtesy mirror)
- [**482**星][3m] [Py] [bashfuscator/bashfuscator](https://github.com/bashfuscator/bashfuscator) A fully configurable and extendable Bash obfuscation framework. This tool is intended to help both red team and blue team.
- [**467**星][2m] [LLVM] [jonathansalwan/tigress_protection](https://github.com/jonathansalwan/tigress_protection) Playing with the Tigress binary protection. Break some of its protections and solve some of its challenges. Automatic deobfuscation using symbolic execution, taint analysis and LLVM.
- [**458**星][1m] [PHP] [pk-fr/yakpro-po](https://github.com/pk-fr/yakpro-po) YAK Pro - Php Obfuscator
- [**423**星][11m] [Py] [d4vinci/cuteit](https://github.com/d4vinci/cuteit) IP obfuscator made to make a malicious ip a bit cuter
- [**420**星][5d] [Py] [dashingsoft/pyarmor](https://github.com/dashingsoft/pyarmor) A tool used to obfuscate python scripts, bind obfuscated scripts to fixed machine or expire obfuscated scripts.
- [**394**星][1y] [Py] [essandess/isp-data-pollution](https://github.com/essandess/isp-data-pollution) ISP Data Pollution to Protect Private Browsing History with Obfuscation
- [**348**星][1y] [C] [codermjlee/mjcodeobfuscation](https://github.com/codermjlee/mjcodeobfuscation) 一个用于代码混淆和字符串加密的Mac小Demo
- [**337**星][22d] [Go] [unixpickle/gobfuscate](https://github.com/unixpickle/gobfuscate) Obfuscate Go binaries and packages
- [**311**星][3m] [PHP] [elfsundae/laravel-hashid](https://github.com/elfsundae/laravel-hashid) Obfuscate your data by generating reversible, non-sequential, URL-safe identifiers.
- [**282**星][29d] [Py] [hnfull/intensio-obfuscator](https://github.com/hnfull/intensio-obfuscator) Obfuscate a python code 2.x and 3.x
- [**276**星][5d] [TS] [javascript-obfuscator/webpack-obfuscator](https://github.com/javascript-obfuscator/webpack-obfuscator) javascript-obfuscator plugin for Webpack
- [**263**星][6m] [C++] [d35ha/callobfuscator](https://github.com/d35ha/callobfuscator) Obfuscate specific windows apis with different apis
- [**263**星][4m] [ObjC] [preemptive/ppios-rename](https://github.com/preemptive/ppios-rename) Symbol obfuscator for iOS apps
- [**235**星][21d] [C#] [xenocoderce/neo-confuserex](https://github.com/xenocoderce/neo-confuserex) Updated ConfuserEX, an open-source, free obfuscator for .NET applications
- [**202**星][6m] [C#] [bedthegod/confuserex-mod-by-bed](https://github.com/bedthegod/confuserex-mod-by-bed) Beds Protector | Best free obfuscation out right now


### <a id="78d0ac450a56c542e109c07a3b0225ae"></a>Payload管理




### <a id="d08b7bd562a4bf18275c63ffe7d8fc91"></a>勒索软件


- [**391**星][1y] [Go] [mauri870/ransomware](https://github.com/mauri870/ransomware) A POC Windows crypto-ransomware (Academic)
- [**331**星][t] [Batchfile] [mitchellkrogza/ultimate.hosts.blacklist](https://github.com/mitchellkrogza/ultimate.hosts.blacklist) The Ultimate Unified Hosts file for protecting your network, computer, smartphones and Wi-Fi devices against millions of bad web sites. Protect your children and family from gaining access to bad web sites and protect your devices and pc from being infected with Malware or Ransomware.


### <a id="82f546c7277db7919986ecf47f3c9495"></a>键盘记录器&&Keylogger


- [**710**星][8m] [Py] [giacomolaw/keylogger](https://github.com/giacomolaw/keylogger) A simple keylogger for Windows, Linux and Mac
- [**462**星][1y] [Py] [mehulj94/radium](https://github.com/mehulj94/Radium) Python keylogger with multiple features.
- [**364**星][12m] [Py] [ajinabraham/xenotix-python-keylogger](https://github.com/ajinabraham/xenotix-python-keylogger) Xenotix Python Keylogger for Windows.


### <a id="8f99087478f596139922cd1ad9ec961b"></a>Meterpreter


- [**244**星][1m] [Py] [mez0cc/ms17-010-python](https://github.com/mez0cc/ms17-010-python) MS17-010: Python and Meterpreter


### <a id="63e0393e375e008af46651a3515072d8"></a>Payload投递


- [**263**星][4m] [Py] [no0be/dnslivery](https://github.com/no0be/dnslivery) Easy files and payloads delivery over DNS




***


## <a id="0b644b2d8119abf6643755ef455fcf2c"></a>文章


### <a id="27962a7633b86d43cae2dd2d4c32f1b6"></a>新添加






# <a id="a9494547a9359c60f09aea89f96a2c83"></a>后渗透


***


## <a id="3ed50213c2818f1455eff4e30372c542"></a>工具


### <a id="12abc279c69d1fcf10692b9cb89bcdf7"></a>未分类-post-exp


- [**7035**星][t] [C] [hashcat/hashcat](https://github.com/hashcat/hashcat) 世界上最快最先进的密码恢复工具
    - 重复区段: [密码->工具->密码](#86dc226ae8a71db10e4136f4b82ccd06) |
- [**3369**星][8d] [C] [screetsec/thefatrat](https://github.com/screetsec/thefatrat) Thefatrat a massive exploiting tool : Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack and etc . This tool compiles a malware with popular payload and then the compiled malware can be execute on windows, android, mac . The malware that created with this tool also have an ability to bypass most AV softw…
    - 重复区段: [Payload->工具->Payload生成](#ad92f6b801a18934f1971e2512f5ae4f) |
- [**2479**星][1m] [Shell] [rebootuser/linenum](https://github.com/rebootuser/linenum) Scripted Local Linux Enumeration & Privilege Escalation Checks
- [**2171**星][1m] [Py] [commixproject/commix](https://github.com/commixproject/commix) Automated All-in-One OS command injection and exploitation tool.
- [**1243**星][10m] [C] [a0rtega/pafish](https://github.com/a0rtega/pafish) Pafish is a demonstration tool that employs several techniques to detect sandboxes and analysis environments in the same way as malware families do.
- [**1225**星][1y] [C#] [cn33liz/p0wnedshell](https://github.com/cn33liz/p0wnedshell) PowerShell Runspace Post Exploitation Toolkit
- [**1116**星][9m] [Py] [0x00-0x00/shellpop](https://github.com/0x00-0x00/shellpop) 在渗透中生产简易的/复杂的反向/绑定Shell
- [**1062**星][2m] [Boo] [byt3bl33d3r/silenttrinity](https://github.com/byt3bl33d3r/silenttrinity) An asynchronous, collaborative post-exploitation agent powered by Python and .NET's DLR
- [**1024**星][4m] [Py] [byt3bl33d3r/deathstar](https://github.com/byt3bl33d3r/deathstar) 在Active Directory环境中使用Empire自动获取域管理员权限
- [**765**星][5m] [Py] [lgandx/pcredz](https://github.com/lgandx/pcredz) This tool extracts Credit card numbers, NTLM(DCE-RPC, HTTP, SQL, LDAP, etc), Kerberos (AS-REQ Pre-Auth etype 23), HTTP Basic, SNMP, POP, SMTP, FTP, IMAP, etc from a pcap file or from a live interface.
- [**743**星][5m] [PS] [hausec/adape-script](https://github.com/hausec/adape-script) Active Directory Assessment and Privilege Escalation Script
- [**697**星][2m] [C#] [cobbr/sharpsploit](https://github.com/cobbr/sharpsploit) SharpSploit is a .NET post-exploitation library written in C#
- [**422**星][16d] [Shell] [thesecondsun/bashark](https://github.com/thesecondsun/bashark) Bash post exploitation toolkit
- [**344**星][5m] [Py] [adrianvollmer/powerhub](https://github.com/adrianvollmer/powerhub) A post exploitation tool based on a web application, focusing on bypassing endpoint protection and application whitelisting
- [**282**星][1y] [JS] [chrisallenlane/novahot](https://github.com/chrisallenlane/novahot) Webshell框架，实现了基于Json的API，可与任何语言编写的后门（默认支持PHP/Ruby/Python）进行通信。
- [**233**星][2d] [Go] [brompwnie/botb](https://github.com/brompwnie/botb) A container analysis and exploitation tool for pentesters and engineers.
- [**204**星][2m] [Py] [elevenpaths/ibombshell](https://github.com/elevenpaths/ibombshell) Tool to deploy a post-exploitation prompt at any time


### <a id="4c2095e7e192ac56f6ae17c8fc045c51"></a>提权&&PrivilegeEscalation


- [**3699**星][5m] [C] [secwiki/windows-kernel-exploits](https://github.com/secwiki/windows-kernel-exploits) windows-kernel-exploits Windows平台提权漏洞集合
- [**1283**星][3m] [Py] [alessandroz/beroot](https://github.com/alessandroz/beroot) Privilege Escalation Project - Windows / Linux / Mac
- [**638**星][11m] [C++] [ohpe/juicy-potato](https://github.com/ohpe/juicy-potato) A sugared version of RottenPotatoNG, with a bit of juice, i.e. another Local Privilege Escalation tool, from a Windows Service Accounts to NT AUTHORITY\SYSTEM.
- [**547**星][5m] [rhinosecuritylabs/aws-iam-privilege-escalation](https://github.com/rhinosecuritylabs/aws-iam-privilege-escalation) A centralized source of all AWS IAM privilege escalation methods released by Rhino Security Labs.
- [**496**星][8m] [Py] [initstring/dirty_sock](https://github.com/initstring/dirty_sock) Linux privilege escalation exploit via snapd (CVE-2019-7304)
- [**492**星][2m] [C#] [rasta-mouse/watson](https://github.com/rasta-mouse/watson) Enumerate missing KBs and suggest exploits for useful Privilege Escalation vulnerabilities
- [**485**星][8m] [C] [nongiach/sudo_inject](https://github.com/nongiach/sudo_inject) [Linux] Two Privilege Escalation techniques abusing sudo token
- [**392**星][4m] [PS] [cyberark/aclight](https://github.com/cyberark/ACLight) A script for advanced discovery of Privileged Accounts - includes Shadow Admins
- [**371**星][3m] [PS] [gdedrouas/exchange-ad-privesc](https://github.com/gdedrouas/exchange-ad-privesc) Exchange privilege escalations to Active Directory
- [**340**星][2m] [Shell] [nullarray/roothelper](https://github.com/nullarray/roothelper) 辅助在被攻克系统上的提权过程：自动枚举、下载、解压并执行提权脚本
- [**308**星][5m] [Batchfile] [frizb/windows-privilege-escalation](https://github.com/frizb/windows-privilege-escalation) Windows Privilege Escalation Techniques and Scripts
- [**269**星][4m] [PHP] [lawrenceamer/0xsp-mongoose](https://github.com/lawrenceamer/0xsp-mongoose) Privilege Escalation Enumeration Toolkit (64/32 ) , fast , intelligent enumeration with Web API integration . Mastering Your Own Finding
- [**223**星][3m] [Py] [initstring/uptux](https://github.com/initstring/uptux) Linux privilege escalation checks (systemd, dbus, socket fun, etc)
- [**222**星][4d] [C#] [carlospolop/privilege-escalation-awesome-scripts-suite](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite) PEASS - Privilege Escalation Awesome Scripts SUITE (with colors)
- [**222**星][4d] [C#] [carlospolop/privilege-escalation-awesome-scripts-suite](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite) PEASS - Privilege Escalation Awesome Scripts SUITE (with colors)


### <a id="caab36bba7fa8bb931a9133e37d397f6"></a>Windows


#### <a id="7ed8ee71c4a733d5e5e5d239f0e8b9e0"></a>未分类-Windows


- [**8785**星][28d] [C] [gentilkiwi/mimikatz](https://github.com/gentilkiwi/mimikatz) A little tool to play with Windows security
- [**2153**星][2m] [Py] [trustedsec/unicorn](https://github.com/trustedsec/unicorn) 通过PowerShell降级攻击, 直接将Shellcode注入到内存
- [**2045**星][13d] [C++] [darthton/blackbone](https://github.com/darthton/blackbone) Windows memory hacking library
- [**999**星][11m] [Batchfile] [sagishahar-zz/lpeworkshop](https://github.com/sagishahar-zz/lpeworkshop) Windows / Linux Local Privilege Escalation Workshop
- [**931**星][6d] [C#] [googleprojectzero/sandbox-attacksurface-analysis-tools](https://github.com/googleprojectzero/sandbox-attacksurface-analysis-tools) 沙箱攻击面（Attack Surface）分析工具，用于测试 Windows 上沙箱的各种属性
- [**700**星][8m] [C] [hfiref0x/tdl](https://github.com/hfiref0x/tdl) Driver loader for bypassing Windows x64 Driver Signature Enforcement
- [**694**星][5m] [C#] [outflanknl/evilclippy](https://github.com/outflanknl/evilclippy) A cross-platform assistant for creating malicious MS Office documents. Can hide VBA macros, stomp VBA code (via P-Code) and confuse macro analysis tools. Runs on Linux, OSX and Windows.
- [**611**星][9m] [C#] [0xbadjuju/tokenvator](https://github.com/0xbadjuju/tokenvator) A tool to elevate privilege with Windows Tokens
- [**519**星][12m] [PS] [a-min3/winspect](https://github.com/a-min3/winspect) Powershell-based Windows Security Auditing Toolbox
- [**416**星][1m] [C++] [hoshimin/kernel-bridge](https://github.com/hoshimin/kernel-bridge) Windows kernel hacking framework, driver template, hypervisor and API written on C++
- [**391**星][2m] [Java] [tiagorlampert/saint](https://github.com/tiagorlampert/saint) a Spyware Generator for Windows systems written in Java
- [**349**星][2m] [Shell] [orlikoski/skadi](https://github.com/orlikoski/Skadi) collection, processing and advanced analysis of forensic artifacts and images.
- [**341**星][1y] [C++] [qax-a-team/eventcleaner](https://github.com/QAX-A-Team/EventCleaner) A tool mainly to erase specified records from Windows event logs, with additional functionalities.
- [**340**星][19d] [C] [mattiwatti/efiguard](https://github.com/mattiwatti/efiguard) Disable PatchGuard and DSE at boot time
- [**302**星][2d] [Py] [skylined/bugid](https://github.com/skylined/bugid) Detect, analyze and uniquely identify crashes in Windows applications
- [**298**星][1y] [PS] [onelogicalmyth/zeroday-powershell](https://github.com/onelogicalmyth/zeroday-powershell) A PowerShell example of the Windows zero day priv esc
- [**290**星][7m] [Py] [ropnop/windapsearch](https://github.com/ropnop/windapsearch) Python script to enumerate users, groups and computers from a Windows domain through LDAP queries
- [**288**星][11m] [maaaaz/impacket-examples-windows](https://github.com/maaaaz/impacket-examples-windows) The great impacket example scripts compiled for Windows
- [**213**星][4m] [PHP] [rizer0/log-killer](https://github.com/rizer0/log-killer) Clear all your logs in [linux/windows] servers
- [**212**星][1m] [C++] [can1357/byepg](https://github.com/can1357/byepg) Defeating Patchguard universally for Windows 8, Windows 8.1 and all versions of Windows 10 regardless of HVCI
- [**211**星][1y] [C++] [tandasat/pgresarch](https://github.com/tandasat/pgresarch) PatchGuard Research
- [**206**星][20d] [Py] [mzfr/rsh](https://github.com/mzfr/rsh) generate reverse shell from CLI for linux and Windows.
- [**203**星][5d] [Py] [ropnop/impacket_static_binaries](https://github.com/ropnop/impacket_static_binaries) Standalone binaries for Linux/Windows of Impacket's examples
- [**201**星][10m] [HTML] [mxmssh/drltrace](https://github.com/mxmssh/drltrace) Drltrace is a library calls tracer for Windows and Linux applications.


#### <a id="58f3044f11a31d0371daa91486d3694e"></a>UAC


- [**2355**星][3d] [C] [hfiref0x/uacme](https://github.com/hfiref0x/uacme) Defeating Windows User Account Control


#### <a id="b84c84a853416b37582c3b7f13eabb51"></a>AppLocker




#### <a id="e3c4c83dfed529ceee65040e565003c4"></a>ActiveDirectory


- [**3652**星][19d] [PS] [bloodhoundad/bloodhound](https://github.com/BloodHoundAD/BloodHound) a single page Javascript web application, uses graph theory to reveal the hidden and often unintended relationships within an Active Directory environment.
- [**2009**星][3m] [infosecn1nja/ad-attack-defense](https://github.com/infosecn1nja/ad-attack-defense) Attack and defend active directory using modern post exploitation adversary tradecraft activity
- [**338**星][9m] [Py] [dirkjanm/ldapdomaindump](https://github.com/dirkjanm/ldapdomaindump) Active Directory information dumper via LDAP
- [**242**星][1y] [Go] [netspi/goddi](https://github.com/netspi/goddi) goddi (go dump domain info) dumps Active Directory domain information


#### <a id="25697cca32bd8c9492b8e2c8a3a93bfe"></a>域渗透




#### <a id="a5c1d88a8e35b6c6223a6d64dbfb5358"></a>WET






### <a id="2dd40db455d3c6f1f53f8a9c25bbe63e"></a>驻留&&Persistence


- [**306**星][3m] [C#] [fireeye/sharpersist](https://github.com/fireeye/sharpersist) Windows persistence toolkit 


### <a id="4fc56d3dd1977b882ba14a9fd820f8e2"></a>Linux&&Xnix






***


## <a id="c86567da7d4004149912383575be3b45"></a>文章


### <a id="fdf10af493284be94033d1350f1e9b5c"></a>新添加






# 贡献
内容为系统自动导出, 有任何问题请提issue