# TWRP device tree for Samsung A7 2017 aka a7y17lte
Kernel source available at 
https://github.com/corsicanu/twrp_android_kernel_samsung_universal7880
```
export CROSS_COMPILE=../toolchains/aarch64-linux-android-4.9/bin/aarch64-linux-android-
make clean

export ARCH=arm64
export ANDROID_MAJOR_VERSION=o
export LOCALVERSION=-twrp

make ARCH=arm64 a7y17lte_defconfig
make ARCH=arm64 -j128
```
