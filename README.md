# Padavan-build for DIR882 A1 DIR-882

        echo "CONFIG_FIRMWARE_INCLUDE_MENTOHUST=n" >> .config #MENTOHUST
        echo "CONFIG_FIRMWARE_INCLUDE_SCUTCLIENT=n" >> .config #SCUTCLIENT
        echo "CONFIG_FIRMWARE_INCLUDE_SHADOWSOCKS=y" >> .config #SS plus+
        echo "CONFIG_FIRMWARE_INCLUDE_SSOBFS=n" >> .config # simple-obfs
        echo "CONFIG_FIRMWARE_INCLUDE_ADBYBY=y" >> .config #adbyby plus+
        echo "CONFIG_FIRMWARE_INCLUDE_DNSFORWARDER=n" >> .config #DNSFORWARDER
        echo "CONFIG_FIRMWARE_INCLUDE_SRELAY=n" >> .config #
        echo "CONFIG_FIRMWARE_INCLUDE_XRAY=n" >> .config #xray  ~4.5M
        echo "CONFIG_FIRMWARE_INCLUDE_V2RAY=n" >> .config #v2ray
        echo "CONFIG_FIRMWARE_INCLUDE_DDNSTO=y" >> .config #ddnsto  ~0.5M
        echo "CONFIG_FIRMWARE_INCLUDE_ALDRIVER=n" >> .config  #  ~3m
        echo "CONFIG_FIRMWARE_INCLUDE_ZEROTIER=y" >> .config #zerotier ~1.3M
        echo "CONFIG_FIRMWARE_INCLUDE_ALIDDNS=n" >> .config #aliddns
        echo "CONFIG_FIRMWARE_INCLUDE_SMARTDNS=y" >> .config #smartdns
        echo "CONFIG_FIRMWARE_INCLUDE_SMARTDNSBIN=y" >> .config #smartdns
        echo "CONFIG_FIRMWARE_INCLUDE_WIREGUARD=y" >> .config #wireguard ~10k
        echo "CONFIG_FIRMWARE_INCLUDE_ADGUARDHOME=n" >> .config
        echo "CONFIG_FIRMWARE_INCLUDE_LANG_RU=y" >> .config
        ##QOS and OverClock##
        echo "CONFIG_FIRMWARE_INCLUDE_SQM=y" >> .config #SQM QOS#CPU
        echo "CONFIG_FIRMWARE_INCLUDE_OC=n" >> .config #CPU overClock
        echo 'CONFIG_FIRMWARE_MT7621_OC="0x362"' >> .config #overClock：1000Mhz=0x312 1100Mhz=0x362 1120Mhz=0x372 1200Mhz=0x3B2

