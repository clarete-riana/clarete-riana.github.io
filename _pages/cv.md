---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Professional Experience

**Senior Principal Engineer** · Hewlett Packard Enterprise (HPE) Labs  
*Present*

Research and development in high-performance computing, disaggregated memory architectures, Fabric Attached Memory (FAM), distributed storage systems (DAOS, OpenFAM), and resilient computing frameworks. Inventor on 32 patents; 15 peer-reviewed publications.

---

## Service & Leadership

**Industry Track Chair**, IEEE IC2E 2026  
**Industry Track Program Chair**, IEEE IC2E 2024–2025  
**SNIA Technical Council Advisor**  
· Reviewed 70+ abstracts on NVMe-over-Fabrics, CXL, FAM, and memory tiering  
· Shapes strategic direction for HPC storage standards  

**Program Committee Member**, HPE Tech Con 2025–2026  
**Reviewer**, HPE Tech Con 2023–2024  

---

## Patents

32 patents total — 3 granted US patents, 1 granted India patent, 1 granted in India; 29+ pending across US, Germany, China, and India.

| Patent ID | Title | Status |
|-----------|-------|--------|
| P169404US | Client Allocation of Memory Across Memory Servers | **In Force** (Apr 2025) |
| P169427US | Client Update of Data Modification Tracking Structure | **In Force** (Oct 2024) |
| P171698US | Incremental Data Backup Using a Combined Tracking Data Structure | **In Force** (Oct 2025) |
| 710230247US01 | Efficient Management of Data Structures Stored in Remote Memory | **In Force** (Oct 2023) |
| 710226946IN01 | Method and Apparatus for Selective Erase of Persistent and Non-volatile Memory Devices | **In Force** (Jun 2023) |
| P178162US | Symmetric Heap-Based Work-Stealing Framework for Resilient Distributed Systems | Pending |
| P176945US | Multi-Tiered Global Cache | Pending |
| P176905US | Dynamic Modification of Global Cache Capacity | Pending |
| P176397US | Cache Management for Multiple Applications | Pending |
| P173871US | Efficient Burst Sort Based on Network-Attached Memory | Pending |
| P171582US | Auto-Scaling, Resilient, and Load Balancing Framework for Workload Deployment | Pending |
| P178527USPRV | Memory Management for In-Memory Databases and Query Engines for Agentic AI Systems | Pending |

[→ Full patent portfolio](/patents/)

---

## Publications

{% assign publications_sorted = site.publications | sort: 'date' | reverse %}
{% for post in publications_sorted %}
  {% include archive-single-cv.html %}
{% endfor %}
