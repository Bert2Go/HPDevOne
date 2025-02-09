# HP Dev One Guide

![HP Dev One Image](/assets/images/20220910-hp-dev-one.png)

**This Guide is available at:** [Website](https://hpdevone.bert2go.com/), [GitHub](https://github.com/Bert2Go/HPDevOne)

## Table of Contents

- [Status](/topics/status.md)
- [Coupon Code](#coupon-code)
- [Shipping Information](#shipping-information)
- [First Steps After Installing Pop!_OS](#first-steps-after-installing-pop_os)
  - [Changing DNS Server Settings](#changing-dns-server-settings)
    - [Cloudflare Public DNS Server](#cloudflare-public-dns-server)
- [Technical Specs](#technical-specs)
- [BIOS Settings](#bios-settings)
  - [Configuration](#configuration)
    - [Adaptive Battery Optimizer](#adaptive-battery-optimizer)  
- [Upgrade Options](#upgrade-options)
  - [Memory](#memory)
    - [32GB Kits](#32gb-kit)
    - [64GB Kits](#64gb-kit)
  - [Solid State Drives](#solid-state-drives)
    - [4TB](#4tb)
  - [Wi-Fi Card](#wi-fi-card)
    - [Wi-Fi 6](#wi-fi-6)
- [External Devices](#external-devices)
  - [Monitors](#monitors)
  - [Hubs](#hubs)
- [Accessories](#accessories)
  - [Chargers](#chargers)
  - [Batteries](#batteries)
  - [Adapters](#adapters)
- [Function Keys Explained](#function-keys-explained)
- [Videos](#videos)
  - [Removing and Replacing Parts](#removing-and-replacing-parts)
  - [Series of Videos about the HP Dev One](#series-of-videos-about-the-hp-dev-one)
- [Pros and Cons](#pros-and-cons)
- [Using Other Linux Distributions](#using-other-linux-distributions)
  - [Arch Linux](#arch-linux)
  - [NixOS](#nixos)
- [Performance](#performance)
  - [Geekbench 5](#geekbench-5)
- [Support and Connect Information](#support-and-connect-information)
  - [Known Issues](#known-issues)
  - [HP](#hp)
  - [Pop!_OS and System76](#pop_os-and-system76)
- [Questions & Answers](#question--answers)
- [Useful Links](#useful-links)
- [Contributors](#contributors)
- [Supporters](#supporters)
- [Disclaimer](#disclaimer)
- [Connect/Follow Me](#connectfollow-me)
- [About this HP Dev One Guide](#about-this-hp-dev-one-guide)
- [Contact](#contact-form)
- [Buy Me A Coffee](#buy-me-a-coffee)

## Coupon Code

**Currently Active Coupon Code(s)**

No coupons available.

**Expired Coupon Codes**

~~Use Coupon Code **` TAKE220 `** through 1/30/2023 to take **$220** off the HP Dev One on their [website](https://hpdevone.com) !!!~~ Contributor: [u/IPorkyChop](https://www.reddit.com/r/System76/comments/yt8z2i/comment/j0mjtip/?utm_source=share&utm_medium=web2x&context=3)

~~Use Coupon Code **` DEV200 `** throgh 12/6/2022 to take **$200** off the HP Dev One on their [website](https://hpdevone.com) !!!~~ Contributor: [u/IPorkyChop](https://www.reddit.com/r/System76/comments/yt8z2i/comment/iwrx2gq/?utm_source=share&utm_medium=web2x&context=3)

~~Use Coupon Code **` TAKE110 `** throgh 11/17/2022 to take **$110** off the HP Dev One on their [website](https://hpdevone.com) !!!~~ Contributor: [u/pailaway](https://www.reddit.com/r/System76/comments/yool02/comment/ivuy3cq/?utm_source=share&utm_medium=web2x&context=3)

~~Use Code **` LAUNCH285 `** or **` LAUNCH142 `** to get the **keyboard for free**!~~ Contributor [davidskeck](https://github.com/Bert2Go/HPDevOne/issues/9)

~~Use Code **` CODE89 `** at checkout to get $89 off!~~

~~Use Code **` HP89 `** at checkout to get $89 off!~~ Contributor [bad_ingots](https://www.reddit.com/r/linuxhardware/comments/vujx95/hp_dev_one_coupon/?utm_source=share&utm_medium=web2x&context=3)

## Shipping Information

- **FedEx** delivered my laptop. Delivery time is **1-2 business days**.
- People are reporting that HP doesn't ship this laptop to Canada. That said it appears HP ships this laptop only within the USA at this point of time.

## First Steps after installing Pop!_OS

### Automatic Screen Brightness

#### Toggle Automatic Screen Brightness

Automatic screen brightness adjusts the displays screen brightness based on the surrounding light. If it is light where you sit, then the screen brightness goes up, if it is darker, the screen brightnes goes down. By default this feature is turned `ON`.

To toggle automatic screen brightness ON/OFF in Pop_OS! using the following steps:

##### Steps:

1. Open **Settings**
2. Select **Power**
3. Toggle **Automatic Screen Brightness**

### Changing DNS Server Settings

DNS servers translate the friendly domain name you enter into a browser (like bert2go.com) into the public IP address that's needed for your device to actually communicate with that site.

Your ISP automatically assigns DNS servers when your smartphone or router connects to the internet, but you don't have to use those. For a lot of reasons, you might want to try alternative ones, privacy and speed are two big wins you could see from switching.

#### Cloudflare Public DNS Server

"[Cloudflare](https://www.cloudflare.com/) will **never log your IP address**, **never sell your data**, and **never use your data to target ads**".

**Steps:**

1. Open Settings
2. Select **Wi-Fi**
3. Click the **Cog Icon** for the Wi-Fi Connection you want to use
4. Click on the **IPv4 Tab**
5. Disable the **Automatic toggle for DNS**
6. In the **input field below DNS** enter:  
    ```
    1.1.1.1, 1.0.0.1
    ```
7. Click on the **IPv6 Tab**
8. Disable the **Automatic toggle for DNS**
9. In the **input field  below DNS** enter:
    ```
    2606:4700:4700::1111, 2606:4700:4700::1001
    ```
10. Click the **Apply Button** to save yoiur changes, and you are Done!

## Technical Specs

| Hardsware | Detail | Additional Information |
| :--- | :--- | :--- |
| Operating System | Linux Pop!_OS 22.04 LTS ||
| Processor Family | AMD Ryzen™ 7 processor ||
| Processor | AMD Ryzen™ 7 PRO 5850U processor¹ <br> 8 CPU Cores, 16 Threads <br> 4.4GHz Max. Boost Clock³ <br> 1.9GHz Base Clock⁴ <br> L3 Cache 16MB | With integrated GPU |
| Available Graphics | Integrated: AMD Radeon™ Graphics (Support HW decode, DX12, HDMI 2.0 and HDCP 2.2) |  |
| Display Size (diagonal) | 14" |  |
| Display | 14" diagonal FHD display with HD Webcam (1920x1080) (1000 nits) | Display is glossy, this is a privacy screen |
| Memory | 16 GB (2x8 GB) DDR4 3200 MT/s | Max memory is 64 GB (2x32 GB) |
| Memory Slots | 2 SODIMM⁵ ||
| Internal Storage | 1 TB PCIe® 3x4 NVMe™ M.2 2280 SSD² | Max 4 TB |
| Audio | Dual stereo speakers, 2 multi-array microphone |  |
| Ports and Connectors | 2 SuperSpeed USB Type-C® 10Gbps signaling rate (USB Power Delivery, DisplayPort™ 1.4) <br> 2 SuperSpeed USB Type-A 5Gbps signaling rate (1 charging) <br> 1 headphone/microphone combo <br> 1 HDMI 2.0 <br> 1 AC power | HDMI cable sold separately |
| Available Keyboards | Dual Point Backlit spill-resistant Premium Keyboard⁷ | Notebook keyboard IS backlit! <br> No NFC, no Fingerprint reader |
| Available Pointing Devices | Glass clickpad with gesture support as default, touchpad |  |
| Sensors | Hall sensor |  |
| Ambient Light Sensor | Ambient light sensor | Can be turned off through Pop!_OS |
| Wireless Connectivity | Realtek RTL8822CE 802.11a/b/g/n/ac (2x2) Wi-Fi® and Bluetooth® 5 combo¹⁵ | 802.11ac (Wi-Fi 5) |
| Camera | 720p HD camera |  |
| Software | Pop!_OS with HP added features and support <br> LibreOffice Suite <br> Productivity Apps <br> Media Player <br> Application Store |  |
| Software Support | HP Support integrated into Pop!_OS <br> HP Expert Technical Support¹⁶ |  |
| Security Management | Full Disk Encryption |  |
| Battery Type | HP Long Life 3-cell, 53 Wh Li-ion¹⁷ |  |
| Power Supply | HP Smart 65 W External AC power adapter¹⁸ |  |
| Color | Mineral Silver |  |
| Dimensions | Imperial: 12.73 x 8.44 x 0.75 in <br> Metric: 32.34 x 21.46 x 1.91 cm |  |
| Weight | 3.24 lb |  |
| Energy Efficiency Compliance | ENERGY STAR® certified <br> EPEAT® registered where applicable. EPEAT ® registration varies by country. See [www.epeat.net](https://www.epeat.net/) for registration status by country. |  |
| Sustainable Impact Specifications | 5% Ocean-bound plastic in speaker enclosure <br> 45% post-consumer recycled plastic¹⁹ <br> Low Halogen <br> Bulk packaging available <br> Outside box and corrugated cushions are 100% sustainably sourced and recyclable²⁰ <br> TCO 9.0 certified |  |
| Warranty | HP Dev One 1 year of parts <br> 1 year of labor <br> no onsite coverage limited warranty <br> (1/1/0 warranty) | Standard one-year limited warranty covers repairs or replacement of parts that are deemed defective <br> Onsite service is not included |

<sub>¹ Multicore is designed to improve the performance of certain software products. Not all customers or software applications will necessarily benefit from the use of this technology. Performance and clock frequency will vary depending on application workload and your hardware and software configurations. AMD’s numbering is not a measurement of clock speed.  
² For storage drives, TB - 1 trillion bytes. Actual formatted capacity is less. Up to 4.7 GB is not user-accessible.  
³ AMD Max Boost frequency performance varies depending on hardware, software, and overall system configuration.  
⁴ Processor speed denotes maximum performance mode; processors will run at lower speeds in battery optimization mode.  
⁵ Due to the non-industry standard nature of some third-party memory modules, we recommend HP branded memory to ensure compatibility. If you mix memory speeds, the system will perform at the lower memory speed.  
⁶ Pop!_Shop requires internet access, some apps may require purchase.  
⁷ Backlit keyboard is an optional feature.  
⁸ Battery life tested by HP running text editing, web browsing with Google Chrome browser in full screen display, and local video at FHD (1080p) H264 24fps MP4 video playback with player audio set for 100% output and system speaker set for 16% volume, 150 nits brightness with Ambient Light Sensor disabled and entire system setup in ~70 degrees Fahrenheit room temperature condition. Battery life will vary depending on various factors including product model, configuration, loaded applications, features, use, wireless functionality, and power management settings. The maximum capacity of the battery will naturally decrease with time and usage.  
⁹ Cover glass reduces the perceived brightness by approximately 20%.  
¹⁰ Internet access and collaboration software are required and sold separately.  
¹¹ Actual battery life will vary with use and environmental conditions, and will naturally decrease with time and usage.  
¹² List of apps: SolidWorks, Windows Office, Sketchup, Adobe, AutoCAD, Tili-Click.  
¹³ Battery life based on 5 day week, 8 hours per day. Actual battery life will vary with use and environmental conditions, and will naturally decrease with time and usage.  
¹⁴ Tested on the glass less than 4mm thickness.  
¹⁵ Wireless access point and internet service required and sold separately. Availability of public wireless access points limited. Wi-Fi 5 (802.11 AC) is backwards compatible with prior 802.11 specs.  
¹⁶ Ticketing Support is only offered in the United States. Cross-border support is not offered. Support is available Monday to Saturday, 5am to 5pm Pacific Standard Time (Monday to Friday 8:30am - 5pm MST for order inquiry support). Sundays and holidays are non-operational hours and inquiries will be responded to as soon as possible on the next business day.  
¹⁷ Actual battery Watt-hours (Wh) will vary from design capacity. Battery capacity will naturally decrease with shelf life, time, usage, environment, temperature, system configuration, loaded apps, features, power management settings, and other factors.  
¹⁸ HP Fast Charge charges up to 50% within 30 minutes when the system is off or in standby mode. Power adapter with a minimum capacity of 65 watts is required. After charging has reached 50% capacity, charging will return to normal. Charging time may vary +/-10% due to System tolerance.  
¹⁹ Recycled plastic content percentage is based on the definition set in the IEEE 1680.1-2018 EPEAT standard.  
²⁰ 100% outer box packaging made from sustainably sourced, certified, and recycled fibers. Fiber cushions made from 100% recycled wood fiber and organic material. Any plastic cushions are made from > 90% recycled plastic.  
²¹ Delivery within 24 hours applies to orders shipping to the continental United States. Additional shipping time is required for orders shipping outside of the continental US.*</sub>

## BIOS Settings

You can enter the BIOS using the following methods right after turning on the HP Dev One:

- Repeatedly push the <kbd>Esc</kbd> until you are presented with a text menu from which you can select the BIOS option to enter the BIOS
- Repeatedly push the <kbd>F10</kbd> button until the BIOS shows up.

*Note: If the computer asks for your partition/drive password (if you set it up) or shows your login screen, then you missed the window to trigger the BIOS using the methods mentioned above.*

### Configuration

- #### Adaptive Battery Optimizer  
  It is a technology developed by HP to prolong the battery life of a laptop. There is no option to set the battery percentage limit/s within the BIOS.
  Adaptive Battery Optimizer monitors various battery parameters, including:
  - battery temperature
  - battery-charging status
  - usage patterns

  When Adaptive Battery Optimizer detects certain conditions, protective measures are activated to minimize premature battery wear. While it is activated, the battery run time may be slightly reduced.  
  HP recommends leaving Adaptive Battery Optimizer enabled to ensure that you get the maximum possible lifespan out of your battery, but it can be disabled at any time. Disabling turns off any protective measures that were implemented and immediately restores any run time that was lost.

  _Note: Disabling Adaptive Battery Optimizer does not affect the battery warranty in any way._ Contributor [afsilva](https://github.com/Bert2Go/HPDevOne/issues/8#issue-1397005852)

- #### Keyboard Backlight Timeout  

  This is where you control to duration of the keyboard backlight before it turns off. There are quite a few people asking if it is possible to keep the keyboard backlight on all the time, and the answer is yes! Simply select 'never' from the the Keyboard Backlight Timeout options available.

## Upgrade Options

### Memory

- #### 32GB Kit

  - **Teamgroup** Elite DDR4 **32GB Kit** (2x16GB) 3200MHZ PC4-25600 CL22 Unbuffered Non-ECC 1.2V SODIMM 260-Pin  
Where to buy: [Newegg](https://www.newegg.com/team-32gb-260-pin-ddr4-so-dimm/p/N82E16820331504), [Walmart](https://www.walmart.com/ip/Team-TED432G3200C22DC-S01-Elite-2-x-16GB-260-Pin-DDR4-SO-DIMM-DDR4-3200-Laptop-Memory-Model/252223474), [Amazon](https://www.amazon.com/TEAMGROUP-PC4-25600-Unbuffered-Notebook-Computer/dp/B08T17RQ87)

  - **Crucial** **32GB Kit** (2x16GB) 260-Pin DDR4 SO-DIMM DDR4 3200 (PC4 25600) Laptop Memory Model CT2K16G4SFD832A  
  Where to buy: [Newegg](https://www.newegg.com/crucial-32gb-260-pin-ddr4-so-dimm/p/20-156-220)
  
  - **G.SKILL** Ripjaws Series DDR4 (Model F4-3200C22D-32GRS) **32GB Kit** (2x16GB) 3200MHZ PC4-25600 CL22 SO-DIMM 260-Pin  
  Where to buy: [Newegg](https://www.newegg.com/g-skill-32gb-260-pin-ddr4-so-dimm/p/N82E16820374024)

- #### 64GB Kit

  - **Teamgroup** Elite DDR4 **64GB Kit** (2x32GB) 3200MHZ PC4-25600 CL22 Unbuffered Non-ECC 1.2V SODIMM 260-Pin  
  Where to buy: [Newegg](https://www.newegg.com/team-64gb-260-pin-ddr4-so-dimm/p/N82E16820331505), [Walmart](https://www.walmart.com/ip/Team-Group-Inc-TED464G3200C22DC-S01-Nbm-2-32g-team-Ted464g3200c22dc-s01/844902433), [Amazon](https://www.amazon.com/TEAMGROUP-PC4-25600-Unbuffered-Notebook-Computer/dp/B08TQBY2NR)

  - **Crucial** **64GB Kit** (32GBx2) DDR4 3200 MT/s CL22 SODIMM 260-Pin Memory - CT2K32G4SFD832A  
  Where to buy: [Newegg](https://www.newegg.com/crucial-64gb-260-pin-ddr4-so-dimm/p/20-156-242) [Crucial](https://www.crucial.com/memory/ddr4/ct2k32g4sfd832a)

  - **G.SKILL** Ripjaws Series DDR4 (Model F4-3200C22D-64GRS) **64GB Kit** (2x32GB) 3200MHZ PC4-25600 CL22 SO-DIMM 260-Pin  
  Where to buy: [Newegg](https://www.newegg.com/g-skill-64gb-260-pin-ddr4-so-dimm/p/N82E16820374025) 

## External Devices and Accessories  

### Solid State Drives

The HP DevOne ships with a 1TB SSD which is sufficient for most users. The HP DevOne supports up to 4TB SSD. For users that need more than 1TB SSD, following a few tested options:

- #### 4TB  

  - **Teamgroup** 4TB SSD M.2 2280 NVMe PCIe Gen 3.0 x 4 3D NAND Internal Solid State Drive  
Where to buy: [Newegg](https://www.newegg.com/team-group-4tb-mp34/p/N82E16820331702)
  
  - **Inland** Platinum 4TB SSD M.2 2280 NVMe PCIe Gen 3.0 x 4 3D NAND Internal Solid State Drive, PCIe Express 3.1 and NVMe 1.3 Compatible - *Credit [brademerica](https://www.reddit.com/r/pop_os/comments/wbk9pm/comment/ii7ck08/?utm_source=share&utm_medium=web2x&context=3)*  
Where to buy: [Amazon](https://www.amazon.com/Inland-Platinum-Internal-Compatible-Solutions/dp/B08FT8LFNM)

### Wi-Fi Card

- #### Wi-Fi 6

The HP Dev One ships with a Realtek RTL8822CE 802.11ac (Wi-Fi 5) card, instead of a 802.11ax (Wi-Fi 6 or 6E) card, while not a big deal, it would help make this Laptop more future-proof.  
What makes this laptop so very valuable is its upgradability! The Wi-Fi card can be upgraded as well. For most users the Wi-Fi 5 option is more than plenty, but for those that need Wi-Fi 6, they do have the option to replace the Wi-Fi 5 with a Wi-Fi 6 card.  

The HP Dev One is compatible with Wi-Fi modules that conform to the [M.2 2230 form factor and are A & E keyed](https://en.wikipedia.org/wiki/M.2#Form_factors_and_keying).

Following options to upgrade this laptop with a compatible Wi-Fi 6 card:

- **Intel Wi-Fi 6 AX200** (GIG+) Contributor: [87x9](https://www.reddit.com/r/System76/comments/yool02/comment/izptd3l/?utm_source=share&utm_medium=web2x&context=3)  
Where to buy: [B&H Photo](https://www.bhphotovideo.com/c/product/1591690-REG/intel_ax200_ngwg_dtk_wi_fi_6_gig_desktop.html)  
*Note: Even though it is the Desktop kit, all you need is the card. When you are replacing the default Wi-Fi 5 card, you will re-use those antenna cables. The kernel supports this card, so no drivers needed*

## External Devices

### Monitors

- SAMSUNG 49-inch Odyssey G9 Gaming Monitor:  
Monitors max resolution is 5120x1440p and max refresh rate is 120Hz. All resolutions are supported. In the settings it shows as 'Unknown 49"' with a refresh rate selection of 59.98Hz only, it should go up to 120Hz, it shows that on my Pop!\_OS Linux desktop. This could be due to the HDMI cable limitations. I will check with other cables and also try the USB-C port using an adapter since the Monitor doesn't have a USB-C monitor input.

### Hubs

- [DELL D6000 Universal USB-C/USB-A Dock](https://www.dell.com/support/home/en-us/product-support/product/dell-universal-dock-d6000/docs), [Spec Sheet (PDF)](https://www.delltechnologies.com/asset/en-us/products/electronics-and-accessories/technical-support/Dell_Universal_Dock_D6000_Spec_Sheet.pdf)  
On the back it has 1x Power Input, 1x HDMI, 2x DisplayLink, 1x Ethernet, 2x USB 3.0, 1x Speaker Out and in the front it has 1x USB 3.0, 1x USB 3.0/BC1.2, 1x USB-C/BC1.2, 1x Audio Combo. The cable to the computer is a USB-C along with an adapter for USB-A!  
*Note: A nice to have is if you use the USB-C port to connect to the HP Dev One, the dock will charge the HP Dev One.  
There is also a version D6000S, which DOES NOT have any audio jacks! Info by [raldara on Reddit](https://www.reddit.com/r/Dell/comments/vn617z/comment/ie5bh28/?utm_source=share&utm_medium=web2x&context=3)*  
Where to buy: Newegg [New](https://www.newegg.com/black-dell-d6000/p/1DN-0002-000H2)/[Refurbished](https://www.newegg.com/dell-d6000-black/p/1DN-0002-00581), [Amazon](https://www.amazon.com/Dell-452-BCYT-D6000-Universal-Black/dp/B071YTQBXM)

- [Pluggable UD-3900C4 USB-C Quad HDMI Docking Station](https://plugable.com/products/ud-3900c4), [Spec Sheet PDF](https://m.media-amazon.com/images/I/61dUzlBY9dL.pdf)  
Where to buy: [Newegg](https://www.newegg.com/p/pl?d=9SIA2XBJC65504), [Walmart](https://walmart.com/ip/4VPQ6TK0RRHS), [Insight](https://www.insight.com/en_US/shop/product/UD-3900C4/PLUGABLE%20TECHNOLOGIES/UD-3900C4/Plugable-UD3900C4--docking-station--USBC--14slot--4-x-HDMI--GigE/), [Amazon](https://www.amazon.com/dp/B09TSQYGKS)

**Important Note**: Some Hubs offer DisplayLink monitor connectors. If you DO NOT already have the DisplayLink drivers installed for Pop!\_OS, you need to install them in order to use the DisplayLink ports of your hub. [Download the DisplayLink drivers](https://www.synaptics.com/products/displaylink-graphics/downloads/ubuntu).  

## Accessories

### Chargers

- 65W Type C USB AC Charger  
This charge is affordable and charges the HP Dev One through its USB-C port.  
Where to buy: [Amazon](https://www.amazon.com/gp/product/B09B78WPXK)  

*Note: Additional chargers are great when you travel between different locations, like home and office. Have a charger for each location. Always the worse when you get where you need to go and the charge was forgotten :D*

### Batteries

The OEM battery may be found on the HP Parts Store [page](https://parts.hp.com/hpparts/Default.aspx).  Using the search box at the top of the page, search for the part number `L78555-005`.  This battery has a capacity of 53Wh or 4.59Ah.

This battery may be sold via other third-party sellers.  See #29 for more details.

### Adapters

Coming Soon !

## Function Keys Explained

HP didn't include any explanation about the FN Keys. So this is where this section comes in handy, it will add a quick description to the FN Keys.
FN-F1: Screen symbol with a bar to the right and the left

| Function Key  | Image/Icon | Description |
| ------------- | ---------- | ----------- |
| <kbd>F1</kbd>  | Rounded Rectangle with a bar to the left and right of it | When connected to an external screen, it offers ways to interact with that external screen. You can cycle through the following options when using this function key: Mirror ( Laptop Screen and External Screen show the same screen content, the laptop screen content ), Join Display ( Using all screen with each their own screen content ), External Only ( The laptop screen will be turned off while the External Screen stays on), Built-In Only ( Only the Laptop screen will be active, all external screens will be turned off) |
| <kbd>F3</kbd> | Small Sun | Decrease screen brightness |
| <kbd>F4</kbd> | Large Sun | Increase screen brightness |
| <kbd>F5</kbd> | Vertical line through speaker | Toggle sound on/off |
| <kbd>F6</kbd> | Speaker with one wave | Decrease sound volume |
| <kbd>F7</kbd> | Speaker with three waves | Increase sound volume |
| <kbd>F8</kbd> | Vertical line through microphone | Mute microphone |
| <kbd>F9</kbd> | Keyboard with outer lines | Cycle through keyboard backlight brightness |
| <kbd>F11</kbd> | Plane | Toggle airplane mode |
| <kbd>F12</kbd> | Triple Square | Programmable hotkey |

## Videos

### Removing and Replacing Parts

- [Removing & Replacing Parts by HP](https://www.youtube.com/watch?v=RkAOS9f5p1I) - Great find by [cutememe](https://www.reddit.com/r/System76/comments/wlpfrk/comment/ikf5oys/?utm_source=share&utm_medium=web2x&context=3)  
*Note: Even though this is for the HP EliteBook 845 G8 Notebook it can be fully applied to the HP Dev One, aside of a few exceptions/differences mentioned below.*  
List of exceptions/differences in this video that do NOT apply to the HP Dev One:
  - The screws on the HP Dev One are Torx T5 screws, not P1 Phillips-head screws
  - The video shows a WAN module covered by a mylar shield, but the HP Dev One does NOT have this piece of hardware
  - The video shows an NFC Board, but the HP Dev One does NOT have this piece of hardware
  - The video shows a Smart Card Board, but the HP Dev One does NOT have this piece of hardware 
  - The video shows a Fingerprint Reader Board, but the HP Dev One does NOT have this piece of hardware

### Series of Videos about the HP Dev One

- [HP Dev One Full Review (Part 1) - First Impressions: Hardware Overview, Software Integration & More!](https://www.youtube.com/watch?v=qF63-jT9_ZQ)  
- [HP Dev One Full Review (Part 2) - Upgrading RAM, Running Other Distros & More!](https://www.youtube.com/watch?v=zJotySEbj3o)  
*Note: Videos by [Learn Linux TV](https://www.youtube.com/c/LearnLinuxtv)*

## Pros and Cons

**🟥 IN PROGRESS**

| Pros | Cons |
| :------------ | :--------- |
| Linux OS as a first class citizen | Glossy display contributes to eye strain |
| Offers USB-C & USB-A Ports | Display has bad viewing angles, not sure if this is done on purpose for privacy |
| Can be charged through the USB-C Port | HP chose 802.11ac (Wi-Fi 5), instead of a 802.11ax (Wi-Fi 6 or 6E) while not a big deal, it would help make this Laptop more future proof! |
| The webcam is decent for a 720p resolution | webcam is 720p, rather than a 1080p - while not a big deal, it is 2022 |
| The webcam has a sliding cover that can fully cover it  |  |
| Excellent built-in keyboard |  |
| Excellent trackpad |  | 
| Memory can be upgraded to 64 GB |  |
| No soldered memory |  |
| Generous 1 TB SSD |  |
| Display brightness up to 1000 Nits |  |
| Upgradable memory and storage |  |


## Using Other Linux Distributions

It is possible to use any Linux distribution, instead of Pop!\_OS. The only downside is that you can't update the firmware or BIOS without some additional work. 

The official documentation for [System 76 firmware upgrade](https://support.system76.com/articles/system-firmware/) suggests to use a live USB of Pop!\_OS to create an environment for updating the firmware.

### Arch Linux

- #### Firmware  

  For Arch Linux, you can install [`firmware-manager`](https://aur.archlinux.org/packages/firmware-manager) and [`system76-firmware`](https://aur.archlinux.org/packages/system76-firmware) from the [AUR](https://aur.archlinux.org/).
    - Once installed, execute `fwupdmgr refresh --force` to identify your device and relevant updates with the service.
    - From here, you can use the GTK-based GUI in Firmware Manager to update. If you have an issue with checksum authentication, run the commend `fwupdmgr get-updates` followed by `fwupdmgr install --force` to force the upgrade.

### NixOS

- #### Firmware  

  Since the [machine](https://fwupd.org/lvfs/devices/com.hp.laptop.devone.firmware) supports the [Linux Vendor Firmware Service](https://fwupd.org) (LVFS), you can use
  ```
    services.fwupd.enable = true; # for firmware updates 
    services.udisks2.enable = true; # needed for fwupd
  ```
  to enable firmware updates on [NixOS](https://nixos.org/).  Then download the metadata from LVFS with `fwupdmgr refresh` and install updates with `fwupdmgr update`.

## Performance

### Geekbench 5

- #### Bert2Go Test Scores  

  | ID | Name | Sincle-core Score | Multi-Core Score |
  | :-- | :-- | :-: | :-: |
  | [17029514](https://browser.geekbench.com/v5/cpu/17029514) | HP Dev One Notebook PC <br><sup>AMD Ryzen 7 PRO 5850U 4505 MHz (8 cores)</sup> | **1562** | **7822** |
  | [17029378](https://browser.geekbench.com/v5/cpu/17029378) | HP Dev One Notebook PC <br><sup>AMD Ryzen 7 PRO 5850U 4505 MHz (8 cores)</sup> | **1561** | **7815** |
  | [17029213](https://browser.geekbench.com/v5/cpu/17029213) | HP Dev One Notebook PC <br><sup>AMD Ryzen 7 PRO 5850U 4505 MHz (8 cores)</sup> | **1547** | **7664** |

*Note: I did a total of three tests. Pop!\_OS Power Setting for all tests was set to `High Performance` and `Adaptive Battery Optimizer` in the BIOS was set to `Enabled`. No tweaking/overclocking has been performed.*

## Support and Connect Information

### Known Issues

- On boot, the BIOS may show the `90B` System Fan Error. This is a known bug that was patched with a later firmware/BIOS update. If you experience this issue, update the firmware to version F.05 (or later).

### HP 

- Login to your HP Account or create an HP Account to initiate a support ticket.
- [Support on hpdevone.com](https://hpdevone.com/user/support). *Note: User has to be logged in, or else there will only be a blank page.*
- Tech Support: Mo-Su 5a-5p (PST)
- Order Status Inquiries: Mo-Fr 8:30a to 5p (MST)
- Email: [support@hpdevone.com](mailto:support@hpdevone.com)
- Creating a Support ticket through Pop!_OS on the HP Dev One: Open Settings and click on Support
- Facebook: [HP](https://www.facebook.com/HP)
- LinkedIn: [HP](https://www.linkedin.com/company/hp)
- Twitter: [HP](https://twitter.com/HP)
- YouTube: [HP](https://www.youtube.com/HP)

### Pop!\_OS and System76

- Facebook: [PopOSOfficial](https://www.facebook.com/poposofficial)
- Instagram: [PopOSOfficial](https://www.instagram.com/pop_os_official/)
- Twitter: [PopOSOfficial](https://twitter.com/pop_os_official)
- GitHub: [System76](https://github.com/system76)
- YouTube: [System76](https://www.youtube.com/c/System76)

## Question & Answers

**Q: Does the HP DevOne have CoreBoot ?**  
A: No

## Useful Links

- [HP Dev One Product Website](https://hpdevone.com/)
- [HP Dev One Product Website - FAQ Section](https://hpdevone.com/faq)
- [Coupon Code Source on Reddit](https://www.reddit.com/r/linuxhardware/comments/vujx95/hp_dev_one_coupon/)
- [System 76 Firmware Upgrade](https://support.system76.com/articles/system-firmware/)
- [Adaptive Battery Optimizer](https://support.hp.com/us-en/document/c06310986)

## Contributors

Thank you to all contributors to the HP Dev One Guide. I really appreciate your help. Contributors are mentioned either inline throughout this documentation or in the list below if they contributed using a pull request.

Pull request contributors:  

[<img src="https://avatars.githubusercontent.com/u/51793?s=60&v=4" alt="Fank Kumro Jr" width="32" height="32" />](https://github.com/fkumro)[<img src="https://avatars.githubusercontent.com/u/87946040?s=60&v=4" alt="woltersdylan" width="32" height="32" />](https://github.com/woltersdylan)[<img src="https://avatars.githubusercontent.com/u/148352?s=60&v=4" alt="Jim Fowler" width="32" height="32" />](https://github.com/kisonecat)[<img src="https://avatars.githubusercontent.com/u/93500165?v=4" alt="Jim Fowler" width="32" height="32" />](https://github.com/lazytownfan)[<img src="https://avatars.githubusercontent.com/u/3860655?v=4" alt="Peter Hoburg" width="32" height="32" />](https://github.com/peterHoburg)[<img src="https://avatars.githubusercontent.com/u/3579286?v=4" alt="Alex DeLorenzo" width="32" height="32" />](https://github.com/alexdelorenzo)

## Supporters

Thank you to the following folks that support/supported this guide using the [Buy me a Coffee](https://www.buymeacoffee.com/Bert2Go) option.

- Wicka

## Connect/Follow Me

- [Reddit](https://www.reddit.com/user/Bert2Go)
- [GitHub](https://github.com/Bert2Go)
- [Twitter](https://twitter.com/Bert_2_Go)

## Disclaimer
* **This is a work in progress, any sharing of this guide and/or pull request is appreciated. Feel free to contact me directly if needed.**
* I am not receiving any financial kickbacks for any of the links and content. I bought my HP Dev One with my own money. I am sharing information readily available on the internet along with my own personal experiences regarding this laptop.*

## About this HP Dev One Guide

**Even though this laptop has officially been sold out by HP, this guide is still under active development.**

How can I contribute to this guide:

- Post anything on Reddit about the HP Dev One and tag me [u/Bert2Go](https://www.reddit.com/user/Bert2Go) and I will add the content to this guide.

- Fork this repo and contribute by creating a pull request

- Use the [Contact Form](#contact-form)

## Contact Form

<form action="https://fabform.io/f/44D576Y" method="post" style="width: 350px; margin: 0 auto"><label for="name">Your Name<br></label><input name="name" type="text" style="width: 100%" required><label for="email">Your Email<br></label><input name="email" type="email" style="width: 100%" required><label for="message" class="label">Message<br></label><textarea name="message" style="width: 100%; height: 200px;" required></textarea><button>Send</button></form>

*Note:   
This contact form only works for the [Website Version](https://hpdevone.bert2go.com#contact-form) of this guide, not through the GitHub version.*

## Buy me a Coffee

<p align="center">
  If you like to support my work, feel free to  
</p>
<p align="center">
  <a href="https://www.buymeacoffee.com/Bert2Go">
    <img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee Image" />
  </a>
</p>
<p align="center">
  Thank you!
</p>

