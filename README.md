# Hackintosh-Clover-Config

四代笔记本黑苹果Clover配置文件

## 笔记本配置

	  电脑型号             MECHREVO X6S
	  操作系统             Windows10+macOS 10.12.6 
	  处理器               i5-4210M
	  主板                Haswell - Lynx Point
	  显卡                HD4600+GTX960M
	  内存                8G
	  硬盘                64G SSD+128G SSD+1T HDD
	  声卡                ALC269vc
	  有线网卡             RTL8111
	  无线网卡             BCM43224HMS

## 工作情况

* 核显工作正常，独显屏蔽
* 有线网卡工作正常；无线网卡免驱，工作正常
* 声卡工作正常，包括扬声器，耳机和麦克风
* 睡眠唤醒正常
* CPU变频正常
* hdmi输出正常，包括音频输出
* 亮度调节正常，可使用Fn快捷键调节
* 电量显示正常
* usb正常，包括usb3.0
* 键盘和触控板工作正常
* 摄像头工作正常

## 目录说明

### kexts

主要存放kexts驱动文件。包括显卡，声卡，网卡等所需驱动文件

### hotpatch

主要存放用hotpatch方式进行系统动态修补的aml文件


### hotpatch-config.plist

用hotpatch方式进行动态修补的clover配置文件

##	参考链接

*	**常用kexts驱动**	[https://bitbucket.org/RehabMan/](https://bitbucket.org/RehabMan/)
* **修补文件**	[https://github.com/RehabMan/OS-X-Clover-Laptop-Config](https://github.com/RehabMan/OS-X-Clover-Laptop-Config)

