
 PLASTIVORE
An autonomous robot that eats ocean plastic — and powers itself doing it.

<img width="473" height="462" alt="image" src="https://github.com/user-attachments/assets/ac0fcbfb-0141-4ea4-8ebe-252972534ef9" />


# 🌊 PLASTIVORE
### An autonomous robot that eats ocean plastic — and powers itself doing it.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Status: Open Concept](https://img.shields.io/badge/Status-Open%20Concept-blue)]()
[![Emissions: Zero](https://img.shields.io/badge/Toxic%20Emissions-ZERO-green)]()

---

## The Problem

The Great Pacific Garbage Patch (GPGP) contains an estimated **80,000 tons** of plastic — an area **7× the size of the Korean Peninsula**. Every year, **8 million more tons** enter the ocean.

Existing cleanup ships run on diesel. They emit CO₂, NOₓ, and SOₓ while cleaning.  
**They pollute the ocean while trying to clean it.**

---

## The Concept

PLASTIVORE is a boat-sized autonomous robot that:

1. **Collects** floating plastic via front-mounted nets and microfilters (≥0.1mm, 98% capture rate)
2. **Pyrolyzes** the plastic at 300°C in oxygen-free conditions — extracting combustible gas (CH₄, H₂) without producing dioxins
3. **Generates electricity** from the extracted gas via an onboard generator
4. **Powers itself** using that electricity combined with solar panels
5. **Emits only** H₂O and trace CO₂ after catalytic filtration — zero toxic byproducts

> Once deployed, it works until it stops. No refueling. No crew. No return to port.

---

## Energy Balance

| Source | Output |
|--------|--------|
| Solar panels (20m²) | +3.0 kW |
| Pyrolysis generator (10kg plastic/hr) | +2.0 kW |
| **Total Input** | **5.0 kW** |

| Consumption | Draw |
|-------------|------|
| Propulsion motor | -2.0 kW |
| Pyrolysis heating | -1.5 kW |
| Sensors / AI / Comms | -0.3 kW |
| **Total Consumption** | **3.8 kW** |

**Surplus: +1.2 kW → battery buffer**  
Solar alone sustains basic navigation in plastic-sparse zones.

---

## Why Pyrolysis, Not Combustion?

Direct combustion of plastic produces **dioxins, HCl, and benzene** — all toxic.  
Oxygen-free pyrolysis at 300°C does **not**.

Residual gases pass through a **catalytic secondary combustion filter** (800°C instantaneous) — a proven industrial method — before any emission. Only H₂O and trace CO₂ exit the system.

---

## Emissions Comparison

| | Diesel Cleanup Ship | PLASTIVORE |
|--|--|--|
| CO₂ | 2.6kg per liter of fuel | Trace (net carbon negative) |
| NOₓ / SOₓ | ✗ Emitted | ✓ Zero |
| Dioxins | ✗ Risk | ✓ Filtered |
| Refueling | Required | Not needed |
| Net impact | Pollutes while cleaning | Removes more than it emits |

---

## Projected Impact — 100 Unit Swarm

| Metric | Value |
|--------|-------|
| Plastic removed per year | ~876 tons |
| Additional CO₂ emitted | 0 kg |
| Continuous operation | 365 days |
| River mouth deployment | Block 10 key rivers → intercept 80% of ocean inflow |

---

## Prior Art

| Technology | Status |
|-----------|--------|
| PETase enzyme (plastic-degrading) | Exists — upgraded 2022 (FAST-PETase) |
| Pyrolysis generators | Exists — industrial scale |
| Autonomous marine vehicles (AUV) | Exists — military / research grade |
| **Self-sustaining plastic-to-power robot** | **Does not exist — this is the gap** |

---

## Roadmap

**Phase 1 — 2025–2026**  
Pyrolysis module development · Solar + generator integration · Tank prototype testing

**Phase 2 — 2027–2028**  
Open-sea trials · AI swarm navigation · Emissions validation

**Phase 3 — 2029+**  
Swarm deployment at GPGP · Key river mouth installations · Full open-source hardware release

---

## License

[Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)  
No patents. No profit motive. Use it, build it, improve it — just credit the source.

---

## Contributing

This is a **public interest concept project**.  
Engineers, marine biologists, roboticists, material scientists, and funders are all welcome.

**Devs & builders — thoughts welcome!**  
📧 andogi@naver.com

---

*The ocean belongs to everyone.*
