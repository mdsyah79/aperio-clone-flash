# aperio-clone-flash (aka AperioUSBKit): ULTRA-portable solution to an existing solution but WITHOUT Desktop or Laptop. AperioUSBKit is super efficient because instead it simply uses the HOST computing power to run instead and much more.

Description of function: Aperio box is, in simple terms, a computer with high speed cards whose job is to quickly process media surface data and tag any abnormalies (e.g. types of abnormalities and location with reference to the processed media). With this data, one can plot out the processed media for analysis work to determine the quality of media without the need to complex hardware-based data collection rig, hence saving time and money.

Aperio Box Maintenance: The high speed cards and harddisk in the Aperio need to be flashed correctly to the correct configuration in order to work correctly. Sometimes the provided Conguration Automation Tool might not work due to bugs or some hardware based fault or faulty or damaged harddisk (HDD). Hence, manual flashing or HDD repair needs to be done. High speed cards manual flashing requires a flashing device (Altera USB Blaster). To repair the HDD, commonly, it is cloned to the basic software, or it could be simply replaced and reflashed using the Auto Config Tool. Both requires a Computer (desktop or Laptop) with Windows based OS installed with Altera Programmer to flash the high speed cards, or Norton Ghost to clone the HDD to a prefabricated image of a good HDD.

Benefits of AperioUSBKit: With AperioUSBKit, the benefits are:
* PC-less or Laptop-less operation (save power, time and energy)
* AperioKITUSB is an all-in-one tool that fits in a small bag (slightly the of A5 paper but thicker).
* Faster flashing time due to Ubuntu (linux) based software (Ubuntu on USB)
* Faster HDD cloning using Linux-based Open-Source CloneZilla
* With CloneZilla, multiple HDD flashing is achieveable via Clonezilla Server (host becomes a Clone Server. Clients connects to Server to be cloned)
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

