# Notes from JBS1776

This is a separate fork of chiaki-ng that is meant to be used in conjunction with the original chiaki app.  This is meant for if you are using a PS4 and PS5 simultaneously via port forwarding.  You can download this fork to have the client send requests to the home IP at different ports since the PS4 and PS5 use the same ports for remote play.  The port forwardings needed to work are homeIP:1987/udp -> ps5ip:987/udp, homeIP:19295-19297,19302/tcp/udp -> ps5ip:9295-9297,9302/tcp/udp.  Since the homeIP and ps5ip listen at different port ranges, you may need to configure individual ports rather than specify port ranges to get this to work for port forwarding in your router.  I have tested this app with my router and it has been working smoothly.  Everything else about this project is identical to the original and props to the developers.

![chiaki-ng Logo](gui/res/chiaking-logo.svg)

# [chiaki-ng](https://streetpea.github.io/chiaki-ng/)

An open source PlayStation remote play project serving as the next-generation of Chiaki with improvements and ongoing support now that the original Chiaki project is in maintenance mode only. [Click here to see the accompanying site for documentation, updates and more](https://streetpea.github.io/chiaki-ng/).

## Discord
[chiaki-ng community Discord](https://discord.gg/tAMbRuwXDH)

## Disclaimer
This project is not endorsed or certified by Sony Interactive Entertainment LLC.

Chiaki is a Free and Open Source Software Client for PlayStation 4 and PlayStation 5 Remote Play
for Linux, FreeBSD, OpenBSD, Android, macOS, Windows, Nintendo Switch and potentially even more platforms.
