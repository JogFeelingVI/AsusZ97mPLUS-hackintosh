# Fixz97DSDT
#### z97m plus DSDT Fix
##### MacOSEFI opencore 0.65

###### Mac Pro (2017)
###### CPU 3.4 GHz 四核Intel Xeon E3 1230v3
###### Asus z97m-plus
###### Ram 16 GB 1923 MHz DDR3
###### Radeon RX 470/570 4 GB
###### Nvme SSD 256Gb Lexar SSD Media Catalina
###### SATA SSD 240Gb TOSHIBA-TR200 Media
###### SATA HDD ST1000DM003-1ER162 Media

#### Fix log 2021-01-05
- 添加 AMD Rx 470 显卡黑苹果驱动 但几乎没作用
- 删除没用的NvMEfix补丁
- ALC layout-id 0700000
- updata opencore 0.65
#### Fix Log 2020-12-31
- add SSDT-EHCx_OFF.aml
- Fix USB
- 一个USB3.0 端口等于两个端口 一个USB3 一个USB2