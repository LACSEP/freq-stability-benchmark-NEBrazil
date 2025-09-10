# NE232 Benchmark System

This repository contains materials and simulations related to the **NE232 Benchmark System**, a test system based on the Northeast (NE) electrical power subsystem of the **Brazilian Interconnected Power System (BIPS)**. It serves as a platform for studying **frequency stability** in power systems with high penetration of **converter-interfaced generation (CIG)** from **renewable energy sources (RESs)**, particularly **wind and solar**.

## Overview

The NE subsystem of the BIPS is notable for its large-scale integration of renewable energy. As of 2020, it hosted nearly 90% of Brazil's 16 GW installed wind power capacity, distributed across 751 wind farms and 8,800 wind turbines. According to Brazil's **2032 Energy Expansion Plan**, the region is expected to add another 10 GW of CIG-based renewable capacity, while conventional generation (hydro and fossil fuels) remains constant.

This evolving energy landscape raises concerns about **frequency stability**, **system inertia**, and **primary frequency control**, especially during contingency events. The NE232 Benchmark System provides a geographically-based model of the NE subsystem to explore these challenges and evaluate potential solutions.

## Tools Used (Currently Available)

The following tools from CEPEL are currently available for system analysis:

- **ANAREDE** – Network analysis software by CEPEL  
- **ANATEM** – Electromechanical transient analysis software by CEPEL  
- **PACDYN** – Small-signal stability analysis software by CEPEL  

> *Note: Further implementations such as PSS/E, POWERFACTORY, and EMTP are not currently available.*



## Purpose

The repository aims to:

- Simulate and analyze frequency stability scenarios in the NE subsystem.
- Investigate the impact of high CIG penetration on system inertia.
- Explore strategies for enhancing local frequency support and resilience.

> ⚠️ Note: The NE subsystem is modeled from a geographical perspective, which differs from the operational boundaries used by Brazil's National System Operator (ONS). While current operations do not exhibit the frequency issues discussed, the benchmark highlights potential future risks and the need for proactive solutions.

## License  
This repository is released under the **MIT License**. 