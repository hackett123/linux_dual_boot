# Dual-Booting Linux

First, downloaded an iso file of the distro of choice (using Linux mint)
Then, download balena etcher and flash the ISO image onto the flash drive
Then, partition the drive.

Following https://ostechnix.com/dual-boot-linux-mint-and-windows/ for this.
- In powershell, run `Get-Disk`. My partition style is GPT.
- In system information, check that you're using UEFI
- Ill advised surely, but skipping turning secure boot off and turning off device encryption
- Creating partition for linux
  - Disk Management -> right clink -> shrink
  - will now have unallocated storage where we can put our mint installation

- now we will restart and boot into bios with either f12, f9, esc, or delete. then navigate with arrow keys within the boot menu to select the usb drive, then select the option to start linux mint in live mode
- then, follow the install linux mint setup
