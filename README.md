# qemu 在线安装脚本
使用 root 权限执行以下命令
```bash
git clone https://github.com/Menhera062/qemu-src-installer.git
cd qemu-src-installer
chmod 755 install_qemu.sh
./install_qemu.sh
# 或者
sudo ./install_qemu.sh
```

## 实现原理
安装 Aria2 


然后下载源码


自动安装依赖（会将镜像源替换为清华源，安装结束后再更换为原先配置的镜像源，如果没有替换成功，请在）
