# usb-audio-interface
USB audio interface based on PCM2906C IC

**NOTE: The PCBs for this project have been ordered but have not arrived yet; as such this project should be considered untested. This README will be updated upon arrival and testing.**

![image](https://github.com/user-attachments/assets/b72c168a-2f2f-4e47-98ff-143e23457da2)

## description
This USB audio interface board has standard RCA inputs and outputs for both analog and digital signals. I designed it because the only products that exist that can record digital S/PDIF over coaxial cost >$200 USD.

While it was designed primarily for digital audio capture and output, I also put thought into the analog design. It has high-capacitance, low ESR output capacitors for good low-frequency response, and an optimized layout for decoupling capacitors and crystal circuitry, to improve ADC/DAC performance, and to reduce jitter, respectively, while maintaining a super compact form factor of only 4x5cm. It could have been even more compact, but at the expense of removing industry standard RCA jacks.

## assembly
The BOM in the KiCAD project is up to date and contains no out-of-production parts at time of creation. All parts were ordered from Mouser Electronics. This was designed to be hand solderable, with SMD components including larger pads in the footprint, however as it does use 0603 components, reflow soldering is preferable if possible.

## features
 - USB-C port with reversibility support
 - Low ESR high capacitance output and input capacitors for good low-frequency response
 - Analog and digital inputs and outputs
 - Compact design layout
 - Standard RCA jacks
