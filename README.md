# vast-gpu-rental-node 🏢⚙️
**Concept Archive – Private GPU Rental Node**

This repo documents a **past experiment and planning exercise** for running a high-performance GPU node in a rental apartment and renting it out via platforms like Vast.ai.

It is kept as an **archived concept** for infrastructure + economics learning.  
I am not actively building or operating this node today.

---

## 🎯 Original Objectives

- Run a single GPU workstation with effectively **free electricity** in a rental.
- Rent the GPU out on compute-sharing platforms (e.g. Vast.ai).
- Track power usage and profitability.
- Use profits to buy more used GPUs and scale.

---

## 🧰 Hardware & Profit Sketch (CAD, historic estimate)

| GPU               | Price   | Power Draw | Monthly kWh | Earnings | Profit | Break Even |
|-------------------|---------|-----------:|------------:|---------:|-------:|-----------:|
| GTX 1080 *(owned)*| $0      | 180 W      | 129.6       | $40      | $40    | Immediate  |
| RTX 3060 *(used)* | $310    | 200 W      | 144.0       | $125     | $125   | 2.5 mo     |
| RTX 3090 *(new)*  | $1,700  | 350 W      | 252.0       | $315     | $315   | 5.4 mo     |

> ⚠️ Back-of-envelope numbers assuming **24/7 uptime**, free power, and average historic Vast.ai rates.  
> Not financial advice and no longer maintained.

---

## 🛠️ Node Zero – Lab Setup (Historic)

1. Build initial node with **GTX 1080** for configuration & testing.
2. Install **Ubuntu Server LTS**.
3. Configure **Docker + NVIDIA Container Toolkit**.
4. Verify GPU availability with `nvidia-smi`.
5. Register node with Vast.ai and tune pricing / power limits.

---

## ⚡ Power & Ops Notes

- Use `nvidia-smi -pl <watts>` for power capping.
- Monitor stability, temperature, and uptime.
- Track income vs. wear-and-tear and risk.

---

## 📂 Folder Structure

```text
docs/
  scale-plan.md
  gpu-tracker.md
  income-log.md

logs/
  node-zero-setup.md
  vast-uptime-log.md

scripts/
  gpu-healthcheck.sh
  auto-reboot.sh
