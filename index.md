---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
author: whad-team
layout: page
title: WHAD
---

**WHAD** is an opensource framework for exploring, hacking and more generally playing with
common wireless protocols. **WHAD** supports natively multiple protocols and provide a set
of tools to interact with any of them independently from the hardware used. And that's the
beauty of it: you only need to plug a hardware device running a firmware compatible with **WHAD**
into your computer, and each tool will adapt to its capabilities!

Tools are therefore generic and support a lot of different hardware devices, the only
condition is they run a compatible firmware and expose the required capabilities. This
encourages interoperability but also allow generic tools to be developed without having
to think about the firmware, by simply reusing simple bricks exposed by **WHAD**.

# WHAD makes wireless hacking easier

**WHAD** supports natively the following protocols and is able to capture, analyze and
inject data exchanged through them: *Bluetooth Low Energy*, *ZigBee*, *RF4CE*, *Enhanced
ShockBurst* (also known as *ESB*), or even *Logitech's Unifying*. It also supports
raw de/modulation based on common schemes such as *GFSK*, *QPSK* or even *LoRa*.

## Main features of WHAD

**WHAD** provides a set of ready-to-use tools and a Python framework that allow:

- Sniffing and capturing data into a PCAP file
- Replaying captured data from a PCAP file
- Interacting with common protocols like ZigBee, Bluetooth Low Energy or LoRaWAN
- Demodulating signals, saving them into PCAP files and replaying them as-is
- Creating custom tools for any supported protocol
- Combining tools to create complex on-the-fly packet processing

# Examples

**WHAD** provides for instance a set of tools to capture packets into a PCAP file,
break a Logitech Unifying encryption key and sniff keystrokes from a specific keyboard:

<div id="keyboard-demo"></div>
<script src="/js/asciinema-player.min.js"></script>
  <script>
    AsciinemaPlayer.create('/demos/whad-keyboard.cast', document.getElementById('keyboard-demo'), {
        terminalFontSize: "18pt"
    });
  </script>

Or if you want to mess with *Bluetooth Low Energy* devices, **WHAD** provides off-the-shelf
tools to scan, connect, discover and explore a device' services and characteristics. These
tools can even be combined to create more complex tools !

<div id="ble-demo"></div>
<script src="/js/asciinema-player.min.js"></script>
  <script>
    AsciinemaPlayer.create('/demos/whad-demo.cast', document.getElementById('ble-demo'), {
        terminalFontSize: "18pt"
    });
  </script>
