---
layout: default
title: Discovery Protocols
parent: Protocols
nav_order: 1
---

# Discovery Protocols

ShowShark’s **Discovery** section displays devices advertising their presence using **SLP** or **mDNS**.  
It helps confirm that controllers, nodes, and software are discoverable on the network.

Use this section to:
- Confirm that devices are broadcasting or responding to discovery messages.  
- Match discovered names with manufacturer and IP data in ShowShark’s host table.  
- Spot missing or duplicate announcements when troubleshooting visibility issues.

### SLP
ShowShark lists detected **Service Type**, **Scope**, and **URL** fields to show how devices announce control or gateway services.

### mDNS
ShowShark groups **Bonjour/Zero-Conf** services by device, displaying names and service types (e.g. `_eos._tcp.local`).

Use this section when checking that lighting and control devices are visible on the network, not for deep protocol analysis.