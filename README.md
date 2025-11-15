# Implementation of Delay Tolerant Routing Protocol using Network Simulator NS-3

This repository contains the implementation and performance analysis of a Delay Tolerant Routing Protocol (Epidemic Routing) using the NS-3 network simulator. The project demonstrates message propagation in intermittently connected MANET/DTN environments using the store–carry–forward routing mechanism.

---

## Project Overview

Delay/Disruption-Tolerant Networks (DTNs) address communication challenges in environments where a stable end-to-end path is not available. The Epidemic Routing Protocol solves this by forwarding messages opportunistically as nodes encounter each other.

This project implements:
- Epidemic Routing logic in NS-3
- Random Waypoint mobility model
- Wi-Fi ad-hoc communications
- Message advertisement, request, and transmission
- NetAnim-based network visualization
- Performance measurement (PDR, delay, packet loss)

---

## Repository Structure

```
/src/          - NS-3 C++ source code (epidemic-routing.cc)
/netanim/      - NetAnim XML and simulation screenshots
/results/      - CSV logs, graphs, PCAP traces
/report/       - Final project report PDF
README.md      - Project documentation
LICENSE
```

---

## Requirements

- NS-3 (recommended: latest stable release)
- NetAnim (for XML visualization)
- C++ compiler (gcc/clang)
- Python 3 (optional for log analysis)
- Wireshark (optional for PCAP analysis)

---

## Running the Simulation

1. Install NS-3.
2. Copy the files from the `src/` directory into your NS-3 `scratch/` folder.
3. Build the project:

```
./waf build
```

4. Run the simulation:

```
./waf --run epidemic-routing
```

5. View the animation output in NetAnim:

```
netanim epidemic.xml
```

---

## Output and Results

The simulation produces:
- Packet Delivery Ratio (PDR)
- Average end-to-end delay
- Packet loss statistics
- NetAnim visualization of node mobility and message spread
- PCAP traces for packet-level inspection

Results and screenshots are available inside:

```
/results/
/netanim/
```

---

## License

This project is licensed under the MIT License.

---

## Author

Sumith
Vikaas Karthik K  
Email: vikaaskarthik.k@gmail.com
