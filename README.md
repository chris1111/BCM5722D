BCM5722D
========
Unofficial Mac OS X driver for Broadcom's BCM5722 NetXtreme and NetLink
family of gigabit Ethernet controllers. It is implemented based on the
BCM5722 Programmer's Guide provided in Broadcom's open source developer
resource. Additional information is gleaned from Linux(tg3) and
FreeBSD(if\_bge) driver.

#### This is a Fork of [adlan](https://github.com/adlan/BCM5722D) With Fix from [long1eu](https://github.com/long1eu)

#### Release Compilling in Xcode 4.5.2 Downloads ➤ [Release BCM5722D ](https://github.com/chris1111/BCM5722D/releases/tag/V-2.3.7 )
Support Mac OS X Lion 10.7 to MacOS High Sierra 10.13


### It supports the following models:

* BCM5722
* BCM5754
* BCM5754M
* BCM5755
* BCM5755M
* BCM57788
* BCM5787
* BCM5787M
* BCM5906
* BCM5906M

### supports Device ID 

- pci14e4,165a
- pci14e4,167a
- pci14e4,1672
- pci14e4,167b
- pci14e4,1673
- pci14e4,169b
- pci14e4,1693
- pci14e4,1712
- pci14e4,1713
- pci14e4,1691
- pci14e4,1698
- pci14e4,16b5
- pci14e4,1692
- pci14e4,1600
- pci14e4,1681
- pci14e4,1680


## Method of installation

### Installation (Clover)
### 10.7 to 10.10
- EFI/CLOVER/kexts/Other/IONetworkingFamily.kext/Contents/Plugins

### 10.11 to 10.13
- EFI/CLOVER/kexts/Other

### Installation (S/L/E) with a correct permision
### 10.7 to 10.13
- Install to `/System/Library/Extensions/IONetworkingFamily.kext/Contents/Plugins`


### For a issues ➤ Please report issues here [Issue ](https://github.com/chris1111/BCM5722D/issues)



License
-------
This project is released under the GNU General Public License Version 2. Please
see LICENSE file or <http://www.gnu.org/licenses/gpl-2.0.html> for detailed
license information.

Credits
-------
* [adlan](https://github.com/adlan/BCM5722D) [long1eu](https://github.com/long1eu)

Disclaimer
----------
This driver is neither supported nor endorsed by Broadcom. Use at your own risk.
