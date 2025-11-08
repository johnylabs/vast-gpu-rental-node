# 🖥️ GPU Tracker – vast-gpu-rental-node

This document tracks all GPUs currently used in the vast-gpu-rental-node project, including their status, usage, ROI, and deployment notes. Updated manually per upgrade cycle.

---

## 📦 Current GPU Inventory

| GPU Model  | Status         | Location       | Source      | Cost (CAD) | Notes                        |
|------------|----------------|----------------|-------------|------------|------------------------------|
| GTX 1080   | Active         | Node Zero      | Already Owned | $0        | Initial test + setup card   |
| RTX 3060   | Planned        | Node Zero      | Facebook Used | $310      | Pending purchase after ROI  |
| RTX 3090   | Planned (New)  | Node Zero      | Retail       | $1,700     | Target after 3060 payoff     |

---

## 🔁 GPU Deployment History

| GPU        | Deployed On | Uptime (%) | Power (W) | Monthly kWh | Earnings/mo | Profit/mo | Break-Even Time |
|------------|-------------|------------|-----------|-------------|-------------|-----------|-----------------|
| GTX 1080   | 2025-08-01  | 97.5%      | 180W      | ~130 kWh    | $40         | $40       | 0.00 months     |
| RTX 3060   | TBD         | —          | 200W      | ~144 kWh    | $125 est.   | $125 est. | 2.48 months     |
| RTX 3090   | TBD         | —          | 350W      | ~252 kWh    | $315 est.   | $315 est. | 5.40 months     |

---

## 🔍 Power Tracking Summary

| Month      | Total GPUs | Total Power Used (kWh) | Power Limit Strategy            | Target kWh Ceiling |
|------------|------------|------------------------|----------------------------------|--------------------|
| 2025-08    | 1 (GTX1080) | 130 kWh                | nvidia-smi -pl 150W              | 500–600 kWh        |
| 2025-09    | (Est.) 2    | ~270 kWh               | 3060 capped at 180W              | 500–600 kWh        |
| 2025-10    | (Est.) 3    | ~522 kWh               | 3090 capped at 280W during peak  | 600 kWh hard cap   |

---

## ⚙️ Usage Notes

- All cards run 24/7 unless maintenance is needed
- Uptime monitored with `vast.ai` logs and external meters
- Manual reboots handled with `auto-reboot.sh`
- Earnings calculated from Vast.ai payout logs

---

## 🧠 Optimization Queue

- [ ] Script automated GPU health checks
- [ ] Monitor temp/power efficiency curve over time
- [ ] Explore vertical stacking airflow optimization
- [ ] Benchmark actual vs estimated power draw (plug meter vs nvidia-smi)
