Пакеты в прошивке (можно закинуть в ИИ и он расскажет что включено):
busybox kmod-usb-storage kmod-fs-ext4 block-mount ntfs-3g luci-app-ksmbd luci-i18n-ksmbd-ru wsdd2 minidlna luci-app-minidlna luci-i18n-minidlna-ru wireguard-tools kmod-wireguard luci-proto-wireguard ddns-scripts ddns-scripts-services luci-app-ddns luci-i18n-ddns-ru inadyn dnscrypt-proxy2 openvpn-easy-rsa openvpn-openssl luci-app-openvpn luci-i18n-openvpn-ru openssh-sftp-server luci-i18n-base-ru luci-i18n-firewall-ru luci-i18n-hd-idle-ru luci-i18n-opkg-ru hd-idle luci-app-hd-idle adblock luci-app-adblock luci-i18n-adblock-ru kmod-usb-net-rndis usb-modeswitch watchcat luci-app-watchcat luci-i18n-watchcat-ru drill curl pbr luci-app-pbr luci-i18n-pbr-ru luci-app-ttyd luci-i18n-ttyd-ru


Установка:
Подлючаемся по SSH по инструкции
https://4pda.to/forum/index.php?showtopic=1053772&view=findpost&p=117509354


В SSH введи:
wget https://github.com/Slevest/ASUS-RT-AX53U/releases/download/v1.0.0/openwrt-24.10.4-e8b97efb5075-ramips-mt7621-asus_rt-ax53u-squashfs-factory.bin


Потом введи:
mtd-write -i openwrt-24.10.4-e8b97efb5075-ramips-mt7621-asus_rt-ax53u-squashfs-factory.bin -d Kernel
