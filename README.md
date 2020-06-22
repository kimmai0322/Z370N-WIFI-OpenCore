# Z370N-wifi-OC0.5.9
1.此efi文件为纯核显版本
2.视频输出接口请用DP或者HDMI2.0接口 HDMI接口暂时没有修复
3.本efi根据OC-0.5.9版本源文件进行修改，根据OpenCore Guide Book规则进行创建
4.请根据自身实际情况进行修改后使用，三码请务必进行修改！！！

配置清单：
CPU:i3-9100 
内存:ddr4 8g*2 3200(OC)
硬盘：Intel660p 500g
网卡:BCM94360cs2

BIOS版本：F14a

CFG lock:缺失，在config中已经添加解锁

BIOS参数设置：
Fast Boot : Disabled

LAN PXE Boot Option ROM : Disabled

Storage Boot Option Control : UEFI

Security Device Support : Disable

Network Stack : Disabled

Legacy USB Support : Enabled (必须开启)

XHCI Hand-off : Enabled (必须开启，不然开不了机)

Vt-d : Disabled

Wake on LAN Enable : Disabled

IOAPIC 24-119 Entries : Enabled


*纯核显设置：
Initial Display Output : IGFX

Integrated Graphics : Enabled

DVMT Pre-Allocated :128M
