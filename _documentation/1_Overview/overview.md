---
layout: default
title: Overview
nav_order: 1
has_children: true
---

# Overview

**ShowShark** is a Lua-based post-dissector for Wireshark, built for entertainment network analysis.

It identifies and interprets protocols such as:
- sACN (Streaming ACN / E1.31)
- Art-Net
- RDMnet
- OSC
- IGMP (for multicast subscription behaviour)
- mDNS / SLP (for service discovery)

ShowShark automatically recognises devices, decodes packet types, and builds a friendly protocol stack view within Wireshark.
