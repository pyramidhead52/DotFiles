# DotFiles
<b>Distro:</b> Void

<b>Hardware:</b> Huawei MateBook D 14 AMD Ryzen 5 3500u

# Live installer keyboard layout
loadkeys trq

# Live installer brightness fix
<code>vi /sys/class/backlight/*/brightness</code>

102

# Live installer WiFi fix
<code>ln -s /etc/sv/wpa_supplicant /etc/runit/runsvdir/default/</code>
