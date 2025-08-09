# LUX–Edificio–Core 🏢⚙️
**Private Node Optimization Project – Infrastructure Build**

This repository documents the **planning and operation** of a private high-performance GPU compute node in a residential rental environment.  
Goal: Build operational expertise with GPU infrastructure, generate rental income, and scale toward a self-owned compute facility.

---

## 🎯 Objectives
- Operate a single-node GPU workstation with **free electricity** in a rental environment
- Generate monthly income via compute-sharing platforms (e.g., Vast.ai)
- Optimize power usage to stay within residential consumption limits
- Reinvest profits into additional used GPUs for gradual scaling
- Long-term relocation and expansion to Paraguay for **ultra-low power costs** and flexible zoning

---

## 🧰 Hardware & Profit Estimates (CAD)

| GPU               | Price   | Power Draw | Monthly kWh | Earnings | Profit | Break Even |
|-------------------|---------|------------|-------------|----------|--------|------------|
| GTX 1080 *(owned)*| $0      | 180W       | 129.6       | $40      | $40    | Immediate  |
| RTX 3060 *(used)* | $310    | 200W       | 144.0       | $125     | $125   | 2.48 mo    |
| RTX 3090 *(new)*  | $1,700  | 350W       | 252.0       | $315     | $315   | 5.4 mo     |

> ⚠️ Based on 24/7 uptime, **free electricity**, and average Vast.ai market rates.

---

## 🛠️ Node Zero – Current Setup
1. Build initial node with **GTX 1080** for configuration & testing
2. Install **Ubuntu Server LTS** or **Pop!_OS** (NVIDIA optimized)
3. Configure **Docker + NVIDIA Container Toolkit**
4. Verify GPU availability with `nvidia-smi`

---

## 🌐 Vast.ai Provider Setup
- Price slightly below market to ensure consistent rentals
- Enable **Spot Buyer Access** for long-term clients
- Use `nvidia-smi -pl <watts>` for power capping

---

## ⚡ Power Budget Strategy
- Reduce household appliance usage to prioritize GPU power
- Switch to LED lighting
- Track usage via `nvidia-smi` and plug-in meters
- Target total **500–600 kWh/month** to stay stable

---

## 📈 Growth Timeline
| Month | Milestone |
|-------|-----------|
| 1     | Deploy GTX 1080 and optimize |
| 2     | Acquire used 3060 with rental income |
| 3–4   | Buy RTX 3090 using savings/profits |
| 5–6   | Test power draw ceiling |
| 6–12  | Rotate uptime across multiple GPUs |
| 12+   | Begin Paraguay relocation planning |

---

## 🇵🇾 Paraguay Expansion – LUX Edificio
- Power cost: **$0.01/kWh** hydroelectric
- 5-story compute building with passive well water cooling
- Capacity target: **250+ GPUs in 12–24 months**
- Lease capacity for AI, rendering, ML workloads
- No crypto mining — focus on stable, long-term hosting

---

## 📂 Folder Structure

```
/docs
├── scale-plan.md
├── gpu-tracker.md
└── income-log.xlsx

/logs
├── node-zero-setup.md
└── vast-uptime-log.md

/scripts
├── **gpu-healthcheck.sh**
└── **auto-reboot.sh**
```

---

## ✅ Next Steps
- [x] Test GTX 1080 on Vast.ai
- [x] Monitor power draw & income
- [ ] Add 3060 if profitable
- [ ] Acquire RTX 3090
- [ ] Confirm income stability
- [ ] Begin Paraguay site planning

---

**Power-included. Zero debt. Self-scaling.**  
