---
layout: default
title: Columns
nav_order: 6
---

# Columns

ShowShark provides clear, structured columns for analysing network captures.  
Each column displays key information about a packet or device to make lighting data easier to interpret.

----

## Default Columns

| Column | Description |
|:--|:--|
| **No.** | Packet index number within the capture |
| **Time** | Timestamp relative to capture start |
| **Source** | Device name or IP/MAC of packet sender |
| **Destination** | Device name or IP/MAC of packet receiver |
| **Protocol** | Protocol decoded (e.g. sACN, Art-Net, IGMP) |
| **Info** | Summary of payload details for quick context |

----

## Manufacturer Awareness

Columns automatically use friendly names when possible.  
For example, known OUIs or ESTA codes are replaced with manufacturer names to make the source and destination easier to identify.

----

## Customising Columns

You can toggle, resize, or reorder columns within Wireshark or ShowShark preferences.  
Column layout is saved between sessions, allowing a consistent analysis view.

----

Use the Columns view to quickly understand packet flow, source/destination roles, and network behaviour at a glance.
