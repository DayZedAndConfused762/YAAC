# Y.A.A.C - Setup

Steps to setup and install operating systems and software on the Y.A.A.C.

<!-- ============================================================ -->

### Setup

<!-- ============================================================ -->

#### Change Raspberry Pi Boot to USB
* Image a SD card with 'Bootloader (Pi 4 family)' using [Raspberry Pi Imager](https://www.raspberrypi.com/software/).
* Boot the Raspberry Pi with SD card, choose USB as the first boot option (Will boot from USB if present, then fallback to SD Card if no USB device)

<!-- ============================================================ -->

#### Operating System 1 - Rasperry Pi OS Bookworm - Internet in a Box - Crucial 1TB SSD
* Image 'Raspberry Pi OS Full (64-bit)' using [Raspberry Pi Imager](https://www.raspberrypi.com/software/).
* Expand File System - Run: sudo raspi-config. Choose 1 Expand File System. Follow the onscreen instructions. Reboot the Raspberry Pi
* Update software - 'sudo apt update' 'sudo apt full-upgrade'
* Setup SSH
* Install Internet in a Box - from command line enter 'curl iiab.io/install.txt | bash'

<!-- ============================================================ -->

#### Operating System 2 - Kali Linux - CyberSecurity - 512 GB Sandisk Micro SD Card
* https://www.kali.org/docs/

<!-- ============================================================ -->

#### Operating System 3 - Raspberry Pi OS Bookworm - General Use - SanDisk 1TB Extreme Portable SSD
* Image 'Raspberry Pi OS Full (64-bit)' using [Raspberry Pi Imager](https://www.raspberrypi.com/software/).
* Expand File System - Run: sudo raspi-config. Choose 1 Expand File System. Follow the onscreen instructions. Reboot the Raspberry Pi
* Update software - 'sudo apt update' 'sudo apt full-upgrade'
* Setup SSH