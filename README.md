## 龙芯直播课堂

### 龙芯直播课堂
<https://loongsonedu.cn/course/>

### 社区主页（筹建中）
<https://loongsonedu.cn/homepage/>

## 龙芯开源技术简介

### Loongson龙芯处理器
#### 龙芯一号：面向嵌入式专门应用
* 龙芯1H - 面向钻井应用的耐高温芯片
* 龙芯1D - 面向超声波热表、水表和气表测量的低功耗、低成本专用处理器
* 龙芯1C101 - 龙芯1C101是在龙芯1C100基础上针对门锁应用而优化设计的单片机芯片
* 龙芯1C - 面向工业控制及物联网等领域的高性价比SOC芯片
* 龙芯1B - 一款面向嵌入式专用应用领域的轻量级的32位SoC芯片
* 龙芯1A - 面向嵌入式专用应用领域的低功耗、低成本处理器

#### 龙芯二号：面向工控和终端类应用
* 龙芯2K1000 - 面向工业控制与终端等领域的低功耗通用处理器
* 龙芯2K0500 - 面向工控互联网应用、打印终端、BMC等应用场景高集成度处理器芯片

#### 龙芯三号：面向桌面/服务器类应用
* 龙芯3A5000/3B5000 - 面向个人计算机、服务器等信息化领域的通用处理器
* 龙芯3C5000L - 龙芯中科专门面向服务器领域的通用处理器
* 龙芯3A4000/3B4000 - 面向个人计算机、服务器等信息化领域的通用处理器

### LoongArch龙芯架构
#### 充分考虑兼容需求的龙芯指令系统LoongArch®
* 2020年，龙芯中科基于二十年的CPU研制和生态建设积累推出了龙芯指令系统（LoongArch®），包括基础架构部分和向量指令、虚拟化、二进制翻译等扩展部分，近2000条指令。
* 龙芯指令系统具有较好的自主性、先进性与兼容性。龙芯指令系统从整个架构的顶层规划，到各部分的功能定义，再到细节上每条指令的编码、名称、含义，在架构上进行自主重新设计，具有充分的自主性。
* 龙芯指令系统在设计时充分考虑兼容生态需求，融合了各国际主流指令系统的主要功能特性，同时依托龙芯团队在二进制翻译方面十余年的技术积累创新，能够实现多种国际主流指令系统的高效二进制翻译。龙芯中科从2020年起新研的CPU均支持LoongArch®。

#### 核心IP自主掌握，龙芯安全程度最高
* 高速接口 - HT控制器和PHY，PCIE4.0控制器和PHY
* 片内互联总线 - AXI,AHB,APB；XBAR、RING、互联总线
* 内存控制器 - SDRAM、DDR2、DDR3、DDR4
* 打通各类接口
  - 存储接口：SPI,SDIO,NANDFlash,NORFlash；
  - 音视频接口：HDA,AC97,I2S,LCD,HDMI；
  - 工业接口：UART,I2C,PWM,CAN,LIO,LPC,TSENSOR,VPWM,RTC,ACPI,ADC，1553B,SpaceWire,PPC,PCM,OC，JBIG,LSU；
* 已掌握2D/3DGPU技术
* 全国产桥片方案7A1000、7A2000
* 多种定制模块多端口寄存器堆、PLL、DDR2/3/4-PHY、HT-PHY

### Loongnix基础版操作系统 
* Loongnix-Server 面向服务器
* Loongnix-Client 面向个人计算机
* Loongnix-Cloud，面向云计算

#### Loongnix掌握操作系统核心技术
* Linux内核
* GCC、LLVM、GOLANG
* Java虚拟机
* .NET
* 浏览器
* 媒体播放器

#### Loongnix内置基础软件
* 内核：基于社区长期维护版(LTS)的龙芯产品化版
* 操作系统基础库：文件系统、包管理系统、安全与审计、基础图形图像库
* 固件支持：支持ACPI标准,兼容支持PMON、昆仑、百敖及UEFI，自适应提供各种固件所需要的启动文件
* 云计算：OpenStack、Docker、KVM、oVirt、Libvirt、Virtmanager等
* 编译工具：GCC，Binutils，LLVM，Rust、Golang等主流编译器
* 内置浏览器：支持Html5、WebAssembly、NPAPI、CSS等技术，支持国密算法、办公插件
* 编程语言：C/C++、C#，Fortran，Java、JavaScript、XML、Python、Ruby、Php、Perl等
* 基础媒体应用：VLC，Smplayer，Flameshot，Openshot，OpenCV等
* API基础环境：JAVA、.Net、Node.js、Qt、Electron、CEF、VS-Code、Eclipse等

### LoongOS嵌入式信息系统
* LoongOS是具备精简、高效、实时特征的工控类操作系统
* LoongOS基于通用Linux内核，利用RT-Linux技术实现实时性
* LoongOS简化了复杂的传统X个人计算机图形系统，支持FrameBuffer、EGL、Wayland三种图形应用模式，其中FrameBuffer（二维）和EGL（三维）都是单窗口应用全屏模式，具备系统轻量、启动迅速、开发便捷等特点；Wayland模式可以支持多窗口应用，实现了全功能的三维OpenGL驱动和编程接口，具备简洁的个人计算机图形环境。LoongOS三种图形模式都支持Qt编程开发和应用环境，支持兼容VxWorks的RTAPI编程接口。针对嵌入式系统的需求，实现了文件系统加固、掉电保护、分区保护、安全隔离等特性，还可以使用配套的集成开发环境LDK根据需求灵活定制专用系统。

### 龙芯云中心

#### 龙芯云生态
#### 龙芯云平台
#### 迁移工具

* 龙芯云中心基于龙芯开源IAAS+云平台，作为龙芯云对外服务窗口，提供龙芯云生态介绍、商业云方案展示、体验中心等龙芯云上功能，助力龙芯生态建设。
* 龙芯云中心为国内主流云厂商提供一个云解决方案展示平台，充分展示各个云厂商基于龙芯CPU的云解决方案及云产品特色，并为信创用户提供一个云体验环境，以更好的为信创业务上云提供服务。
* 龙芯云目前主要用于软件适配、开源软件移植、开源生态用户体验、环境模拟测试(问题复现)、业务上云、生态培训协作、研发测试等场景。


---
<https://loongsonedu.cn> 

主体备案编号：<a href="https://beian.miit.gov.cn/" target="_blank">京ICP备16045052号-14</a>
