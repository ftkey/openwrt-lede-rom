## 插件：

MINI
```
如果出现WIFI不工作。
vi /etc/rc.local
nohup sleep 60 && /sbin/wifi up &

echo "nohup sleep 60 && /sbin/wifi up & \n exit 0" > /etc/rc.local
```

```
CONFIG_TARGET_ramips=y
CONFIG_TARGET_ramips_mt7620=y
CONFIG_TARGET_ramips_mt7620_DEVICE_xiaomi_miwifi-mini=y

CONFIG_PACKAGE_luci-app-ssr-plus_INCLUDE_V2ray=y
CONFIG_PACKAGE_luci-app-ssr-plus_INCLUDE_V2ray_plugin=y

CONFIG_PACKAGE_luci-app-wrtbwmon=y
CONFIG_PACKAGE_luci-i18n-wrtbwmon-zh-cn=y
CONFIG_PACKAGE_luci-theme-darkmatter=y
CONFIG_PACKAGE_openssh-sftp-server=y
CONFIG_PACKAGE_v2ray=y
CONFIG_PACKAGE_v2ray-plugin=y

CONFIG_V2RAY_COMPRESS_GOPROXY=y
CONFIG_V2RAY_COMPRESS_UPX=y
CONFIG_V2RAY_DISABLE_NONE=y
CONFIG_V2RAY_EXCLUDE_ASSETS=y
CONFIG_V2RAY_EXCLUDE_V2CTL=y
CONFIG_V2RAY_JSON_INTERNAL=y



CONFIG_PACKAGE_etherwake=n
CONFIG_PACKAGE_luci-app-accesscontrol=n
CONFIG_PACKAGE_luci-app-ddns=n
CONFIG_PACKAGE_luci-app-filetransfer=n
CONFIG_PACKAGE_luci-app-ramfree=n
CONFIG_PACKAGE_luci-app-rclone_INCLUDE_fuse-utils=n
CONFIG_PACKAGE_luci-app-rclone_INCLUDE_rclone-ng=n
CONFIG_PACKAGE_luci-app-rclone_INCLUDE_rclone-webui=n

CONFIG_PACKAGE_luci-app-unblockmusic=n
CONFIG_PACKAGE_luci-app-vlmcsd=n
CONFIG_PACKAGE_luci-app-vsftpd=n
CONFIG_PACKAGE_luci-app-webadmin=n
CONFIG_PACKAGE_luci-app-wol=n

CONFIG_PACKAGE_luci-lib-fs=n

CONFIG_PACKAGE_vlmcsd=n
CONFIG_PACKAGE_vsftpd-alt=n
CONFIG_PACKAGE_wol=n
```

K2P MINI 都使用MTK闭源驱动

192.168.1.1
root password
