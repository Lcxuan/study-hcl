```powershell
下册书：

26章：
1.以下关于冲突域、广播域的描述正确的是(ABC) 。
A．通过中继器连接的所有段都属于同一个冲突域
B.通过桥连接的段分别属于不同的冲突域
C.通过中继器连接的所有段都属于同一个广播域
D.通过桥连接的段分别属于不同的广播域
2．下列(CD )设备的不同物理端口属于不同的冲突域。
A.集线器
B.中继器
C.交换机
D.路由器
3．交换机通过记录端口接收数据帧中的(B)和端口的对应关系来进行MAC地址
表学习。
A.目的 MAC地址	B.源MAC地址	C.目的IP地址	D.源IP地址
4．交换机从端口接收到一个数据帧后,根据帧中的(A)查找MAC地址表来进行转发。
A.目的 MAC地址	B.源MAC地址	C.目的IP地址	D.源IP地址
5．为了杜绝不必要的帧转发,交换机可以对符合特定条件的(ABC)进行过滤。
A.单播帧	B.广播帧	C.组播帧	D.任播帧

27章：
1.VLAN 技术的优点是内（ ABCD ）
A 增强通讯的安全性					B .增强网络络的健壮性输
C.建立虚拟工作组						D.限制广播域范围 

2.VIAN 编号最大是（ C ）
A.1024				B.2048					C.4096					D .无限制

3. Access端口在收到以太网帧后﹐需要进行（ B ）操作;把以太网帧从端日转发出去时,需要进行（ B ）操作。
A.添加VLAN标签;添加VLAN标签
B.添加VLAN标签;剥离VLAN标签
C.剥离VLAN标签;剥离VLAN标签
D.剥离VLAN标签;添加VLAN标签

4.两个交换机之间互连,交换机上的PC属于相同的 VLAN。如果要想便PC间能够相互通讯,则通常情况下﹐需要设置交换机连接到PC的端口是（ B ），设置交换机之间相连的端口是（ B ）。
A. Access端口;Access端口
B. Access端口;Trunk端口
C.Trunk端口;Trunk端口
D.Trunk端口;Access端口

5．默认情况下,交换机上所有端口属于VLAN( B )。
A.0
B.1
C.1024
D．4095


28章
1.如下( ABCD )信息是在STP协议的配置BPDU中所携带的。
A.根桥ID(Root ID)
B.根路径开销(Root Path Cost)
C.指定桥ID(Designated Bridge ID)
D.指定端口 ID(Designated Port ID)

2.STP进行桥ID 比较时,先比较优先级,优先级值( A )为优;在优先级相等的情况下,再用MAC地址来进行比较,MAC地址( A )为优。
A.小者;小者
B.小者;大者
C.大者;大者
D.大者;小者

3.在802.1D的协议中,端口共有5种状态。其中处于下列( ABD )状态的端口能够发送 BPDU 配置消息。
A. Learning
B.Listening
C. Blocking
D.Forwarding

4．交换机从两个不同的端口收到BPDU,则其会按照( A )的顺序来比较BPDU,从而决定哪个端口是根端口。
A.根桥ID、根路径开销、指定桥ID、指定端口ID
B.根桥ID、指定桥ID、根路径开销、指定端口ID
C.根桥ID、指定桥ID、指定端口ID、根路径开销
D.根路径开销、根桥ID、指定桥ID、指定端口ID

5.在一个交换网络中,存在多个VLAN。管理员想在交换机间实现数据流转发的负载均衡,则应该选用( C )协议。
A. STP
B.RSTP 
C.MSTP
D.以上三者均可

29章
1.链路聚合的优点有( AB )。
A.增加链路带宽
B.提供链路可靠性
C.降低组网成本
D.减少维护工作量

2.在下面( B )方式中,双方交换机需要使用链路聚合协议。
A.静态聚合
B.动态聚合
C.手工聚合
D.协议聚合

3．在交换机上创建聚合端口的配置命令为( A )。
A.[SWA] interface bridge-aggregation 1
B.[SWA-GigabitEthernet1/0/1] interface bridge-aggregation 1
C.[SWA] port link-aggregation group 1
D.[SWA-GigabitEthernet1/0/1] port link-aggregation group 1

4.将交换机的端口加人到聚合端口的配置命令为( D )。
A. [SWA] interface bridge aggregation 1
B. [SWA-GigabitEthernet1/0/1] interface bridge aggregation 1
C. [SWA] port link aggregation group 1
D. [SWA-GigabitEthernet1/0/1] port link aggregation group 

5.如果两台交换机间需要使用链路聚合，但其中某台 交换机不支持 LACP协议，则
需要使用以下( A )方式。
A.静态聚合
B.动态聚合
C.手工聚合
D.协议聚合

30章
1.路由表中的要素包括( ABCD )。
B.下一跳地址
A.目的地址/子网掩码
D.度量值
C.出接口

2.路由的来源有( ABC )。
A.数据链路层协议发现的路由
B.管理员手工配置的路由
C.路由协议动态发现的路由
D.根据IP报文计算出的路由
3.下列( ABCD )因素是路由协议定义度量值时可能需要考虑的。
A.带宽
B. MTU
C.时延
D.可信度

4.静态路由的默认优先级是( C )。
A.0
C.60
B.1
D. 100

5.路由器根据IP报文中的( B )进行路由表项查找，并选择其中( B )的路由项用
于指导报文转发。
A.源IP地址:掩码最长
B.目的IP地址;掩码最长
C.源IP地址:掩码最短
D.目的IP地址:掩码最短

31章
1.直连路由的优先级为( A )。
A.0
B.1
C. 60
D.100

2相比于在路由器上使用802 1Q封装和子技口来实现VLAN间路由，使用三层交执
机实现VLAN间路由的优点有( ABC )。
A.路由转发引擎速度高.香吐量大
B.交换机内部转发时延低
C.相同数据吞吐量的情况下.交换机的成本比路由器低
D.交换机比路由器易于使用

3.相比于动态路由，静态路由的优点有( AB ).
A.无协议开销
B.不占用链路带宽
C.维护简单容易
D.可自动适应网络拓扑变化

4.默认路由的优点有( AB )。
A.减少路由表表项数量
B.节省路由表空间
C. 加快路由表查找速度
D.降低产生路由环路可能性

5.在路由器上配置到目的网络10. 1. 0, 0/24的静态路由命令为( C )。
A. [RTA] ip route-static 10. 1.0.0 255. 255. 255.0
B. [RTA Ethernet1/0/1] ip route statice 10. 1.0.0 25.25.25.0
C. [RTA] ip route static 10.1.0.0 255 2525.0 10.2.0.1
D. [RTA Etermet1/0/1] ip route staie 10. 1.0.0 25.25 25.0 1.2.0.1


32章
1.下列( CD )协议是可路由协议。
A. RIP
B. OSPF
C. IP
D. IPX

2.动态路由协议的工作过程包括以下( ABCD )阶段。
A.邻居发现
B.路由交换
C.路由计算
D.路由维护

3. ( ABD )协议属于IGP,( C )协议属于EGP。
A. RIP
B. OSPF
C. BGP
D. IS-IS

4.相比于距离矢量型路由协议，链路状态路由协议的优点有( ABC )。
A.协议算法本身无环路
B.协议交互占用带宽小
C.收敛速度快
D.配置维护简单

5.距离矢量路由协议基于贝尔曼福特算法。这种算法所关心的要素有( AB )。
A.到目的网段的距离
B.到目的网段的方向
C.到目的网段的链路带宽开销
D.到目的网段的链路延迟

33章
1. RIP使用( D )协议来承载，其端口号是(  )。
A. TCP,179
B. UDP,179
C. TCP,520
D. UDP,520

2. RIP协议的Update定时器的默认时间是( A )s.
A.30
B.60
C.120
D. 180

3.以下( ABD )是RIPv2中具有，但RIPv1中没有的。
A.组播方式发送协议报文
B.认证
C.水平分割机制
D.支持VLSM

4.以下( ABCD )是RIP协议防止环路的机制。
A.水平分割
B.毒性逆转
C.抑制时间
D.触发更新

5.在路由器上指定相关接口使能RIP协议的命令为( C )。
A. [RTA] network 192. 168.0. 0
B. CRTA] network 192. 168.0.00.0.255.255
C. [RTA-rip] network 192. 168. 0.0
D. [RTA-rip] network 192.16.0.00.255 255
34章
1.OSPF 协议是使用链路延迅作为路由选择的参考值的。( B )
A.True
B. False

2.下列不是OSPF相对RIPv2协议改进点的是( D )。
A.OSPF协议使用LSA进行交互
B.OSPF协议没有最大跳数限制
C. OSPF协议不使用跳数进行路由选择
D.OSPF使用组播地址进行更新

3.第四类LSA是( C )。
A. Network LSA
B. Summary LSA
c. ASBR Summary LSA
D. AS External LSA

4. Stub 区域和NSSA区域内部能够注人的LSA类型是一样的。( B )
A. True
B. False
35章
3.以太网交换机针对网络安全问题提供了多种安全机制，包括地址绑定、端口隔离和接入认证等技术。

4.移动办公用户 -般采用( AC )VPN 接人。
A. L2TP
B. GRE
C. SSL.
D. DVPN

5.AAA分别指认证、授权和计费


第36章：
1.	下列关于ACL包过滤的说法正确的有(AB)
A.基本 ACL匹配IP包的源地址
B.高级 ACL可以匹配IP包的目的地址和端口号
C.包过滤的默认规则总是 permit
D.包过滤的默认规则总是deny
2.为某ACL配置了下列4条ACL规则,如果设置其匹配次序为auto,则系统首先将尝试用下列(A)规则匹配数据包。
A. rule deny source 192.18.0.10.0.0.15
B. rule permit source 192.18.0.00.0.0.63
C. rule deny source 192.18.0.1 0.0.1.255
D. rule permit source 192.18.0.1 255.255.255.255
3．要查看所配置的ACL,应使用命令(B)。
A. display packet-filter statistics
B.display acl
C. display packet-filter
D.display firewall packet-filter
4.某ACL规则为rule deny source 10.0.0.00.0.7.255,该规则将匹配的IP地址范围为(D)。
A.10.0.0.0/16
B. 10.0.0.0/22
C. 10.0.0.0/8
D.10.0.0.0/21
5．要配置ACL包过滤,必须(ABC)。
A.创建ACL		B.配置ACL规则		C.启动包过滤功能		D.配置默认规则

第37章：
1.	以下 NAT技术中,可以使多个内网主机共用一个IP地址的是(BC)。
A. Basic NAT 		B. NAPT		C.Easy IP		D.NAT ALG
2．以下 NAT技术中,不允许外网主机主动对内网主机发起连接的是(ABC)。
A. Basic NAT 		B. NAPT		C.Easy IP		D.NAT Server
3.地址池2的地址范围为202.101.10.7~202.101.10.15,以下命令(A)在接口Serial1/0上配置了NAT,使ACL 2001匹配的地址被转换为地址池2内的地址。
A. nat outbound 2001 address-group 2
B.nat outbound 200 1 address-group 2202.101.10.7 202.101.10.15
C.nat outbound aci2001 address-group 2
D. nat outbound acl 2001 address-group 2 202.101.10.7 202.101.10.15
4.在配置NAT时,确定了(C)内网主机的地址将被转换。
A.地址池		B.NAT Table	C. ACL	D.配置NAT的接口
5.NAT的特点包括(AB)。
A.节约IP地址
B.提高内网安全性
C.私网主机不允许使用公网地址
D.NAT设备必须具有固定的公网地址

第38章：
1.AAA中的三个A分别代表认证、授权、计费
2.RADIUS的认证和授权合一,不独立提供授权功能,因此在AAA的 Domain中也可以不用配授权。上述说法正确吗?(B )
A. True
B.False
3.下列RADIUS报文是NAS发送给服务器的是(AD)。
A. Access-Request		B.Access-Aceept	C. Access-Reject	D. Accounting-Request
E. Accounting-Response
4. RADIUS使用(CD)两个端口号作为认证和计费的UDP端口。
A. 1645		B.1646		C.1812		D.1813

第39章：
1.IEEE 802. 1x的系统为典型的客户端/服务器体系结构、包括(ABD)实体。
A客户端(Supplicant System)		B. 设备端(Authenticator System)
C.用户端(User System)		D.认证服务器(Authentication Server System)
2交换机端口对用户的接人控制方式包括(AB ).
A.基于端口的认证方式		B.基于MAC的认证方式
C.基于用户的认证方式		D.基于VLAN的认证方式
3. 配置了端口隔离以后，以下(AD )说法是正确的。
A.普通端口之间被二层隔离,不能互通
B.上行端口之间被二层隔离，不能互通
C.普通端口和上行端口之间被二层隔离,不能互通
D.普通端口和上行端口之间可以互通
4.交换机上配置端口绑定后，当端口接收到报文时，会查看报文中的(AC )与交换机上所配置的静态表项是否致，以决定是否转发。
A.源MAC	B.目的MAC		C.源IP地址		D.目的IP地址
5.在交换机上配置开启端口的EEE 802. 1x特性命令为( B)。
A. [SWA] dotlx
B[SWA-GigabitGigabitEthernet1/0/1] dotlx
C.[SWA-802.1x] dotlx
D.[SWA-802.1x] dot1x interface GigabitEthernet1/0/1

第40章：
1、可以保证数据机密性的是(AB )。
A. DES	B.AES	C.MD5	D.SHA
2、可以保证数据元整性的是(CD )。
A. DES	B.AES	C.MD5	D.SHA
3、IPSec的安全协议包括(B)。
A.DES	B.ESP	C.SHA	D.IKE
4、4.IPSec可以工作于(AB)。
A.隧道模式	B.传输模式	C.主模式		D.野蛮模式
5、要设定IPSec使用的加密算法，应修改(B )配置.
A.安全ACL	B.安全提议	C.IKE提议	D.IKE对等体

第41章：
1.简述EAD方案模型中各环节的功能。略
2.EAD解决方案与微软_WSUS_产品可以无缝集成,能够实现系统补丁检查和自动升级。

第42章：
42.9.1习题
1网络设计分层模型包括下列(BC)。
A.网络接口层		B.接入层		C.汇聚层		D.核心业务层
2以下接口可以用作备份接口的有(ABCD).
A.运行帧中继的串口	B.运行PPP的串口		C.快速以太口		D.快速以太口的一个子接口
3.局域网设备和链路备份通常采用(BCD)技术,
A.DCC	B.链路聚合	C.生成树协议		D.VRRP
4.要在一个拥有20台路由器和50台交换机的网络中实现路由备份,应使用(D).
A.备份中心	B.VRRP	C.生成树协议		D.路由协议
5．下列关于VRRP协议的播述,正确的是(AB).
A.优先级影响虚拟路由器的选举结果
B.路由器如果设置为抢占方式,它一旦发现自已的优先级比当前的Master的优先
级高,就会成为Master
C.发送 VRRP报文的周期越小越好,因为这样可以迅速感知故障,降低故障恢复
时间
D.发送 VRRP报文的周期越大越好,因为这样可以避免偶然性丢包等带来的不必
要切换

第43章：
1.	简述网络管理系统的功能。
2.	简述 SNMP协议的模型结构。
3.	简述 H3C iMC平台的基本功能。
4.	当网络出现异常,SNMP代理将主动发出__Trap__报文向网管站汇报异常
5.	
第44章：
1.	堆叠的王要功能包括(ABC)。
A．简化管理		B.增加端口接入密度	C.提高设备可靠性		D.减低成本
2.	IRF堆叠支持的拓扑结构有(AB)
A.环型拓扑	B.链型拓扑	C.新型拓扑	D.树型拓扑
3. IRF堆叠中Master的编号肯定为0，slave 的编亏肯足为1。上述说法正确吗？（B）
A. True	B.False

第45章：
1.一般来说,如下(ABC)原因可能会导致计算机网络性能故障。
A.网络拥塞	B.网络环路	C.非最佳路由		D.电源中断
2.网络故障的一般解决步骤包括（ABCD）
A.现象观察与信息收集		B.可能原因列表	C.排障方案实施	D.排障经验文档化
3．下列()信息能够在设备上通讨display  version命令来收集。
A.处理器与内存	B.引导程序版本	C.协议配置	D.设备名称
4．当怀疑硬件如线缆损坏时,可以用(C)来进行排障。
A．分块故障排除法	B.分段故障排除法		C.替换法		D.分层故障排除法
5．以下(ABCD )命令可用于故障信息收集及排除。
A. Ping		B.tracert		C. display		D.debugging




上册书：

第十章
1.广域网技术主要对应	OSI参考模型的（	）
A．物理层
B．数据链路层
C．网络层
D．网路接口层
2.广域网连接方式包括（）
A．时分复用
B．分组交换
C．频分复用
D．专线
3.下列技术属于电路交换广域网连接技术的是（）
A．PSTN
B．ISDN
C．ATM
D．帧中继
4.下列技术属于分组交换广域网连接技术的是（）
A．PSTN
B．ISDN
C．ATM
D．帧中继
5.下列技术中，可以用于分组交换广域网连接的有（）
A．LAPB
B．V．35
C．RJ-11
D．CSU/DSU
1.AB     2.BD   3.AB   4.CD   5.ABCD



第十一章
1．	路由器串口可以使用的电缆包括（）
A．V．24
B．RS-449
C．V．35
D．X．21
2．路由器CE1接口可以使用的电缆包括（）
A．75电阻非平衡同轴电缆
B．120电阻平衡双绞线电缆
C．75电阻平衡双绞线电缆
D．120电阻非平衡同轴电缆
3．路由器T1接口可以使用的电缆包括（）
A．75电阻非平衡同轴电缆
B．120电阻平衡双绞线电缆
C．100电阻双绞线电缆
D．RJ-	11电缆
4.可以使用RJ-11电缆的路由器广域网接口包括（0
A．异步串口
B．E1接口
C．ADSL接口
D．AM接口
1.ABCD   2.AB   3.C   4.CD


第十二章
1.	HDLC协议位于OSI参考模型()
A.物理层
B数据链路层
C.网络层
D.传输层
2.HDLC协议既可以运行在同步串行线路又可以运行在异步串行线路。()
A. True
B.False
3.在MSR路由器上,HDLC协议默认的Keepalive消息周期是()s
A.10
B.15
C.20
D.25
4.HDLC同一链路两端设备的轮询时间间隔应设为相同的值。( )
A.True
B. False
5.下列()是HDLC协议的使用限制。
A.只支持点到点连接,不支持点到多点
B．只能工作于同步方式
C．不支持验证，缺乏安全感
D．不支持IP地址协商
1.B   2.B  3.A   4.A   5.ABCD

第十三章
1. PPP在LCP的协商状态变为Opend后,可能进入( )阶段。
A.Dead
B.Establish
C. Authenticate
D.Network
2.PAP验证是()次握手,而CHAP验证为()握手。
A. 2
B.3
C.4
D.5
3.PPP协商包含()阶段。
A.Dead
B. Establish
C. Authenticate
D.Network
E.Terminate
4. PPP由( )组成。
A. LCP
B.NCP
C. PAP
D. CHAP
5.PPP MP的实现方式有( )。
A.将链路直接绑定到VT上
B.按用户名查找VT
C.将链路绑定到MP-Group接口
D.按用户名查找MP-Group
1.CD   2.AB   3.ABCDE   4.ABCD


第十四章
1.下列选项中( )属于非对称性的DSL技术。
A. VDSL
B.SDSL 
C. HDSL
D. ADSL2+
E. VDSL2
F.SHDSL
2.ADSL一代标准中用来传输数据的频带范围为()。
A. 20kHz～1MHz
B.0～4kHz
C. 1.1~2.2MHz
D.高于10MHz
3.下列ITU-T的标准中()定义了ADSL2标准。
A.ITU G.992.1
B.ITU G.992.2
C.ITU G.992.3
D.1TU G.992.4eaA
E. ITU G.993.4
1.ADE   2.A   3.CD


```

