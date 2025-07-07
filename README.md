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
    A[Streaming Input<br> (Pathway)] --> B[Real-Time Feature Extraction]
    B --> C1[Model 1: Linear Pricing]
    B --> C2[Model 2: Demand-Based Pricing]
    B --> C3[Model 3: Competitive Pricing]
    C1 --> D[Price Output]
    C2 --> D
    C3 --> D
    D --> E[Live Visualization<br>(Bokeh)]
    D --> F[Optional: Vehicle Rerouting]
