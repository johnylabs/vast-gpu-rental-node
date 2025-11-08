# 🏗️ vast-gpu-rental-node

This document outlines the step-by-step growth plan for expanding the vast-gpu-rental-node GPU node project from a single-node residential deployment into a high-capacity compute facility located in Paraguay.

---

## 🔰 Phase 1: Residential Bootstrap (Months 0–3)

**Location:** Current rental (with power included)  
**Hardware:** GTX 1080 → RTX 3060 → RTX 3090  
**Power Target:** Under 500–600 kWh/month

### Goals:
- Achieve operational uptime >95%
- Hit minimum profitability with 1080 and 3060
- Reinvest 100% of rental income into new hardware
- Validate long-term rental demand on Vast.ai

---

## 🔁 Phase 2: Incremental Scaling (Months 4–12)

**Location:** Still in rental  
**Hardware Strategy:**  
- Add 3090 or equivalent (based on earnings + savings)  
- Continue purchasing used cards only (maximize ROI)

### Upgrades:
- GPU Count: 1 → 3+
- Add GPU power limit automation (`nvidia-smi -pl`)
- Introduce monitoring scripts (e.g., power, income logs)
- Consider rackmount case or GPU cradle for airflow

---

## 🇵🇾 Phase 3: Paraguay Relocation Prep (Months 10–12)

**Research Tasks:**
- Identify city with consistent power and lax zoning (e.g., outskirts of Asunción)
- Compare cost of land purchase vs long-term rental
- Check Starlink viability and backup internet options
- Plan passive cooling and physical security

**Financial Milestones:**
- $300–500/month stable income
- Break even on 3090 investment
- Build $1,000+ hardware reinvestment buffer

---

## 🏢 Phase 4: LUX Edificio Launch (Year 2)

**Infrastructure Concept:**
- Five-story modular structure (one floor at a time)
- Passive water-cooled intake via natural well
- 250+ GPU capacity across the full build

**Key Features:**
- $0.01/kWh hydroelectric power
- No crypto rigs — all AI/render training capacity
- Custom racks, vertical cabling, and remote monitoring
- Separate power zones for redundancy and upgrades

---

## 📊 Capacity Planning

| Phase        | GPU Count | Monthly Profit | Power Budget | Key Constraint              |
|--------------|-----------|----------------|---------------|-----------------------------|
| Bootstrap    | 1–2       | $40–$125        | 250–350 kWh   | Learning + config time      |
| Scaling      | 3–5       | $250–$500       | 600 kWh       | Physical space              |
| Edificio 1F  | 15–25     | $1,200–$2,000   | 2,000+ kWh    | Network stability (Starlink)|
| Edificio 3F+ | 100+      | $5,000+/mo      | 8,000+ kWh    | Cooling, scaling hardware   |

---

## 🔒 Notes & Policies

- **No crypto**: Focus on real workload rentals (rendering, LLMs, AI)
- **No debt**: Scale only from profit and reinvested surplus
- **No hidden ops**: Everything documented publicly as a learning archive

---

## ✅ Current Status

- [x] Node Zero live with GTX 1080  
- [x] Monitoring power/income  
- [ ] 3060 upgrade in progress  
- [ ] 3090 + income stabilization  
- [ ] Paraguay site research (location + cost + internet)  
