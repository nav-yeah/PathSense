# PathSense- Dynamic Delay Analysis in Software Defined Networks

# SDN Network Delay Measurement Tool (Mininet + Ryu)

## Problem Statement
The objective of this project is to design and implement an SDN-based network delay measurement tool using Mininet and the Ryu controller.

The system measures and analyzes latency (RTT) between hosts and demonstrates how SDN can dynamically influence network performance through flow rule control.

---

## Setup Instructions

### Environment Setup (Important)

Ryu is not compatible with newer Python versions. Hence, we use Python 3.8.

```bash
conda create -n sdn python=3.8 -y
conda activate sdn
