# RouteWise: Interactive Network Layer Routing Lab 🌐

[![CA-3 Computer Networks](https://img.shields.io/badge/Project-CA3%20Computer%20Networks-blue.svg)]()
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-success.svg)](https://cometvs7.github.io/routewise-simulator/)

> **Student Author:** Vardhan Shah  
> **PRN:** 24070126195  
> **Course:** Computer Networks — Continuous Assessment (CA-3)  
> **Unit:** The Network Layer  

---

## 🚀 Overview
**RouteWise** is an interactive, browser-based laboratory and visual explainer designed to demonstrate how routers make split-second path decisions across the Internet. 

Built entirely as a lightweight, self-contained web application (`index.html`), it transforms core routing theories into hands-on simulations complete with step-by-step navigation, editable link costs, and live network failure testing.

---

## ✨ Key Features & Interactive Labs

1. **Distance-Vector Simulator ("Routing by Rumor"):**
   * Walk step-by-step through the **Bellman-Ford equation** ($D_x(y) = \min_v \{c(x,v) + D_v(y)\}$) as neighbor nodes trade distance tables.
   * Includes auto-play controls, speed tuning, and step-jumping timeline logs.

2. **Link-State Simulator ("The Live Satellite GPS Map"):**
   * Experience **Link-State Advertisement (LSA)** flooding and **Link-State Database (LSDB)** synchronization.
   * Step through **Dijkstra’s Shortest Path First (SPF)** algorithm as tentative nodes lock into a loop-free shortest path tree.

3. **Live Map Customization & Roadblocks:**
   * **Edit Link Costs Live:** Click any road cost badge on the map to modify weights ($1–15$) and watch the routing tables re-converge instantly.
   * **Simulate Link Failures:** Click any road segment to introduce roadblocks and test how protocols handle network partitions.

4. **RIP vs. OSPF Side-by-Side Comparison Lab:**
   * Test why **RIP** (which counts junctions/hops blindly) and **OSPF** (which measures bandwidth cost and uses Area 0 hierarchies) choose completely different pathways on the exact same network map.

5. **BGP Analogy & Case Study Storyboard:**
   * Explores Inter-AS routing, **AS-PATH** loop prevention (passport stamp analogy), business policy selection, and a deep dive into the **October 2021 Facebook Global BGP Outage**.

6. **Comprehensive Summary Matrix & Exam Prep:**
   * Includes a side-by-side comparison matrix, 5 core exam takeaways, and formal academic references (Kurose & Ross, Tanenbaum, and IETF RFCs).

---
