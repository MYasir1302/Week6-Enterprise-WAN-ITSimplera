# Week 6 — Enterprise WAN Technologies & High Availability
## IT-SIMPLERA Network Administration Internship

| | |
|---|---|
| **Submitted By** | [Apna Naam] |
| **Reg No** | [Apna Reg No] |
| **Date** | 8th August, 2026 |
| **Supervisor** | Jawad Qayum (Senior Network Administrator) |
| **Institute** | IT-SIMPLERA Institute |
| **Department** | Network Administration |

## Overview
Multi-branch enterprise WAN infrastructure designed and 
implemented exclusively in GNS3 for ITSimplera Solutions 
connecting 6 branch offices.

## Topology
- 15 Cisco Routers (c3725)
- 6 Branch Offices (Lahore, Islamabad, Peshawar, 
  Karachi, Multan, ISP)
- Hub and Spoke Design
- Redundant WAN Links (Primary + Backup)

## Protocols Implemented
| Protocol | Purpose |
|----------|---------|
| PPP/CHAP | WAN Authentication |
| GRE Tunnel | Secure Overlay |
| OSPF | Dynamic Routing |
| NAT/PAT | Internet Access |
| Floating Static Routes | High Availability |

## Tools Used
- GNS3
- PuTTY
- Cisco IOS c3725

## Results
| Test | Result |
|------|--------|
| OSPF Neighbors | FULL State ✅ |
| GRE Tunnel | Up/Up ✅ |
| PPP/CHAP | Authenticated ✅ |
| Ping HQ→Branch | 100% Success ✅ |
| NAT/PAT | Configured ✅ |
| Floating Static | AD 110/200 ✅ |

## Files
- `Report.pdf` — Complete documentation
- `Screenshots/` — Verification screenshots
- `Configs/` — Router configurations
