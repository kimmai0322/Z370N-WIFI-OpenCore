# Z370N-wifi-OC-0.5.9
1.此efi文件为纯核显版本
2.视频输出接口请用DP或者HDMI2.0接口 HDMI接口暂时没有修复
3.本efi根据OC-0.5.9版本源文件进行修改，根据OpenCore Guide Book规则进行创建
4.请根据自身实际情况进行修改后使用，三码请务必进行修改！！！

配置清单：
CPU:i3-9100 
内存:ddr4 8g*2 3200(OC)
硬盘：Intel 660p 500G
网卡: BCM94360cs2
屏幕：ASUS MG248 1080p （未开启HIDPI）

BIOS版本：F14a

CFG lock:缺失(V0.1)，在config中已经添加解锁
CFG lock:已经打开(V0.4)，在config中已经关闭解锁，详情请根据文件 解锁bios中CFG lock操作说明书.txt 进行操作，或者自行打开 config.plist 进行解锁开关


BIOS参数设置：
Fast Boot : Disabled

LAN PXE Boot Option ROM : Disabled

Storage Boot Option Control : UEFI

Security Device Support : Disable

Network Stack : Disabled

Legacy USB Support : Enabled (必须开启)

XHCI Hand-off : Enabled (必须开启，不然开不了机)

Vt-d : Disabled

Above 4G Decoding : Enabled

Wake on LAN Enable : Disabled

IOAPIC 24-119 Entries : Enabled

*纯核显设置：
Initial Display Output : IGFX

Integrated Graphics : Enabled

DVMT Pre-Allocated : 256M

DVMT Total Gfx Mem : 256M
