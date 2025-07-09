# Capstone_Project_SummerAnalytics

# 🚗 Dynamic Pricing for Urban Parking Lots

## 🌎 Project Overview

This project is a simulation of a real-time **dynamic pricing engine** for 14 urban parking spaces across 73 days. Unlike static pricing which often leads to congestion or underuse, our system adapts in real-time to:

- Current occupancy levels
- Queue lengths
- Nearby traffic
- Vehicle types
- Special day indicators
- Competition from nearby lots

The result: smarter, fairer, and more efficient parking pricing.

---

## 🧰 Tech Stack

| Component               | Technology                     |
|-------------------------|-------------------------------|
| Data Streaming          | [Pathway](https://pathway.com) |
| Data Processing         | Python, Pandas, NumPy          |
| Visualization           | Bokeh                          |
| Notebook Environment    | Google Colab                   |
| Reporting               | Markdown, PDF (optional)       |

---

## 📊 Architecture Diagram (Mermaid)

# Capstone_Project_SummerAnalytics

# 🚗 Dynamic Pricing for Urban Parking Lots

## 🌎 Project Overview

This project is a simulation of a real-time **dynamic pricing engine** for 14 urban parking spaces across 73 days. Unlike static pricing which often leads to congestion or underuse, our system adapts in real-time to:

- Current occupancy levels
- Queue lengths
- Nearby traffic
- Vehicle types
- Special day indicators
- Competition from nearby lots

The result: smarter, fairer, and more efficient parking pricing.

---

## 🧰 Tech Stack

| Component               | Technology                     |
|-------------------------|-------------------------------|
| Data Streaming          | [Pathway](https://pathway.com) |
| Data Processing         | Python, Pandas, NumPy          |
| Visualization           | Bokeh                          |
| Notebook Environment    | Google Colab                   |
| Reporting               | Markdown, PDF (optional)       |

---

## 📊 Architecture Diagram (Mermaid)

```mermaid
graph TD
    A[CSV Data Source (dataset.csv)] --> B[Pathway Streaming Engine]
    B --> C[Model 1: Linear Pricing]
    B --> D[Model 2: Demand-Based Pricing]
    B --> E[Model 3: Competitive Model]
    C --> F[Real-time Pricing Table]
    D --> F
    E --> F
    F --> G[Bokeh Visualization]
    F --> H[Output as JSONL]

