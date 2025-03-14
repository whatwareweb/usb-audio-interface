# usb-audio-interface
USB audio interface based on PCM2906C IC

**NOTE: This design is tested to work properly. If you have any problems using this design, feel free to send me an email or leave a GitHub issue.**

![Assembled and tested PCB](https://github.com/user-attachments/assets/8c498b1a-abfe-4e52-9e4f-ab29094d7333)


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
