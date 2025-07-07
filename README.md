# 🚗 Dynamic Pricing Engine for Urban Parking Lots  
**Summer Analytics 2025 – Capstone Project**  
Hosted by: Consulting & Analytics Club, IIT Guwahati × Pathway

---

## 📘 Project Overview

This project simulates a real-time **dynamic pricing system** for 14 urban parking spaces using real-world features such as occupancy, queue length, vehicle type, traffic congestion, and special events. The objective is to implement smart pricing logic from scratch using only **NumPy**, **Pandas**, and **Pathway**, and to visualize the results using **Bokeh**.

The goal is to ensure efficient use of parking resources through data-driven, explainable pricing adjustments that reflect real-time demand and competition.

---

## 🛠 Tech Stack

| Layer                | Tools / Libraries       |
|---------------------|-------------------------|
| Programming Language| Python (NumPy, Pandas)  |
| Data Streaming      | Pathway                 |
| Visualization       | Bokeh                   |
| Platform            | Google Colab            |

---

## 🏗 Architecture Diagram

```mermaid
flowchart TD
    A1[Streaming Input: Pathway] --> B1[Real-Time Feature Extraction]
    B1 --> C1[Model 1: Linear Pricing]
    B1 --> C2[Model 2: Demand-Based Pricing]
    B1 --> C3[Model 3: Competitive Pricing]
    C1 --> D1[Price Output]
    C2 --> D1
    C3 --> D1
    D1 --> E1[Live Visualization using Bokeh]
    D1 --> F1[Optional: Vehicle Rerouting]
