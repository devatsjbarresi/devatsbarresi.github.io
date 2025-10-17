---
layout: default
title: Filters
nav_order: 7
---

# Filters

ShowShark includes quick filtering tools that help narrow down what you see in Wireshark while using the dissector.  
Filters hide irrelevant traffic and make it easier to focus on the devices and protocols you care about.

---

## Using Filters

You can apply filters through the Wireshark **Display Filter Bar** or from ShowShark’s **Host Table** view.

Typical use cases:
- Focus on one **protocol** (e.g., sACN, Art‑Net, IGMP).  
- Show packets from a single **device or manufacturer**.  
- Hide **discovery or background** traffic to focus on lighting data.  
- Compare two universes or devices side by side.

---

## Example Filters

| Purpose | Filter |
|----------|--------|
| Show sACN packets only | `acn` |
| View Art‑Net traffic | `artnet` |
| Show multicast joins | `igmp` |
| Focus on ETC devices | `eth.src contains 00:60:2B` |
| Hide discovery chatter | `not mdns and not slp` |

---

These filters are for simplifying analysis, not for protocol deep‑dive or diagnostics.  
Future releases will include pre‑built filter buttons inside the ShowShark UI for faster access.
