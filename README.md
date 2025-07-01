# LUX-Edificio-Core 🏢⚙️  
**Private Node Optimization Project – Stealth Infrastructure Build**

This repository documents the planning and execution of a private high-performance compute node operated within a residential setting. The goal is to develop hands-on operational experience with GPU infrastructure while maintaining low visibility and maximum efficiency. All deployments begin with existing equipment and used GPUs, scaling over time into a self-funded compute asset.

---

## 🎯 Objective

- Operate a single-node GPU workstation from a residential rental with **power included**
- Generate monthly income through compute-sharing platforms
- Avoid drawing attention to power usage by staying under normal residential consumption levels
- Use profits to acquire additional used GPUs and expand capacity gradually
- Relocate and scale into Paraguay long-term with ultra-low energy costs and zoning freedom

---

## 🧰 Hardware Strategy (Used GPUs – CAD)

| GPU              | Purchase Price (CAD) | Power Draw (Watts) | Monthly kWh | Monthly Earnings (CAD) | Monthly Profit (CAD) | Months to Break Even |
|------------------|----------------------|--------------------|-------------|------------------------|----------------------|----------------------|
| GTX 1080         | $0 (already owned)   | 180W               | 129.6 kWh   | $40                    | $40                  | 0.00 months          |
| RTX 3060 (Used)  | $310                 | 200W               | 144.0 kWh   | $125                   | $125                 | 2.48 months          |
| RTX 3090 (New)   | $1,700               | 350W               | 252.0 kWh   | $315                   | $315                 | 5.40 months          |

> ⚠️ All estimates assume 24/7 uptime, **free electricity**, and average **Vast.ai** market rates.  
> Starlink is the only networking device. No router, no ISP charges. Household usage is minimized to preserve GPU budget.

---

## 🛠️ Setup Plan (Node Zero – Current Rental)

1. **Build Node Zero**
   - Use GTX 1080 initially to configure and test
   - Install Ubuntu Server LTS or Pop!_OS (NVIDIA optimized)
   - Set up Docker + NVIDIA Container Toolkit
   - Confirm setup using `nvidia-smi`

2. **Join Vast.ai as a Provider**
   - Set price slightly below average market
   - Enable “Spot Buyer Access” for long-term clients
   - Use `nvidia-smi -pl <watt>` to control card usage

3. **Power Budget Strategy**
   - Unplug main fridge, only run baby fridge-freezer
   - Replace bulbs with LED and limit appliance use
   - Track usage via `nvidia-smi` and plug-in meters

4. **Reinvest & Expand**
   - Track uptime, usage, and rental income
   - Reinvest into 3060 → 3090 → larger setups
   - Stay below 500–600 kWh/month to stay unnoticed

---

## 🔁 Sample Growth Timeline

| Month | Milestone                            |
|-------|---------------------------------------|
| 1     | Deploy GTX 1080 and optimize          |
| 2     | Buy used 3060 with rental income      |
| 3–4   | Use savings to acquire RTX 3090       |
| 5–6   | Test total power draw ceiling         |
| 6–12  | Rotate uptime for multiple GPUs       |
| 12+   | Begin relocation planning to Paraguay |

---

## 🌐 Platforms for Profit

| Platform       | Purpose                 | Link                                 |
|----------------|-------------------------|--------------------------------------|
| Vast.ai        | GPU rental marketplace  | (https://vast.ai/console/provider/) |
---

## 📈 Paraguay Plan – LUX Edificio

- $0.01/kWh hydroelectric power
- Build disguised 5-story compute building
- Passive water-cooling from natural well
- Scale to 250+ GPUs over 12–24 months
- Lease GPU capacity for AI, rendering, ML training

---

## 🧠 Philosophy

> This is not a “data center.”  
> It’s a private infrastructure project designed for stealth, efficiency, and self-funding growth.  
> No crypto, no hype — just a pure hosting experiment.

---

## 📂 Folder Structure (Recommended)

/docs
	•	scale-plan.md
	•	gpu-tracker.md
	•	income-log.xlsx

/logs
	•	node-zero-setup.md
	•	vast-uptime-log.md

/scripts
	•	gpu-healthcheck.sh
	•	auto-reboot.sh

---

## ✅ Next Steps

- ✅ Test GTX 1080 on Vast.ai
- ✅ Monitor power draw and rental income
- ⬜ Add 3060 if profitable
- ⬜ Save for RTX 3090 (new)
- ⬜ Test income stability
- ⬜ Begin Paraguay site research

---

**Stealth-first. Power-included. Zero debt. Self-scaling.**
