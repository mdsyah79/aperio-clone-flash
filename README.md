# aperio-clone-flash (aka AperioUSBKit): ULTRA-portable (PC-less) [Seagate-Woodlands] Aperio Flashing-Cloning solution powered by Ubuntu and Clonezilla!

Description of function: Aperio box is, in simple terms, a computer with high speed cards whose job is to quickly process media surface data and tag any abnormalies (e.g. types of abnormalities and location with reference to the processed media). With this data, one can plot out the processed media for analysis work to determine the quality of media without the need to complex hardware-based data collection rig, hence saving time and money.

Aperio Box Maintenance: The high speed cards and harddisk in the Aperio need to be flashed correctly to the correct configuration in order to work correctly. Sometimes the provided Conguration Automation Tool might not work due to bugs or some hardware based fault or faulty or damaged harddisk (HDD). Hence, manual flashing or HDD repair needs to be done. High speed cards manual flashing requires a flashing device (Altera USB Blaster). To repair the HDD, commonly, it is cloned to the basic software, or it could be simply replaced and reflashed using the Auto Config Tool. Both requires a Computer (desktop or Laptop) with Windows based OS installed with Altera Programmer to flash the high speed cards, or Norton Ghost to clone the HDD to a prefabricated image of a good HDD.

Benefits of AperioUSBKit: With AperioUSBKit, the benefits are:
* PC-less or Laptop-less operation (save power, time and energy)
* AperioKITUSB is an all-in-one tool that fits in a small bag (slightly the of A5 paper but thicker).
* Faster flashing time due to Ubuntu (linux) based software (Ubuntu on USB)
* Faster HDD cloning using Linux-based Open-Source CloneZilla
* With CloneZilla, multiple HDD flashing is achieveable via Clonezilla Server (host becomes a Cloned Image Server. Clients connects to Server to receive Image)
* Another neat feature is CopyClone where a production-ready HDD is imaged and restored back to the faulty HDD without the need to re-flash, all within 1.5hours.
* No licenses required for any software (Open Source)
* Configurable settings via Syslinux can enable multiple feature to run pre or post CloneZilla op.
* Example of pre Clone op: 1- run FSCK to auto-repair HDD metadata 2- delete unnecassary files (log files, tmp files) before imaging HDD to reduce image size.
* Example of post Clone op.: 1- rename the HDD ID number to the correct ID instead of -88 which is the default ID set in the image
* AperioUSBKit also has these tools under the hood: Hardware Detection Tool, Quicktech Pro, Seagate HDD Diagnostics tool, Parted Magic Linux OS.

With all this benefits, AperioUSBKit is a very powerful kit indeed.

See a demo on youtube: https://youtu.be/bRm1tIB4tsk

Screengrab of AperioUSBKit menu (version 4.5)
![image](https://user-images.githubusercontent.com/18409384/233894201-2bd30032-dbc8-45ef-ad63-c5f2767b1eef.png)

Detection of USB, LVM, type of LVM amd cellnumber (Machine ID) [Example of Pre Clone Ops]
![image](https://user-images.githubusercontent.com/18409384/233923046-0e32a017-4f7a-4827-9d32-05da260d3b6c.png)

Start of HDD Restore
![image](https://user-images.githubusercontent.com/18409384/233923887-b46d38fb-ab27-4dda-a8c7-03cbc7f8767e.png)

Restoring of cellnumber to Newly Cloned HDD [Example of Post Clone Ops]
![image](https://user-images.githubusercontent.com/18409384/233924575-f8cba770-4c8f-4c2c-a13a-2f7c0132e713.png)

Multiple Clone via Server [ServerMode]
![image](https://user-images.githubusercontent.com/18409384/233925586-753aab53-c9f9-41ee-87aa-bfb4d393258e.png)

ServerMode - How it works
![image](https://user-images.githubusercontent.com/18409384/233925956-97f0fb34-5662-4368-a493-aa11f7b8bacd.png)

Selectable Cloned Images
![image](https://user-images.githubusercontent.com/18409384/233926477-e0e504f2-0a6f-4f9c-ab68-3957999d71ec.png)

ServerMode - Client side screengrab
![image](https://user-images.githubusercontent.com/18409384/233926820-b67737db-0137-4ed2-bca5-74da358acb88.png)

Aperio Flash
![image](https://user-images.githubusercontent.com/18409384/233928199-989a1df8-6d3a-4d88-930c-4388a24e481a.png)

Aperio Flash - Ubuntu Login page (Linux on USB)
![image](https://user-images.githubusercontent.com/18409384/233928333-21354fb9-0d62-4b77-a2de-3c026b1294af.png)

Altera Qartus on Ubuntu (on usb)
![image](https://user-images.githubusercontent.com/18409384/233928851-9db012b4-747c-484b-85bc-6b83b88dc4f5.png)

Flashing in progress
![image](https://user-images.githubusercontent.com/18409384/233929057-22395f09-f050-4c04-ae1c-5ac06bfb3c68.png)

