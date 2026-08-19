# Energy Efficiency Analysis of IEEE 802.15.4 Network Using AODVEEP

## 📌 Overview

This project analyzes the energy efficiency and network performance of IEEE 802.15.4 wireless networks using a modified AODV routing protocol called **AODV Energy-Efficient Protocol (AODVEEP)**.

The protocol is evaluated through **NS-2 simulations** under different network conditions to determine its impact on energy consumption, throughput, delay, and packet loss.

The main goal is to develop a more energy-efficient routing approach suitable for resource-constrained wireless and IoT environments.

---

## 🎯 Objectives

- Analyze the energy efficiency of IEEE 802.15.4 wireless networks.
- Modify the standard AODV routing protocol to create AODVEEP.
- Reduce overall energy consumption during data transmission.
- Minimize packet loss and communication delay.
- Improve network throughput and transmission reliability.
- Evaluate protocol performance under different network conditions.
- Study the suitability of the approach for IoT and smart-home applications.

---

## 🛠️ Technologies Used

- **Network Simulator:** NS-2
- **Wireless Standard:** IEEE 802.15.4
- **Routing Protocol:** AODV
- **Proposed Protocol:** AODVEEP
- **Network Simulation:** Wireless / IoT Network
- **Performance Analysis:** Energy Consumption, Throughput, Delay, Packet Loss

---

## 🔬 Methodology

The project follows these major steps:

### 1. Network Configuration

An IEEE 802.15.4 wireless network is created and configured in NS-2.

Different network parameters are considered, including:

- Number of nodes
- Traffic flows
- Packet transmission rates
- Network coverage area

### 2. Standard AODV Simulation

The standard **AODV routing protocol** is simulated to establish baseline network performance.

The following metrics are recorded:

- Energy consumption
- Throughput
- Packet delay
- Packet loss

### 3. AODVEEP Implementation

A modified version of AODV, called **AODV Energy-Efficient Protocol (AODVEEP)**, is implemented to improve energy efficiency while maintaining reliable communication.

### 4. Performance Evaluation

The performance of AODVEEP is compared with standard AODV under different network configurations.

The comparison focuses on:

| Metric | Purpose |
|---|---|
| Energy Consumption | Measure overall energy usage |
| Throughput | Measure successful data transmission |
| Packet Loss | Measure transmission reliability |
| Delay | Measure communication latency |

---

## 📊 Parameters Analyzed

The simulations investigate the effect of changing:

- **Node Count**
- **Traffic Flow**
- **Packet Rate**
- **Coverage Area**

These parameters help evaluate how the proposed routing protocol behaves under different operating conditions.

---

## 📈 Results

The simulation analysis shows that **AODVEEP reduces overall energy consumption compared with standard AODV while improving data transmission success rates**.

The evaluation also considers the relationship between:

- Energy consumption
- Throughput
- Packet loss
- Delay
- Network reliability

The results indicate that the modified protocol can provide improved energy efficiency while maintaining effective communication performance.

---

## 🌐 Applications

The proposed approach is particularly relevant to energy-constrained wireless environments such as:

- Internet of Things (IoT)
- Smart Home Networks
- Wireless Sensor Networks
- Low-power Wireless Communication Systems

---

## 📁 Project Structure

```text
IEEE-802.15.4-AODVEEP/
│
├── README.md
│
├── simulation/
│   ├── aodv/
│   ├── aodveep/
│   └── configuration/
│
├── results/
│   ├── energy/
│   ├── throughput/
│   ├── delay/
│   └── packet-loss/
│
├── analysis/
│   └── performance-analysis/
│
└── documentation/
    └── project-report/


⚙️ Simulation Workflow

IEEE 802.15.4 Network
        │
        ▼
Configure Network Parameters
        │
        ├── Node Count
        ├── Traffic Flow
        ├── Packet Rate
        └── Coverage Area
        │
        ▼
Run Standard AODV
        │
        ▼
Collect Performance Metrics
        │
        ▼
Run AODVEEP
        │
        ▼
Collect Performance Metrics
        │
        ▼
Compare Results
        │
        ├── Energy Consumption
        ├── Throughput
        ├── Delay
        └── Packet Loss
        │
        ▼
Performance Evaluation


📚 Research Publication
Energy Efficiency Analysis of IEEE 802.15.4 Network Using Modified AODV Routing

Published at PEIS 2025.

👨‍💻 Project Focus

This project focuses on improving the efficiency of wireless communication by optimizing routing behavior and analyzing network performance under different operating conditions.

The work demonstrates how routing protocol modifications can contribute to more energy-efficient and reliable wireless communication systems for IoT-oriented applications.

🔑 Key Concepts

IEEE 802.15.4 · AODV · AODVEEP · NS-2 · Wireless Networks · IoT · Energy Efficiency · Routing Protocols · Network Simulation · Throughput · Packet Loss · Network Delay

