+++
title = "Wi-Fi Stack"
description = ""
weight = 1
+++


{{< lead >}}
Imagine the Wi-Fi stack as a layered cake, each layer responsible for a specific task in ensuring smooth wireless communication.
{{< /lead >}}

## Description

## Physical Layer (PHY)
The foundation: Handles the actual transmission of radio waves.
Key responsibilities:
- Encoding and decoding data into electrical signals.
- Modulating and demodulating signals to carry information.
- Frequency hopping to avoid interference.
## Media Access Control (MAC) Layer
The traffic cop:
Manages access to the shared wireless medium.   
Key responsibilities:
- Assigning time slots to devices for transmission.
- Detecting and resolving collisions.
- Handling frame synchronization.
## Logical Link Control (LLC) Layer
The bridge: Connects the MAC layer to the higher-level network protocols.
Key responsibilities:
- Flow control to prevent overwhelming the receiver.
- Error detection and correction.
- Multiplexing data from multiple applications.
## Internet Protocol (IP) Layer
The navigator: Provides addressing and routing for data packets.
Key responsibilities:
- Assigning IP addresses to devices.
- Routing packets through the internet.
- Fragmenting and reassembling packets if necessary.
## Transport Layer
The delivery service: Ensures reliable data transfer between applications.
Key responsibilities:
- Establishing connections between devices.
- Flow control to prevent data loss.
- Error detection and correction.

{{< childpages >}}