# TeamTrek
A futuristic, space-based, 'game' simulator involving personnel on a ship bridge and in away-team missions.

Preliminary testing equipment/materials:
 - (3-5) Raspberry Pi 3B/3B+ single-board computers
 - (3-5) EW-7822ULC/UTC USB ethernet adapters
 - at least one PC/laptop (x86_64, not armhf) with dual-band wireless capability

**Modular approach**:
Each player is tied to their SBC (single-board computer). In this case, their Raspberry Pi. Each Raspberry Pi is tied to its player's role/job in the simulator. For our current testing purposes, we will limit the number of players, and thus roles, to 3. By limiting the number of players, we increase the workload for each of them. Below are the three jobs and a sub-hiearchy of their duties.

 - Command - Communications, Helm, Operations

 - Science - Engineering, Cartography, Sensors

 - Tactical - Medical, Stealth, Weaponry


**Styles of gameplay**
There are two main modes of gameplay/simulation involved.

 - Bridge/Cockpit simulation
 - "Away Team" mission

**Team dynamics**

All gameplay/simulation is team-based (and team-building!), and the even bigger goal is to have multiple teams that can eventually interact/cooperate/duel.

**Physical computing & interactive hardware**

 - Short-term goal: functionality with barebones hardware.
 - Long-term goal: functionality with full design implementation.
