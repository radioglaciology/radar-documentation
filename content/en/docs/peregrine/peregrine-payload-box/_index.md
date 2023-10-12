---
title: Peregrine Radar Payload Box
description: Build instructions for the core of the radar payload
weight: 2
resources:
  - src: "*.{png,jpg}"
---

<!-- {{< figure src="payload-box-cad.png" title="Cut-away view of a CAD rendering of the radar payload box" caption="Major components of the radar payload box" >}} -->


{{% imgproc payload-box-cad Fit "800x400" %}}
Major components of the Peregrine radar payload box
{{% /imgproc %}}

## Bill of Materials

A complete bill of materials for the payload box is available in [this Google Sheet](https://docs.google.com/spreadsheets/d/1dFItvJ4mGw7Axdo4Iq9m_65ks9YspEahcemvucNRllk/edit?usp=sharing), embedded below.

Some parts are custom made. See the [Custom Parts]({{< ref "custom-parts.md" >}}) page for suggestions on how to build these yourself or source them from reliable vendors.

{{% iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSJbgsZBh6xJ8d5_O48yUdmh09coE1oZ8njQWZqQKYorwuMoUEFA6LCj9P5QiVQtoCGBCOOl3b1RTjY/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" style="min-height: 40vh;" %}}

## Assembly instructions

### Preparing enclosure halves

The payload box is a clamshell-style design with two interlocking halves. The
"upper" half contains the SDR. The "lower" half holds the Raspberry Pi.
Sandwiched between the two halves is the "payload divider" PCB, which houses
some sensors and provides for external connections.

Starting with the Pi Shell:

1. Place 4x M2.5 heat inserts into the four mounting holes at the bottom of the box.
2. Place 2x M2.5 heat inserts into the two front panel mounting holes on the
front of the box.

Continuing with the SDR Shell:

3. Place 4x M2.5 heat inserts into the four holes in the tabs sticking up, to
accept bolts from the outside to connect the two shells together.

### Copper foil wrapping

