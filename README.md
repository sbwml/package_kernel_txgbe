# kmod-txgbe

## WangXun(R) 10GbE PCI Express ethernet driver for OpenWrt

## How to build

- Enter in your openwrt dir

- Get Source & building
  
  ```shell
  git clone https://github.com/sbwml/package_kernel_txgbe package/kernel/txgbe
  make menuconfig # choose Kernel modules -> Network Devices -> kmod-txgbe
  make package/kernel/txgbe/compile V=s
  ```
  
