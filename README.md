# Lenovo-Yoga910-Hacintosh-Mojave10.14<br>
## 适用于yoga910的8G版本，16G版可以修改config.plist的SIMBUS部分，把两个4G内存都修改成8G即可。
这个EFI具体情况如下：<br>
电池补丁部分和触控板/触控屏采用的是给DSDT打补丁，其余的都是hotpatch;<br>
触控板/触摸屏驱动用的是VoodooI2C系列驱动，手势基本完善；<br>
声卡用的AppleALC,自编译的，id为21<br>
显卡部分采用的是Whatevergreen<br>
声卡用的是AppleALC驱动<br>
无线网卡是高通的网卡，无法驱动，由于没有可用的内建无线网卡，Siri失效(可以更换DW1560无线网卡，airdrop和handoff、Siri均可用)<br>

#################################################################################<br>

安装时请自己使用USB鼠标，在安装界面触控板/触控板无法使用（VoodooI2C驱动的锅）<br>


电脑已经卖了，此EFI仅供参考，不再提供更多支持<br>
PS:这个电脑不建议入手<br>
大家可以在此EFI上进行改善之类的<br>
