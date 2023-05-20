# qemu 在线安装脚本
由于编译 Qemu 太麻烦，所以写了个脚本

使用 root 权限执行以下命令

```bash
git clone https://github.com/Menhera062/qemu-src-installer.git
cd qemu-src-installer
chmod 755 install_qemu.sh
python ./install_qemu.py
# 或者
sudo python ./install_qemu.py
```

