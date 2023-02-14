---
description: Mbed Shield
title: Mbed Shield
keywords:
- Seeed_Elderly
image: https://files.seeedstudio.com/wiki/wiki-platform/S.png
last_update:
  date: 1/13/2023
  author: shuxu hu
---
![](https://files.seeedstudio.com/wiki/mbed_Shield/img/Mbed_Shield_01.jpg)

The Mbed Shield is the Mbed application board based on Mbed LPC1768 Prototyping Board. Just try to imagine controlling Ethernet devices by using environmental data from sensors. It integrates a series of external interfaces,such as CAN, Ethernet, USB and 4 standard Grove sockets, all together on a single board.The Mbed Shield is also compatible with other standard Arduino Shields, providing you an even more powerful extension for your Mbed.

[![](https://files.seeedstudio.com/wiki/common/Get_One_Now_Banner.png)](https://www.seeedstudio.com/mbed-shield-p-1390.html?cPath=132_134)

##   Feature
---
*   Standard shield shape design
*   Arduino-compatible base pins
*   Various on-board interfaces: CAN, Ethernet, USB, Grove

##   Hardware Overview
---
![](https://files.seeedstudio.com/wiki/mbed_Shield/img/mBed_Shield_Hardware_Overview.jpg)

##   Getting Started
---
Here is a brief description of how to read the Ethernet data and a removable disk data.
### Connection

- Connect the USB connector of Mbed Protyboard Board to the computer’s USB port.
- Wait for the new found hardware prompt.
- Download [the Mbed serial port Driver](https://files.seeedstudio.com/wiki/mbed_Shield/res/MbedDriver.zip) and install it.
- Plug the Mbed Protyboard Board into the Mbed Base Shield.

### Read a U disk

 The Universal Serial Bus (USB) is the most widely used bus in today's computer. USB has particularly been designed to standardize connections between the computer and peripherals. For instance, keyboards, mice, USB audio devices, printers, scanners, disk drives or cameras can use the same bus to exchange data with a computer. A USB device stack has been developed in order to provide all great capabilities from USB to mbed.

- Plug a U disk into the USB interface.
- Download [MSCUsbHost.bin](https://files.seeedstudio.com/wiki/mbed_Shield/res/MSCUsbHost.zip) and copy the File into Mbed Disk .

:::note
    1) The MSCUsbHost.bin File is generated by Mbed online compiler. 2) Delete any unrelated bin files appear in Mbed disk.
:::
- Press the Reset button. The Serial port should receive following information.

![](https://files.seeedstudio.com/wiki/mbed_Shield/img/MSCUsbHost.jpg)

### Read a Ethernet data

The example demonstrates how to get started with the Ethernet function.

- Connect an available Ethernet cable into the Ethernet interface.
![](https://files.seeedstudio.com/wiki/mbed_Shield/img/Mbed_Shield1.jpg)
- Download [TCPSocket_HelloWorld.bin](https://files.seeedstudio.com/wiki/mbed_Shield/res/TCPSocket_HelloWorld.zip) and copy the file into MBED Disk .

:::note
    Delete any unrelated bin files appear in Mbed disk.
:::
- Press the Reset button. The Serial port should receive following information.
![](https://files.seeedstudio.com/wiki/mbed_Shield/img/Ethernet_Connector_Data.jpg)
- Open the web page and you can view the returned information.
![](https://files.seeedstudio.com/wiki/mbed_Shield/img/Mbed_Ethernet.jpg)


## Schematic Online Viewer
<div className="altium-ecad-viewer" data-project-src="https://files.seeedstudio.com/wiki/mbed_Shield/res/Mbed_Shield_Eagle_File.zip" style={{borderRadius: '0px 0px 4px 4px', height: 500, borderStyle: 'solid', borderWidth: 1, borderColor: 'rgb(241, 241, 241)', overflow: 'hidden', maxWidth: 1280, maxHeight: 700, boxSizing: 'border-box'}}>
</div>



##   Resource
---
- **[Eagle]**[Mbed Shield Eagle File](https://files.seeedstudio.com/wiki/mbed_Shield/res/Mbed_Shield_Eagle_File.zip)
- **[PDF]**[Mbed Shield Schematic File](https://files.seeedstudio.com/wiki/mbed_Shield/res/mbed%20shield%20v0.9b%20Sch.pdf)
- **[PDF]**[Mbed Shield PCB File](https://files.seeedstudio.com/wiki/mbed_Shield/res/mbed%20shield%20v0.9b%20PCB.pdf)
- **[Tools]**[MSCUsbHost](https://files.seeedstudio.com/wiki/mbed_Shield/res/MSCUsbHost.zip)
- **[Tools]**[MbedDriver](https://files.seeedstudio.com/wiki/mbed_Shield/res/MbedDriver.zip)
- **[Tools]**[TCPSocket_HelloWorld](https://files.seeedstudio.com/wiki/mbed_Shield/res/TCPSocket_HelloWorld.zip)

## Tech Support
<div>
  Please submit any technical issue into our [forum](https://forum.seeedstudio.com/). <br /><p style={{textAlign: 'center'}}><a href="https://www.seeedstudio.com/act-4.html?utm_source=wiki&utm_medium=wikibanner&utm_campaign=newproducts" target="_blank"><img src="https://files.seeedstudio.com/wiki/Wiki_Banner/new_product.jpg" /></a></p>
</div>