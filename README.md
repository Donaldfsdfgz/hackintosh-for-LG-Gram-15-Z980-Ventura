# hackintosh-for-LG-Gram-15-Z980-Ventura
EFI for LG Gram 15 Z980, MAC 13.4.1 Ventura
感谢OpCore-Simplify-main 项目，使用这个项目我把LG Gram 15 Z980 安装上了黑苹果
EFI由该软件直接生成，全部使用默认参数。安装的版本为Ventura 13.4.1
经过测试大部分的功能都可以正常使用. 合盖后休眠模式为hibernatemode 3, 底部微微发热. 
比较严重的问题如下: 直接默认为使用插电模式, 电量一直是100%, 无法显示电池电量.
安装前需要设置一下BIOS:
Modify the BIOS settings (press F2 to enter the BIOS when booting, Ctrl + Alt + F7 to open the hidden BIOS options, thanks to as695336480 for providing: source) The following is provided by linGinc, thanks!
BIOS-Main-Boot Features: CMS Support [No], Fast Boot [Disabled]
BIOS-Advanced-Intel Advanced Menu-Power&Performance-CPU Power Management Control: CFG Lock [Disabled]
BIOS-Advanced-System Agent(SA) Configuration: VT-d [Disabled], Above 4GB MMIO BIOS assignment [Enabled]
BIOS-Advanced-System Agent(SA) Configuration-Graphics Configuration: DVMT Pre-Allocated [64M]
