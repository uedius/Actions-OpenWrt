# Actions-OpenWrt

### E8820S 正常
- 使用immortalwrt master，
- 对照https://github.com/siwind/openwrt，增加E8820S dts，修改Makefile编译内核为5.10
- CONFIG_PACKAGE_dnsmasq_full_ipset=y
- make menuconfig
Kernel modules -> Netfilter Extensions -> kmod-ipt-nat



