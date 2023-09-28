# OC-EFI-ASUS-B250M-KYLIN

测试系统：macOS Ventura/macOS Sonoma

主板:ASUS B250M-KYLIN 黑苹果OC（安装过程中 请使用的config-install.plist《记得重新命名为config.plist》进行安装，安装之后再替换config.plist）

有任何问题都可提交 issues。但我并不经常登陆github 只要看到就会回复或处理。敬请谅解

cpu:i7 7700

显卡:rx590

OC版本：基于OC 0.9.5 (建议使用 OpenCore Configurator 2.74.1.0 编辑)

# 我不确定有几个人会用这个EFI，警告：

所有功能完整完美

1.核显已驱动

2.睡眠可用

3.有线网卡可用

4.无线网卡可自购：奋威 T919（此卡为PCI-E卡 免驱）。无线网卡会占用主板的usb2.0插口，自行决断（可自行购买主板usb2.0扩展线，由于usb2.特性，与T919共用会导致机箱的usb2.0只有一个可用）

macOS Ventura 免驱可用

macOS Sonoma 原生已经移除对博通网卡的所有无线驱动（奋威 T919是博通网卡），不支持博通系列全系无线网卡

5.声卡可用

6.usb口已定制（install的config是未定制的）
（由于机箱USB口的多样化，你的USB可能和我的不一样，安装系统之后，可以按照[【黑苹果】全新的定制USB教程-哔哩哔哩](https://b23.tv/Qlab1sC)中的教程定制自己的USB)
