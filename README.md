# 📦 Retail Logistics SLA & Delivery Performance Analysis

> **Transforming 10,998 shipment records into actionable operational insights using Microsoft Excel.**

---

![Project Banner](https://img.shields.io/badge/Tools-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Category](https://img.shields.io/badge/Domain-Retail%20%26%20Logistics-blue?style=for-the-badge)

---

## 🎯 Project Overview

This project explores **retail shipment and delivery performance** using Excel-based data analysis.

The core evaluation focuses on **Service Level Agreement (SLA) performance, shipment weight, delivery delays, and transit modes** to pinpoint operational bottlenecks rather than just reporting high-level numbers.

---

## 🏢 Business Questions

The analysis answers five practical questions an Operations Manager would ask:

1. 🚚 **SLA Baseline:** What percentage of total shipments arrive on time?
2. 📦 **Volume Distribution:** Which weight categories contain the most shipments?
3. ⏱️ **Delay Risk:** Which weight categories experience the highest failure rates?
4. 🔎 **Delay Drivers:** Which segments account for the largest share of overall late orders?
5. 🚢 **Transit Mode Context:** How does shipment mode impact overall logistics performance?

---

## 📊 Executive Snapshot

> [!IMPORTANT]
> **Key Operational Takeaway:** **Heavy shipments ($>4,000\text{g}$)** represent the primary area requiring operational review. While making up **54.25% of total shipment volume**, they account for **76.4% of all recorded delays**.

| Key Performance Indicator (KPI) | Result | Operational Significance |
| :--- | :---: | :--- |
| **Total Shipments Evaluated** | `10,998` | Full network volume |
| **On-Time SLA Rate** | `59.67%` | Baseline network throughput |
| **Delayed SLA Rate** | `40.33%` | Target area for operational efficiency |
| **Largest Weight Category** | **Heavy (54.25%)** | Comprises >50% of total cargo |
| **Heavy Shipment Delay Rate** | **56.80%** | >15% higher delay rate than total average |
| **Heavy Share of Total Delays** | **76.40%** | Concentrates 3 out of every 4 late orders |
| **Maritime (Ship) Volume Share** | **67.85%** | Primary operational transit mode |
| **Heavy + Ship Share of All Delays** | **52.00%** | Single largest delay combination |

---

## 📦 Shipment Distribution & SLA Performance

### Volume Breakdown by Weight Category

The dataset divides cargo into three standard operational classes based on package weight:

* **Heavy:** $> 4,000\text{g}$
* **Medium:** $2,000\text{g} - 4,000\text{g}$
* **Light:** $< 2,000\text{g}$

| Weight Class | Shipments | Volume Share | Operational Context |
| :--- | :---: | :---: | :--- |
| 🔴 **Heavy** | `5,966` | **54.25%** | Dominates freight capacity & warehouse handling |
| 🟠 **Light** | `3,245` | **29.51%** | Standard parcel volume |
| 🟢 **Medium** | `1,787` | **16.25%** | Smaller parcel volume |
| **Total** | `10,998` | **100.0%** | Full dataset scope |

---

### Delivery Performance Matrix

| Weight Class | Total Orders | Late Orders | On-Time Orders | Late % | On-Time % |
| :--- | :---: | :---: | :---: | :---: | :---: |
| 🔴 **Heavy** | `5,966` | `3,389` | `2,577` | **56.8%** | `43.2%` |
| 🟠 **Light** | `3,245` | `1,046` | `2,199` | **32.2%** | `67.8%` |
| 🟢 **Medium** | `1,787` | `1` | `1,786` | **0.1%** | `99.9%` |
