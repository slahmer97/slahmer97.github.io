---
title: "Implementation of Centralized Scheduler in 6TiSCH Network Stack"
summary: A centralized MAC-layer scheduler was implemented within the 6TiSCH network stack using RIOT OS. The project focuses on ensuring reliable communication, deterministic timing, and low duty cycle in an IIoT context.
tags:
  - Embedded Operating System
  - MAC Layer
  - Scheduling
  - IoT Networking
  - Reliability
  - Graph Theory
date: "2020-11-11T00:00:00Z"

links:
  - icon: github
    icon_pack: fab
    name: openwsn-fw
    url: https://github.com/slahmer97/openwsn-fw
  - icon: github
    icon_pack: fab
    name: openwsn-sw
    url: https://github.com/slahmer97/openwsn-sw
  - icon: github
    icon_pack: fab
    name: openvisualizer
    url: https://github.com/slahmer97/openvisualizer
  - icon: github
    icon_pack: fab
    name: riot-os
    url: https://github.com/slahmer97/RIOT

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

The core of this work lies in the MAC layer scheduler, a vital piece that orchestrates when devices in the network can talk to each other. Our aim was to make sure these communications happen reliably (low drop probability), at the right time (deterministic timing), and without using too much energy (low duty cycle).

The central server requires insights from the network topology to make informed scheduling decisions, as well as to be able to inject scheduling policies within the IoT nodes as needed. We implemented a CoAP-based REST API on the IIoT nodes. This allows the central server to seamlessly interface with the nodes, enabling it to gather network topology information and inject MAC scheduling policies. This approach streamlined communication and ensured efficient coordination between the central scheduler and the network nodes.

For demonstration and testing purposes, we utilized the infrastructure provided by https://www.iot-lab.info, employing two main boards: M3 and A8-M3. This enabled us to validate the functionality and effectiveness of our centralized scheduler in real-world IIoT scenarios.
