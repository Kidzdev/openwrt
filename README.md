# Passwall
opkg update && wget --no-check-certificate "https://github.com/Kidzdev/openwrt/blob/main/luci-app-openclash_0.42.06-beta_all.ipk?raw=true" -O /root/install.ipk && cd /root && opkg install --force-depends install.ipk && rm -rf install.ipk
# Openclash
opkg update && wget --no-check-certificate "https://github.com/Kidzdev/openwrt/blob/main/luci-app-passwall_4-22_all.ipk?raw=true" -O /root/install.ipk && cd /root && opkg install --force-depends install.ipk && rm -rf install.ipk
# Corksrew
opkg update && wget --no-check-certificate "https://github.com/Kidzdev/openwrt/blob/main/corkscrew_2.0-1_x86_64.ipk?raw=true" -O /root/install.ipk && cd /root && opkg install --force-depends install.ipk && rm -rf install.ipk
