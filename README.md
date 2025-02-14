# luci-app-log
Advanced syslog and kernel log (tail, search, etc) for LuCI (OpenWrt webUI).

OpenWrt >= 19.07.

Supported LuCI themes: luci-theme-bootstrap, luci-theme-material.

**Installation notes:**

    wget --no-check-certificate -O /tmp/luci-app-log_0.4-3_all.ipk https://github.com/gSpotx2f/luci-app-log/raw/master/packages/19.07/luci-app-log_0.4-3_all.ipk
    opkg install /tmp/luci-app-log_0.4-3_all.ipk
    rm /tmp/luci-app-log_0.4-3_all.ipk
    /etc/init.d/rpcd restart

**i18n-ru:**

    wget --no-check-certificate -O /tmp/luci-i18n-log-ru_0.4-3_all.ipk https://github.com/gSpotx2f/luci-app-log/raw/master/packages/19.07/luci-i18n-log-ru_0.4-3_all.ipk
    opkg install /tmp/luci-i18n-log-ru_0.4-3_all.ipk
    rm /tmp/luci-i18n-log-ru_0.4-3_all.ipk

**Screenshots:**

_Kernel log_

![](https://github.com/gSpotx2f/luci-app-log/blob/master/screenshots/01.jpg)

_System log (logd)_

![](https://github.com/gSpotx2f/luci-app-log/blob/master/screenshots/02.jpg)

_System log (syslog-ng)_

![](https://github.com/gSpotx2f/luci-app-log/blob/master/screenshots/03.jpg)
