# LUX–Edificio–Core 🏢⚙️

**Private Node Optimization Project – Infrastructure Build**

This repository documents the planning and execution of a private high-performance compute node operated within a residential setting. The goal is to develop hands-on operational experience with GPU infrastructure and scale into a profitable, self-funded compute asset using used GPUs and existing hardware.

---

## 🎯 Objective

- Operate a single-node GPU workstation from a residential rental with **power included**
- Generate monthly income through compute-sharing platforms
- Optimize power usage to stay within typical residential consumption limits
- Use profits to acquire additional used GPUs and expand capacity gradually
- Relocate and scale into **Paraguay** long-term with ultra-low energy costs and flexible zoning

---

## 🧰 Hardware Strategy (Used GPUs – CAD)

| GPU            | Purchase Price (CAD) | Power Draw (Watts) | Monthly kWh | Monthly Earnings (CAD) | Monthly Profit (CAD) | Months to Break Even |
|----------------|----------------------|---------------------|-------------|--------------------------|------------------------|------------------------|
| GTX 1080       | $0 (already owned)   | 180W                | 129.6       | $40                      | $40                    | 0.00                   |
| RTX 3060 (Used)| $310                 | 200W                | 144.0       | $125                     | $125                   | 2.48                   |
| RTX 3090 (New) | $1,700               | 350W                | 252.0       | $315                     | $315                   | 5.40                   |

⚠️ *All estimates assume 24/7 uptime, free electricity, and average Vast.ai market rates.*

> Starlink is the only networking device. No router, no ISP charges. Household energy usage is minimized to optimize GPU power availability.

---

## 🛠️ Setup Plan (Node Zero – Current Rental)

### ✅ Build Node Zero

- Use GTX 1080 initially to configure and test
- Install Ubuntu Server LTS or Pop!_OS (NVIDIA optimized)
- Set up Docker + NVIDIA Container Toolkit
- Confirm setup using `nvidia-smi`

### ✅ Join Vast.ai as a Provider

- Set price slightly below average market
- Enable “Spot Buyer Access” for long-term clients
- Use `nvidia-smi -pl <watt>` to control card usage

### ⚡ Power Budget Strategy

- Reduce household appliance use to prioritize GPUs
- Replace bulbs with LED
- Track usage via `nvidia-smi` and plug-in meters

### 🔁 Reinvest & Expand

- Monitor uptime, usage, and rental income
- Reinvest into 3060 → 3090 → larger setups
- Stay within 500–600 kWh/month for consistent performance

---

## 📈 Sample Growth Timeline

| Month | Milestone                            |
|--------|--------------------------------------|
| 1      | Deploy GTX 1080 and optimize         |
| 2      | Buy used 3060 with rental income     |
| 3–4    | Use savings to acquire RTX 3090      |
| 5–6    | Test total power draw ceiling        |
| 6–12   | Rotate uptime for multiple GPUs      |
| 12+    | Begin relocation planning to Paraguay|

---

## 🌐 Platforms for Profit

| Platform | Purpose               | Link                                      |
|----------|------------------------|-------------------------------------------|
| Vast.ai  | GPU rental marketplace | [vast.ai/console/provider](https://vast.ai/console/provider/) |

---

## 🇵🇾 Paraguay Plan – LUX Edificio

- $0.01/kWh hydroelectric power
- Build high-efficiency 5-story compute building
- Passive water-cooling from natural well
- Scale to 250+ GPUs over 12–24 months
- Lease GPU capacity for AI, rendering, and ML training

---

## 🧠 Philosophy

> This is **not** a commercial data center.  
> It’s a personal infrastructure project designed for efficiency, education, and long-term ownership.  
> No crypto, no hype — just a hosting experiment focused on long-term capacity growth.

---

<pre>
### 📂 Recommended Folder Structure

```
/docs
  ├── scale-plan.md
  ├── gpu-tracker.md
  └── income-log.xlsx

/logs
  ├── node-zero-setup.md
  └── vast-uptime-log.md

/scripts
  ├── gpu-healthcheck.sh
  └── auto-reboot.sh
```
</pre>

---

## ✅ Next Steps

- ✅ Test GTX 1080 on Vast.ai  
- ✅ Monitor power draw and rental income  
- ⬜ Add 3060 if profitable  
- ⬜ Save for RTX 3090 (new)  
- ⬜ Test income stability  
- ⬜ Begin Paraguay site research  

> Power-included. Zero debt. Self-scaling.
