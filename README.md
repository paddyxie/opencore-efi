# opencore-efi

硬件配置：
* CPU：Intel 10700
* 主板：ROG STRIX B460-I GAMING
* 显卡：CPU内置(UHD 630)
* 硬盘：三星970 PRO 512GB
* 网卡：主板内置(I219-V)
* 无线网卡：Fenvi T919(BCM94360CD)
* 内存：无所谓

安装后配置：
1. USB定制 - 用USBMap直接生成kext（https://dortania.github.io/OpenCore-Post-Install/usb/intel-mapping/intel.html）
2. RTC问题 - 二分法屏蔽CMOS写入（https://dortania.github.io/OpenCore-Post-Install/misc/rtc.html#finding-our-bad-rtc-region）

安装后配置参考：
https://dortania.github.io/OpenCore-Post-Install/
