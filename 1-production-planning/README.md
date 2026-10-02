# 🏭 Production Planning & Control (PPC) Operations Hub

## 📌 Executive Summary
The **Production Planning & Control (PPC) Operations Hub** is an advanced operational intelligence system designed to serve as the "Single Source of Truth" for Shayan Diesel's manufacturing ecosystem. This dashboard integrates data from production lines, assembly floors, quality control, and commercial departments into a unified interface, enabling real-time, data-driven decision-making. By eliminating information silos, this system allows management to optimize production throughput, minimize lead times, and proactively manage inventory health.

## 🎥 Dashboard Overview
![Production Planning Operations Hub](production-planning.gif)

---

## 📊 Detailed Operational Modules

### 1. Production Achievement Analysis
*   **Concept:** This module benchmarks actual production output against the Master Production Schedule (MPS).
*   **Deep Dive:** It goes beyond simple counting by calculating "Variance Analysis." It tracks whether the factory is meeting daily quotas relative to sales forecasts. By visualizing deviations, management can instantly see if the factory is falling behind, allowing for immediate corrective action on resources or shifts to recover the schedule.

### 2. Production Stages Average
*   **Concept:** Monitors the average cycle time (Turnaround Time) required for a unit to pass through a specific workstation.
*   **Deep Dive:** This identifies "hidden time" in the process. By monitoring the average time per stage, the system flags workstations that consistently exceed standard processing time, indicating either technical equipment issues, skill gaps in the workforce, or logistical delays.

### 3. Comparison of Production Stages
*   **Concept:** A benchmarking tool that compares the efficiency and throughput velocity of different manufacturing phases.
*   **Deep Dive:** This is essential for "Line Balancing." It highlights synchronization issues where one stage moves too fast for the next, causing an accumulation of Work-in-Progress (WIP). This module ensures a smooth, rhythmic flow across the factory floor.

### 4. Painting Unit
*   **Concept:** Dedicated monitoring of the chassis painting and surface finishing process.
*   **Deep Dive:** Due to the sensitivity of this stage, this module tracks throughput, rework rates (due to defects), and curing times. It helps minimize the risk of bottlenecks at the painting station, ensuring that the critical final protective layers are applied without compromising the overall lead time.

### 5. Commercialization Process
*   **Concept:** Manages the administrative and technical workflow required to transition a finished vehicle into a legally market-ready asset.
*   **Deep Dive:** This tracks the lifecycle of documentation, compliance checks, and legal approvals. It provides the sales department with transparency regarding how many units are currently moving through the "legalization pipeline" and when they can realistically be promised to customers.

### 6. Commercial Status
*   **Concept:** Provides a real-time snapshot of marketability for all finished inventory.
*   **Deep Dive:** This distinguishes between physical availability and commercial availability. It tracks statuses like "Ready for Sale," "Awaiting Licensing," or "Allocated/Reserved." This prevents the sales team from promising vehicles that are physically finished but legally restricted.

### 7. Finished Goods Inventory
*   **Concept:** A comprehensive overview of current stock levels and inventory turnover rates.
*   **Deep Dive:** This module focuses on asset liquidity. It monitors "Inventory Aging," identifying which models are selling fast and which are accumulating in the yard. This data is critical for Demand Planning and prevents the overproduction of slower-moving SKUs.

### 8. Pre-Delivery Inspection (PDI)
*   **Concept:** The final quality gateway before a vehicle is cleared for shipping or customer handover.
*   **Deep Dive:** This tracks "First Pass Yield" (FPY)—the percentage of units that pass inspection on the first attempt. It captures critical technical data (brakes, electronics, engine performance) and serves as the ultimate safeguard for brand reputation and safety compliance.

### 9. Kit & Cab Assembly Status
*   **Concept:** Manages the readiness of critical sub-assemblies (the "Kit" and the "Cab") that must be integrated with the chassis.
*   **Deep Dive:** This is a supply-chain-sensitive module. If components for the cab or wings are missing, the entire assembly line halts. By monitoring this, the system acts as an early-warning trigger for the logistics/purchasing department to ensure JIT (Just-in-Time) delivery of parts.

### 10. Uncommercialized Chassis
*   **Concept:** An "Exception Reporting" system that isolates units that cannot be sold due to technical, quality, or documentation blocks.
*   **Deep Dive:** This module focuses on "Blocked Capital." It categorizes the root causes of why a chassis is uncommercialized (e.g., QC failure, missing paperwork, pending repair). By quantifying these blocked assets, management can prioritize and allocate resources to "unlock" these vehicles and generate revenue.

---

## 🛠️ Technical Stack & Implementation
*   **Data Model:** Advanced relational data modeling via **Power Pivot**, linking heterogeneous data sources (production logs, inventory, and commercial records).
*   **Dynamic UI:** A robust, VBA-free interface that utilizes object linking and interactive navigation for a seamless, app-like experience.
*   **Advanced Logic:** Leverages dynamic array functions (`FILTER`, `XLOOKUP`, `INDEX/MATCH`) to ensure the dashboard reflects live data changes without manual intervention.

## 📈 Strategic Business Value
1. **Bottleneck Identification:** Management can pinpoint delays in real-time, drastically reducing "Work-in-Progress" (WIP) time.
2. **Quality Assurance:** Integrated QC modules prevent defective units from ever reaching the shipping dock.
3. **Optimized Inventory:** Tight coupling between production output and commercial status improves inventory turnover, optimizing cash flow and minimizing dead stock.
