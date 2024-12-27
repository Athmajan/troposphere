# Automated Tropospheric Ducting and External Interference Prediction System

## Overview
This project demonstrates a solution I developed during my tenure at **Dialog Axiata PLC**. While company policy restricts the sharing of source code, this repository explains the basic operations and design principles of the system.

### What is Tropospheric Ducting?
Tropospheric ducting is a natural phenomenon that affects radio wave propagation. It occurs when variations in atmospheric conditions create layers that trap radio waves, allowing them to travel long distances. This can result in interference between communication systems that rely on consistent radio wave behavior.

**Learn more:** [DX Info Centre Tropospheric Ducting Predictions](https://dxinfocentre.com/)

### Problem Statement
Dialog Axiata operates a vast network of over 9,700 base station sites across Sri Lanka, covering approximately 91% of the country's landmass and 99% of the population. These include:
- **2G Base Stations:** 4,800+ sites
- **4G Base Stations:** 4,900+ sites

**Customer Base (as of June 30, 2024):**
- **Total Customers:** 16,680,385
  - Prepaid Customers: 15,192,245
  - Postpaid Customers: 1,488,140

Tropospheric ducting, combined with other sources of external interference, often disrupts customer experience, leading to increased complaints and operational inefficiencies. Engineers relied on manual weather observations and instinct-based grouping to predict interference and optimize base station configurations, a process that was reactive and time-consuming.

### The Solution
I developed an automated system to:
1. **Ingest Data:**
   - Collect tropospheric ducting predictions.
   - Aggregate external interference measurements from base stations.
2. **Classification Algorithm:**
   - Group base stations into clusters based on interference levels, ensuring minimal external interference and inter-group interference.
3. **Automated Alerts:**
   - Send proactive email alerts to engineering, finance, and executive teams about areas likely to experience interference.
   - Include recommendations for configuration changes to mitigate disruption.
4. **Operational Efficiency:**
   - Automate configuration scripts and schedule downtimes in advance, reducing manual workload.
5. **Data Analytics:**
   - Store structured and unstructured data for future business intelligence and decision-making tasks.

### Key Benefits
1. **Enhanced Customer Experience:**
   - Reduced customer complaints due to proactive interference mitigation.
   - Streamlined complaint handling process.
2. **Improved Operational Efficiency:**
   - Transitioned from a reactive to a proactive approach in interference management.
   - Enabled engineers to save significant time previously spent on manual observations.
3. **Business Intelligence:**
   - Provided meaningful data for advanced analytics and strategic decision-making.

### How It Works
1. **Data Collection:**
   - External interference measurements from base stations.
   - Tropospheric ducting predictions from reliable sources.
2. **Data Processing:**
   - Develop classification algorithms to group base stations optimally.
3. **Proactive Alerting:**
   - Automated email alerts sent to subscribers (engineering team, finance team, CEO office).
4. **System Integration:**
   - Generate configuration change scripts and schedule downtime planning.

### Impact
The automated system transformed manual, reactive processes into digitized, proactive workflows. By optimizing base station configurations and delivering timely alerts, the solution not only enhanced operational efficiency but also improved customer satisfaction and complaint handling.

<div style="display: flex; justify-content: space-around; align-items: center;" style="margin: 50px 0;">
<img src="https://github.com/Athmajan/athmajan/blob/main/tropospheric.gif" alt="tropospheric prediction" width="70%">
</div>

---

### Note
The source code cannot be shared publicly due to company policy, but the principles and operations outlined here offer a high-level understanding of the solution's impact and design.

