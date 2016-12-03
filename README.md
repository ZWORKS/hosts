# hosts

打开我对世界的窗口





**修改hosts后生效的方法**：
**Windows**
在CMD窗口输入

### ipconfig /flushdns



Linux
终端输入

### sudo rcnscd restart

对于systemd发行版，请使用命令
sudo systemctl restart NetworkManager





Mac OS X
终端输入

### sudo killall -HUP mDNSResponder



Android
开启飞行模式 -> 关闭飞行模式

