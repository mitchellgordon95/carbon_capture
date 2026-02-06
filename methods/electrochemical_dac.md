# Electrochemical Separation DAC: Comprehensive Feasibility Assessment

> **Method Summary:** Electrochemical Direct Air Capture (eDAC) uses electricity-driven
> electrochemical reactions to capture and release CO2 from ambient air, bypassing the
> energy-intensive thermal regeneration step ("thermal swing") used by conventional DAC.
> This "Thermal Bypass" could theoretically deliver 3-4x better energy efficiency than
> heat-based approaches.

> **Note on Sources:** This document was compiled from published literature, company
> disclosures, DOE reports, academic papers, and press coverage through early 2025.
> Figures marked with ~ are estimates or projections. Figures marked [unverified] should
> be cross-checked against the latest company announcements.

---

## Table of Contents

1. [Technology Overview](#1-technology-overview)
2. [Key Players](#2-key-players)
3. [Physical Constraints](#3-physical-constraints)
4. [Resource Constraints](#4-resource-constraints)
5. [Throughput Metrics](#5-throughput-metrics)
6. [End Game: Storage](#6-end-game-storage)
7. [Economic Friction](#7-economic-friction)
8. [Additional Feasibility Data](#8-additional-feasibility-data)
9. [Comparison to Thermal DAC Approaches](#9-comparison-to-thermal-dac-approaches)
10. [10 Gigaton/Year Scale Assessment](#10-ten-gigatonyear-scale-assessment)
11. [Sources & References](#11-sources--references)

---

## 1. Technology Overview

### 1.1 The Core Concept: Electro-Swing Adsorption

Conventional DAC methods (liquid solvent systems like Carbon Engineering/Occidental, solid sorbent systems like Climeworks) capture CO2 by binding it chemically, then use **heat** (80-900 degC) to break those bonds and release concentrated CO2. This thermal regeneration step dominates energy consumption -- typically 80%+ of total energy demand.

Electrochemical DAC replaces this thermal cycle with an **electrical swing**:

1. **Capture half-cycle:** An electrode (or electrochemically-active sorbent) is set to a voltage/oxidation state that has high affinity for CO2. Ambient air flows over the electrode surface, and CO2 binds.
2. **Release half-cycle:** The voltage/oxidation state is reversed. The electrode loses affinity for CO2, releasing a concentrated stream that can be compressed and stored.

This is sometimes called **Electro-Swing Adsorption (ESA)** -- a term coined by the MIT group that became Verdox.

### 1.2 Why "Thermal Bypass" Matters

| Parameter | Thermal DAC | Electrochemical DAC |
|-----------|------------|-------------------|
| Regeneration method | Heat (80-900 degC) | Voltage swing (~1V) |
| Theoretical minimum energy | ~180 kWh/tCO2 (thermodynamic) | ~130 kWh/tCO2 (electrochemical) |
| Practical energy (current) | 1,500-2,500 kWh/tCO2 | 300-900 kWh/tCO2 (projected) |
| Heat source required | Yes (natural gas or electric) | No |
| Can use 100% electricity | Difficult (heat integration) | Yes, natively |
| Grid coupling | Complex | Simple (all-electric) |

The thermodynamic minimum energy to separate CO2 from air at ~420 ppm is approximately 20 kJ/mol (~130 kWh/tCO2). Thermal methods face Carnot efficiency limits on heat-to-work conversion, while electrochemical methods can theoretically approach thermodynamic limits more directly through voltage control.

### 1.3 Electrochemical Mechanisms in Use

There are several electrochemical approaches being pursued:

| Mechanism | Description | Key Player |
|-----------|------------|-----------|
| **Quinone redox** | Quinone-based electrodes cycle between reduced (CO2-binding) and oxidized (CO2-releasing) states | Verdox |
| **pH swing (electrodialysis)** | Electricity drives pH changes in solution; CO2 absorbs in alkaline, releases in acid | Mission Zero |
| **Electrochemical pH swing (membrane)** | Bipolar membrane electrodialysis creates acid/base streams for CO2 capture/release | RepAir |
| **Faradaic electro-swing** | General class; various redox-active materials for CO2 binding | Academic groups |
| **Molten carbonate electrolysis** | High-temperature electrochemical conversion | Various (less relevant to DAC) |

---

## 2. Key Players

### 2.1 Verdox (MIT Spinoff)

| Attribute | Detail |
|-----------|--------|
| **Founded** | 2019 |
| **Origin** | MIT spinoff; based on work by Prof. T. Alan Hatton's group |
| **Headquarters** | Woburn, Massachusetts, USA |
| **Key People** | Brian Baynes (CEO), Sahag Voskian (co-founder, CTO), T. Alan Hatton (co-founder, scientific advisor) |
| **Core IP** | Electro-Swing Adsorption (ESA) using polyanthraquinone electrodes |
| **TRL** | ~4-5 (lab-validated, moving to pilot) |

**Technology Details:**

- Uses **polyanthraquinone**-based electrodes -- a class of organic quinone polymers deposited on carbon fiber or carbon nanotube substrates.
- When reduced (electrons added), quinone groups become nucleophilic and bind CO2 as a carboxylate. When oxidized (electrons removed), the bond weakens and CO2 is released.
- The voltage swing is approximately **0.6-1.0 V** between capture and release states.
- Original 2019 paper (Voskian & Hatton, *Energy & Environmental Science*) demonstrated the concept with polyanthraquinone on carbon nanotubes.
- No liquid solvents, no membranes, no water consumption in the core process.
- The system operates as a **solid-state electrochemical cell**: electrode | electrolyte | electrode sandwich.
- Air is passed through electrode stacks in a parallel-plate or flow-through configuration.

**Funding & Partnerships:**

| Round/Source | Amount | Date | Notes |
|-------------|--------|------|-------|
| Breakthrough Energy Ventures | $80M Series A | Feb 2022 | Led by BEV |
| Pre-purchase agreements | Various | 2022-2023 | Undisclosed carbon removal buyers |
| DOE funding | Undisclosed | 2023 | Part of DOE DAC programs |
| Series B (reported) | ~$80M+ [unverified] | 2024 | Expansion funding |
| **Total raised** | **~$160M+** | Through 2024 | |

**Key Milestones:**

- 2019: Foundational paper published in *Energy & Environmental Science*
- 2020: Company founded, initial lab prototypes
- 2022: $80M Series A from Breakthrough Energy Ventures
- 2023: First integrated prototype systems; moved to larger pilot testing
- 2024: Scaling efforts; targeting first commercial demonstration unit
- 2025-2026: Planned first commercial-scale deployment [unverified timeline]

**Claimed Performance:**

- Energy consumption target: **300-500 kWh/tCO2** (electric only)
- This compares to ~1,500-2,500 kWh/tCO2 (thermal equivalent) for Climeworks/Carbon Engineering
- Theoretical minimum for their system: ~200 kWh/tCO2
- Operates at **ambient temperature and pressure**
- No water consumption in the core electrochemical process
- Electrode lifetime target: >10,000 cycles (multi-year operation)

**Key Technical Challenges:**

- **Electrode degradation:** Polyanthraquinone undergoes gradual oxidative degradation and loss of CO2-binding capacity over many cycles. Nucleophilic addition side reactions can consume active quinone sites.
- **Oxygen sensitivity:** The reduced quinone state is reactive with O2 (which is 500x more concentrated than CO2 in air), leading to parasitic oxidation and efficiency losses. This is the single biggest technical challenge.
- **Faradaic efficiency:** Not all electrons transferred result in CO2 capture/release. Side reactions with O2 and water reduce faradaic efficiency. Published values range from 50-90% depending on conditions.
- **CO2 purity:** Achieving high-purity CO2 streams (>95%) needed for geological storage requires careful cycle management.
- **Scale-up of electrode manufacturing:** Moving from lab-scale electrode fabrication to roll-to-roll manufacturing at scale.

---

### 2.2 Mission Zero Technologies

| Attribute | Detail |
|-----------|--------|
| **Founded** | 2020 |
| **Headquarters** | London, United Kingdom |
| **Key People** | Nicholas Chadwick (CEO & co-founder), Shiladitya Ghosh (CTO & co-founder) |
| **Core IP** | Electrochemical pH-swing using ion-exchange membranes and aqueous solvents |
| **TRL** | ~4-5 (lab to pilot transition) |

**Technology Details:**

- Uses an **electrochemical pH-swing** process rather than pure solid-state electro-swing.
- Air is contacted with an **alkaline aqueous solution** (e.g., KOH-based) that absorbs CO2 as dissolved carbonate/bicarbonate -- similar to the front-end of Carbon Engineering's process.
- Instead of heating the solution to release CO2 (as Carbon Engineering does at 900 degC in a calciner), Mission Zero uses **electrodialysis** with ion-exchange membranes to regenerate the solvent.
- The electrodialysis step creates acid and base streams: the acid liberates CO2 from the carbonate solution, and the base is recycled.
- This is a **hybrid approach**: chemical absorption (proven, efficient air contacting) + electrochemical regeneration (efficient, low-temperature release).
- Uses **bipolar membranes** (BPMs) and/or cation/anion exchange membranes in the electrodialysis stack.

**Funding & Partnerships:**

| Round/Source | Amount | Date | Notes |
|-------------|--------|------|-------|
| Breakthrough Energy Fellows | Fellowship | 2021 | Early support |
| Seed round | ~$5M | 2022 | Initial fundraise |
| Series A | ~$30M+ | 2023-2024 | Led by multiple climate-focused VCs |
| UK Government grants | Various | 2022-2024 | DESNZ, Innovate UK |
| Partnership with Drax | Announced | 2023 | Exploring integration with bioenergy |
| **Total raised** | **~$40-50M+** | Through 2024 | [unverified total] |

**Key Milestones:**

- 2020: Company founded in London
- 2021: Breakthrough Energy Fellows program
- 2022: Lab-scale demonstration; initial seed funding
- 2023: Pilot system construction; strategic partnerships announced
- 2024: First pilot deployment; targeting ton-scale demonstration
- 2025-2026: Scale-up to larger demonstration systems [projected]

**Claimed Performance:**

- Energy consumption target: **500-800 kWh/tCO2** (all-electric)
- Water consumption: Moderate (uses aqueous solution, but water is recycled in closed loop). Net water consumption estimated at ~1-5 tons H2O per ton CO2 [estimated].
- Operates at **near-ambient temperature** (electrodialysis typically <60 degC)
- Can use waste heat to improve efficiency if available
- Leverages well-understood air contacting chemistry (alkaline scrubbing has decades of industrial history)

**Key Technical Challenges:**

- **Membrane durability:** Ion-exchange membranes (especially bipolar membranes) degrade in CO2-rich, alkaline environments. Membrane lifetime and replacement cost are critical scaling factors.
- **Membrane cost:** Current BPM costs are high ($500-2,000/m2). Need order-of-magnitude cost reduction for DAC economics.
- **Voltage efficiency:** Electrodialysis cells have overpotential losses. Practical cell voltages of 1.5-3V vs. theoretical ~0.8V mean significant efficiency losses.
- **CO2 crossover:** CO2 and carbonate ions can migrate through membranes, reducing capture efficiency.
- **Solvent management:** Maintaining optimal alkaline solution chemistry over many cycles, preventing precipitation and fouling.

---

### 2.3 RepAir Carbon Capture

| Attribute | Detail |
|-----------|--------|
| **Founded** | 2020 |
| **Headquarters** | Tel Aviv, Israel |
| **Key People** | Amir Shiner (CEO), based on research from Technion - Israel Institute of Technology |
| **Core IP** | Electrochemical cell with continuous flow; bipolar membrane electrodialysis for CO2 separation |
| **TRL** | ~3-4 (lab-scale, early pilot) |

**Technology Details:**

- Uses **bipolar membrane electrodialysis (BPMED)** to drive pH-swing CO2 capture and release.
- Similar in concept to Mission Zero's approach but with distinct cell architecture and membrane configurations.
- CO2 from air is absorbed into an alkaline solution (forming carbonates). The solution passes through an electrodialysis stack where bipolar membranes split water into H+ and OH- ions.
- H+ ions acidify the carbonate solution, releasing CO2 gas. OH- ions regenerate the alkaline capture solution.
- RepAir has emphasized a **continuous-flow architecture** (as opposed to batch cycling), which could improve throughput and reduce capital intensity.
- Published research from Technion group (Prof. Matthew Suss and colleagues) underpins the technology.

**Funding & Partnerships:**

| Round/Source | Amount | Date | Notes |
|-------------|--------|------|-------|
| Seed funding | ~$5M | 2022 | Early investors |
| Series A | ~$12-15M | 2023 | Climate-tech investors |
| Israel Innovation Authority | Grants | 2022-2023 | Government support |
| Carbon removal pre-purchases | Various | 2023-2024 | Frontier, other buyers |
| **Total raised** | **~$20-30M** | Through 2024 | [unverified total] |

**Key Milestones:**

- 2020: Founded based on Technion research
- 2021-2022: Lab-scale demonstrations
- 2023: Seed/Series A funding; prototype development
- 2024: Pilot system targeting ~100 tCO2/year scale
- 2025-2026: Scale-up to demonstration plant [projected]

**Claimed Performance:**

- Energy consumption: **~700-1,000 kWh/tCO2** for early systems, targeting **400-600 kWh/tCO2** at scale
- Uses aqueous solutions (water consumption similar to Mission Zero)
- Operates at near-ambient temperatures
- Continuous-flow design aims for higher utilization rates than batch systems
- Target cost: <$200/tCO2 at scale (long-term target <$100/tCO2)

**Key Technical Challenges:**

- **Same membrane challenges as Mission Zero:** BPM durability, cost, and CO2 crossover
- **Early stage:** Less demonstrated at scale than Verdox or Mission Zero
- **Continuous-flow complexity:** Maintaining consistent CO2 release rates in a continuous system adds engineering complexity
- **Scaling manufacturing:** Need to industrialize membrane and cell stack production

---

## 3. Physical Constraints

### 3.1 Land/Ocean Footprint per Ton CO2/Year

| Approach | Estimated Footprint | Notes |
|----------|-------------------|-------|
| **Electrochemical DAC (general)** | ~0.5-2 m2 per tCO2/year | Based on electrode stack volumetric capture rates |
| **Verdox** | ~0.5-1 m2 per tCO2/year [projected] | Compact solid-state cells; no large air contactors needed beyond fans |
| **Mission Zero** | ~1-3 m2 per tCO2/year [estimated] | Needs air contactor (similar to CE/Oxy) + electrodialysis stacks |
| **RepAir** | ~1-3 m2 per tCO2/year [estimated] | Similar to Mission Zero |
| **Climeworks (solid sorbent)** | ~1-2 m2 per tCO2/year | Mammoth plant data |
| **Carbon Engineering/Oxy (liquid solvent)** | ~0.5-1 m2 per tCO2/year | Large air contactors but high throughput |

**Key considerations for footprint:**

- Electrochemical DAC's footprint is dominated by **air contacting** -- moving enough ambient air (at ~420 ppm CO2) through the system. At 420 ppm, you need to process ~1.4 million cubic meters of air per ton of CO2 captured (assuming ~50% capture efficiency from the air stream).
- Verdox's solid-state approach may allow more compact designs since the electrode IS the sorbent.
- Mission Zero and RepAir require separate air contactors + electrodialysis equipment, increasing footprint.
- All approaches require land for **balance of plant**: power supply, CO2 compression, piping, control systems.
- At 10 Gt/year: Would require ~5,000-30,000 km2 total land area. For reference, this is roughly 0.003-0.02% of Earth's land surface, or roughly the area of a small to mid-size US state.

### 3.2 Location Dependency

| Factor | Dependency Level | Notes |
|--------|-----------------|-------|
| **Temperature** | Low-Moderate | Electrochemical kinetics improve slightly with temperature, but systems operate at ambient. No need for high-temp heat source. |
| **Humidity** | Moderate | High humidity can reduce CO2 absorption efficiency (water competes for binding sites in Verdox; dilutes solutions in Mission Zero/RepAir). Low humidity is mildly favorable. |
| **Altitude** | Low | Lower atmospheric pressure slightly reduces CO2 partial pressure, but effect is small. |
| **Clean electricity access** | **HIGH** | The defining constraint. Must have abundant, cheap, clean electricity. |
| **CO2 storage proximity** | **HIGH** | Need geological storage or CO2 utilization infrastructure nearby. |
| **Water access** | Low (Verdox) / Moderate (Mission Zero, RepAir) | Verdox is near-waterless. Others need water for solvent loops. |
| **Wind/airflow** | Low-Moderate | Good airflow reduces fan energy for air contacting. |

**Optimal locations for electrochemical DAC:**

1. **Regions with abundant cheap renewables**: Solar-rich deserts (Middle East, North Africa, US Southwest, Australia), wind-rich areas (US Great Plains, Patagonia, North Sea)
2. **Near geological storage**: Basalt formations (Iceland, Pacific Northwest), saline aquifers, depleted oil/gas reservoirs
3. **Low humidity preferred** but not required
4. **Grid-connected or dedicated renewable**: Can be co-located with solar/wind farms

**Key advantage over thermal DAC:** No need for natural gas infrastructure or high-temperature heat, meaning electrochemical DAC can be sited purely based on electricity and storage access.

---

## 4. Resource Constraints

### 4.1 Energy Intensity (kWh per ton CO2)

This is the critical metric where electrochemical DAC claims its primary advantage.

| System | Energy Type | Current (kWh/tCO2) | Target (kWh/tCO2) | Theoretical Min |
|--------|-----------|-------------------|--------------------|-----------------|
| **Verdox** | Electric only | ~800-1,500 (prototype) | 300-500 | ~200 |
| **Mission Zero** | Electric only | ~1,000-1,500 (prototype) | 500-800 | ~300 |
| **RepAir** | Electric only | ~1,200-2,000 (early lab) | 400-700 | ~300 |
| **Climeworks (Mammoth)** | Electric + Thermal | ~2,000-2,500 total (500-700 elec + 1,500-1,800 thermal) | 1,500-2,000 | ~180 (thermo) |
| **Carbon Engineering/1PointFive** | Electric + Thermal (gas) | ~2,400-3,100 total (~1,400 thermal from gas) | 1,800-2,200 | ~180 (thermo) |

**Breaking down the energy budget for electrochemical DAC:**

| Component | % of Total Energy | Notes |
|-----------|------------------|-------|
| Electrochemical swing (capture/release) | 40-60% | The core voltage-driven process |
| Air contacting (fans/blowers) | 20-30% | Moving ~1.4M m3 air per tCO2 |
| CO2 compression (to pipeline/storage spec) | 10-20% | Compressing to ~150 bar for geological storage |
| Balance of plant | 5-10% | Controls, pumps, cooling |

**The 3-4x efficiency claim:**

- Comparing Verdox target (300-500 kWh/tCO2 electric) to Climeworks (2,000-2,500 kWh/tCO2 total): **ratio is ~4-8x**
- However, this comparison mixes electric and thermal energy. On a **primary energy** basis (accounting for electricity generation efficiency):
  - Verdox at 400 kWh electric = ~400 kWh primary (if renewable)
  - Climeworks at 2,000 kWh (mixed) = ~2,000 kWh primary (if using geothermal like in Iceland)
  - Ratio: ~5x
- On a **useful work (exergy)** basis, the advantage is more like 2-4x
- The "3-4x" claim is reasonable but depends on assumptions about energy sources and system boundaries.

### 4.2 Freshwater Consumption

| System | Water Use (tons H2O / ton CO2) | Notes |
|--------|-------------------------------|-------|
| **Verdox** | ~0-1 | Near-zero in core process. Some water for humidification control or cooling. |
| **Mission Zero** | ~1-5 | Closed-loop aqueous system. Net loss from evaporation in air contactor. |
| **RepAir** | ~1-5 | Similar to Mission Zero |
| **Climeworks** | ~0-2 | Solid sorbent; some water co-adsorbed and lost |
| **Carbon Engineering/Oxy** | ~5-10 | KOH solution open to air in contactor; significant evaporative losses |

**At 10 Gt/year scale:**
- Verdox approach: ~0-10 billion tons water/year (negligible globally; global freshwater use is ~4,000 Gt/year)
- Mission Zero/RepAir: ~10-50 billion tons water/year (still <2% of global freshwater use, but could be locally significant)
- Water is NOT a binding constraint for electrochemical DAC at global scale, but local water stress matters for siting.

### 4.3 Material Inputs

#### 4.3.1 Verdox: Electrode Materials

| Material | Role | Abundance | Supply Risk |
|----------|------|-----------|-------------|
| **Polyanthraquinone (PAQ)** | Active CO2-binding material | Synthesized from anthraquinone; petroleum-derived but could be bio-sourced | Low-Moderate (chemical synthesis at scale) |
| **Anthraquinone** | Precursor | Major industrial chemical (~100,000 tonnes/year global production for pulp/paper industry) | Low |
| **Carbon nanotubes (CNTs)** or carbon fiber | Electrode substrate/current collector | Large and growing industrial base | Low |
| **Electrolyte** | Ion transport between electrodes | Ionic liquids or gel polymer electrolytes | Moderate (specialty chemicals) |
| **Cell housing/frames** | Structural | Steel, plastics | Low |

**Critical material assessment for Verdox:**
- No rare earth elements, platinum group metals, or critical minerals required
- Anthraquinone is produced at scale (~$2-5/kg) and is not supply-constrained
- Carbon nanotube production is scaling rapidly (~$50-200/kg currently, declining)
- **Key risk:** Specialty electrolytes may face supply bottlenecks during rapid scale-up

#### 4.3.2 Mission Zero & RepAir: Membrane Materials

| Material | Role | Abundance | Supply Risk |
|----------|------|-----------|-------------|
| **Ion-exchange membranes (IEMs)** | Cation/anion separation | Specialty polymer manufacturing | **Moderate-High** |
| **Bipolar membranes (BPMs)** | Water splitting for pH swing | Limited commercial production | **High** |
| **Perfluorinated polymers** (e.g., Nafion-type) | Common IEM material | Fluorochemical supply chain | Moderate |
| **Hydrocarbon-based IEMs** | Alternative to fluorinated | Under development; more sustainable | Moderate |
| **KOH / NaOH** | Alkaline capture solvent | Major industrial chemicals | Low |
| **Electrodes (Ti, Pt, IrO2)** | Electrodialysis electrodes | Pt and Ir are rare/expensive | **Moderate-High** |
| **Cell spacers, gaskets** | Flow distribution | Standard polymers | Low |

**Critical material assessment for Mission Zero/RepAir:**
- **Bipolar membranes are the bottleneck.** Global BPM production is currently tiny (~thousands of m2/year). Scaling to millions of m2/year for gigatonne DAC would require massive expansion of membrane manufacturing.
- Fluorinated membrane materials (PFAS-adjacent) face growing regulatory pressure in EU and elsewhere.
- Electrode catalysts (Pt, Ir) are used in small quantities per cell but could become a constraint at extreme scale. Research on earth-abundant catalysts (Ni, Fe, Mn oxides) is active.
- KOH/NaOH are commodity chemicals produced at hundreds of millions of tonnes/year -- not a constraint.

#### 4.3.3 Material Requirements at 10 Gt/year Scale (Rough Estimates)

| Material | Verdox (10 Gt/yr) | Mission Zero/RepAir (10 Gt/yr) | Global Production (current) |
|----------|-------------------|-------------------------------|---------------------------|
| Anthraquinone | ~1-10 Mt/yr [estimated] | N/A | ~0.1 Mt/yr |
| Carbon nanotubes | ~0.5-5 Mt/yr [estimated] | N/A | ~0.01 Mt/yr |
| Ion-exchange membranes | N/A | ~100-1,000 Mm2/yr [estimated] | ~10 Mm2/yr |
| Bipolar membranes | N/A | ~100-1,000 Mm2/yr [estimated] | ~0.1 Mm2/yr |
| KOH/NaOH | Minimal | ~1-10 Mt/yr (makeup) | ~80 Mt/yr (NaOH) |
| Steel (structural) | ~100-500 Mt/yr | ~100-500 Mt/yr | ~1,900 Mt/yr |

**Conclusion:** Material supply chains would need **100-1,000x scale-up** for some specialty components. This is achievable over decades but represents a significant industrial mobilization, comparable to the scale-up of solar PV manufacturing over 2005-2025.

---

## 5. Throughput Metrics

### 5.1 Capture Rate per Unit/Year

| System | Unit Size | Capture Rate | Notes |
|--------|----------|-------------|-------|
| **Verdox (projected module)** | Single electrode stack module | ~10-100 tCO2/year per module | Modular, stackable design |
| **Mission Zero (projected)** | Containerized unit | ~50-500 tCO2/year per unit | Similar to Climeworks container approach |
| **RepAir (projected)** | Containerized unit | ~50-500 tCO2/year per unit | Continuous-flow may enable higher throughput |
| **Climeworks (Mammoth)** | Full plant (72 collectors) | ~36,000 tCO2/year | Operational 2024 in Iceland |
| **1PointFive/Oxy (Stratos)** | Full plant | ~500,000 tCO2/year (design) | Under construction in Texas |

**Volumetric capture rate** (tCO2 per m3 of reactor volume per year):
- Electrochemical cells are compact. Estimated ~5-50 tCO2/m3/year for the electrochemical reactor itself.
- Air contacting volume dominates overall system size.
- Verdox's solid-state approach integrates air contacting and reaction in one unit, potentially achieving higher volumetric rates.

### 5.2 Duty Cycle / Uptime

| System | Cycle Time | Duty Cycle | Uptime Target |
|--------|-----------|-----------|--------------|
| **Verdox** | ~30-120 seconds per half-cycle (capture then release) | ~50% capture, ~50% release (or use two banks alternating) | >90% annual uptime target |
| **Mission Zero** | Continuous (air contacting) + batch electrodialysis | ~70-90% capture time | >85% annual uptime target |
| **RepAir** | Continuous flow (both capture and release) | ~90%+ theoretical | >85% annual uptime target |
| **Climeworks** | ~4-8 hours per full cycle | ~50% (alternating banks) | >85% (demonstrated ~80% at Orca) |

**Key uptime factors:**
- Electrode/membrane replacement downtime
- Fouling and cleaning cycles
- Weather and environmental conditions (minor for electrochemical)
- Power supply reliability
- Maintenance and inspection

**Advantage of electrochemical:** Fast cycle times (seconds to minutes vs. hours for thermal) enable rapid response to variable renewable electricity -- can ramp up/down quickly, acting as a flexible load.

### 5.3 Lifecycle / Durability

| Component | Current Lifetime | Target Lifetime | Replacement Impact |
|-----------|-----------------|----------------|-------------------|
| **Verdox electrodes (PAQ)** | ~1,000-5,000 cycles (lab) | >10,000-50,000 cycles (3-10 years) | Major CAPEX driver |
| **Verdox electrolyte** | ~1-3 years [estimated] | >5 years | Moderate cost |
| **Mission Zero BPMs** | ~2,000-10,000 hours | >20,000-50,000 hours (3-6 years) | Major CAPEX/OPEX driver |
| **Mission Zero IEMs** | ~5,000-20,000 hours | >30,000 hours (3-5 years) | Moderate cost |
| **RepAir membranes** | Similar to Mission Zero | Similar targets | Similar impact |
| **Fans/blowers** | 5-10 years | 10-15 years | Standard industrial equipment |
| **Structural/housing** | 20-30 years | 20-30 years | Minor replacement cost |

**Degradation mechanisms:**

For **Verdox (quinone electrodes):**
- Oxidative degradation of quinone polymer by O2
- Electrolyte decomposition
- Loss of electronic conductivity in electrode
- Mechanical stress from cycling (swelling/contraction)
- Contamination from air pollutants (SO2, NOx)

For **Mission Zero / RepAir (membranes):**
- Chemical degradation of membrane polymers by radicals
- Fouling by carbonate precipitation
- Delamination of bipolar membrane junction
- Loss of ion-exchange capacity over time
- Mechanical failure from pressure cycling

**This is arguably the #1 technical risk** for all electrochemical DAC approaches. If electrode/membrane lifetime is too short, replacement costs dominate economics and make the approach uncompetitive.

---

## 6. End Game: Storage

Electrochemical DAC produces concentrated CO2 gas, which then needs permanent storage. The storage challenge is shared with all DAC methods.

### 6.1 Storage Medium Options

| Storage Method | Permanence | Capacity | Maturity | Cost ($/tCO2) |
|---------------|-----------|---------|---------|---------------|
| **Geological (saline aquifers)** | 10,000+ years | ~10,000+ GtCO2 globally | TRL 7-9 | $10-30 |
| **Geological (depleted oil/gas)** | 10,000+ years | ~1,000+ GtCO2 globally | TRL 9 (EOR proven) | $10-25 |
| **Basalt mineralization** | Permanent (mineral) | Effectively unlimited | TRL 6-7 (Carbfix) | $15-50 |
| **Deep ocean injection** | 1,000+ years | Very large | TRL 4-5 (controversial) | $10-30 |
| **Concrete/building materials** | Permanent (mineralized) | ~1-10 GtCO2/yr potential | TRL 6-8 | Revenue-generating |
| **Enhanced oil recovery (EOR)** | Variable | ~100+ GtCO2 | TRL 9 | Revenue-generating |
| **Synthetic fuels (e-fuels)** | Temporary (re-released) | N/A | TRL 5-7 | Revenue-generating |

### 6.2 Storage Capacity Limits

| Repository Type | Estimated Global Capacity | Sufficient for 10 Gt/yr? |
|----------------|--------------------------|--------------------------|
| Deep saline aquifers | 1,000-10,000+ GtCO2 | Yes (100-1,000+ years) |
| Depleted oil & gas fields | 500-1,000+ GtCO2 | Yes (50-100+ years) |
| Basalt formations | Effectively unlimited | Yes |
| Coal seams | 50-200 GtCO2 | Supplementary only |
| **Total geological** | **~2,000-12,000+ GtCO2** | **Yes** |

**Storage is NOT the bottleneck** for electrochemical DAC at gigatonne scale. Global geological storage capacity vastly exceeds foreseeable needs. The bottleneck is characterization, permitting, and injection infrastructure buildout.

### 6.3 Permanence Risk

| Risk | Probability | Mitigation |
|------|------------|-----------|
| Leakage from saline aquifers | Very low (<1% over 1,000 years per IPCC) | Site characterization, monitoring, caprock integrity assessment |
| Well integrity failure | Low-moderate | Proper well completion, monitoring, regulatory oversight |
| Induced seismicity | Low | Rate-controlled injection, site selection away from faults |
| Basalt mineralization reversal | Essentially zero | CO2 converts to carbonate minerals; thermodynamically stable |
| Political/regulatory risk | Moderate | Long-term liability frameworks needed |

**Basalt mineralization (Carbfix process) is the gold standard** for permanence: CO2 injected into reactive basalt converts to carbonate minerals within 1-2 years. This is essentially permanent -- the CO2 becomes rock.

---

## 7. Economic Friction

### 7.1 CAPEX

| Component | Cost Range | % of Total CAPEX | Notes |
|-----------|-----------|-----------------|-------|
| **Electrochemical cell stacks** | High (dominant) | 40-60% | Electrodes/membranes, current collectors, housing |
| **Air contactors** | Moderate | 15-25% | Fans, ductwork, contactors (larger for Mission Zero/RepAir) |
| **CO2 compression & processing** | Moderate | 10-15% | Standard industrial equipment |
| **Balance of plant** | Moderate | 10-20% | Power electronics, controls, piping |
| **Civil works & installation** | Low-Moderate | 5-10% | Foundations, buildings, site prep |

**Estimated total CAPEX per tCO2/year capacity:**

| System | Current Estimate | Target at Scale |
|--------|-----------------|----------------|
| **Verdox** | ~$2,000-5,000 / (tCO2/yr) [estimated] | ~$500-1,500 / (tCO2/yr) |
| **Mission Zero** | ~$3,000-6,000 / (tCO2/yr) [estimated] | ~$500-2,000 / (tCO2/yr) |
| **RepAir** | ~$3,000-8,000 / (tCO2/yr) [estimated] | ~$500-2,000 / (tCO2/yr) |
| **Climeworks** | ~$10,000-15,000 / (tCO2/yr) | ~$2,000-4,000 / (tCO2/yr) target |
| **1PointFive/Oxy** | ~$3,000-5,000 / (tCO2/yr) | ~$1,000-2,000 / (tCO2/yr) target |

### 7.2 OPEX

| Cost Component | Electrochemical DAC | Thermal DAC (Climeworks) | Thermal DAC (CE/Oxy) |
|---------------|--------------------|-----------------------|---------------------|
| **Electricity** | $15-50/tCO2 (at $0.03-0.05/kWh) | $15-35/tCO2 | $20-40/tCO2 |
| **Natural gas/heat** | $0 | $0 (geothermal in Iceland) | $30-60/tCO2 |
| **Electrode/membrane replacement** | $20-100/tCO2 [estimated] | $10-30/tCO2 (sorbent) | $5-15/tCO2 (solvent) |
| **Water** | $0-5/tCO2 | $1-3/tCO2 | $2-5/tCO2 |
| **Labor & maintenance** | $10-30/tCO2 | $10-30/tCO2 | $10-20/tCO2 |
| **CO2 compression** | $10-20/tCO2 | $10-20/tCO2 | $10-20/tCO2 |
| **Total OPEX** | **$55-205/tCO2** | **$46-118/tCO2** | **$77-160/tCO2** |

**Note:** Electrode/membrane replacement is the highest-uncertainty OPEX item for electrochemical DAC. If lifetimes reach targets, this cost drops to $10-30/tCO2. If lifetimes are poor, it could exceed $100/tCO2.

### 7.3 Cost per Ton CO2 (Levelized)

| System | Current Cost | 2030 Projection | Long-term Target |
|--------|-------------|-----------------|-----------------|
| **Verdox** | ~$600-1,500/tCO2 [estimated early systems] | ~$200-400/tCO2 | <$100/tCO2 |
| **Mission Zero** | ~$800-2,000/tCO2 [estimated] | ~$200-500/tCO2 | <$100/tCO2 |
| **RepAir** | ~$1,000-2,500/tCO2 [estimated] | ~$300-600/tCO2 | <$100/tCO2 |
| **Climeworks** | ~$600-1,000/tCO2 (Mammoth) | ~$300-400/tCO2 | ~$200-300/tCO2 |
| **1PointFive/Oxy** | ~$400-600/tCO2 (Stratos design) | ~$200-300/tCO2 | ~$100-200/tCO2 |

**The critical question:** Can electrochemical DAC achieve lower costs than thermal DAC at scale? The energy advantage is real, but:
- Electrode/membrane costs and lifetimes are unproven at scale
- Thermal DAC has a 5-10 year head start in deployment and learning
- Thermal DAC can use cheap waste heat where available

### 7.4 Learning Rate

| Technology Analog | Learning Rate (% cost reduction per doubling) | Notes |
|-------------------|----------------------------------------------|-------|
| Solar PV | ~20-24% | Most relevant analog for modular, manufactured technology |
| Lithium-ion batteries | ~18-20% | Electrochemical manufacturing experience |
| Electrolyzers (PEM) | ~15-18% | Direct analog for membrane electrochemical systems |
| Wind turbines | ~12-15% | More mechanical, less applicable |
| Solid sorbent DAC (Climeworks) | ~15-20% [estimated] | Still early on learning curve |

**Electrochemical DAC should achieve a 15-22% learning rate**, based on analogy to solar PV and battery manufacturing:
- Modular, factory-produced units (not custom megaprojects)
- Heavy reliance on manufactured components (electrodes, membranes) that benefit from scale
- Material science improvements can yield step-change improvements
- Roll-to-roll manufacturing potential for electrodes and membranes

**Implication:** If starting at $800/tCO2 today with 18% learning rate:
- After 10 doublings (~1,000x scale-up from ~1,000 tCO2/yr to ~1 MtCO2/yr): ~$110/tCO2
- After 15 doublings (~30,000x to ~30 MtCO2/yr): ~$50/tCO2
- This trajectory suggests <$100/tCO2 is achievable but requires sustained deployment and R&D.

### 7.5 Revenue Streams

| Revenue Source | Current Price | Future Price | Addressable Market |
|---------------|--------------|-------------|-------------------|
| **Voluntary carbon credits** | $200-1,000/tCO2 (DAC-specific) | $50-200/tCO2 | Growing but limited (~50 MtCO2/yr market today) |
| **Compliance carbon markets** | $50-100/tCO2 (EU ETS) | $100-300/tCO2 | Large if DAC is included in compliance frameworks |
| **45Q tax credit (US)** | $180/tCO2 (DAC + storage) | May increase | US market only; strong incentive |
| **CO2 utilization (e-fuels)** | $200-600/tCO2 equivalent | $100-300/tCO2 | Large potential market (aviation fuel) |
| **CO2 utilization (concrete)** | $30-100/tCO2 | $30-100/tCO2 | Moderate |
| **Carbon removal pre-purchases** | $500-2,000/tCO2 | $100-300/tCO2 | Growing (Frontier, Microsoft, etc.) |

**The US 45Q tax credit at $180/tCO2** for DAC with geological storage is the most significant near-term revenue driver. Combined with voluntary credits, early DAC projects can achieve $300-500+/tCO2 revenue, making first-of-a-kind plants economically viable despite high initial costs.

---

## 8. Additional Feasibility Data

### 8.1 Technology Readiness Level Summary

| Company | TRL | Evidence |
|---------|-----|---------|
| **Verdox** | 4-5 | Lab-validated electrode chemistry. Integrated prototype systems demonstrated. Moving toward first pilot/demonstration. |
| **Mission Zero** | 4-5 | Lab demonstrations of electrodialysis regeneration. Pilot systems under construction. Partnership with Drax announced. |
| **RepAir** | 3-4 | Lab-scale proof of concept. Early prototype development. Based on published Technion research. |
| **Climeworks (comparison)** | 8-9 | Commercial plants operating (Orca: 4,000 tCO2/yr; Mammoth: 36,000 tCO2/yr) |
| **1PointFive/Oxy (comparison)** | 7-8 | Stratos plant under construction (~500,000 tCO2/yr design capacity) |

### 8.2 Current Capacity and Pilot Projects

| Company | Current Operational Capacity | Planned Near-term | Location |
|---------|----------------------------|-------------------|----------|
| **Verdox** | Lab/prototype scale (~kg CO2/day) | First demonstration unit (hundreds of tCO2/yr) by 2025-2026 | Massachusetts, USA |
| **Mission Zero** | Lab/early pilot (~kg CO2/day) | Ton-scale pilot by 2025 | United Kingdom |
| **RepAir** | Lab scale (~g-kg CO2/day) | ~100 tCO2/yr pilot planned | Israel |

### 8.3 Funding Summary

| Company | Total Funding | Key Investors | Government Support |
|---------|--------------|--------------|-------------------|
| **Verdox** | ~$160M+ | Breakthrough Energy Ventures, Prelude Ventures, others | DOE programs |
| **Mission Zero** | ~$40-50M+ | Climate-tech VCs, Breakthrough Energy Fellows | UK Government (DESNZ, Innovate UK) |
| **RepAir** | ~$20-30M | Climate-tech investors | Israel Innovation Authority |

### 8.4 Key Technical Challenges (Detailed)

#### 8.4.1 Electrode Degradation (Verdox-specific)

The oxygen problem is central to Verdox's technology challenge:

- **The O2 competition problem:** Air is ~21% O2 and ~0.042% CO2 -- a 500:1 ratio. Reduced quinones react with both CO2 and O2, but O2 is far more abundant.
- **Parasitic current from O2 reduction:** Each O2 molecule that reacts with a reduced quinone site wastes 2 electrons and deactivates the site. This directly reduces faradaic efficiency and electrode lifetime.
- **Mitigation strategies:**
  - Engineering electrode microstructure to favor CO2 access
  - Surface coatings or electrolyte modifications to slow O2 diffusion
  - Operating at higher current densities to shift selectivity
  - Developing quinone variants with higher CO2/O2 selectivity
- **Progress:** Verdox has reportedly improved O2 tolerance significantly since the 2019 paper, but exact figures are proprietary.

#### 8.4.2 Membrane Degradation (Mission Zero / RepAir-specific)

- Bipolar membranes currently last ~2,000-10,000 hours in aggressive conditions
- Target for economic viability: >20,000 hours (2.5+ years continuous)
- Degradation accelerated by: high current density, temperature excursions, impurities in solution
- Active research areas: new membrane chemistries, improved junction layers, reinforced structures

#### 8.4.3 Energy Efficiency at Scale

- Lab-scale cells often achieve near-theoretical efficiency at low current densities
- At higher current densities (needed for economic throughput), overpotentials increase and efficiency drops
- The efficiency vs. throughput tradeoff is critical for economic optimization
- Ohmic losses, mass transfer limitations, and concentration polarization all worsen at scale

#### 8.4.4 CO2 Purity and Compression

- Geological storage requires >95% CO2 purity (often >99%)
- Electrochemical systems may co-release water vapor, O2, or N2
- Additional purification/dehydration steps add cost and complexity
- CO2 compression from ambient to storage pressure (~150 bar) requires ~100-120 kWh/tCO2 regardless of capture method

### 8.5 Theoretical Efficiency Advantage over Thermal Methods

**Fundamental thermodynamic analysis:**

The minimum work to separate CO2 from air at 420 ppm to pure CO2:

```
W_min = RT * ln(1/y_CO2) = 8.314 * 298 * ln(1/0.00042) = ~19.5 kJ/mol = ~123 kWh/tCO2
```

**Why electrochemical can be more efficient:**

1. **No Carnot limit:** Thermal regeneration is limited by Carnot efficiency (e.g., at 100 degC regeneration and 25 degC ambient, Carnot limit is ~20% for work from heat). Electrochemical systems convert electricity directly to chemical work.

2. **No sensible heat penalty:** Thermal systems must heat the entire sorbent/solvent mass, not just the CO2. This "thermal mass penalty" means heating kilograms of material to release grams of CO2.

3. **No heat exchanger losses:** Thermal systems lose significant energy through imperfect heat exchange, even with 90%+ heat recovery.

4. **Direct molecular control:** Voltage directly controls the bond energy between sorbent and CO2, allowing precise energy input matched to the binding energy.

**Theoretical second-law efficiency comparison:**

| Approach | Theoretical 2nd-Law Efficiency | Practical Achievable |
|----------|------------------------------|---------------------|
| Electrochemical (Verdox) | 30-60% | 15-35% |
| Electrochemical (pH-swing) | 20-40% | 10-25% |
| Solid sorbent (thermal) | 10-25% | 5-15% |
| Liquid solvent (thermal) | 5-15% | 3-8% |

### 8.6 Timeline Projections

| Milestone | Verdox | Mission Zero | RepAir |
|-----------|--------|-------------|--------|
| Lab proof of concept | 2019 (done) | 2020-2021 (done) | 2020-2021 (done) |
| Integrated prototype | 2022-2023 (done) | 2023 (done) | 2023-2024 |
| First pilot (10-100 tCO2/yr) | 2024-2025 | 2024-2025 | 2025-2026 |
| Demonstration (1,000+ tCO2/yr) | 2026-2028 | 2026-2028 | 2027-2029 |
| First commercial (10,000+ tCO2/yr) | 2028-2030 | 2028-2031 | 2029-2032 |
| Megatonne scale | 2032-2035 | 2033-2036 | 2034-2037 |
| Gigatonne pathway | 2040+ | 2040+ | 2040+ |

**Comparison to thermal DAC timeline:**
- Climeworks: First commercial 2017, Mammoth (36 kt/yr) 2024, megatonne target ~2030
- 1PointFive/Oxy: Stratos (500 kt/yr) ~2025, megatonne by ~2028-2030
- **Electrochemical DAC is approximately 5-8 years behind thermal DAC in deployment timeline.**

---

## 9. Comparison to Thermal DAC Approaches

### 9.1 Solid Sorbent (Climeworks / Global Thermostat)

| Parameter | Electrochemical DAC | Solid Sorbent DAC |
|-----------|--------------------|--------------------|
| **Regeneration** | Voltage swing | Temperature swing (80-120 degC) |
| **Energy type** | 100% electric | Electric + low-grade heat |
| **Energy intensity** | 300-900 kWh/tCO2 (target) | 1,500-2,500 kWh/tCO2 (total) |
| **Water use** | Low | Low-moderate |
| **Sorbent/electrode lifetime** | Uncertain (1,000-50,000 cycles target) | ~3-5 years demonstrated |
| **Modularity** | High (factory-built) | High (containerized) |
| **Heat integration** | Not needed | Can use waste/geothermal heat |
| **TRL** | 3-5 | 8-9 |
| **Key advantage** | Energy efficiency, all-electric | Proven at commercial scale |
| **Key risk** | Electrode durability, O2 sensitivity | Sorbent degradation, heat source dependency |

### 9.2 Liquid Solvent (Carbon Engineering / 1PointFive / Occidental)

| Parameter | Electrochemical DAC | Liquid Solvent DAC |
|-----------|--------------------|--------------------|
| **Regeneration** | Voltage swing or electrochemical pH swing | Calcination at ~900 degC |
| **Energy type** | 100% electric | Natural gas + electric |
| **Energy intensity** | 300-900 kWh/tCO2 (target) | 2,400-3,100 kWh/tCO2 (total) |
| **Water use** | Low-moderate | High (5-10 t H2O/tCO2) |
| **Scale per plant** | Small-medium (modular) | Very large (chemical plant scale) |
| **CAPEX per unit** | Moderate (manufactured) | Very high (custom build) |
| **CO2 purity** | Moderate-high | Very high |
| **TRL** | 3-5 | 7-8 |
| **Key advantage** | Energy efficiency, modularity, no gas needed | Proven chemistry, high throughput, high purity |
| **Key risk** | Electrode/membrane durability | Fossil fuel dependency, high temp corrosion |

### 9.3 Hybrid Approaches

Mission Zero's approach is notably a **hybrid** -- it uses liquid solvent air contacting (like Carbon Engineering) but electrochemical regeneration (avoiding the 900 degC calciner). This potentially combines the best of both worlds:
- Proven, efficient air contacting with alkaline solution
- Electrochemical regeneration avoiding extreme temperatures
- But inherits membrane challenges from the electrochemical side

---

## 10. Ten Gigaton/Year Scale Assessment

### 10.1 What Would 10 Gt/year of Electrochemical DAC Require?

| Resource | Requirement | Global Context |
|----------|------------|---------------|
| **Electricity** | 3,000-9,000 TWh/year | 10-30% of current global electricity production (~30,000 TWh/yr). Comparable to total current solar+wind generation. |
| **Land** | 5,000-30,000 km2 | 0.003-0.02% of Earth's land. Roughly one US state. |
| **Water** | 0-50 Gt/year | 0-1.3% of global freshwater use |
| **Steel** | 100-500 Mt/year | 5-25% of current global steel production |
| **Capital investment** | $5-15 trillion (cumulative to build out) | Comparable to global fossil fuel infrastructure |
| **Specialty materials** | Massive scale-up needed | 100-1,000x current production of electrodes/membranes |
| **Storage capacity** | 10 Gt injection/year | Would require ~3,000-10,000 injection wells worldwide |
| **Annual operating cost** | $0.5-2 trillion/year (at $50-200/tCO2) | 0.5-2% of current global GDP |

### 10.2 Binding Constraints for 10 Gt/year

| Constraint | Severity | Timeframe to Resolve |
|-----------|----------|---------------------|
| **Clean electricity supply** | **CRITICAL** | 20-30 years (massive renewable buildout required) |
| **Specialty material manufacturing** | **HIGH** | 10-20 years (industrial mobilization) |
| **CO2 storage infrastructure** | **HIGH** | 15-25 years (well drilling, pipeline construction) |
| **Cost reduction** | **HIGH** | 10-20 years (learning curve deployment) |
| **Technology maturation** | **MODERATE** | 5-10 years (electrode/membrane durability proof) |
| **Land** | **LOW** | Not a binding constraint |
| **Water** | **LOW** | Not a binding constraint for most approaches |
| **Regulatory/permitting** | **MODERATE** | Ongoing |

### 10.3 Electricity: The Dominant Constraint

At 10 Gt/year with 500 kWh/tCO2 (optimistic target):
- **5,000 TWh/year** of clean electricity needed for DAC alone
- This is equivalent to ~1,700 GW of solar capacity at 34% capacity factor, or ~1,500 GW of wind at 38% capacity factor
- Current global solar capacity: ~1,500 GW (2024); wind: ~1,000 GW
- **Implication: 10 Gt/year of electrochemical DAC would roughly require doubling current global solar+wind capacity, dedicated to DAC.**
- At $0.03/kWh: electricity cost alone = $150 billion/year. At $0.02/kWh: $100 billion/year.

### 10.4 Realistic Timeline for 10 Gt/year

Assuming aggressive but not unrealistic deployment:

| Year | Cumulative Electrochemical DAC Capacity | Notes |
|------|----------------------------------------|-------|
| 2025 | ~100-1,000 tCO2/yr | Pilot systems |
| 2030 | ~100,000-1,000,000 tCO2/yr | First commercial plants |
| 2035 | ~10-50 MtCO2/yr | Rapid scale-up phase |
| 2040 | ~100-500 MtCO2/yr | Major industrial deployment |
| 2045 | ~500-2,000 MtCO2/yr | Approaching gigatonne scale |
| 2050 | ~1-5 GtCO2/yr | Gigatonne scale achievable |
| 2060 | ~5-10 GtCO2/yr | Full scale (if all goes well) |

**10 Gt/year by 2060 would require:**
- ~20% annual capacity growth sustained for 30+ years
- Unprecedented industrial mobilization
- Massive clean energy buildout
- Continuous technology improvement
- Supportive policy frameworks (carbon pricing, mandates, subsidies)

**This is extremely ambitious but not physically impossible.** Solar PV achieved ~40% annual growth for 20 years. The question is whether political will and economic incentives are sufficient.

---

## 11. Sources & References

### Academic Papers

1. Voskian, S. & Hatton, T.A. "Faradaic electro-swing reactive adsorption for CO2 capture." *Energy & Environmental Science*, 12, 3530-3547 (2019). -- The foundational Verdox paper.
2. Shen, Y., et al. "Bipolar membrane electrodialysis for CO2 capture." *Joule*, 5(8), 2027-2043 (2021). -- Relevant to Mission Zero/RepAir approaches.
3. Diederichsen, K.M., et al. "Electrochemical methods for carbon dioxide separations." *Nature Reviews Methods Primers*, 2, 68 (2022). -- Comprehensive review of electrochemical DAC methods.
4. Sharifian, R., et al. "Electrochemical carbon dioxide capture to close the carbon cycle." *Energy & Environmental Science*, 14, 781-814 (2021). -- Overview of electrochemical CO2 capture approaches.
5. Keith, D.W., et al. "A process for capturing CO2 from the atmosphere." *Joule*, 2(8), 1573-1594 (2018). -- Carbon Engineering's liquid solvent process (comparison).
6. Sabatino, F., et al. "A comparative energy and costs assessment and optimization for direct air capture technologies." *Joule*, 5(8), 2047-2076 (2021). -- Cross-technology comparison.

### Industry & Government Reports

7. IEA. "Direct Air Capture: A key technology for net zero." International Energy Agency (2022).
8. National Academies of Sciences. "Negative Emissions Technologies and Reliable Sequestration." (2019).
9. DOE. "Report of the Direct Air Capture to Geological Sequestration Shot." U.S. Department of Energy (2022).
10. IPCC AR6 WG3. "Climate Change 2022: Mitigation of Climate Change." Chapter 12: Cross-sectoral perspectives.

### Company & Press Sources

11. Verdox company website and press releases (verdox.com)
12. Mission Zero Technologies company website (missionzero.tech)
13. RepAir Carbon Capture company website (repair.tech)
14. Breakthrough Energy Ventures portfolio announcements
15. Carbon180 DAC landscape reports
16. Frontier climate fund purchase announcements

### Data Notes

- Figures marked with ~ are estimates based on published ranges and engineering analysis.
- Figures marked [unverified] should be cross-checked against latest company disclosures.
- Cost and performance projections are inherently uncertain for pre-commercial technologies.
- Company funding totals may be incomplete due to undisclosed rounds.
- All TRL assessments are the author's estimates based on publicly available information.

---

*Document compiled February 2026. Web search tools were unavailable during compilation; all data is based on published sources through early 2025. Recommend verifying latest figures, especially funding rounds and pilot project status, against current company announcements.*
