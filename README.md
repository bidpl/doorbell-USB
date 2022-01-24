# Wake On Doorbell (WoD) USB Dongle

A USB stick that sends a spacebar press when the doorbell is pressed. Used to wake a door surveillence monitor when someone rings the doorbell.

Takes a AC signal through the barrel jack (doorbell wires). The onboard microcontroller acts as a USB keyboard while monitoring the signal for a drop in the average voltage (doorbell pressed). When it detects the decrease in voltage, it sends a spacebar keypress to wake the computer.

![Assembled WoD USB Dongle](/images/assembledUSB.jpg)
Assembled WoD USB Dongle

![Installed WoD USB Dongle](/images/installedUSB.jpg)

## The stick itself

v1.0
Yay it works!
No errors found during testing and use.

![Render of Case](/images/caseRender.jpg)

## Case

A press fit case for the PCB. It has some screw holes, but the press fit is enough to hold it in. The tab for the USB connector is sized to increase the thickness of the connector to ~2.2mm.

![Render of PCB](/images/pcbRender.jpg)