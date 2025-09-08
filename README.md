# NE230 Benchmark System

This repository contains materials and simulations related to the **NE230 Benchmark System**, a test system based on the Northeast (NE) electrical power subsystem of the **Brazilian Interconnected Power System (BIPS)**. It serves as a platform for studying **frequency stability** in power systems with high penetration of **converter-interfaced generation (CIG)** from **renewable energy sources (RESs)**, particularly **wind and solar**.

## Overview

The NE subsystem of the BIPS is notable for its large-scale integration of renewable energy. As of 2020, it hosted nearly 90% of Brazil's 16 GW installed wind power capacity, distributed across 751 wind farms and 8,800 wind turbines. According to Brazil's **2032 Energy Expansion Plan**, the region is expected to add another 10 GW of CIG-based renewable capacity, while conventional generation (hydro and fossil fuels) remains constant.

This evolving energy landscape raises concerns about **frequency stability**, **system inertia**, and **primary frequency control**, especially during contingency events. The NE230 Benchmark System provides a geographically-based model of the NE subsystem to explore these challenges and evaluate potential solutions.

## Tools Used

- **ANAREDE** – Network analysis software by CEPEL
- **ANATEM** – Electromechanical transient analysis software by CEPEL
- **PACDYN** – Small-signal stability analysis software by CEPEL

## Purpose

The repository aims to:

- Simulate and analyze frequency stability scenarios in the NE subsystem.
- Investigate the impact of high CIG penetration on system inertia.
- Explore strategies for enhancing local frequency support and resilience.

> ⚠️ Note: The NE subsystem is modeled from a geographical perspective, which differs from the operational boundaries used by Brazil's National System Operator (ONS). While current operations do not exhibit the frequency issues discussed, the benchmark highlights potential future risks and the need for proactive solutions.

## References

1. CEPEL ANAREDE User Manual  
2. CEPEL ANATEM User Manual  
3. CEPEL PACDYN User Manual  
4. ABEEólica, 2022 – Brazilian Wind Energy Association  
5. EPE, 2022 – Energy Research Company, PDE 2032

---

## License  
This repository is released under the **MIT License**. 