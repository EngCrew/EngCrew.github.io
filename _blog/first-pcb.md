---
title: "Your first PCB: 6 mistakes to catch before you order"
date: 2026-11-07
topic: "Hardware"
minutes: 5
summary: "Boards take days to arrive. These checks save you from waiting twice."
draft: false
---
Designing your first circuit board is a rush. Getting it back and finding out a part doesn't fit is not. Run through these before you send the files to the fab house.

## 1. Check every footprint against the real part

Print the layout at 1:1 scale and lay the actual components on the paper. A footprint that's one size off is the most common first-board mistake.

## 2. Run the electrical and design rule checks

Run the electrical rules check on your schematic and the design rules check on your layout, and set the design rules to your manufacturer's minimum trace width, spacing and drill sizes first.

## 3. Size traces for the current they carry

Signal traces can be thin. Power traces need to be wider. Use a trace width calculator for anything carrying real current.

## 4. Put decoupling capacitors right at the chip

A decoupling cap on the other side of the board barely helps. Place it as close to the IC's power pin as you can.

## 5. Label everything on the silkscreen

Pin names, connector polarity, your board name and version number. Future you, holding a probe, will be grateful.

## 6. Add test points and mounting holes

Give yourself easy places to clip a multimeter or scope, and holes to actually mount the board in your project.
