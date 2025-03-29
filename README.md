# J1850VPW Transceiver
This is the Rev B of the J1850VPW Transciever featured on my YouTube channel "Fixed Until Broken". I sell them on eBay but the fabrication files are here if you want to assemble them yourself.
The PDF is the schematic and the zip file contains the fabrication files. 

## Code
Code can be found with the Rev A of this project. https://github.com/garnerm91/Arduino_J1850VPW

## Credits
The inspiration was taken from the Macchina M2 hardware. https://github.com/macchina/m2-hardware?tab=readme-ov-file <br>
The code is from redheadedrod: https://github.com/redheadedrod/j1850/tree/master/M2_J1850_VPW I modified it to work on the atmega328 instead of due. (I think that is what they were using). I also changed the easy_send function to be memory-safe. I removed the "test" mode because it wasn't documented in the original API; I didn't want it to confuse users. I removed pin setting for J1850 PMW on the M2 since version of the module does not support that at a hardware level <br>
