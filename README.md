### 一些说明

这里只分享我自己目前在用的配置，不一定适合你，可以参考，修改成自己合用的。

这套配置是我在`11.0.1`用的，在全新安装的情况下请自行测试。

感谢@zycer、@zhanglong5460、@qw1363673600几位[帮忙尝试](https://github.com/darkhandz/XPS15-9550-Catalina/issues/11)。

### 硬件配置

- 机型：DELL XPS15 9550
- BIOS：v1.14.0
- CPU：Intel i7 6700HQ
- 内存：16G DDR4 2400（原厂8G，自己换了）
- 硬盘：SM961 256G NVMe SSD
- 核显：HD530, `1920x1080`
- 声卡：Realtek ALC298（也叫ALC3266）
- 无线网卡：DW1830（带蓝牙）

DW1830我是机器原配的，如果你要另外买，建议考虑下DW1560或DW1820a，买之前自己了解下是否可以完美使用，另外BCM94360CS2+转接延长线也可以考虑。

### 安装完之后的一些问题

- 独显不指望了
- 无线5GHz达不到最高速度（我没具体测试过）
- ThunderBolt没设备测试
- USB-C的扩展坞在睡眠唤醒之后需要再拔插一次
- 低亮度会有轻微闪屏
- 睡眠唤醒后AirDrop可能搜索不到设备，关闭WiFi再打开就可以了
- 耳机拔插个人没什么需求，要自行研究下

### 参考
- [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [OpenCore 0.5+ 部件补丁](https://ocbook.tlhub.cn/)