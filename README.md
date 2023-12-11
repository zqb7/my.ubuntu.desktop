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
