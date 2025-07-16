# Galaxy A13 4G (MTK) touchGrassKernel

> [!NOTE]
> Feel free to FORK or create PR.

> [!NOTE]
> Make sure you have build tools/packages installed, else it won't compile properly.

## Looking for linux readme?
- [Click here](https://github.com/micr0softstore/samsung_kernel_a13ve/blob/enforcing-u8/README)

## To compile:
- $ git clone --depth=1 https://github.com/micr0softstore/samsung_kernel_a13ve -b enforcing-u8
- $ cd samsung_kernel_a13ve
- $ sudo bash build_kernel.sh

## Download:
[LATEST] Release v0.2 Alpha:
https://creascola.github.io/creacloud/share/?file=touchgrasskernel_v0.2_alpha_a13ve.zip

Changelogs:
v0.4
 - upstreamed sdfat to 2.8.1 to fix SDcard on oneui 7, commit by Extreme XT
v0.3
- turned off kbrobes as we had issues with it on 4.x kernel
- added manual hooks for ksu
- added erofs
  
v0.2:
- turned on kprobes

### Features
- Bootable upto OneUI7
- Dex TouchPad [SEC_TOUCHPAD] (Not yet)
- KernelSU-Next
- erofs
- Maybe more in future

### About kernel:
- Got some commits from others like:
  - bpf commit from: t.me/nnhglong
  - sdfs upstream commit by Extreme XT
- Tested on: Binary 8
- telegram channel on: t.me/a13vedev
- Discussion on: https://t.me/a13mtkdiscuss
