---
title: Getting Started
sidebar_label: Getting Started
parent: Documentation
nav_order: 2
--- 

# Getting Started

Welcome to **ShowShark**, the Wireshark post-dissector built for entertainment networking protocols such as **sACN**, **Art-Net**, **RDMnet**, and **OSC**.

---

## Overview

ShowShark extends Wireshark with smart detection, analysis, and friendly labelling for lighting network traffic.  
This documentation will help you install, configure, and use ShowShark effectively.

---

## Installation

### macOS
Copy the Lua plugin files to:
```
~/.local/lib/wireshark/plugins/
```

### Windows
Copy the Lua plugin files to:
```
%APPDATA%\Wireshark\plugins\
```

### Linux
Copy the Lua plugin files to:
```
~/.config/wireshark/plugins/
```

Then restart Wireshark.

---

## Quick Start

Once installed, open Wireshark and look for the **ShowShark** dissector in the *Decode As...* list.  
You should see extra protocol layers for sACN, Art-Net, and related traffic.

---

## Configuration

You can configure logging, verbosity, and analysis options inside:
```
entnet_config.lua
```

This allows advanced control of behaviour for development, testing, or show environments.

---

## Support

If you encounter issues or have feature requests, please visit:
[GitHub Repository](https://github.com/devatsjbarresi/showshark)

---