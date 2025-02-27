# luci-app-log
Advanced syslog and kernel log (tail, search, etc) for LuCI (OpenWrt webUI).

OpenWrt >= 19.07.

Supported LuCI themes: luci-theme-bootstrap, luci-theme-material.

**Installation notes:**

    wget --no-check-certificate -O /tmp/luci-app-log_0.2-1_all.ipk https://github.com/gSpotx2f/luci-app-log/raw/master/packages/19.07/luci-app-log_0.2-1_all.ipk
    opkg install /tmp/luci-app-log_0.2-1_all.ipk
    rm /tmp/luci-app-log_0.2-1_all.ipk
    /etc/init.d/rpcd restart

**i18n-ru:**

    wget --no-check-certificate -O /tmp/luci-i18n-log-ru_0.2-1_all.ipk https://github.com/gSpotx2f/luci-app-log/raw/master/packages/19.07/luci-i18n-log-ru_0.2-1_all.ipk
    opkg install /tmp/luci-i18n-log-ru_0.2-1_all.ipk
    rm /tmp/luci-i18n-log-ru_0.2-1_all.ipk

**Screenshots:**

![](https://github.com/gSpotx2f/luci-app-log/blob/master/screenshots/01.jpg)
![](https://github.com/gSpotx2f/luci-app-log/blob/master/screenshots/02.jpg)
