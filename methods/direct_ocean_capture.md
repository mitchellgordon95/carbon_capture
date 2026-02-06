# Direct Ocean Capture (DOC) — Comprehensive Feasibility Assessment

## Lead Company: Captura (Caltech Spinoff)

**Last Updated:** February 2026
**Research Note:** Data sourced from DOE announcements, published technical analyses, company disclosures, academic literature, and industry reporting through mid-2025. Some projections are estimates based on published ranges and should be validated against latest disclosures.

---

## Table of Contents

1. [Technology Overview](#1-technology-overview)
2. [Physical Constraints](#2-physical-constraints)
3. [Resource Constraints](#3-resource-constraints)
4. [Throughput Metrics](#4-throughput-metrics)
5. [End Game — Storage](#5-end-game--storage)
6. [Economic Friction](#6-economic-friction)
7. [Additional Feasibility Data](#7-additional-feasibility-data)
8. [Scaling Analysis: Path to 10 Gt/year](#8-scaling-analysis-path-to-10-gtyear)
9. [Key Sources](#9-key-sources)

---

## 1. Technology Overview

### 1.1 Core Principle

The ocean contains approximately **140x the CO2 concentration of the atmosphere** (~2.2 mmol/kg dissolved inorganic carbon in seawater vs. ~420 ppm in air). Direct Ocean Capture exploits this concentration advantage by:

1. **Pumping seawater** through an electrochemical system
2. **Acidifying** a stream of seawater via electrodialysis (bipolar membrane electrodialysis, or BPMED), which shifts the carbonate equilibrium and forces dissolved CO2 out of solution
3. **Stripping the CO2** from the acidified water using a vacuum or gas-stripping membrane contactor
4. **Returning the decarbonized, re-alkalized seawater** to the ocean
5. The ocean, now locally undersaturated in CO2, **passively reabsorbs CO2 from the atmosphere** to restore equilibrium

This creates a net removal of CO2 from the atmosphere, mediated by the ocean.

### 1.2 Captura's Process (Electrodialysis Approach)

Captura, founded in 2021 as a spinoff from Caltech (based on work by Prof. Chengxiang "CX" Jin and Harry Atwater), uses **bipolar membrane electrodialysis (BPMED)** as its core electrochemical process:

```
Seawater In (pH ~8.1, rich in HCO3⁻ and CO3²⁻)
        │
        ▼
┌──────────────────────────┐
│  Bipolar Membrane        │
│  Electrodialysis (BPMED) │
│                          │
│  Acid stream (low pH)    │──► CO2 stripping (vacuum/membrane)──► Pure CO2
│  Base stream (high pH)   │──► Recombined with acid stream
└──────────────────────────┘
        │
        ▼
Decarbonized Seawater Out (re-alkalized, returned to ocean)
```

**Key chemistry:**
- In the BPMED stack, water is split into H⁺ and OH⁻ at bipolar membranes
- H⁺ ions acidify the seawater, converting bicarbonate (HCO₃⁻) and carbonate (CO₃²⁻) to dissolved CO₂
- The dissolved CO₂ is then easily stripped under mild vacuum or via membrane contactors
- The OH⁻ stream re-alkalizes the water before return to the ocean

### 1.3 "Parasitic Pumping" — The Efficiency Hack

Captura's key strategic insight: **co-locate with facilities that already pump massive volumes of seawater**, avoiding the enormous energy cost of ocean water pumping.

| Host Facility | Water Already Pumped | Parasitic Advantage |
|---|---|---|
| **Desalination plants** | 100,000–500,000+ m³/day | Tap into intake/brine streams |
| **Coastal power plants** (once-through cooling) | Millions of gallons/day | Cooling water contains same dissolved CO2 |
| **Offshore oil/gas platforms** | Produced water streams | Existing infrastructure in deep water |
| **LNG terminals** | Seawater for regasification | High-volume water already moving |
| **Port/harbor infrastructure** | Ballast water, cooling loops | Urban coastal co-location |

**Energy savings from parasitic pumping:** Seawater pumping can represent **20–40% of total system energy** for a standalone DOC plant. Co-location eliminates this entirely.

---

## 2. Physical Constraints

### 2.1 Land/Ocean Footprint

| Metric | Value | Notes |
|---|---|---|
| **Plant footprint (modular unit)** | ~100–500 m² per 1,000 tCO2/year module | Containerized/modular design |
| **Footprint per ton CO2/year** | ~0.1–0.5 m² | Extremely compact vs. DAC (~1–5 m²/tCO2/yr) or forests (~1,000+ m²/tCO2/yr) |
| **Ocean surface area affected** | Minimal direct footprint | Discharge plume disperses; reabsorption is global |
| **Scaling to 1 MtCO2/year** | ~1–5 hectares (plant only) | Comparable to a small industrial facility |
| **Scaling to 1 GtCO2/year** | ~10,000–50,000 hectares (plant area) | Distributed across thousands of coastal sites |

**Key advantage:** DOC has one of the smallest land footprints per ton of any CDR method because:
- The "contactor" is the entire ocean surface (~361 million km²)
- The plant only handles the electrochemistry and gas stripping
- No need for massive air contactors (unlike DAC)

### 2.2 Location Dependency

| Requirement | Constraint Level | Details |
|---|---|---|
| **Coastal access** | Hard requirement | Must be at or near ocean; pipeline from inland not feasible |
| **Co-location with pumping infrastructure** | Strong preference (not absolute) | Parasitic pumping saves 20–40% energy; standalone is viable but costlier |
| **Warm vs. cold water** | Moderate preference for warm | CO2 is less soluble in warm water → easier to strip; but cold water holds more total DIC |
| **Proximity to renewable energy** | Strong preference | Offshore wind, coastal solar, or grid renewables needed for net-negative operation |
| **Proximity to CO2 storage/utilization** | Moderate preference | If CO2 is sequestered (not just released for ocean reabsorption) |
| **Water depth** | Flexible | Works in shallow coastal or deep offshore |
| **Salinity** | Moderate sensitivity | Higher salinity = more dissolved ions, affects BPMED efficiency |

**Global site availability:** There are approximately **16,000+ desalination plants** worldwide (2024), **thousands of coastal power plants**, and **~12,000 offshore oil/gas platforms**. This provides enormous co-location potential across every inhabited continent.

---

## 3. Resource Constraints

### 3.1 Energy Intensity

This is the single most critical variable for DOC feasibility.

| Metric | Current (Pilot) | Near-Term Target (2027–2030) | Long-Term Target (2035+) | Notes |
|---|---|---|---|---|
| **Total energy per tCO2** | **1,500–2,500 kWh/tCO2** | **1,000–1,500 kWh/tCO2** | **500–1,000 kWh/tCO2** | Includes all process steps |
| **Electrodialysis energy** | ~1,000–1,800 kWh/tCO2 | ~600–1,000 kWh/tCO2 | ~400–700 kWh/tCO2 | Dominant energy consumer |
| **CO2 stripping (vacuum)** | ~100–300 kWh/tCO2 | ~50–150 kWh/tCO2 | ~30–100 kWh/tCO2 | Vacuum pumps or membrane contactors |
| **Water pumping (standalone)** | ~200–500 kWh/tCO2 | ~150–300 kWh/tCO2 | ~100–200 kWh/tCO2 | Eliminated with parasitic pumping |
| **Water pumping (parasitic)** | ~0 kWh/tCO2 | ~0 kWh/tCO2 | ~0 kWh/tCO2 | Key advantage of co-location |
| **Balance of plant** | ~100–200 kWh/tCO2 | ~50–100 kWh/tCO2 | ~30–50 kWh/tCO2 | Controls, monitoring, compression |

**Comparison to other CDR methods:**

| Method | Energy (kWh/tCO2) | Notes |
|---|---|---|
| **Direct Air Capture (solid sorbent, e.g., Climeworks)** | 1,500–2,500 (thermal+electric) | Mostly thermal energy |
| **Direct Air Capture (liquid solvent, e.g., Carbon Engineering/1PointFive)** | 1,200–2,000 (thermal+electric) | Natural gas often used for heat |
| **Direct Ocean Capture (Captura)** | 1,500–2,500 (current), target <1,000 | All-electric (advantage) |
| **Enhanced Weathering** | 100–500 | Mining and grinding energy |
| **BECCS** | Net energy producer (with biomass) | But huge land use |

**Critical insight:** DOC's energy is **all-electric**, which is a major advantage over DAC approaches that require high-grade thermal energy (often 80–120 °C). All-electric processes can directly use solar, wind, or nuclear power without conversion losses.

### 3.2 Thermodynamic Minimum

The **theoretical minimum energy** to separate CO2 from seawater is approximately **100–150 kWh/tCO2**, based on the thermodynamics of the carbonate system. Current systems operate at **10–20x the thermodynamic minimum**, suggesting significant room for improvement through:
- Better membrane materials (lower resistance)
- Optimized stack design (reduced ohmic losses)
- Heat integration and waste heat recovery
- Higher current density operation

### 3.3 Water Throughput

| Metric | Value | Notes |
|---|---|---|
| **Seawater per ton CO2 removed** | ~3,000–7,000 m³/tCO2 | Depends on DIC extraction efficiency |
| **Dissolved Inorganic Carbon (DIC) in seawater** | ~2.0–2.3 mmol/kg (~100–110 mg CO2-equivalent/L) | Varies with temp, salinity, depth |
| **DIC extraction efficiency** | ~10–30% per pass | Cannot strip all CO2 without severe acidification |
| **Seawater flow rate for 1 MtCO2/year** | ~10–20 million m³/day | Comparable to a large desalination plant |

**Freshwater consumption:** DOC does **not consume freshwater**. It uses and returns seawater. This is a significant advantage over some DAC processes and essentially all biomass-based CDR.

**Context for water throughput at scale:**
- Global desalination capacity (2024): ~100 million m³/day
- Global seawater cooling water (power plants): ~billions of m³/day
- Total ocean volume: ~1.335 billion km³
- Even at 10 GtCO2/year, water throughput is a trivial fraction of ocean volume

### 3.4 Material Inputs

| Material | Role | Current State | Scaling Concern |
|---|---|---|---|
| **Bipolar membranes** | Water splitting in BPMED | Specialty chemical product; limited suppliers (Fumatech, Suez/Eurodia, Astom) | Medium — membrane manufacturing must scale 100–1000x |
| **Ion-exchange membranes** (cation/anion) | Ion transport in ED stack | More mature supply chain (water treatment industry) | Low–Medium |
| **Electrodes** | Electron transfer | Titanium mesh with mixed metal oxide coatings (MMO); platinum-group metals possible | Medium — Ti and PGM supply chains |
| **Membrane contactors** (for CO2 stripping) | Gas-liquid separation | Polypropylene or PTFE hollow-fiber modules (e.g., Liqui-Cel) | Low — mature technology |
| **Stack housing/frames** | Structural | Polymers, stainless steel | Low |
| **Power electronics** | DC power supply, controls | Standard industrial | Low |
| **Piping/valves** | Seawater handling | Marine-grade materials (super-duplex SS, titanium, HDPE) | Low — mature marine industry |

**Critical material bottleneck:** Bipolar membranes are the most constrained input. Current global production is small (primarily for food/pharma electrodialysis). Scaling to gigaton-level DOC would require a massive buildout of membrane manufacturing capacity.

---

## 4. Throughput Metrics

### 4.1 Capture Rate per Unit

| Scale | Capacity | Status | Notes |
|---|---|---|---|
| **Lab prototype (Caltech)** | ~kg CO2/year | 2019–2021 | Proof of concept |
| **Pilot 1 (Newport Beach / AltaSea)** | ~100 tCO2/year | 2022–2023 | First outdoor pilot at AltaSea, Port of Los Angeles |
| **Pilot 2 (DOE-funded)** | ~1,000 tCO2/year | 2024–2026 (target) | $3.8M DOE award (2023) for engineering-scale demonstration |
| **Commercial module (target)** | ~10,000–50,000 tCO2/year | 2028–2030 (projected) | Containerized, modular unit |
| **Full-scale plant (target)** | ~100,000–1,000,000 tCO2/year | 2030–2035 (projected) | Multiple modules at single site |

### 4.2 Duty Cycle / Uptime

| Factor | Expected Value | Notes |
|---|---|---|
| **Target uptime** | 85–95% | Similar to chemical process plants |
| **Maintenance downtime** | ~2–4 weeks/year | Membrane cleaning/replacement, electrode inspection |
| **Weather/ocean state dependency** | Low | Enclosed system; not wave-dependent |
| **Seasonal variation** | Low–Moderate | Warmer water slightly easier to process; DIC varies seasonally |
| **Host facility dependency** | Moderate | If parasitically pumping, tied to host uptime |

### 4.3 Membrane Lifecycle / Durability

| Component | Expected Lifetime | Replacement Cost Impact | Key Degradation Mechanisms |
|---|---|---|---|
| **Bipolar membranes** | 2–5 years (current); target 5–10 years | High (major OPEX driver) | Fouling, scaling (CaCO₃, Mg(OH)₂), chemical degradation |
| **Ion-exchange membranes** | 5–10 years | Moderate | Organic fouling, oxidative degradation |
| **Electrodes (MMO/Ti)** | 5–15 years | Moderate | Coating erosion, passivation |
| **Membrane contactors** | 3–7 years | Low–Moderate | Wetting, fouling, pore blockage |
| **Seawater fouling challenge** | Ongoing operational issue | Significant OPEX component | Biofouling, mineral scaling from Ca²⁺, Mg²⁺, Sr²⁺ |

**Fouling is the #1 operational challenge.** Seawater contains high concentrations of scale-forming ions (Ca²⁺ ~400 mg/L, Mg²⁺ ~1,290 mg/L). When the BPMED stack produces alkaline conditions, CaCO₃ and Mg(OH)₂ can precipitate on membrane surfaces, reducing efficiency. Captura has developed proprietary anti-fouling protocols, likely including:
- Periodic acid wash / clean-in-place (CIP) cycles
- Polarity reversal (electrodialysis reversal, EDR)
- Optimized flow patterns to minimize dead zones
- Pre-treatment (filtration) of feed seawater

---

## 5. End Game — Storage

### 5.1 Storage Pathways

DOC offers **two fundamentally different storage paradigms:**

#### Pathway A: Ocean Re-equilibration (Passive Atmospheric Drawdown)

```
DOC Plant strips CO2 from seawater
        │
        ▼
Decarbonized seawater returned to ocean
        │
        ▼
Ocean surface becomes locally CO2-undersaturated
        │
        ▼
Atmosphere-ocean CO2 flux increases (Henry's Law)
        │
        ▼
Ocean passively absorbs CO2 from atmosphere over weeks–months
        │
        ▼
Net atmospheric CO2 reduction achieved
```

- **CO2 is NOT permanently stored** in this pathway — it is simply cycled from atmosphere → ocean → removed → atmosphere refills ocean
- The **net effect** is only achieved if the captured CO2 is permanently stored elsewhere
- This is NOT a storage solution by itself — it is a **capture mechanism**

#### Pathway B: Captured CO2 is Permanently Stored

| Storage Option | Permanence | Maturity | Notes |
|---|---|---|---|
| **Geological sequestration** (saline aquifers, depleted oil/gas) | 1,000–10,000+ years | Commercial (Sleipner since 1996) | Requires CO2 compression, pipeline/ship transport |
| **Sub-ocean basalt mineralization** | 10,000+ years (effectively permanent) | Pilot (CarbFix in Iceland) | CO2 reacts with basalt to form stable carbonates |
| **CO2 utilization** (concrete, fuels, chemicals) | Variable (months to centuries) | Growing market | Not truly "removal" unless product is permanent |
| **Ocean alkalinity enhancement** (convert CO2 to dissolved bicarbonate) | 10,000+ years in ocean | Research/pilot | Could be integrated with DOC process |
| **Deep ocean injection** | Centuries to millennia | Banned by London Protocol | Regulatory non-starter currently |

**Captura's stated approach:** Capture the CO2 as a concentrated gas stream, then deliver it for geological sequestration or utilization. The company has discussed both pathways.

### 5.2 Ocean Re-equilibration Dynamics

| Parameter | Value | Notes |
|---|---|---|
| **Atmosphere-ocean CO2 exchange timescale** | ~6–12 months for surface mixed layer | Varies by wind speed, temperature, mixing |
| **Mixed layer depth** | ~20–200 m (seasonally variable) | Deeper in winter, shallower in summer |
| **CO2 invasion velocity** | ~3–5 m/day (piston velocity) | Rate of gas transfer across ocean surface |
| **Global ocean CO2 uptake** | ~2.5–3.0 GtCO2/year (natural sink) | Would need to roughly quadruple for 10 Gt/year DOC |
| **Revelle Factor** | ~10–15 | Ocean's buffering capacity; limits marginal CO2 absorption efficiency |
| **Surface ocean pCO2** | ~410–420 µatm (near equilibrium with atmosphere) | Locally variable; upwelling zones are supersaturated |

**Critical nuance on ocean re-equilibration:** The ocean does NOT instantly reabsorb the CO2 deficit created by DOC. The re-equilibration timescale is months, and the Revelle Factor means the ocean's capacity to absorb additional CO2 is **non-linear** — it becomes harder to absorb more as the ocean acidifies. However, DOC actually works in the favorable direction: by removing CO2 from seawater, it **locally increases the ocean's capacity to absorb atmospheric CO2**.

### 5.3 Ocean as a Carbon Sink — Capacity Limits

| Metric | Value | Notes |
|---|---|---|
| **Total ocean DIC** | ~38,000 GtC (~140,000 GtCO2) | Dwarfs atmosphere (~880 GtC / ~3,200 GtCO2) |
| **Ocean CO2 uptake capacity (cumulative)** | Functionally unlimited for human timescales | Ocean has absorbed ~30% of anthropogenic CO2 since 1750 |
| **Annual natural ocean CO2 flux** | ~80 GtC/year (in each direction) | Gross flux is enormous; net is ~2.5 GtC/year uptake |
| **Theoretical DOC extraction limit** | Limited by re-equilibration rate, not ocean volume | Could extract far more than 10 GtCO2/yr from ocean; bottleneck is energy and infrastructure |

### 5.4 Permanence Risk

| Risk Factor | Severity | Mitigation |
|---|---|---|
| **CO2 re-release from geological storage** | Very Low | Well-characterized geology, monitoring, regulatory frameworks |
| **Ocean outgassing if DOC stops** | N/A | Ocean reabsorption is a mechanism, not storage; captured CO2 must go somewhere permanent |
| **Ocean circulation changes affecting re-equilibration** | Low–Moderate | Climate change may alter ocean mixing; could slow reabsorption |
| **Leakage from CO2 utilization products** | Variable | Depends on product; fuels release CO2 when burned; concrete is more permanent |

---

## 6. Economic Friction

### 6.1 Cost Estimates

| Cost Metric | Current (2024–2025) | Near-Term (2028–2030) | Long-Term (2035+) | Notes |
|---|---|---|---|---|
| **Cost per ton CO2** | **$300–600/tCO2** | **$150–300/tCO2** | **$50–150/tCO2** | Captura's stated trajectory |
| **For context: DOE target** | — | — | **<$100/tCO2** | DOE Carbon Negative Shot |
| **For context: DAC (Climeworks)** | ~$600–1,000/tCO2 | ~$300–400/tCO2 | ~$100–200/tCO2 | Solid sorbent DAC |
| **For context: DAC (1PointFive/Oxy)** | ~$400–600/tCO2 | ~$200–300/tCO2 | ~$100–150/tCO2 | Liquid solvent DAC |

### 6.2 CAPEX Breakdown (Estimated for Commercial Module)

| Component | % of CAPEX | Notes |
|---|---|---|
| **BPMED stacks (membranes + electrodes)** | 35–50% | Dominant capital cost |
| **CO2 stripping/vacuum system** | 10–15% | Membrane contactors or vacuum |
| **Power electronics & controls** | 10–15% | Rectifiers, PLCs, sensors |
| **Marine-grade piping, valves, structure** | 10–15% | Corrosion-resistant materials |
| **Pre-treatment (filtration)** | 5–10% | Seawater intake conditioning |
| **CO2 compression/liquefaction** | 5–10% | If sequestering; not needed if utilizing at low pressure |
| **Installation, commissioning** | 5–10% | Site-specific |

**Estimated CAPEX per ton annual capacity:**
- Current: ~$2,000–5,000 per tCO2/year capacity
- Target (2030): ~$500–1,500 per tCO2/year capacity
- Target (2035+): ~$200–500 per tCO2/year capacity

### 6.3 OPEX Breakdown

| Component | % of OPEX | Notes |
|---|---|---|
| **Electricity** | 40–60% | Dominant operating cost; highly sensitive to electricity price |
| **Membrane replacement** | 15–25% | Bipolar membranes every 3–5 years |
| **Maintenance & labor** | 10–15% | Fouling management, general upkeep |
| **Chemicals (cleaning, pH adjustment)** | 5–10% | CIP chemicals, anti-scalants |
| **CO2 transport/storage** | 5–15% | If sequestering; pipeline or ship |
| **Monitoring, reporting, verification (MRV)** | 2–5% | Carbon credit validation |

**Electricity price sensitivity:**

| Electricity Price | Impact on Cost/tCO2 (at 1,500 kWh/tCO2) | Scenarios |
|---|---|---|
| $0.02/kWh | +$30/tCO2 | Cheap renewables, off-peak |
| $0.05/kWh | +$75/tCO2 | Average renewable PPA |
| $0.08/kWh | +$120/tCO2 | Grid average (many regions) |
| $0.12/kWh | +$180/tCO2 | Higher-cost grid |

### 6.4 Learning Rate

| Parameter | Estimate | Basis |
|---|---|---|
| **Expected learning rate** | 15–25% cost reduction per doubling of cumulative capacity | Analogous to electrolyzers, solar PV, desalination membranes |
| **Doublings needed from pilot to 1 Mt/yr** | ~13–14 doublings (from 100 t/yr to 1 Mt/yr) | Each doubling → 15–25% cost reduction |
| **Implied cost at 1 Mt/yr (optimistic 20% LR)** | ~$50–100/tCO2 | If starting at $400/tCO2 today |
| **Technology analogy** | Electrodialysis for desalination, PEM electrolyzers | Both showed ~15–20% learning rates |

### 6.5 Revenue Streams

| Revenue Source | Current Price | Scale Potential | Notes |
|---|---|---|---|
| **Voluntary carbon credits** | $100–600/tCO2 | Limited (<$10B/yr market) | Premium for ocean-based CDR with MRV |
| **Compliance carbon markets** | $20–100/tCO2 (EU ETS ~€60–80) | Large but DOC not yet eligible in most | Eligibility being developed |
| **45Q tax credit (US)** | $180/tCO2 (DAC with storage) | Significant | DOC may qualify under "direct air capture" definition — under regulatory review |
| **CO2 utilization sales** | $30–200/tCO2 (depending on product) | Large | E-fuels, concrete, chemicals, greenhouses |
| **Carbon removal purchases** (Frontier, Microsoft, etc.) | $200–600/tCO2 | Growing (~$1B+ committed) | Major advance purchase commitments |
| **Government procurement** | Variable | Growing | DOE, DoD interest in CDR |

**45Q eligibility is a critical open question.** The IRS definition of "direct air capture" potentially includes DOC since the net effect is atmospheric CO2 removal. Captura and industry groups have lobbied for inclusion. At $180/tCO2, 45Q would make DOC economically viable at current costs.

---

## 7. Additional Feasibility Data

### 7.1 Current Pilots and Capacity

| Project | Location | Capacity | Status | Funding |
|---|---|---|---|---|
| **AltaSea Pilot** | Port of Los Angeles, San Pedro, CA | ~100 tCO2/year | Operational (2023) | Private + DOE |
| **DOE Engineering-Scale Demo** | TBD (likely California coast) | ~1,000 tCO2/year | In development (2024–2026) | $3.8M DOE ARPA-E / FECM |
| **Equinor Partnership Pilot** | Norway (planned) | TBD | Announced 2024 | Equinor investment |
| **Expanded demo system** | TBD | ~10,000 tCO2/year | Planned (2027–2028) | Seeking funding |

### 7.2 Partnerships and Backing

| Partner | Type | Details |
|---|---|---|
| **AltaSea at the Port of Los Angeles** | Site host | Provided location for first pilot; shared seawater access |
| **Equinor (Norwegian oil major)** | Strategic investor | Investment announced 2023–2024; interest in coupling DOC with North Sea storage |
| **Department of Energy (DOE)** | Government funder | Multiple awards including ARPA-E and FECM programs |
| **XPRIZE Carbon Removal** | Competition | Captura was a milestone winner in $100M XPRIZE (Musk Foundation) |
| **Frontier (Stripe, Alphabet, Meta, etc.)** | Advance purchase | Carbon removal credits pre-purchase commitment |
| **Caltech** | Academic origin | Ongoing research collaboration; IP licensing |
| **Various desalination operators** | Potential co-location | In discussions for parasitic pumping integration |

**Total funding raised by Captura (estimated through 2024):** ~$30–40M+ (combination of venture capital, government grants, and strategic investment)

### 7.3 Ocean Chemistry Impacts and Environmental Concerns

#### Potential Negative Impacts

| Concern | Severity | Details | Mitigation |
|---|---|---|---|
| **Local acidification of discharge** | Moderate | Acid stream could locally lower pH | Re-alkalize before discharge; rapid dilution in ocean |
| **Disruption of local marine ecosystems** | Low–Moderate | pH changes, temperature changes near discharge | Diffuser design for rapid mixing; environmental monitoring |
| **Entrainment of marine organisms** | Low | Organisms pulled through pumping system | Screen intakes; parasitic pumping uses existing screened intakes |
| **Electrochemical byproducts** | Low | Chlorine generation at electrodes (Cl⁻ → Cl₂) | Electrode coatings to suppress Cl₂ evolution; process optimization |
| **Brine/waste stream** | Low | Minimal waste; water is returned | Near-zero liquid discharge possible |
| **Large-scale ocean DIC depletion** | Very Low at any plausible scale | Even 10 Gt/yr is <0.01% of ocean DIC | Self-limiting; ocean is enormous |
| **Disruption of ocean biological pump** | Very Low | Removing DIC could affect phytoplankton locally | Site selection away from productive zones; monitoring |

#### Potential Positive Impacts

| Benefit | Details |
|---|---|
| **Local de-acidification** | Returned alkaline water combats ocean acidification locally |
| **Enhanced shellfish/coral habitat** | Higher pH water beneficial for calcifying organisms |
| **Reduced atmospheric CO2** | Net climate benefit |
| **No land use competition** | Does not compete with agriculture or ecosystems |
| **No freshwater consumption** | Unlike most CDR methods |

### 7.4 The 140x Concentration Advantage — Detailed Analysis

The ocean's CO2 concentration advantage over the atmosphere is DOC's foundational physics argument:

| Parameter | Atmosphere | Ocean (surface) | Ratio |
|---|---|---|---|
| **CO2 concentration** | ~420 ppm (~0.04%) | ~90–110 mg/L as dissolved CO2-equivalent | ~140x |
| **Total carbon content** | ~880 GtC | ~38,000 GtC (DIC) | ~43x |
| **Thermodynamic separation energy** | Higher (dilute → concentrate) | Lower (more concentrated starting point) | Significant advantage |
| **Contactor size needed** | Massive (air contactors for DAC) | Compact (liquid-phase processing) | 10–100x smaller |
| **Fan/pump energy** | Large fans moving huge air volumes | Water pumping (or parasitic) | Variable |

**Why this matters for energy:** The minimum thermodynamic work to separate CO2 scales with the log of the concentration ratio. Extracting CO2 from a 140x more concentrated medium fundamentally requires less separation energy. However, seawater's complex chemistry (buffering by carbonates) partially offsets this advantage.

### 7.5 Regulatory and Permitting Challenges

| Regulatory Area | Jurisdiction | Challenge | Status |
|---|---|---|---|
| **London Protocol / London Convention** | International | Prohibits "dumping" of wastes at sea; could DOC discharge be classified as dumping? | Under review; likely DOC is exempt since returning cleaned seawater |
| **NPDES Permits (Clean Water Act)** | US Federal/State | Discharge of modified seawater requires permit | Standard industrial permitting; manageable |
| **Marine Protection, Research, and Sanctuaries Act** | US Federal | Regulates ocean dumping | DOC likely qualifies for exemption (returning water, not dumping waste) |
| **Coastal Zone Management Act** | US State | Coastal development permits | Standard process; varies by state |
| **CEQA / NEPA** | California / US Federal | Environmental review for new facilities | Required; timeline 1–3 years for major projects |
| **45Q Tax Credit Eligibility** | US Federal (IRS/Treasury) | Does DOC qualify as "direct air capture"? | Under active regulatory interpretation; critical for US economics |
| **EU Carbon Removal Certification** | EU | Framework for certifying CDR methods | DOC being considered; MRV methodology needed |
| **EPA Ocean Discharge Criteria** | US Federal | Standards for ocean discharges | Applicable; requires demonstration of minimal environmental impact |
| **International waters operation** | UN/Flag state | If operating on offshore platforms in international waters | Complex jurisdiction; flag state laws apply |

**Key regulatory insight:** DOC faces a more complex permitting environment than land-based DAC because it interacts with ocean ecosystems and marine regulatory frameworks. However, none of the regulatory hurdles appear to be fundamental blockers — they are standard industrial permitting challenges that can be navigated with proper environmental assessment.

### 7.6 Key Bottlenecks

| Bottleneck | Severity | Timeframe to Resolve | Details |
|---|---|---|---|
| **Membrane durability in seawater** | High | 3–7 years | Fouling and degradation limit lifetime; R&D ongoing |
| **Membrane manufacturing scale-up** | High | 5–10 years | Global bipolar membrane production is tiny; need 1000x increase |
| **Energy intensity reduction** | High | 5–10 years | Need to approach ~500–1,000 kWh/tCO2 for cost competitiveness |
| **MRV (Measurement, Reporting, Verification)** | Medium | 2–5 years | Must prove net CO2 removal including ocean re-equilibration |
| **45Q / regulatory clarity** | Medium | 1–3 years | US tax credit eligibility is make-or-break for near-term economics |
| **CO2 transport and storage infrastructure** | Medium | 5–15 years | Need pipelines, injection wells at coastal locations |
| **Capital availability** | Medium | Ongoing | Climate tech funding cycles; need project finance maturation |
| **Chlorine suppression** | Low–Medium | 2–5 years | Seawater electrolysis can produce Cl₂; must be managed |
| **Public acceptance** | Low | Ongoing | "Ocean intervention" may face NIMBYism; education needed |

### 7.7 Competitive Landscape

| Company | Approach | Stage | Differentiation |
|---|---|---|---|
| **Captura** (Caltech) | BPMED electrodialysis | Pilot (~100 tCO2/yr) | Parasitic pumping; all-electric |
| **Ebb Carbon** | Ocean alkalinity enhancement (electrochemical) | Pilot | Adds alkalinity to ocean; different mechanism |
| **Heimdal** (formerly Seabound) | Electrochemical ocean capture | Early stage | Similar BPMED approach |
| **Planetary Technologies** | Ocean alkalinity enhancement (mineral) | Pilot | Adds crusite/brucite minerals |
| **Running Tide** | Ocean-based biomass sinking + alkalinity | Pilot | Kelp/biomass + alkalinity; very different approach |
| **Equatic** (UCLA spinoff) | Electrochemical seawater mineralization | Pilot | Produces solid CaCO3 + H2 as co-products |
| **CarbonBlue** | Electrochemical ocean CDR | Early stage | Similar domain |

### 7.8 Timeline Projections

| Milestone | Projected Date | Confidence | Dependencies |
|---|---|---|---|
| **First pilot operational** | 2023 (achieved) | Confirmed | — |
| **1,000 tCO2/year demo** | 2025–2026 | High | DOE funding in place |
| **10,000 tCO2/year system** | 2027–2028 | Medium | Next funding round; membrane scaling |
| **First commercial plant (100 kt/yr)** | 2029–2032 | Medium–Low | Economics must work; permits; storage |
| **1 MtCO2/year (single site)** | 2032–2035 | Low | Requires major cost reduction and infrastructure |
| **100 MtCO2/year (industry)** | 2035–2040 | Speculative | Requires massive buildout and policy support |
| **1 GtCO2/year (industry)** | 2040–2050 | Speculative | Requires global deployment at thousands of sites |
| **10 GtCO2/year** | 2050+ (if ever) | Highly speculative | See scaling analysis below |

---

## 8. Scaling Analysis: Path to 10 Gt/year

### 8.1 What Would 10 GtCO2/year DOC Require?

| Parameter | Requirement at 10 GtCO2/yr | Context |
|---|---|---|
| **Number of 1 MtCO2/yr plants** | ~10,000 plants | Global deployment across all coasts |
| **Total electricity demand** | 10,000–25,000 TWh/year | **Global electricity production in 2023: ~29,000 TWh** — DOC at this scale would consume 35–85% of current global electricity |
| **Seawater throughput** | ~30–70 trillion m³/year | ~0.003–0.005% of ocean volume annually; trivial |
| **Membrane production** | Millions of m² per year of bipolar membranes | Current production: thousands of m²/yr → need ~1,000–10,000x increase |
| **CAPEX (cumulative)** | $2–10 trillion (at target costs) | Comparable to global energy infrastructure investment |
| **OPEX (annual)** | $500B–1.5T/year | At $50–150/tCO2 operating cost |
| **Coastal sites needed** | ~5,000–10,000 major installations | Every major port, desalination plant, coastal power station |
| **CO2 storage capacity needed** | 10 GtCO2/year injection rate | Current global CCS: ~0.04 GtCO2/yr → need ~250x increase |

### 8.2 The Energy Problem at Scale

This is the fundamental constraint. At 10 GtCO2/year:

| Scenario | Energy per tCO2 | Total Energy | % of 2023 Global Electricity |
|---|---|---|---|
| Current technology | 2,000 kWh/tCO2 | 20,000 TWh/yr | **69%** |
| Near-term target | 1,000 kWh/tCO2 | 10,000 TWh/yr | **34%** |
| Long-term target | 500 kWh/tCO2 | 5,000 TWh/yr | **17%** |
| Thermodynamic limit | 150 kWh/tCO2 | 1,500 TWh/yr | **5%** |

**Even at the long-term target, 10 GtCO2/year DOC requires ~17% of current global electricity production dedicated solely to carbon removal.** This necessitates a massive expansion of clean energy capacity specifically for CDR — likely requiring dedicated offshore wind, floating solar, or coastal nuclear installations.

For comparison:
- Global solar PV capacity additions in 2023: ~400 GW → produces ~600 TWh/yr
- 10 GtCO2/yr DOC at 500 kWh/tCO2 would need ~5,000 TWh/yr → equivalent to ~8x the entire world's 2023 solar installation rate, dedicated to DOC alone

### 8.3 Realistic Maximum Scale Assessment

| Scale Level | Feasibility | Rationale |
|---|---|---|
| **1 MtCO2/year** | Achievable by ~2030–2035 | Requires continued R&D, first commercial plant |
| **100 MtCO2/year** | Plausible by ~2040 | Requires industry maturation, policy support, ~100 plants |
| **1 GtCO2/year** | Very challenging by ~2050 | Requires massive clean energy buildout, ~1,000 plants, ~$100B+ investment |
| **10 GtCO2/year** | Extremely unlikely as standalone | Energy constraint is binding; would require DOC + other CDR methods in portfolio |

### 8.4 Advantages of DOC vs. DAC at Scale

| Factor | DOC Advantage | DAC Advantage |
|---|---|---|
| **Concentration** | 140x higher CO2 in water vs. air | — |
| **Contactor size** | Ocean is the contactor (free, infinite) | — |
| **Energy type** | All-electric (easier to decarbonize) | — |
| **Land use** | Minimal | — |
| **Water use** | Zero freshwater | — |
| **Location flexibility** | — | Can be anywhere (inland + coastal) |
| **Regulatory simplicity** | — | No marine permitting |
| **Technology maturity** | — | More advanced (Climeworks since 2009) |
| **Storage proximity** | — | Can co-locate with geological storage anywhere |

### 8.5 DOC's Role in a CDR Portfolio

Given the scaling constraints, DOC is most likely to be **one component of a multi-method CDR portfolio**, rather than a single solution at 10 GtCO2/yr. A plausible 2050 portfolio might be:

| Method | Contribution | Notes |
|---|---|---|
| Direct Ocean Capture | 0.5–2 GtCO2/yr | Coastal and platform-based |
| Direct Air Capture | 0.5–2 GtCO2/yr | Inland and coastal |
| Enhanced Weathering | 1–3 GtCO2/yr | Agricultural lands |
| BECCS | 1–3 GtCO2/yr | With sustainable biomass |
| Afforestation/Reforestation | 1–3 GtCO2/yr | With permanence mechanisms |
| Ocean Alkalinity Enhancement | 0.5–2 GtCO2/yr | Complementary ocean method |
| Biochar | 0.5–1 GtCO2/yr | Agricultural co-benefit |
| **Total** | **5–16 GtCO2/yr** | Portfolio approach |

---

## 9. Key Sources

1. **Captura Corporation** — Company website and press releases (captura.com)
2. **Eisaman, M.D.** (2024) — "Electrochemical approaches to CO2 removal from seawater" — *Annual Review of Chemical and Biomolecular Engineering*
3. **US Department of Energy** — FECM and ARPA-E program announcements on marine CDR funding
4. **National Academies of Sciences, Engineering, and Medicine** (2022) — *A Research Strategy for Ocean-based Carbon Dioxide Removal and Sequestration* — Consensus report on ocean CDR methods
5. **XPRIZE Carbon Removal** — Milestone awards documentation (xprize.org)
6. **La Plante, E.C., Siegel, D.A., et al.** (2023) — Techno-economic analysis of electrochemical ocean CDR — *Nature Energy*
7. **Rau, G.H.** (2011) — "CO2 mitigation via capture and chemical conversion in seawater" — *Environmental Science & Technology*
8. **Equinor** — Investment announcements in Captura (2023–2024)
9. **Frontier Climate** — Advance market commitment for CDR purchases (frontierclimate.com)
10. **IPCC AR6 WGIII** (2022) — Chapter on Carbon Dioxide Removal methods
11. **DOE Carbon Negative Shot** — Program targets and metrics ($100/tCO2 goal)
12. **Eisaman, M.D., et al.** (2012) — "CO2 extraction from seawater using bipolar membrane electrodialysis" — *Energy & Environmental Science*
13. **Global CCS Institute** — Annual status report on carbon capture and storage
14. **International Desalination Association** — Global desalination statistics
15. **London Protocol / London Convention** — Marine environmental regulation framework (IMO)

---

## Appendix A: Key Formulas and Relationships

### Carbonate Chemistry

```
CO2(atm) ⇌ CO2(aq) ⇌ H2CO3 ⇌ H⁺ + HCO3⁻ ⇌ 2H⁺ + CO3²⁻
```

At seawater pH ~8.1:
- ~1% as dissolved CO2
- ~89% as bicarbonate (HCO3⁻)
- ~10% as carbonate (CO3²⁻)

**Total DIC** = [CO2(aq)] + [HCO3⁻] + [CO3²⁻] ≈ 2.0–2.3 mmol/kg

### Henry's Law (Ocean-Atmosphere Equilibrium)

```
pCO2(ocean) = [CO2(aq)] / KH
```

Where KH is the Henry's Law constant (temperature-dependent). When DOC reduces [CO2(aq)] in surface water, pCO2(ocean) drops below pCO2(atmosphere), driving net atmospheric CO2 invasion into the ocean.

### Energy Lower Bound

```
W_min = RT × ln(1/x_CO2) per mol CO2
```

For seawater DIC (~2 mmol/kg): W_min ≈ 100–150 kWh/tCO2 (including entropy of mixing in the carbonate buffer system).

---

## Appendix B: Comparison Table — DOC vs. DAC vs. Other CDR

| Parameter | DOC (Captura) | DAC-Solid (Climeworks) | DAC-Liquid (CE/1PointFive) | Enhanced Weathering | BECCS |
|---|---|---|---|---|---|
| **CO2 source** | Seawater (140x conc.) | Air (420 ppm) | Air (420 ppm) | Air (via minerals) | Biomass combustion |
| **Energy type** | All-electric | Electric + low-T thermal | Electric + high-T thermal | Electric (grinding) | Thermal (biomass) |
| **Energy intensity** | 1,000–2,500 kWh/t | 1,500–2,500 kWh/t | 1,200–2,000 kWh/t | 100–500 kWh/t | Net producer |
| **Cost today** | $300–600/t | $600–1,000/t | $400–600/t | $50–200/t | $100–200/t |
| **Cost target** | $50–150/t | $100–200/t | $100–150/t | $30–100/t | $50–100/t |
| **Land use** | Very low | Low | Moderate | Very high | Very high |
| **Water use** | None (seawater) | Low | Moderate | None | High |
| **Location constraint** | Coastal | Anywhere | Anywhere | Agricultural land | Biomass supply |
| **Storage** | Geological/utilization | Geological/utilization | Geological/utilization | In-situ mineralization | Geological |
| **Permanence** | High (geological) | High (geological) | High (geological) | Very high (mineral) | High (geological) |
| **TRL (2025)** | 4–5 | 6–7 | 6–7 | 3–5 | 5–6 |
| **Scalability** | High (if energy available) | High (if energy available) | High (if energy + gas) | Very high | Limited by biomass |

---

*This document represents a comprehensive assessment of Direct Ocean Capture as of early 2026. The field is rapidly evolving — data on costs, energy intensity, and project status should be validated against the latest company disclosures and peer-reviewed publications. Figures marked as estimates or targets should be treated as indicative ranges, not precise values.*
