# Backpower Protecter
Current revision: 1.0

## Introduction
Based on the RPi HAT specification, all power going to the +5VDC net must have backpower
protection built into it. This way, if multiple sources of power are connected, it won't break
the devices.

This is simply an implementation of the circuit provided in the HAT specification, except that
instead of being built directly into the board, it is installed via a 3-pin header. If the circuit
board is removed, a simple jumper restores the power connection.

## Why?
While building the TIEVox Interface Board, I realized I needed two of these circuits.  Adding them
directly caused issues when adding the traces to the board, which I was already fighting. Pulling the
circuit off board like this helped simplify the other board, while still providing protection.

Also, since the TIEVox Interface Board already has several devices attached in a similar manner, it
won't look any sillier than it already does.

## Usage