# README
**pxe tftp server for local booting and install/config of pxe-boot devices**

<br />

# PXE Network Booting
```PXE``` (Preboot eXecution Environment) is a method to boot a PC or device using the system BIOS/UEFI and a connected ethernet card ([read more](https://en.wikipedia.org/wiki/Preboot_Execution_Environment)) to load or install a tool or operating system.

There are several means to accomplish network booting into an environment, but the most common are using tools like [iPXE](#ipxe-project) and [Netboot.xyz](netbootxyz-project), or by creating your own solution using a PXE server with DHCP and a TFTP or some type of network storage server, or even HTTP.  The following describes the two most commonly-used existing systems to achieve this. 


## iPXE Project
For booting to a specific PXE or TFTP/HTTP/Network Storage device to load/install a tool or system.

- **Website:** https://ipxe.org/
- **Download:** https://boot.ipxe.org/ipxe.iso

Best used when compiled for specific network card hardware, see [GitHub site](https://github.com/ipxe/ipxe) or:

- **Build from Source:** https://ipxe.org/download#source_code
  ```
  git clone https://github.com/ipxe/ipxe.git
  cd ipxe/src
  make
  ```
  
See documentation: https://ipxe.org/docs

<br/>

## Netboot.xyz Project
For general network boot and access to many boot images, use the netboot.xyz solution:
- **Docs:** https://netboot.xyz/docs/
- **GitHub:** https://github.com/netbootxyz/netboot.xyz

  For Linux-based machines using GRUB bootloader:
  - **Read:** https://netboot.xyz/docs/booting/grub
  - **Download:** https://boot.netboot.xyz/ipxe/netboot.xyz.iso

  For booting from a USB drive:
  - **Read:** https://netboot.xyz/docs/booting/usb
  - **Download:** https://boot.netboot.xyz/ipxe/netboot.xyz.img

<br />

<br />

# TFTP Serving of Images


<br /><br />

### Visit this project on my website
**Project Website:** https://www.jinet.us/dev/dev-projects/automated-boot-install-pxe-tftp-server/


<br />

Copyright &copy; 2023-2024 Jacob Eiler, Isreal Consulting, LLC.  All rights reserved.

