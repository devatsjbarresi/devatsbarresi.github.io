---
layout: default
title: Manufacturers
nav_order: 6
---

# Manufacturers

ShowShark identifies devices by manufacturer to make lighting network captures easier to read.  
Friendly manufacturer names appear in the **Source** and **Destination** columns and within the **Host Table**.

---

## How it Works

- The first three bytes of each MAC address (the **OUI**) identify the manufacturer.  
- ShowShark uses an internal table combining **IEEE OUIs** and **ESTA manufacturer codes**.  
- If no match is found, the device is shown as *Unknown Manufacturer*.  

---

## Custom Entries

You can add or override manufacturer names for testing or internal systems.

Example JSON:
```json
{
  "00:12:34": "My Lighting Co",
  "00:AB:CD": "ShowTech Ltd"
}
```

Place the file alongside the ShowShark Lua scripts; it will merge automatically on load.

---

Use this feature to keep device names clear and consistent when analysing captures from multiple vendors.
---
layout: default
title: Columns
parent: Documentation
nav_order: 6
---

# Columns

ShowShark provides clear, structured columns for analysing network captures.  
Each column displays key information about a packet or device to make lighting data easier to interpret.

---

## Default Columns

| Column | Description |
|:--|:--|
| **No.** | Packet index number within the capture |
| **Time** | Timestamp relative to capture start |
| **Source** | Device name or IP/MAC of packet sender |
| **Destination** | Device name or IP/MAC of packet receiver |
| **Protocol** | Protocol decoded (e.g. sACN, Art-Net, IGMP) |
| **Info** | Summary of payload details for quick context |

---

## Manufacturer Awareness

Columns automatically use friendly names when possible.  
For example, known OUIs or ESTA codes are replaced with manufacturer names to make the source and destination easier to identify.

---

## Customising Columns

You can toggle, resize, or reorder columns within Wireshark or ShowShark preferences.  
Column layout is saved between sessions, allowing a consistent analysis view.

---

Use the Columns view to quickly understand packet flow, source/destination roles, and network behaviour at a glance.