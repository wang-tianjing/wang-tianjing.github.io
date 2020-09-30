---
permalink: /teaching/
title: "Teaching"
author_profile: true
redirect_from: 
  - /md/
  - /teaching.html
---

---

Computer Networks - Undergraduate course - Spring 2016, Spring 2017


| Item                | Links & Description                                          |
| ------------------- | ------------------------------------------------------------ |
| Textbook            | [《Computer Networks》, Andrew S. Tanenbaum, 5ed](ed2k//%7Cfile%7CComputer.Networks,.Andrew.S..Tanenbaum,.David.J..Wetherall,.5ed,.PH,.2011(ED2000.COM).pdf%7C8454231%7Cf0a691aab8968fbd2b14e98391a9da20%7Ch=d6qfkoyxhj3oottqmyykyhdfc75u6ms7%7C/) |
| Reference           | [《Computer Networking: A Top-Down Approach》, James F. Kurose, 6ed.](http://www.bau.edu.jo/UserPortal/UserProfile/PostsAttach/10617_1870_1.pdf)<br/>《计算机网络》，作者：谢希仁，出版社：电子工业出版社，第7版 |
| Introduction        | [基本概念](http://blog.csdn.net/goodboy1881/article/details/665041),  [网络分层结构](https://www.cnblogs.com/zhouxiangting/p/10651641.html), [协议vs服务vs服务原语vs接口](https://www.cnblogs.com/wx2013/archive/2013/04/23/3037514.html), [电路vs报文vs分组交换](https://blog.csdn.net/didiaola4003/article/details/102136766) |
| Physical      Layer | [码元](https://blog.csdn.net/qq_40774175/article/details/82953153), [符号vs波特率vs比特率](https://blog.csdn.net/ymdq1113/article/details/69677116), [奈式准则与香农定理](https://blog.csdn.net/Bee_Darker/article/details/86757613) |
| Datelink layer      | [ARQ与滑动窗口协议](https://blog.csdn.net/yo746862873/article/details/51546753)*,* [Transmission vs Propagation Delay动画](http://www.ccs-labs.org/teaching/rn/animations/propagation/)*,* [Queuing and Loss动画](http://www.ccs-labs.org/teaching/rn/animations/queue/)*,* [Flow Control动画](http://www.ccs-labs.org/teaching/rn/animations/flow/)*,* [Selective Repeat / Go Back N动画](http://www.ccs-labs.org/teaching/rn/animations/gbn_sr/)*,* [CSMA/CA原理](https://blog.csdn.net/loveCC_orange/article/details/79177129)*,* [CSMA/CA动画](http://www.ccs-labs.org/teaching/rn/animations/csma/)*,* [ALOHAnet](https://zh.wikipedia.org/wiki/ALOHAnet)*,* [1-persistent vs Non-persistent vs P-persistent CSMA](https://en.wikipedia.org/wiki/Carrier-sense_multiple_access)*,* [Exponential backoff](https://en.wikipedia.org/wiki/Exponential_backoff) |
| Network Layer       | [Congestion Control: Open Loop & Closed Loop](https://www.brainkart.com/article/Congestion-Control--Open-Loop-and-Closed-Loop_13488/)*,* [网段、网关](https://blog.csdn.net/qq_41324483/article/details/100179816)*,* [IP/ARP/RARP协议](http://blog.csdn.net/goodboy1881/article/details/668556), [ICMP协议/ping/Traceroute](http://blog.csdn.net/goodboy1881/article/details/670761)*,* [IP选路和动态选路](http://blog.csdn.net/goodboy1881/article/details/695304), [CIDR地址块及子网划分](https://blog.csdn.net/dan15188387481/article/details/49873923)*,* [全0全1子网号](https://blog.csdn.net/qq_34228570/article/details/80245031?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1.nonecase&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1.nonecase)*,* [前缀vs网络vs子网vs主机号](https://qastack.cn/networkengineering/7106/how-do-you-calculate-the-prefix-network-subnet-and-host-numbers)*,* [P2P中NAT穿越](https://blog.csdn.net/do_best_/article/details/80423495)*,* [ARP与RARP](https://blog.csdn.net/qq_32642107/article/details/105478858) |
| Transport Layer     | [端到端vs点到点](https://blog.csdn.net/qq_34940959/article/details/78583993)*,* [TCP为什么要3次握手](https://blog.csdn.net/lengxiao1993/article/details/82771768)*,* [为什么是四次挥手不是三次挥手](https://blog.csdn.net/judgejames/article/details/86654689)*,* [面向连接VS无连接](http://blog.csdn.net/goodboy1881/article/details/755248), [流量控制vs拥塞控制](https://www.zhihu.com/question/38749788)*,* [UDP协议](http://blog.csdn.net/goodboy1881/article/details/713856), [广播/多播/IGMP协议](http://blog.csdn.net/goodboy1881/article/details/726860), [TCP协议概述](http://blog.csdn.net/goodboy1881/article/details/741087), [TCP控制位](https://www.cnblogs.com/bonelee/p/9077266.html), [TCP连接建立与中止](http://blog.csdn.net/goodboy1881/article/details/744534), [TCP交互数据流/成块数据流](http://blog.csdn.net/goodboy1881/article/details/745606), [TCP超时与重传](http://blog.csdn.net/goodboy1881/article/details/755248), [TCP坚持/保活定时器](http://blog.csdn.net/goodboy1881/article/details/758034)*,* [TCP快速重传为什么是三次冗余ACK](https://www.zhihu.com/question/21789252) |
| Appliaction Layer   | [DNS域名系统](http://blog.csdn.net/goodboy1881/article/details/743816) |

---
计算机网络实验相关问题：
<details>
<summary>A. 链路层实验</summary>
1、广播帧(broadcast frame)和单播帧(unicast frame)的区别是什么？<br/>
2、从实验中任选一个广播帧，一个单播帧，分析这两个帧帧头中每个字段的含义，并比较它们的区别。<br/>
3、什么是以太网的帧类型(Ethernet Type)? 它的重要性是什么? 
</details>
<details>
<summary>B. 网络层实验</summary>
1、 针对实验2.1，试着将ITS 1的interface 1的子网掩码(subnet mask)数值改为 “255.255.255.255”或“255.255.0.0”。这样一来，ITS 1是不是还可以在这个网络拓扑中传递IP数据报？<br/>
2、针对实验2.2，在路由规则中，Destination(目的网络)字段与 Mask(掩码)字段如果都设为“0.0.0.0”的话，代表什么意义？<br/>
3、如果一个ISP(Internet Services Provider)要给数十万的网络使用者提供服务，静态路由(static routing)的方式是否可以满足需求？是否有其它的不同类型的路由方式？<br/>
4、在实验2.1和2.2中，两种不同的拓扑结构，路由表有什么不同？<br/>
5、在IP数据报发送的过程中，观察并比较每台主机和路由器收到的同一个IP数据报中TTL的变化？这种变化代表了什么含义？<br/>
6、在IP数据报发送的过程中，观察每台主机和路由器收到的同一个IP数据报的帧结构，比较每段链路上帧头的变化和区别，并解释原因。<br/>
7、针对实验2.3，ITS的网络路由表是否有错，又或者有缺陷？ 如何解决步骤7与8中，IP数据报会陷入无穷循环的问题？<br/>
8、针对实验2.2，重新连接网络，使得中间任意两台机器作为主机，其他四台机器作为路由器，随机分配IP地址，重新配置路由表，完成实验2.2。<br/>
9、发送一个长度小于46字节的IP数据报，观察接收方数据链路层接收数据的情况，并解释该现象。
</details>
<details>
<summary>C. 运输层实验</summary>
1、针对实验3.3，如果在ITS 1尚未处于监听状态的情形下，我们就从ITS 2要连接到ITS 1，会发生什么状况？<br/>
2、找出TCP连接建立的三个报文，说明理由。<br/>
3、观察发送窗口和接收窗口的变化。<br/>
4、根据数据发送和接收的过程，理解TCP报文段首部序号和确认号的作用。<br/>
5、观察TCP连接释放的过程。TCP连接半关闭状态下是否可以发送和接收数据？
</details>
<details>
<summary>D. 应用层实验</summary>
1、针对实验4.1，当ITS与指定服务器建立TCP连接后，在编辑框输入的命令不正确时，网站将如何回复？<br/>
2、如果编辑框内输入GET命令，并且能正确收到服务器返回的页面，请从“Network Message Browser”窗口中，分析与GET命令和收到的页面相对应数据的链路层、网络层和运输层封装情况。<br/>
</details>

---
Internet of Things - Undergraduate course - Fall 2015, Fall 2016, Fall 2017, Fall 2019, Fall 2020

| Item          | Links & Description                                          |
| ------------- | ------------------------------------------------------------ |
| Textbook      | 《物联网导论（第3版）》，作者：刘云浩，出版社：科学出版社    |
| 参考课件      | [参考课件下载(rx4s)](https://pan.baidu.com/s/1dJMNoDkS6nUIZqXMK_is2A) |
| RFID          | [RFID原理](https://blog.csdn.net/yuyangyg/article/details/78253069), [RFID攻防](https://blog.csdn.net/sinat_23338865/article/details/71195810) |
| 定位技术      | [GPS定位基本原理](https://www.cnblogs.com/sddai/p/9692722.html), [AGPS定位机制](https://www.cnblogs.com/prayer521/p/6636457.html) |
| 作业&文献阅读 | [模板下载](http://cjc.ict.ac.cn/wltg/new/submit/CJC-Templet_Word2003.doc), [PPT汇报参考文献(uf8j)](https://pan.baidu.com/s/1Hdqtx3fph_KPXuzZkJQ83A) |

---
Linux Programming - Undergraduate course - Spring 2015, Spring 2016, Spring 2017

| Item                  | Links & Description                                          |
| --------------------- | ------------------------------------------------------------ |
| Textbook              | 《Linux教程（第4版）》，作者：孟庆昌等，出版社：电子工业出版社 |
| Reference             | 《UNIX编程艺术》，作者：Eric S·Raymond，出版社：电子工业出版社，译者：姜宏等<br/>《TCP/IP详解》（共三卷），作者：W Richard Stevens等，出版社：机械工业出版社<br/>[《鸟哥的Linux私房菜》](http://linux.vbird.org/linux_basic/), [C Library](https://www-s.acm.illinois.edu/webmonkeys/book/c_guide/), [C++ library](http://www.cplusplus.com/reference/clibrary/), [STL](http://www.cplusplus.com/reference/stl/) |
| Kernel data structure | [Kernel Archives](https://www.kernel.org/), [Cross Reference](http://lxr.free-electrons.com/), [Interactive map](http://www.makelinux.net/kernel_map/), [内核中文手册](http://net.pku.edu.cn/~yhf/lyceum/linuxK/tlk.html), [链表数据结构](https://www.ibm.com/developerworks/cn/linux/kernel/l-chain/), [Linked List](https://isis.poly.edu/kulesh/stuff/src/klist/), [循环双向链表(上)](http://blog.csdn.net/npy_lp/article/details/7294494/), [循环双向链表(下)](http://blog.csdn.net/npy_lp/article/details/7299375), [红黑树](http://blog.csdn.net/npy_lp/article/details/7420689), [ring buffer](http://blog.csdn.net/yusiguyuan/article/details/41985907), [内存池](https://www.ibm.com/developerworks/cn/linux/l-cn-ppp/index6.html), [编码风格](http://iyu.is-programmer.com/posts/30315.html), [设备驱动Hello World程序](http://coolshell.cn/articles/566.html) |
| Process               | Preliminary: [fork函数详解](http://blog.csdn.net/jason314/article/details/5640969), [使用GDB调试多进程程序](https://www.ibm.com/developerworks/cn/linux/l-cn-gdbmp/)<br/>IPC: [管道](https://www.ibm.com/developerworks/cn/linux/l-ipc/part1/), [信号(上)](http://www.ibm.com/developerworks/cn/linux/l-ipc/part2/index1.html), [信号(下)](http://www.ibm.com/developerworks/cn/linux/l-ipc/part2/index2.html), [消息队列](https://www.ibm.com/developerworks/cn/linux/l-ipc/part3/), [信号灯](https://www.ibm.com/developerworks/cn/linux/l-ipc/part4/), [共享内存(上)](http://www.ibm.com/developerworks/cn/linux/l-ipc/part5/index1.html), [共享内存(下)](http://www.ibm.com/developerworks/cn/linux/l-ipc/part5/index2.html), [套接口](https://www.ibm.com/developerworks/cn/linux/l-ipc/part6/) |
| POIX Thread           | Preliminary: [Threads Programming](https://computing.llnl.gov/tutorials/pthreads/), [Pthreads Tutorial](http://randu.org/tutorials/threads/), [GNU Portable Threads](http://www.gnu.org/software/pth/pth-manual.html)<br/>POSIX: [创建多线程](https://www.ibm.com/developerworks/cn/linux/thread/posix_thread1/), [互斥](https://www.ibm.com/developerworks/cn/linux/thread/posix_thread2/), [条件变量](https://www.ibm.com/developerworks/cn/linux/thread/posix_thread3/), [线程池](http://blog.csdn.net/hinyunsin/article/details/6650879/)<br/>Timer: [实现方式](https://www.ibm.com/developerworks/cn/linux/l-cn-timers/), [时钟管理](https://www.ibm.com/developerworks/cn/linux/l-cn-timerm/), [应用层编程](https://www.ibm.com/developerworks/cn/linux/1307_liuming_linuxtime1/), [硬件和GLibC库的细节](https://www.ibm.com/developerworks/cn/linux/1307_liuming_linuxtime2/), [内核工作1](https://www.ibm.com/developerworks/cn/linux/1308_liuming_linuxtime3/), [内核工作2](https://www.ibm.com/developerworks/cn/linux/1308_liuming_linuxtime4/) |
| Editor                | VIM: [实用技巧](https://www.ibm.com/developerworks/cn/linux/l-tip-vim1/), [常用插件](https://www.ibm.com/developerworks/cn/linux/l-tip-vim2/), [定制VIM](https://www.ibm.com/developerworks/cn/linux/l-tip-vim3/), [Vimdiff使用](https://www.ibm.com/developerworks/cn/linux/l-vimdiff/), [SpaceVim](http://spacevim.org/)<br/>Emacs: [Emacs Chat](https://plus.google.com/communities/114815898697665598016), [Planet Emacsen](http://planet.emacsen.org/), [EmacsWiki](http://planet.emacsen.org/), [Emacs论坛](https://plus.google.com/communities/114815898697665598016)<br/>Flowchart: [Drakon](http://drakon-editor.sourceforge.net/), [FSME](https://sourceforge.net/projects/fsme/) |

---
Mobile Internet - Undergraduate course - Fall 2019

| Item          | Links & Description                                          |
| ------------- | ------------------------------------------------------------ |
| Textbook      | 《移动互联网（第2版）》，作者：王新兵，出版社：清华大学出版社 |
| 基本概念      | [LTE基础概念](http://blog.csdn.net/wangkai_123456/article/details/77948540)*,* [天线科普](https://blog.csdn.net/zq07506149/article/details/80091140)*,* [信道极限容量](https://blog.csdn.net/cainv89/article/details/50582967) |
| 5G            | [5G科普](http://network.51cto.com/art/201812/589511.htm)*,* [4G 5G区别](https://blog.csdn.net/csdnnews/article/details/93429083)*,* [5G接入网+承载网+核心网](https://blog.csdn.net/bingfeilongxin/article/details/93138651) |
| 关键技术      | [多址接入技术](https://blog.csdn.net/jxwxg/article/details/53366657)*,* [OFDM原理](https://blog.csdn.net/madongchunqiu/article/details/18614233)*,* [移动IP](https://blog.csdn.net/williananjhon/article/details/90748688)*,* [数字签名](http://www.ruanyifeng.com/blog/2011/08/what_is_a_digital_signature.html)*,* [哈希锁](https://www.jianshu.com/p/d78196150350?utm_campaign) |
| 作业&文献阅读 | [模板下载](http://cjc.ict.ac.cn/wltg/new/submit/CJC-Templet_Word2003.doc), [PPT汇报参考文献(sa7u)](https://pan.baidu.com/s/1o6WFIN45XVade5eRZkZMMQ) |

---
Wireless Networks & Mobile Computing  - Graduate course - Spring 2016, Fall 2017

| Item      | Description                                                  |
| --------- | ------------------------------------------------------------ |
| Reference | 1. 《移动互联网导论（第2版）》, 作者：王新兵，出版社：清华大学出版社 <br/>2. 《从互联到新工业革命》, 作者：刘云浩，出版社：清华大学出版社 |

---

![Visitor Count](https://profile-counter.glitch.me/shen-hang/count.svg)