# -Hackintosh-I2C
对应大佬们一些I2c的补充（主要针对用完大佬方法还不能使用的）

看我这个说明之前，请务必先看过这两位大佬的博客

https://www.penghubingzhou.cn/2019/01/06/VoodooI2C%20DSDT%20Edit/ 

望川之洲，主要提供了修改DSDT的教程。

https://blog.gzxiaobai.cn/2020/05/17/%E7%94%A8%E7%83%AD%E8%A1%A5%E4%B8%81%E4%BF%AE%E7%90%86%E4%BD%A0%E7%9A%84%E8%A7%A6%E6%91%B8%E6%9D%BF%EF%BC%88TouchPad-Hotpatch%EF%BC%89/

神乐小白，主要提供热补丁的修改方法。

另外也可以先去宪武大佬的OC-little里找到一些思路

https://github.com/daliansky/OC-little

以及官方文档VoodooI2c

https://github.com/VoodooI2C/VoodooI2C

具体补丁过程就不在赘述，看上面大佬的修改以及很详细了，就补充一些我发现的方法。

本人使用ELAN与HID混合型的触摸板，在用了上述大佬的补丁方法后发现仍不能使用触摸板。

在@Bat.bat大佬的提供的EFI的帮助下，我成功实现了驱动。但是大佬使用了一种不同与上述驱动的方法。

具体不举例，涉及大佬隐私，而且有一定缺陷。

但是我利用大佬方法成功发现了另一种驱动方法。

修补I2c总线方法的方式驱动触摸板

下面具体说明地址





