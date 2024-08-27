# ASUS-PRIME-B660M-K-D4-12400-RX560-4g-Hackintosh-EFI
2024-08-27，更新 OC 版本到 1.0.1，更新所有Kexts	到最新版本，优化多余 Kexts

| 名称 | 型号 |
| ---- | ---- |
| CPU | Intel Core i5-12400（核显不驱动）
| 主板 | ASUS PRIME B660M-K D4 
| 内存 | 金士顿 DDR4 3200MHz 16Gx2
| 硬盘 | lexar NM620 256G
| 显卡 | AMD Radeon RX560 4G D5 白金版 OC
| 网卡 | BCM94360 2CS
| 系统 | 13.6.9 黑苹果星球恢复镜像
<br />
 华硕新bios会锁cfg lock，导致卡EB<br />
使用u盘 引导 bootx64.efi   先esc 再ctrl = <br />
找到cpuSetup 修改0x44（此地址不同主板不同） 修改为00 ctrl w 保存 alt q退出<br />
参考此教程 BV1LV4y1N7jF<br />
<br />

![20231120193113](https://github.com/jmiaob/ASUS-PRIME-B660M-K-D4-12400-RX560-4g-Hackintosh-EFI/assets/115988904/3ae502e1-6bab-40d9-bfe3-65c2640274b7)
![20231120193719](https://github.com/jmiaob/ASUS-PRIME-B660M-K-D4-12400-RX560-4g-Hackintosh-EFI/assets/115988904/747d99ac-e95c-48f2-97ab-6c30d5ca9df1)
