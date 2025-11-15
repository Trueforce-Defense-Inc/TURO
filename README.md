<img width="200" alt="Logo" src="https://www.trueforce.ca/images/Logo.svg">


# TURO
Welcome to TURO - the Trueforce Unified Radio OS
## Goal
The goal of TURO is to create a single, unified list of frequencies and optimized settings for usage in HAM radios especially for users who are not that experienced with radio usage. It consists of two parts: A list of channels and corresponding frequencies which can be used with any programmable radio and images for the most used radios with optimized settings.
## Frequencies
TURO contains .csv files with the above-mentioned list of frequencies and channels, one for analog and one for digital radios. These files can be imported in radio programming software such as [CHIRP](https://chirp.danplanet.com) to build individual images for radios not supported by TURO. It can be found in the [releases tab](https://github.com/Trueforce-Defense-Inc/TURO/releases). Furthermore, a printable PDF version is also available.
## Images
Images are radio specific and contain optimized settings such as disabling of transmitting sounds when pressing the emergency button and above mentioned frequencies. There are currently the following versions with support the listed radios:

 * **Version U** *(Baofeng F8HP Family)*
   * Baofeng GT-3TP
   * Baofeng UV-5R Plus 
   * Baofeng UV-5RTP 
   * Baofeng UV-5R EX
 * **Version G** *(Baofeng F8HP Family)*
   * Baofeng GT-3
 * **Version R**
   * Retevis RT90
* **Version A**
   * Ailunce HD1 GPS<br>
  *Works on hardware revisions 1 and 2.<br>Might work on HD1 non GPS and HD2 but untested* 
 ## Interoperability
Versions with the same version code will be guaranteed to work together when selecting the same channel. Minor versions such as *v.1.**1**_U* and *v.1.**2**_U* will probably work as they only contain bugfixes.
The letter after the version number specifies the device version the image is. This means *v.1.2_**U*** and *v.1.2_**B*** for example, share the same settings and frequencies.

Images for the digital radios are compatible with the analog radios on the analog channels.
## Installation
### Analog Radios
To flash the image to your radio, you need [CHIRP](https://chirp.danplanet.com) or similar software and a programming cable.
 
 1. Download the corresponding image for your device [here](https://github.com/MasterPuffin/TURO/releases) (distinguishable by the letter at the end of the version number)
 2. Open CHIRP and go to File > Open and open the downloaded file
 3. Go to Device > Upload to device
 4. Select the right port (COM3 on Windows, USB0 on Linux), Vendor and Model
 5. Click OK and follow the onscreen instructions
### Digital Radios
#### Retevis RT90
Use the official programming software. The software can't be downloaded from the Retevis site anymore, but can be found [here](https://www.iz8wnh.it/rpts/softwares.php)
#### Ailunce HD1
Use the official programming software which can be aquired [here](https://www.ailunce.com/Supports/HD1/Software/)

## Manuals
Please see the [manuals folder](https://github.com/Trueforce-Defense-Inc/TURO/tree/master/Manuals) for detailed instructions on how to use the radios with the images.

## Read More
Check out this great [Baofeng Cheat Sheet](https://w7apk.com/baofeng), which contains all you must know for programming your radio in the field
