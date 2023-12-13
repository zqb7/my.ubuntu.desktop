# my.ubuntu.desktop
> version=23.10

### 设置交换分区大小
```
# 设置大小为32G
sudo swapoff -v /swap.img
sudo fallocate -l 32G /swap.img
sudo mkswap /swap.img
sudo swapon
```
### flameshot截图
```
sudo apt install flameshot
```
```
配置快捷键时，有bug无法截图，需要编写一个脚本使其快捷键执行该脚本
#!/bin/env bash
flameshot gui
```
