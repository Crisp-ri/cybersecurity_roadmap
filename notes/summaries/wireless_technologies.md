---
title: "Wireless Technologies - TL;DR"
date: 2025-11-10
tags: [wireless, wifi, networking]
level: beginner
---

# Wireless Networking - TL;DR

**What:** Wireless networking uses radio frequencies and IEEE 802.11 standards to connect devices without cables.  
**Why it matters:** Enables mobility, scalability, and flexible network deployment across homes, offices, and public spaces.

---

## Wi-Fi Standards (IEEE 802.11)
- **Generations:**  
  - 802.11ac = Wi-Fi 5  
  - 802.11ax = Wi-Fi 6 / 6E  
  - 802.11be = Wi-Fi 7  

- **Frequencies:** 2.4 GHz, 5 GHz, 6 GHz  
- **Bandwidths:** 20 / 40 / 80 / 160 MHz  
- **Channels:** Use non-overlapping for best performance  

---

## Key Concepts
- **Band Steering:** Push dual-band clients to faster bands (5 / 6 GHz)  
- **Regulation:** DFS (dynamic channel switching) + TPC (power control) for global compliance  
- **SSID vs BSSID:**  
  - SSID = network name  
  - BSSID = MAC of access point  
- **ESSID:** Same SSID across multiple APs for roaming  
- **Captive Portal:** Login page on public Wi-Fi  

---

## Security
- **Open:** No password (don’t do this)  
- **WPA2 / WPA3-PSK:** Shared password  
- **WPA2 / WPA3-Enterprise:** Individual login via RADIUS/LDAP  
- **Encryption:**  
  - WPA → stop using  
  - WPA2 = AES + CCMP  
  - WPA3 = AES + GCMP (stronger)

---

## Antennas
- **Omni-directional:** Equal coverage all around  
- **Directional:** Focused signal for distance (Yagi, parabolic)

---

## Deployment Types
- **Infrastructure mode:** Clients connect to AP (normal Wi-Fi)  
- **Ad-hoc:** Device-to-device, no AP  
- **Mesh:** Multiple APs self-connect and self-heal  
- **Point-to-Point:** Wireless link between buildings  

---

## Management
- **Autonomous AP:** Configured individually  
- **Lightweight AP + Controller (CAPWAP):** Centralized config, monitoring, and deployment

---

## Quick checks
- `iwconfig` / `nmcli` – wireless interface info  
- AP dashboards / controller logs – roaming & interference  
- Wi-Fi analyzer – channels & signal strength  
- Captive portal test – browser redirect  

---

## Read more
- Practice with AP settings, security modes, and channel planning.  
- WPA3 and 6 GHz are becoming the norm.
