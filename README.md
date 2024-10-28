## 自编译lede_openwrt用DL包
使用机型，树莓派3B+ </br>
make menuconfig前三项选择，
![image](https://github.com/user-attachments/assets/cf6a69b1-309d-4ecf-a904-c85565b0111b)

Target Images的内核空间Kernel partition size (in MiB) ,给他差不多1G，以避免编译固件的时候，勾选太多东西，
导致编译出来的固件，烧写到设备上以后，不能读写、保存。
![image](https://github.com/user-attachments/assets/f35107e8-bb0f-4ecc-856d-0fdf8b9f29df)

近期dl包编译时间：2024-10-25
此为较为干净的版本（对于部分人来说，部分依赖库、依赖包没用）


……假装是程序员
