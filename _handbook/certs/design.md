---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# <span class="badge badge-primary">Github CI</span>
#<span class="badge badge-secondary">Web Service</span>
#<span class="badge badge-success">Open Source</span>
#<span class="badge badge-danger">Paid Service</span>
#<span class="badge badge-info">Free Service</span>

title: "Design to Pass"
layout: single

---

**Disclaimer**: Nothing on this website should be considered legal advice. You should always consult with a lawyer and a certification house in regards to the tests you are legally required to complete. Everything on this site should be considered anecdotal advice, and has no guarantee of being factually correct.

## Summary

Passing EMC testing can be made much easier by considering passing early on in the design phase.

## PCB Design

### Radiated EMC

- Avoid long skinny copper pours. These can act as antennas and cause issues for both emissions and immunity.
    ![]()
- Use at least four layers, and keep one of them as a full, uninterrupted ground pour. Ideally use a ground pour on your signal layers as well.
- Keep all traces with high switching frequencies as short as possible. These are commonly found in buck converters, where the higher current being switched makes this particularly bad for emissions.
- For motor or other high-power outputs, consider adding a ferrite bead inline. These can reduce high frequency signals on a high current line, which should greatly reduce any emissions for the frequencies that they attenuate.
- Enclose your PCB in a metal enclosure, ideally grounded. This will shield the board from interference, and also block a tremendous amount of emissions coming from the board.

### ESD

- Adding TVS (Transient Voltage Suppression) diodes on every single exposed line is a sure-fire way to protect against ESD. This includes both power and signal lines. There are dedicated TVS diodes with clamping voltages for specific electrical standards, like USB or RS-485.

<kicanvas-embed src="https://github.com/opulo-inc/feeder/blob/main/pcb/mobo/mobo.kicad_sch" controls="basic"> </kicanvas-embed>

usb shield termination? contentious, can leave as option https://electronics.stackexchange.com/questions/661902/usb-shielding-device-or-host-side
TVS everywhere, power, signal. lots of diodes made for specific things, like rs485 and usb

Floating everything in plastic, can't zap it



## Cabling

Shielded, ideally also grounded any long cable runs
typically RE in the range of ____

## Power Supply

If at all possible, choose to use an off-the-shelf power supply brick or module. These are designed to pass Conducted Emissions and Conducted Immunity testing, and should be an easy way to ensure your device passes without issue.

Ferrite Bead



## Software

Although the vast majority of EMC tests are related to your device's hardware, RI in particular can be made easier to pass with some software updates.

Many standards only require that a device will continue normal operation, or resume normal operation if it's interrupted during RI testing. This means that adding some software checks to ensure a restart or reconnection in the case of issues can mean the difference between passing and failing.

For example, if your device's standard operating mode involves a serial communication between a computer and a microcontroller, having consistent checks for serial data integrity and re-establishing connection in the case of an error can make any interference not an issue. 