# Realme 3 Server Kernel Builder (Docker, BlueZ, ESP32 Serial)

Automated GitHub Actions compilation of Linux 4.14 for Realme 3 (MT6771 / RMX1821 / RMX1825).

Features enabled:
- Docker / Container Namespaces & Virtual Ethernet
- BlueZ Linux Bluetooth sockets (`AF_BLUETOOTH`)
- ESP32 CP210x, CH340, and CDC-ACM USB Serial drivers
- WireGuard VPN
- AnyKernel3 flashable packaging for TWRP
