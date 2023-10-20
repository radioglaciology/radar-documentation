---
title: External button
#description: 
#weight: 10
---

An external lighted push button can be added to turn the radar on and off. A
connector for this is included on the Payload Divider PCB.

## Button choices

The intended button for the UAV version is [HB15CKW01-5C-CB](https://www.digikey.com/en/products/detail/nkk-switches/HB15CKW01-5C-CB/1056598).

Most other similar buttons can be used. For the ground-based version, we use [ULV4F2BSS311](https://www.digikey.com/en/products/detail/e-switch/ULV4F2BSS311/5299297).
Some of the photos on this page are taken with this button, which can be mounted externally.

## Wiring the button

The button connector is a 5 position JST GH connector. The
[connectors](https://www.digikey.com/en/products/detail/jst-sales-america-inc/GHR-05V-S/807817)
and
[pre-crimped wires](https://www.digikey.com/en/products/detail/jst-sales-america-inc/AGHGH28K102/10108415)
are available separately or you can
[buy a kit](https://www.amazon.com/Pre-Crimped-Connectors-Pixhawk2-Pixracer-Silicone/dp/B07PBHN7TM/).

{{% imgproc button-wiring Fit "800x400" %}}
Schematic section for the button connector. Right side shows recommended connections to the lighted button.
{{% /imgproc %}}

If you buy pre-crimped wires, you'll need to cut the connector on one side off.

For JST connectors, the small notch on the contact aligns with the bottom side of the connector.
On the bottom of the connector housing, there are a series of small plastic pins that will
raise up as you insert the contact. Once you get the contact fully inserted, this pin will fall back down
to lay flush.

To assemble the button:

1. Cut pre-crimped JST wires to length
2. Following the image above, strip and solder the free end of each wire to the
specified terminals on the switch.
3. Place a piece of heatshrink over each terminal and shrink.
4. (Optional) Twist the wires gently and use small pieces of heat shrink to
keep them in a neat bundle.
5. Insert the contacts into the JST GH 5 position housing, following the diagram
above.
6. Mount the button and insert the connector into the plug on the payload divider PCB.

{{% imgproc button-components-eyas Fit "800x400" %}}
Components of the button assembly. Note that these pictures were taken with the
alternative version of the button designed to be mounted on the outside of a
Pelican case.
{{% /imgproc %}}

{{% imgproc button-soldering-eyas Fit "800x400" %}}
Cables soldered to the terminals of the button
{{% /imgproc %}}