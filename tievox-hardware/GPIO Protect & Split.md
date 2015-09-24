# GPIO Protect & Split
Current revision: 1.1

## Introduction
The GPIO Protect & Split does two things.  First, it splits the GPIO connection
into two connectors, wired in parallel.

Second, it adds protection to the IO circuits so they can only take +3.3VDC and no
more. All extra power gets diverted to the ground.

## Why?
I created this board for two reasons. The first and arguably more important reason is that
I accidentally blew an RPi A+ by sending it too much current. I believe this board would have
saved that one.  Second, for the TIEVox, I needed to be able to connect to multple points on the
GPIO interface on multiple boards. This seemed an easy way since I needed to create a protection
circuit anyway.

## Mounting
The assembly is made to mount underneat the RPi, with the single GPIO connector hanging out.
Tall enough standoffs should be used to allow connection to both connectors underneath it using
ribbon cables.

## Usage Notes