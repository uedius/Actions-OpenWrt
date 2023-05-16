# Actions-OpenWrt

### E8820S 正常
- 使用immortalwrt master，
- 对照https://github.com/siwind/openwrt ,增加E8820S dts，修改target/linux/ramips/image/mt7621.mk，target/linux/ramips/mt7621/base-files/etc/board.d/01_leds
- CONFIG_PACKAGE_dnsmasq_full_ipset=y
- make menuconfig
Kernel modules -> Netfilter Extensions -> kmod-ipt-nat



