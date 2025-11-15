# 🚀 Implementation of Delay Tolerant Routing Protocol using NS-3

A simulation-based implementation of **Epidemic Routing** in **Delay Tolerant Networks (DTNs)** using the **NS-3 Network Simulator**.  
This project demonstrates message propagation in intermittently connected MANETs using the **store–carry–forward** mechanism.

---

## 📘 About the Project

Delay/Disruption-Tolerant Networks enable communication even when stable end-to-end paths fail.  
This project implements:

- 📡 Epidemic Routing Protocol  
- 🚶 Random Waypoint Mobility Model  
- 📶 802.11b Wi-Fi Ad-Hoc Network  
- 📨 Message Advertisement → Request → Transmission  
- 📷 NetAnim Visual Simulation  
- 📊 Performance Metrics (PDR, Delay, Packet Loss)  
- 🧪 Packet-level tracing using PCAP  

---

## 📂 Repository Structure

```
📦 Epidemic-Routing-NS3
│
├── src/            → NS-3 C++ source code (epidemic-routing.cc)
├── netanim/        → NetAnim XML + screenshots
├── results/        → PDR graphs, delay charts, PCAP traces
├── report/         → Full PDF report
├── README.md       → Documentation
└── LICENSE
```

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **NS-3** | Network Simulation |
| **C++** | Protocol Implementation |
| **NetAnim** | Mobility + message visualizer |
| **PCAP/Wireshark** | Packet-level tracing |
| **Random Waypoint Model** | Node mobility simulation |

---

## ▶️ How to Run the Simulation

### 1️⃣ Install NS-3  
Download from official NS-3 releases.

### 2️⃣ Copy the source code  
Move `/src/` contents into your NS-3 scratch folder:

```
ns-3.xx/scratch/
```

### 3️⃣ Build the project

```
./waf build
```

### 4️⃣ Run the simulation

```
./waf --run epidemic-routing
```

### 5️⃣ View the visualization in NetAnim

```
netanim epidemic.xml
```

---

## 📊 Simulation Outputs

This project generates:

### ✔ Packet Delivery Ratio (PDR)
Indicates delivery success in DTN environments.

### ✔ Average End-to-End Delay
Shows latency caused by mobility, queueing and message replication.

### ✔ Packet Loss
Increases with:
- mobility,
- network congestion,
- node density.

### ✔ NetAnim Visualization
Displays:
- node mobility  
- message advertisement  
- message forwarding  
- packet flow animations  

All outputs are stored in:

```
/results/
/netanim/
```

---

## 📄 Full Project Report

Included inside:

```
/report/
```

Report contains:
- Introduction  
- DTN Architecture  
- Epidemic Routing Protocol  
- NS-3 Setup  
- Pseudocode & Algorithm  
- Graphs + Results  
- Conclusion  

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Vikaas Karthik K**  

**Sumith**
📧 Email: **vikaaskarthik.k@gmail.com**

## 📄 Published Research Paper

This project is based on my peer-reviewed published paper:

**“Implementation of Delay Tolerant Routing Protocol using Network Simulator NS-3”**  
*Author: Vikaas Karthik K*  
*Published in: International Journal of Engineering Sciences & Emerging Technologies (IJESE)*  
*Volume: 24, Issue 1, 2024*  
*DOI:* **10.35940/ijese.K2586.12111024**

### 🔗 DOI Link  
[https://doi.org/10.35940/ijese.K2586.12111024](https://doi.org/10.35940/ijese.K2586.12111024)

### 🏷️ DOI Badge
[![DOI](https://img.shields.io/badge/DOI-10.35940%2Fijese.K2586.12111024-blue)](https://doi.org/10.35940/ijese.K2586.12111024)

### 📥 Download Paper (Author Copy)
> *(Upload your PDF into a folder named `paper/` and rename it `Published_Paper.pdf`)*  
[Click to Download](paper/Published_Paper.pdf)

---

### 📘 IEEE Citation (Copy for academic use)

K. V. Karthik, **"Implementation of Delay Tolerant Routing Protocol using Network Simulator NS-3,"**  
*International Journal of Engineering Sciences & Emerging Technologies (IJESE)*,  
vol. 24, no. 1, pp. 1–8, 2024, doi: 10.35940/ijese.K2586.12111024.


