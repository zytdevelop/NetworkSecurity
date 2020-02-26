# TCP/IP(Transmission Control Protocol/Internet Protocol)  
## 1.1 TCP/IP 背景和介绍
> - 定义  
> TCP/IP是传输控制协议和网络协议的简称,它定义了电子设备如何连入英特网,  
> 以及数据如何再他们之间传输的标准  
  
## 1.2 网络协议栈结构
  <head>
  <meta http-equiv=Content-Type content="text/html; charset=gb2312">
  <meta name=ProgId content=Excel.Sheet>
  <meta name=Generator content="Microsoft Excel 15">
  <link rel=File-List href="网络协议栈结构1.files/filelist.xml">

  <!--table
    {mso-displayed-decimal-separator:"\.";
    mso-displayed-thousand-separator:"\,";}
  .font520257
    {color:windowtext;
    font-size:9.0pt;
    font-weight:400;
    font-style:normal;
    text-decoration:none;
    font-family:宋体;
    mso-generic-font-family:auto;
    mso-font-charset:134;}
  .xl1520257
    {padding-top:1px;
    padding-right:1px;
    padding-left:1px;
    mso-ignore:padding;
    color:black;
    font-size:11.0pt;
    font-weight:400;
    font-style:normal;
    text-decoration:none;
    font-family:宋体;
    mso-generic-font-family:auto;
    mso-font-charset:134;
    mso-number-format:General;
    text-align:general;
    vertical-align:middle;
    mso-background-source:auto;
    mso-pattern:auto;
    white-space:nowrap;}
  .xl6520257
    {padding-top:1px;
    padding-right:1px;
    padding-left:1px;
    mso-ignore:padding;
    color:black;
    font-size:11.0pt;
    font-weight:400;
    font-style:normal;
    text-decoration:none;
    font-family:宋体;
    mso-generic-font-family:auto;
    mso-font-charset:134;
    mso-number-format:General;
    text-align:center;
    vertical-align:middle;
    mso-background-source:auto;
    mso-pattern:auto;
    white-space:nowrap;}
  .xl6620257
    {padding-top:1px;
    padding-right:1px;
    padding-left:1px;
    mso-ignore:padding;
    color:black;
    font-size:11.0pt;
    font-weight:400;
    font-style:normal;
    text-decoration:none;
    font-family:宋体;
    mso-generic-font-family:auto;
    mso-font-charset:134;
    mso-number-format:General;
    text-align:center;
    vertical-align:middle;
    mso-background-source:auto;
    mso-pattern:auto;
    white-space:normal;}
  ruby
    {ruby-align:left;}
  rt
    {color:windowtext;
    font-size:9.0pt;
    font-weight:400;
    font-style:normal;
    text-decoration:none;
    font-family:宋体;
    mso-generic-font-family:auto;
    mso-font-charset:134;
    mso-char-type:none;}
  -->

  </head>

  <body>
  <!--[if !excel]>　　<![endif]-->
  <!--下列信息由 Microsoft Excel 的发布为网页向导生成。-->
  <!--如果同一条目从 Excel 中重新发布，则所有位于 DIV 标记之间的信息均将被替换。-->
  <!----------------------------->
  <!--“从 EXCEL 发布网页”向导开始-->
  <!----------------------------->

  <div id="网络协议栈结构_20257" align=center x:publishsource="Excel">

  <table border=0 cellpadding=0 cellspacing=0 width=349 style='border-collapse:
   collapse;table-layout:fixed;width:262pt'>
   <col width=92 style='mso-width-source:userset;mso-width-alt:3271;width:69pt'>
   <col width=116 style='mso-width-source:userset;mso-width-alt:4124;width:87pt'>
   <col width=141 style='mso-width-source:userset;mso-width-alt:5006;width:106pt'>
   <tr height=19 style='height:14.4pt'>
    <td height=19 class=xl6520257 width=92 style='height:14.4pt;width:69pt'>OSI七层模型</td>
    <td class=xl6520257 width=116 style='width:87pt'>TCP/IP四层模型</td>
    <td class=xl6520257 width=141 style='width:106pt'>常见协议</td>
   </tr>
   <tr height=19 style='height:14.4pt'>
    <td height=19 class=xl6520257 style='height:14.4pt'>应用层</td>
    <td rowspan=3 class=xl6520257>应用层</td>
    <td rowspan=3 class=xl6620257 width=141 style='width:106pt'>SMTP HTTP DNS
    <br>
      HTTP Telnet POP3 <br>
      SNMP FTP NFS</td>
   </tr>
   <tr height=19 style='height:14.4pt'>
    <td height=19 class=xl6520257 style='height:14.4pt'>表示层</td>
   </tr>
   <tr height=19 style='height:14.4pt'>
    <td height=19 class=xl6520257 style='height:14.4pt'>会话层</td>
   </tr>
   <tr height=19 style='height:14.4pt'>
    <td height=19 class=xl6520257 style='height:14.4pt'>传输层</td>
    <td class=xl6520257>传输层</td>
    <td class=xl6520257>TCP UDP</td>
   </tr>
   <tr height=19 style='height:14.4pt'>
    <td height=19 class=xl6520257 style='height:14.4pt'>网络层</td>
    <td class=xl6520257>网络层</td>
    <td class=xl6520257>IP ICMP ARP</td>
   </tr>
   <tr height=19 style='height:14.4pt'>
    <td height=19 class=xl6520257 style='height:14.4pt'>数据链路层</td>
    <td rowspan=2 class=xl6520257>网际接口层</td>
    <td rowspan=2 class=xl6520257>PPP Ethernet</td>
   </tr>
   <tr height=19 style='height:14.4pt'>
    <td height=19 class=xl6520257 style='height:14.4pt'>物理层</td>
   </tr>
   <![if supportMisalignedColumns]>
   <tr height=0 style='display:none'>
    <td width=92 style='width:69pt'></td>
    <td width=116 style='width:87pt'></td>
    <td width=141 style='width:106pt'></td>
   </tr>
   <![endif]>
  </table>

  </div>


  <!----------------------------->
  <!--“从 EXCEL 发布网页”向导结束-->
  <!----------------------------->
  </body>

  </html>
   
 TCP/IP被分成4层,每一层承担的任务不一样,各层的协议的工作方式也不一样,每层封装上层数据的方式也不一样:  

(1)应用层：应用程序通过这一层访问网络，常见 FTP、HTTP、DNS 和 TELNET 协议；

(2)传输层：TCP 协议和 UDP 协议；

(3)网络层：IP 协议，ARP、RARP 协议，ICMP 协议等；
 
(4)网络接口层：是 TCP/IP 协议的基层，负责数据帧的发送和接收。    

  
## 2.1 IP地址

- 网络上每一个节点都必须有一个独立的IP地址, 通常使用的IP地址是一个32bit的数字, 
被 `.` 分成4组, 例如, `255.255.255.255`
有了IP地址, 用户的计算机就可以发现并连接互联网中的另外一台计算机.
  
## 2.2 域名
- 互联网给每个IP起的别名  
- 域名与计算机的IP地址相对应, 并把这种对应关系存储在域名服务系统DNS(Domain Name System)
- 常见的域名
    - com , net 和 org 三种顶级域名
    - 每个国家还有自己的专属域名后缀, 比如我国后缀名为cn
- 如何查看域名对应的IP
    - 使用`nslookup` 或者 `ping` 来查看域名对应的IP地址.
      
## 2.3 MAC地址
- MAC(Media Access Control)地址, 或称物理地址,硬件地址, 用来定义互联网中的设备位置.  
- 在TCP/IP层次模型中, 网络层管理IP地址, 链路层负责MAC地址.  
因此每个网络位置会有一个专属于它的IP地址,而每个主机都会有一个专属于它的MAC地址.

  
## 2.4 端口号
- 把IP地址比作一间房子, 那么端口号就是出入房子的门.
- 端口号采用16bit的端口号标识, 一个IP地址端口号可以有65536(2^16)个.
- 服务器的默认程序一般都是通过人们所熟知的端口号来识别.
    - 常见协议对应端口号:
        * SSH 22
        * FTP 20和21
        * Telnet 23
        * SMTP 25
        * TFTP 69
        * HTTP 80
        * SNMP 161
        * Ping使用ICMP, 无具体端口号
