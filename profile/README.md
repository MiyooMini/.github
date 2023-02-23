<div align="center">
<img src="https://user-images.githubusercontent.com/16083854/146627768-4fc5cb75-90d6-4b52-b490-50500cd72256.png" width="400"><br>
<img src="https://img.shields.io/badge/Current%20Version-v1.6%202022--04--19-green.svg"><br>
<b>Note:</b> Firmware is not open-source, the updates came directly from the manufacturer.<br>Other stuff like front-end, themes, emus and apps still can be modified by the community.
</div>

## Information
- Miyoo Official Updates [(ENG](https://lemiyoo-cn.translate.goog/upgrade/?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en-US) | [CN)](https://lemiyoo.cn/upgrade)
- Miyoo Firmware Updates Backup [(Download)](https://drive.google.com/drive/folders/192KkgJ6rTy5gpYRyPIK4D0_apm8bwVlm?usp=sharing)
- Update Guide [(View)](https://github.com/TriForceX/MiyooCFW/wiki/Miyoo-Mini#firmware-update-guide)
- Miyoo Mini SDK [(Download)](https://github.com/MiyooMini)

## Console Specs
- Sigmastar SSD202D Dual Core Cortex-A7 1.2GHz [(Data Sheet)](https://github.com/linux-chenxing/linux-chenxing.org/blob/master/infinity2/SSD202D_pb_S_v01.pdf)
- 128MB DDR3 RAM
- 16MB ROM (SPI)
- 32GB TF Card storage (up to 128GB)
- 2.8 inch IPS screen 640x480
- Weight 110g
- 3.7V 1900mAh (v1) 2000mAh(v2) 5V/1A Battery
- USB-C Charge only

## Custom OS

Download | Guides | Dev / Port by
:------: | :------: | :------:
[Onion OS](https://github.com/OnionUI/Onion/releases/latest) | [Wiki](https://github.com/OnionUI/Onion/wiki) | [Onion Team](https://github.com/OnionUI)
[Koriki](https://github.com/Rparadise-Team/Koriki) | [Wiki](https://github.com/Rparadise-Team/Koriki/wiki) | [Rparadise Team](https://github.com/Rparadise-Team)
[Mini UI](https://github.com/shauninman/MiniUI/releases/latest) | [Readme](https://github.com/shauninman/MiniUI/tree/main/skeleton) | [shauninman](https://github.com/shauninman/MiniUI)
[Taki SD Card](https://github.com/Takiiiiiiii/Miyoo-Mini) | [Wiki](https://github.com/Takiiiiiiii/Miyoo-Mini/wiki) | [Takiiiiiiii](https://github.com/Takiiiiiiii/Miyoo-Mini)
[Better SD Card](https://github.com/nicosensei/miyoo-mini-better-sd-card/releases/latest) | [Wiki](https://github.com/nicosensei/miyoo-mini-better-sd-card/wiki) | [nicosensei](https://github.com/nicosensei/miyoo-mini-better-sd-card)

## Apps and Homebrew

Download | Dev / Port by
:------: | :------:
[RTC Emulator](https://github.com/lucamadd/MiyooMini-emuRTC/releases/latest) | [lucamadd](https://github.com/lucamadd/MiyooMini-emuRTC)
[GMU Music Player](https://github.com/TechDevangelist/gmu/releases/latest) | [TechDevangelist](https://github.com/TechDevangelist/gmu)
[DinguxCommander](https://github.com/shauninman/DinguxCommander/tree/union-miyoomini) | [shauninman](https://github.com/shauninman/DinguxCommander)
[SDL 2048](https://github.com/MiyooMini/sdl2048/releases/latest) | [miyoo](https://github.com/MiyooMini/sdl2048)
[SDL Pal](https://github.com/MiyooMini/sdlpal/releases/latest) | [miyoo](https://github.com/MiyooMini/sdlpal)

## Others

Download | Description
:------: | :------:
[Language Pack](https://github.com/MiyooMini/language-pack) | Community updates for firmware translation files 

## Firmware Update Guide
**Important Note:** Check the official site before update, sometimes there are extra steps or additional notes.

<details><summary>Install Guide</summary><br>

![miyoo-mini-upgrade](https://user-images.githubusercontent.com/16083854/157445688-7f650b58-12ac-42e0-99cd-620a434f1058.jpg)

</details>

<details><summary>Alternative Guide (Written)</summary><br>

Download latest update direct from Miyoo from official [website](https://lemiyoo.cn/upgrade) or from our [backups](https://drive.google.com/drive/folders/192KkgJ6rTy5gpYRyPIK4D0_apm8bwVlm?usp=sharing)

***NOTE PLEASE READ FIRST*** 
1. use a trustworthy SD card(sandisk, toshiba, etc.)
2. Make sure miyoo283_fw.img was downloaded correctly (file size: 15,134,744 CRC32:814ED165)& MD5 (miyoo283_fw.img) = 32ce41b44cf9d35f4ee9ceae0ba7827d

Additional Tips: Please use a power plug that is not more than 5V, do not upgrade through the computers usb charging, 
copy the firmware files to TF card immediately after upgrading the machine do not flash after playing games, otherwise its easy to lose data AND END UP WITH A brick!:)

***Note: VERY IMPORTANT Remove the battery first then proceed with the upgrade!***
Step 1 Download Miyoo283_fw. Img firmware & the A wild card zip.
Step 2 Copying TF cards connect to a computer through a card reader then copy the downloaded Miyoo283_Fw. img firmware directly to the root directory of the TF card.
Step 3 Upgrading Do not power off during upgrade! You can't press the power button! It turns into bricks!

1. Power off remove the battery
2. Install the TF card back
3. Power on through Type C plug the data cable and enter charging state
4. Do not press the power button. It will enter the firmware upgrade state automatically.
5. The upgrade takes about 2 minutes after the update it will enter a charging state only then remove the cable very important as its still writing to internal NAND.

Step 4 Please delete the Miyoo283_fw. Img firmware copied from the TF card after the upgrade!
Step 5 Copy (first backup your card,you will loose your saved data)Copy APP, Emu, RApp, RetroArch from the wild card folder that you downloaded to the TF card and directly overwrite any files is ask to.```

Additional Tips: Please use a power plug that is not more than 5V, do not upgrade through the computers usb charging, 
copy the firmware files to TF card immediately after upgrading the machine do not start playing games, otherwise its easy to lose data AND END UP WITH A brick! :)

</details>

<details><summary>Change log</summary>

```
v1.6 - 2022-04-19
----------
1. Fix the ticking sound when entering and leaving the game
2. Optimize the battery level icon and charging animation
3. Repair idle mode wake-up freeze and key failure problems
4. Fix TF error reporting problem
5. Open UI font large display option or open font size customization
6. Open theme and background music options
7. Disable R2.L2 in non-game interface

TF card emulator update:
1. Fix the problem that more than 20 games in the collection are stuck
2. After repairing the non-full screen game screen, the loaded ra menu screen appears
3. Fix the automatic frame skipping image, the screen will be enlarged and the screen will flicker
4. Correct the mask, screen display function
5. Correct the custom ratio of ra kernel
6. Fix the flashback when changing the filter
7. Open ra32.ss file advanced options
8. Add native ps simulator to add support for chd format
9. Fix the problem of screen rotation in the kernel
10. Change the game list and preview mode

v1.5 - 2022-01-08
----------
1. Firmware modification Move the UI main program, language, sound effects, and skin to the TF card directory.
2. Support custom theme support, and fix the display inversion problem when changing skins.
3. When charging when the battery is low, the low battery icon overlaps the charging icon.
4. Add UI main program, language, sound effect, skin and other directories, and support custom themes.
   - The miyoo directory is placed in the root directory of the sd card, and the directory contains the main program and all resources.
   - skin: theme image
   - sound: background music/sound effects
   - lang: Multilingual translation
   - MainUI: main program
5. Added LCD color adjustment options. After adjusting the color, all frame rates will be temporarily abnormal and need to be restarted.
6. Fixed the problems of GB battery save, fullscreen/showfps option save, continuous instant save, etc.
7. Modify the native menu key value, A confirms, B returns
8. Fixed the fast-forward problem of RA acceleration setting. Audio fast-forwards mute when OSS is selected, and fast-forward has sound when SDL is selected
9. Fix the display inversion of arcade (KONAMI base version) 

v1.4 - 2021-12-29
----------
1. Fixed popping and noise in the game
2. Fix the recent game and collection records appear empty
3. Correct the battery curve and increase the low battery prompt in the game
4. Add the function of directly deleting game files on the game list 

v1.3 - 2021-12-26
----------
1. Fix the crackling and other noises in the game.
2. Fix the recent clearing of games and favorites
3. Fixed the battery curve and added the low battery hint in the game
4. Added the function of deleting game files directly from the game list
5. Modify RA to adjust display ratio
6. Native GBA speed and sound lag
7. The INTERFACE of RA simulator is set as LR page flipping L/R is 2 ~ 3 lines of original scrolling L2/R2 is 10 lines of original scrolling
8. Fix RA simulator original menu selection golden finger is invalid without Chinese display
9. Fix the vibration problem of PS simulator
10.Fix RA PS kernel not full frame

v1.2 - 2021-12-11
----------
1. Fix the screen upside down
2. Repair the screen overlay
3. Repair sound effects
4. Fix automatic shutdown
5. Increase the collection function
```

</details>

## Developer Resources
The next stuff is some developer logs and useful info. To access the required tools to build apps click [here](https://github.com/MiyooMini)

---

<details><summary>GPIO Log</summary>

```
/ # cat /sys/kernel/debug/gpio                                                  
gpiochip0: GPIOs 0-90, gpio:                                                    
 gpio-1   (                    |GPIO Key Up         ) in  hi                    
 gpio-5   (                    |GPIO Key Right      ) in  hi                    
 gpio-6   (                    |GPIO Key B          ) in  hi                    
 gpio-7   (                    |GPIO Key Y          ) in  hi                    
 gpio-8   (                    |GPIO Key A          ) in  hi                    
 gpio-9   (                    |GPIO Key X          ) in  hi                    
 gpio-10  (                    |GPIO Key START      ) in  hi                    
 gpio-11  (                    |GPIO Key SELECT     ) in  hi                    
 gpio-12  (                    |GPIO Key MENU       ) in  hi                    
 gpio-13  (                    |GPIO Key L          ) in  hi                    
 gpio-14  (                    |GPIO Key L2         ) in  hi                    
 gpio-47  (                    |GPIO Key R2         ) in  hi                    
 gpio-59  (                    |sysfs               ) in  hi                    
 gpio-69  (                    |GPIO Key Down       ) in  hi                    
 gpio-70  (                    |GPIO Key Left       ) in  hi                    
 gpio-72  (                    |                    ) out lo                    
 gpio-86  (                    |GPIO Key POWER      ) in  lo                    
 gpio-90  (                    |GPIO Key R          ) in  hi                    
/ #
```

</details>

<details><summary>Boot Log</summary>

```
IPL g5da0ceb
D-1e
HW Reset
miupll_233MHz
MIU0 zq=0x003b
miu_bw_set
utmi_1_init done
utmi_2_init done
utmi_3_init done
usbpll init done......
cpupll init done
SPI 54M
clk_init done 
P1 USB_rterm trim=0x000d
P1 USB_HS_TX_CURRENT trim=0x000d
P2 USB_rterm trim=0x0000
P2 USB_HS_TX_CURRENT trim=0x0000
P3 USB_rterm trim=0x0000
P3 USB_HS_TX_CURRENT trim=0x0000
PM_vol_bgap trim=0x0003
GCR_SAR_DATA trim=0x0191
ETH 10T output swing trim=0x0011
ETH 100T output swing trim=0x0012
ETH RX input impedance trim=0x0000
ETH TX output impedance trim=0x0001
MIPI_HS_RTERM trim=0x0001
MIPI_LP_RTERM trim=0x0000
128MB
BIST0_0001-OK
Enable MMU and CACHE
Load IPL_CUST from NOR
offset:00010000
Flash:ef4018
GD QE=1
Load time 824 us, 25864 KiB/s
Checksum OK

IPL_CUST g5da0ceb
MXP found at 0x00020000
runUBOOT()
runUBOOT()
[SPI_NOR]
Load time 12906 us, 13277 KiB/s
 -Verify UBOOT CRC32 passed!
 -Decompress UBOOT XZ
  decomp_size=0x00073600
Disable MMU and D-cache before jump to UBOOT�

U-Boot 2015.01 (Nov 20 2021 - 16:56:14)

Version: I2g#######
       Watchdog enabled
I2C:   ready
DRAM:  
WARNING: Caches not enabled
MMC:   MStar SD/MMC: 0
nor_flash_mxp allocated success!!
Flash is detected (0x0709, 0xEF, 0x40, 0x18)
SF: Detected nor0 with total size 16 MiB
MXP found at mxp_offset[4]=0x00020000, size=0x1000
env_offset=0x5F000 env_size=0x1000
Flash is detected (0x0709, 0xEF, 0x40, 0x18)
SF: Detected nor0 with total size 16 MiB
In:    serial
Out:   serial
Err:   serial
========= power adapter 1========
get_dev_hwpart (mmc, 0, 0)
get_dev_hwpart ifname mmc, name usb,reloc_get_dev 23f3aa74, select_hwpart 00000000,mmc_get_dev 23f748ac, mmc_select_hwpart 23f7385c
get_dev_hwpart ifname mmc, name mmc,reloc_get_dev 23f748ac, select_hwpart 23f7385c,mmc_get_dev 23f748ac, mmc_select_hwpart 23f7385c
gpio debug MHal_GPIO_Pad_Set: pin=19
part unspecified1
part_type is 2, part -2
part unspecified2
get_partition_info part 1, ret 0
return part 1
get_device_and_partition(mmc, 0) return 1, fstype=1
probe fstype = 1, info->fstype=1
probe fs_dev_desc = 00000001, info->null_dev_desc_ok=0
reading miyoo283_fw.img
** Unable to read file miyoo283_fw.img **
miyoo283_fw.img not found
========= power key 0========
bootcheck start
fore uup u8KeyPad_KeyVal [0x5a]
BootMode 0
gpio debug MHal_GPIO_Pad_Set: pin=85
        ====   mdrv_gpio_set_high   ====
        ====   mdrv_gpio_get_level   ====
gpio[85] is 1
LOGO in flash offset=0x270000 size=0x20000
Header count 3
Name DISP Sub head sz 56 total sz 1140 node cnt 4
DB Table and setting match.
First offset 884 out buf size 0x300000 out buf addr 0x7c00000 en 1
Total size 1196
Total sz 18440, Node cnt 1
_BootJpdYuvCtrl 1471::  Create Decompress struct
_BootJpdYuvCtrl 1479::  Set memory buffer as source
_BootJpdYuvCtrl 1491::  Read the JPEG header
_BootJpdYuvCtrl 1504::  Initiate JPEG decompression
_BootJpdYuvCtrl 1516::  Image is 640 by 480 with 3 components
_BootJpdYuvCtrl 1528:: BmpBuffer: 0x23d1ee28
_BootJpdYuvCtrl 1541:: Start reading scanlines
_BootJpdYuvCtrl 1551:: Done reading scanlines
_BootJpdYuvCtrl 1556:: End of decompression
_BootLogoYuv444ToYuv420 1195:: 444 To 422, In:23d1ee28, Out:27c00000, Width:640, Height:480
_BootDispCtrl 1655, H(48 4 48 640) V(10 4 10 480) Fps:60
_BootDispCtrl 1734, PnlLink:11
gpio debug MHal_GPIO_Pad_Set: pin=4
        ====   mdrv_gpio_set_high   ====
        ====   mdrv_gpio_get_level   ====
gpio[4] is 1
gpio debug MHal_GPIO_Pad_Set: pin=8
        ====   mdrv_gpio_set_low   ====
        ====   mdrv_gpio_get_level   ====
gpio[8] is 0
Flash is detected (0x0709, 0xEF, 0x40, 0x18)
SF: Detected nor0 with total size 16 MiB
SF: 2097152 bytes @ 0x60000 Read: OK
gpio debug MHal_GPIO_Pad_Set: pin=8
        ====   mdrv_gpio_set_high   ====
        ====   mdrv_gpio_get_level   ====
gpio[8] is 1
##  Booting kernel from Legacy Image at 22000000 ...
   Image Name:   MVX4##I2M#g#######KL_LX409##[BR:
   Image Type:   ARM Linux Kernel Image (lzma compressed)
   Data Size:    1787784 Bytes = 1.7 MiB
   Load Address: 20008000
   Entry Point:  20008000
   Verifying Checksum ... OK
-usb_stop(USB_PORT0)
-usb_stop(USB_PORT1)
-usb_stop(USB_PORT2)
   Uncompressing Kernel Image ... 
[XZ] !!!reserved 0x21000000 length=0x 1000000 for xz!!
   XZ: uncompressed size=0x344000, ret=7
OK
atags:0x20000000

Starting kernel ...

mount: can't find devpts in /etc/fstab
mount: mounting none on /sys failed: Device or resource busy
mount: mounting none on /sys/kernel/debug/ failed: Device or resource busy
chmod: /etc/core.sh: Read-only file system
[1]+  Done                       busybox telnetd
insmod: can't read '/config/modules/4.9.84/cifs.ko': No such file or directory
insmod: can't read '/config/modules/4.9.84/grace.ko': No such file or directory
insmod: can't read '/config/modules/4.9.84/sunrpc.ko': No such file or directory
insmod: can't read '/config/modules/4.9.84/lockd.ko': No such file or directory
insmod: can't read '/config/modules/4.9.84/nfs.ko': No such file or directory
insmod: can't read '/config/modules/4.9.84/nfsv2.ko': No such file or directory
insmod: can't read '/config/modules/4.9.84/usb-common.ko': No such file or directory
insmod: can't read '/config/modules/4.9.84/usbcore.ko': No such file or directory
insmod: can't read '/config/modules/4.9.84/scsi_mod.ko': No such file or directory
insmod: can't read '/config/modules/4.9.84/usbhid.ko': No such file or directory
mknod: /dev/mi_alsa: File exists
mount: mounting /dev/mmcblk0p1 on /mnt/SDCARD failed: Device or resource busy
mount fail!
/ # orig value: 110, fix to: 10
chmod: /usr/bin/notify: No such file or directory
sh: write error: Invalid argument
Ao Param:
AO InPut Path:/customer/app/sound/change.wav
Device:LineOut
Hpf:Disable
Nr:Disable
Agc:Disable
Eq:Disable
Resample:Disable
3067 Start test: MI_SYS_Init()
AUDIO_TEST [3067] MI_SYS_Init()  exec function pass
3067 End test: MI_SYS_Init()
3081 Start test: initAo()
eSamplerate 44100, channel 2
2394 Start test: MI_AO_SetPubAttr(AoDevId, &stAoSetAttr)
AUDIO_TEST [2394] MI_AO_SetPubAttr(AoDevId, &stAoSetAttr)  exec function pass
2394 End test: MI_AO_SetPubAttr(AoDevId, &stAoSetAttr)
2400 Start test: MI_AO_GetPubAttr(AoDevId, &stAoGetAttr)
AUDIO_TEST [2400] MI_AO_GetPubAttr(AoDevId, &stAoGetAttr)  exec function pass
2400 End test: MI_AO_GetPubAttr(AoDevId, &stAoGetAttr)
2406 Start test: MI_AO_Enable(AoDevId)
 _MI_AO_OpenVqeLib: success
 _MI_AO_OpenSrcLib: success
 _MI_AO_OpenG711Lib: success
 _MI_AO_OpenG726Lib: success
AUDIO_TEST [2406] MI_AO_Enable(AoDevId)  exec function pass
2406 End test: MI_AO_Enable(AoDevId)
2412 Start test: MI_AO_EnableChn(AoDevId, AoChn)
AUDIO_TEST [2412] MI_AO_EnableChn(AoDevId, AoChn)  exec function pass
2412 End test: MI_AO_EnableChn(AoDevId, AoChn)
2477 Start test: MI_AO_SetVolume(AoDevId, s32AoVolume)
AUDIO_TEST [2477] MI_AO_SetVolume(AoDevId, s32AoVolume)  exec function pass
2477 End test: MI_AO_SetVolume(AoDevId, s32AoVolume)
2478 Start test: MI_AO_GetVolume(AoDevId, &s32AoGetVolume)
AUDIO_TEST [2478] MI_AO_GetVolume(AoDevId, &s32AoGetVolume)  exec function pass
2478 End test: MI_AO_GetVolume(AoDevId, &s32AoGetVolume)
create ao thread needsize = 4096.
AUDIO_TEST [3081] initAo()  exec function pass
3081 End test: initAo()
play 13840 bytes finished
join Ao thread done.
3110 Start test: deinitAo()
2675 Start test: MI_AO_DisableChn(AoDevId, AoChn)
AUDIO_TEST [2675] MI_AO_DisableChn(AoDevId, AoChn)  exec function pass
2675 End test: MI_AO_DisableChn(AoDevId, AoChn)
2676 Start test: MI_AO_Disable(AoDevId)
AUDIO_TEST [2676] MI_AO_Disable(AoDevId)  exec function pass
2676 End test: MI_AO_Disable(AoDevId)
AUDIO_TEST [3110] deinitAo()  exec function pass
3110 End test: deinitAo()
3114 Start test: MI_SYS_Exit()
AUDIO_TEST [3114] MI_SYS_Exit()  exec function pass
3114 End test: MI_SYS_Exit()
add device 1: /dev/input/event0
  name:     "soc:gpio_keys"
could not get driver version for /dev/input/mice, Inappropriate ioctl for device
open device /dev/input/mice fail
set keymap to L2,L,R2,R,X,A,B,Y
set hibernate to 5
set language en.lang
5147 start
MI_SYS_Init cost 2068.000000ms
7331.000000 driver_name (nil)
7332.000000 FB_CreateDevice GFX_Open return 0
vtpath = /dev/vc/2, fd = -1
vtpath = /dev/tty2, fd = 6
Current VT: 2
7470.000000 FB_VideoInit shadow_fb is 0
init audio 21
7481 ttf inited
read from pwr key file: 0, 0

pluged in: 1, 1

7541 sdl inited
SDL_GetVideoMode 640x480 32 -> 640x480 32
FB_EnterGraphicsMode start
iotcl VT_GETSTATE start
iotcl VT_ACTIVATE start 1
iotcl VT_WAITACTIVE start
iotcl KDGKBMODE start
iotcl KDSKBMODE start 3
iotcl KDSETMODE start
iotcl VT_LOCKSWITCH start
FB_EnterGraphicsMode end
SDL_SetVideoMode publicsurface 0x163658, shadowsurface (nil), videosurface 0x163658
Double buf enabled 0, use SDL_UpdateRect when flip
_gfx_alloc_surface 0x164520, 0xb5a28000, idx 0
FB_AllocHWSurface1 0x1644b0, 0x164520, 0xb5a28000, flags 10001, 640x480, idx 0
7542 screen inited
[InitKeyShm]: create shm fail : File exists, size 52
set keymap to L2,L,R2,R,X,A,B,Y
set hibernate to 5
set language en.lang
sys lang en.lang, path /customer/app/, support multilanguage 1
sfonticon = 0x16f120
_gfx_alloc_surface 0x199b48, 0xb575a000, idx 1
FB_AllocHWSurface1 0x19f0a0, 0x199b48, 0xb575a000, flags 10001, 640x480, idx 1
_gfx_alloc_surface 0x19f138, 0xb6f51000, idx 2
FB_AllocHWSurface1 0x19eff8, 0x19f138, 0xb6f51000, flags 10001, 640x4, idx 2
_gfx_alloc_surface 0x19f278, 0xb6f4e000, idx 3
FB_AllocHWSurface1 0x19f208, 0x19f278, 0xb6f4e000, flags 10001, 640x4, idx 3
SStar_CheckHWBlit
SStar_CheckHWBlit
FB_FreeHWSurface 0x19eff8, 0x19f138, 0xb6f51000
_gfx_free_surface 0x19f138 , 0xb6f51000
_gfx_alloc_surface 0x19f138, 0xb6f52000, idx 4
FB_AllocHWSurface1 0x19f160, 0x19f138, 0xb6f52000, flags 10001, 4x360, idx 4
_gfx_alloc_surface 0x199c08, 0xb59b1000, idx 5
FB_AllocHWSurface1 0x199b98, 0x199c08, 0xb59b1000, flags 10001, 4x360, idx 5
SStar_CheckHWBlit
SStar_CheckHWBlit
FB_FreeHWSurface 0x19f160, 0x19f138, 0xb6f52000
_gfx_free_surface 0x19f138 , 0xb6f52000
open stat_bg fail: Couldn't open /customer/app/skin/nav-bar-item-bg.png
   src format: flags 10000 bpp 32 loss(0, 0, 0, 0) shift(0, 8, 16, 24) mask(ff, ff00, ff0000, ff000000)
target format: flags 10000 bpp 32 loss(0, 0, 0, 0) shift(0, 8, 16, 24) mask(ff, ff00, ff0000, ff000000)
_gfx_alloc_surface 0x19a6c8, 0xb598b000, idx 6
FB_AllocHWSurface1 0x19eff8, 0x19a6c8, 0xb598b000, flags 10001, 640x60, idx 6
_gfx_alloc_surface 0x19a418, 0xb593f000, idx 7
FB_AllocHWSurface1 0x19a3a8, 0x19a418, 0xb593f000, flags 10001, 640x60, idx 7
SStar_CheckHWBlit
SStar_CheckHWBlit
FB_FreeHWSurface 0x19eff8, 0x19a6c8, 0xb598b000
_gfx_free_surface 0x19a6c8 , 0xb598b000
_gfx_alloc_surface 0x19a6c8, 0xb598b000, idx 8
FB_AllocHWSurface1 0x19a300, 0x19a6c8, 0xb598b000, flags 10001, 640x60, idx 8
_gfx_alloc_surface 0x19a4e8, 0xb5965000, idx 9
FB_AllocHWSurface1 0x19a478, 0x19a4e8, 0xb5965000, flags 10001, 640x60, idx 9
SStar_CheckHWBlit
SStar_CheckHWBlit
FB_FreeHWSurface 0x19a300, 0x19a6c8, 0xb598b000
_gfx_free_surface 0x19a6c8 , 0xb598b000
Load Music /customer/app/sound/change.wav
load music /customer/app/sound/change.wav fail: Audio device hasn't been opened
Load Music /etc/enter.wav
load music /etc/enter.wav fail: Couldn't open /etc/enter.wav
Load Music /customer/app/sound/bgm.mp3
_gfx_alloc_surface 0x19e210, 0xb5997000, idx 10
FB_AllocHWSurface1 0x19aa78, 0x19e210, 0xb5997000, flags 10001, 154x170, idx 10
_gfx_alloc_surface 0x19e2e0, 0xb5925000, idx 11
FB_AllocHWSurface1 0x19e270, 0x19e2e0, 0xb5925000, flags 10001, 154x170, idx 11
SStar_CheckHWBlit
SStar_CheckHWBlit
FB_FreeHWSurface 0x19aa78, 0x19e210, 0xb5997000
_gfx_free_surface 0x19e210 , 0xb5997000
_gfx_alloc_surface 0x19aa50, 0xb5997000, idx 12
FB_AllocHWSurface1 0x19aa78, 0x19aa50, 0xb5997000, flags 10001, 155x170, idx 12
_gfx_alloc_surface 0x19e3b0, 0xb590b000, idx 13
FB_AllocHWSurface1 0x19e340, 0x19e3b0, 0xb590b000, flags 10001, 155x170, idx 13
SStar_CheckHWBlit
SStar_CheckHWBlit
FB_FreeHWSurface 0x19aa78, 0x19aa50, 0xb5997000
_gfx_free_surface 0x19aa50 , 0xb5997000
_gfx_alloc_surface 0x19e210, 0xb5997000, idx 14
FB_AllocHWSurface1 0x19aa78, 0x19e210, 0xb5997000, flags 10001, 214x120, idx 14
_gfx_alloc_surface 0x19ede0, 0xb58f1000, idx 15
FB_AllocHWSurface1 0x19ed70, 0x19ede0, 0xb58f1000, flags 10001, 214x120, idx 15
SStar_CheckHWBlit
FB_FreeHWSurface 0x19aa78, 0x19e210, 0xb5997000
_gfx_free_surface 0x19e210 , 0xb5997000
load font height is 29
cp: can't stat '/usr/trimui/res/licenses/mame/COPYING': No such file or directory
cp: can't stat '/usr/trimui/res/licenses/mame/COPYING': No such file or directory
cp: can't stat '/usr/trimui/res/licenses/fceux/COPYING': No such file or directory
cp: can't stat '/usr/trimui/res/licenses/gamebatte/COPYING': No such file or directory
cp: can't stat '/usr/trimui/res/licenses/picodrive/COPYING': No such file or directory
cp: can't stat '/usr/trimui/res/licenses/gPsp/COPYING.DOC': No such file or directory
cp: can't stat '/usr/trimui/res/licenses/temper/COPYING': No such file or directory
read lang file /customer/app/lang/en.lang ok=1
genShortLangFile en.lang index 0, size 1
read lang file /customer/app/lang/ch.lang ok=1
add language 1 ch.lang to 1. example RA模拟��������
genShortLangFile ch.lang index 1, size 2
read lang file /customer/app/lang/cht.lang ok=1
add language 2 cht.lang to 2. example �復�古�遊�戲
genShortLangFile cht.lang index 2, size 3
read lang file /customer/app/lang/es.lang ok=1
add language 3 es.lang to 3. example RetroArch
genShortLangFile es.lang index 3, size 4
read lang file /customer/app/lang/ja.lang ok=1
add language 4 ja.lang to 4. example RetroArch
genShortLangFile ja.lang index 4, size 5
read lang file /customer/app/lang/ko.lang ok=1
add language 5 ko.lang to 5. example �복�고�놀�이
genShortLangFile ko.lang index 5, size 6
read lang file /customer/app/lang/pt.lang ok=1
add language 6 pt.lang to 6. example RetroArch
genShortLangFile pt.lang index 6, size 7
8588 charging
SStar_CheckHWBlit

/ # uname -a
Linux (none) 4.9.84 #573 SMP PREEMPT Sat Nov 20 16:56:19 CST 2021 armv7l GNU/Linux
/ # 
```

</details>

<details><summary>U-Boot Env</summary>

```
SigmaStar # printenv 
SdUpgradeImage=miyoo283_fw.img
baudrate=115200
bootargs=console=ttyS0,115200 root=/dev/mtdblock4 rootfstype=squashfs ro init=/linuxrc LX_MEM=0x7f00000 mma_heap=mma_heap_name0,miu=0,sz=0x1500000 mma_memblock_remove=1 highres=off mmap_r0
bootcmd=gpio output 85 1; bootlogo 0 0 0 0 0; gpio output 4 1; mw 1f001cc0 11; gpio out 8 0; sf probe 0;sf read 0x22000000 ${sf_kernel_start} ${sf_kernel_size}; gpio out 8 1; bootm 0x22000
bootdelay=0
cpu_part_start=14270000
dispout=K101_IM2BVL
ethact=sstar_emac
ethaddr=00:30:1b:ba:02:db
filesize=be44
miyoo_upgrade=gpio output 4 1; bootlogo 1 0 0 0 0;sdstar;
miyoo_version=202111201656
sdfw_version=202110071805
sf_kernel_size=200000
sf_kernel_start=60000
sf_part_size=20000
sf_part_start=270000
stderr=serial
stdin=serial
stdout=serial
usb_folder=images

Environment size: 913/4092 bytes
```

</details>

<details><summary>PCB Pictures</summary>

Thanks to Rhith08#0737
![miyoo-pcb](https://i.imgur.com/vhWpPWw.jpeg)
![miyoo-pcb](https://i.imgur.com/8BugRdc.jpeg)
![miyoo-pcb](https://i.imgur.com/UY9NTEp.jpeg)
![miyoo-pcb](https://i.imgur.com/m0GSf4J.jpeg)
![miyoo-pcb](https://i.imgur.com/onNoe3G.jpeg)
![miyoo-pcb](https://i.imgur.com/dv2Kj8J.jpeg)
![miyoo-pcb](https://i.imgur.com/f0dTpgt.jpeg)
![miyoo-pcb](https://i.imgur.com/Gee9HwO.jpeg)
![miyoo-pcb](https://i.imgur.com/VywmN3J.jpeg)
![miyoo-pcb](https://i.imgur.com/RBiSDaz.jpeg)
![miyoo-pcb](https://i.imgur.com/GoRMod2.jpeg)

</details>
