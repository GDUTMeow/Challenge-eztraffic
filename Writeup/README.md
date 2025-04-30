# ez_traffic

流量分析很简单哦！

用 wireshark 打开后过滤 http 流量，发现有 `flag.png`

![](https://cdn.jsdelivr.net/gh/GDUTMeow/Challenge-eztraffic/img/image-20250418193112430.png)

对 `9716` 包中的数据进行导出

![](https://cdn.jsdelivr.net/gh/GDUTMeow/Challenge-eztraffic/img/image-20250418193240262.png)

可以得到一个二维码

![flag](https://cdn.jsdelivr.net/gh/GDUTMeow/Challenge-eztraffic/img/flag-1744976012327-1.png)

拿去解码后得到 flag

![](https://cdn.jsdelivr.net/gh/GDUTMeow/Challenge-eztraffic/img/image-20250418193313567.png)

`flag{TrAffIC_4n4Ly5IS_l5-5oooo-EZz2ZZ2_lOl}`