# OpenCore-EFI-for-MSI-MPG-X570-Gaming-Plus
 
## EFI for Opencore，Support MacOS 10.15.2,i don't know if it works with other version

### BIOS Setting
+ Secure Boot -> Disable 
+ Serial Port -> Disable
+ XHCI Hand-off -> Enable
+ Legacy USB Support -> Enable
+ Boot mode select -> UEFI
 
### Specs
+ AMD Ryzen 7 3700x
+ XFX RX Vega64 Liq
+ MSI MPG X570 Gaming Plus
+ Asgard DDR4 2666 32G * 4
+ USB Bluetooth BCM 20702 (VID_0A5C&PID_215C)
+ NO Wireless,Bt maybe suitable for DW 1560A
+ ACER XV273K 4K Display

---
### Works
+ Lan
+ Bluetooth
+ USB 3.0 & USB 2.0 Port
+ Video Card

---
### Not Works
+ Sleep
+ Power button
+ Boot Disk Select

---
### Don't Know
+ iMessage
+ Facetime
+ Sidecar

---
## You should change you owen code
+ SmUUID
+ Board Serial Number 
+ MLB 
+ ROM 
these can be generate with clover
