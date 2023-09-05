
# 后台管理地址：
# 管理ip：192.168.5.1
# 用户名和密码：root/password
# 无线wifi名称：OpenWrt
# 无线wifi密码：password

## https://blog.wwang.pw/post/nx30pro.html

## 1. 固定电脑网卡进入uboot，刷入`immortalwrt-mediatek-mt7981-h3c_nx30pro-squashfs-factory.bin`

   ![1](https://gitlab.com/xiaowansm/img/-/raw/main/pictures/2023/08/16_10_51_7_202308161051591.png)

![2](https://gitlab.com/xiaowansm/img/-/raw/main/pictures/2023/08/16_10_51_2_202308161051378.png)

## 2. 网卡改为自动获取，进入op后台【如系统未启动，插拔电源重启即可】，再刷入`openwrt-mediatek-filogic-h3c_magic-nx30-pro-squashfs-sysupgrade.bin`即可

![3](https://gitlab.com/xiaowansm/img/-/raw/main/pictures/2023/08/16_10_51_4_202308161051830.png)

![4](https://gitlab.com/xiaowansm/img/-/raw/main/pictures/2023/08/16_10_50_59_202308161050982.png)

![5](https://gitlab.com/xiaowansm/img/-/raw/main/pictures/2023/08/16_10_50_58_202308161050094.png)

![6](https://gitlab.com/xiaowansm/img/-/raw/main/pictures/2023/08/16_10_50_55_202308161050966.png)

## 3. 等待几分钟后，192.168.5.1进入op后台

![Snipaste_2023-08-16_10-49-51](https://cdn.staticaly.com/gh/xiaowansm5/img@master/Typora/Snipaste_2023-08-16_10-49-51.6c5l6p2213g0.webp)
