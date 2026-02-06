# Solid Sorbent Direct Air Capture (DAC)

## Key Player: Climeworks (Switzerland/Iceland)

**Method Summary:** Ambient air is blown over solid sorbent filters that chemically bind CO2 at low concentrations (~420 ppm). Once saturated, the filters are heated to ~80-120°C, releasing concentrated CO2 for permanent geological storage or utilization. Climeworks pairs this process with waste geothermal heat in Iceland and partners with Carbfix for basalt mineralization storage.

---

## Table of Contents

1. [Technology Overview](#1-technology-overview)
2. [Physical Constraints](#2-physical-constraints)
3. [Resource Constraints](#3-resource-constraints)
4. [Throughput Metrics](#4-throughput-metrics)
5. [End Game: Storage](#5-end-game-storage)
6. [Economic Friction](#6-economic-friction)
7. [Feasibility & Scaling Data](#7-feasibility--scaling-data)
8. [10 Gt/year Scaling Analysis](#8-10-gtyear-scaling-analysis)
9. [Sources & References](#9-sources--references)

---

## 1. Technology Overview

### 1.1 How It Works

Climeworks uses a **Temperature-Vacuum Swing Adsorption (TVSA)** process:

1. **Adsorption phase:** Large fans draw ambient air through modular collector units containing solid sorbent filters. CO2 molecules chemically bind to amine-functionalized sorbent material on the filter surface. This occurs at ambient temperature (~15-25°C).
2. **Desorption phase:** Once the sorbent is saturated (after several hours), the collector chamber is sealed. Low-grade heat (~80-120°C) is applied, combined with a vacuum, causing the CO2 to release from the sorbent as a concentrated stream (~99%+ purity).
3. **Storage/Utilization:** The concentrated CO2 is either:
   - Mixed with water and injected into basalt rock for permanent mineralization (Carbfix process in Iceland), or
   - Sold for utilization (greenhouses, synthetic fuels, beverages, etc.)

### 1.2 Sorbent Chemistry

| Property | Detail |
|---|---|
| **Sorbent Type** | Amine-functionalized solid sorbent on cellulose/silica substrate |
| **Active Agent** | Amine groups (primary/secondary amines grafted onto porous support) |
| **Binding Mechanism** | Chemisorption — amines form carbamate bonds with CO2 under ambient conditions |
| **Regeneration** | Thermal swing at 80-120°C breaks the CO2-amine bond |
| **Selectivity** | High selectivity for CO2 over N2 and O2; some co-adsorption of water |
| **CO2 loading capacity** | ~1-2 mmol CO2/g sorbent (varies by formulation) |

### 1.3 Comparison: Solid Sorbent vs. Liquid Solvent DAC

| Parameter | Solid Sorbent (Climeworks) | Liquid Solvent (Carbon Engineering/Oxy) |
|---|---|---|
| **Regeneration temperature** | 80-120°C (low-grade heat) | 300-900°C (high-grade heat via calciner) |
| **Energy source compatibility** | Geothermal, waste heat, heat pumps, solar thermal | Natural gas (with CCS), electric calciner |
| **Water consumption** | Low (~1-2 t H2O/t CO2, net) | Higher (~4.7 t H2O/t CO2) |
| **Modularity** | Highly modular (shipping container scale) | Large-scale industrial plants |
| **CO2 purity output** | >99% | >97% |
| **Current cost range** | $600-1,000+/t CO2 | $250-600/t CO2 (claimed) |
| **Maturity (TRL)** | TRL 7-8 | TRL 6-7 |
| **Land footprint** | Smaller per unit, larger per ton at scale | Larger plant, potentially less land/ton |
| **Key companies** | Climeworks, Global Thermostat, Heirloom (lime-based variant) | Carbon Engineering (now 1PointFive/Oxy), Verdox |

---

## 2. Physical Constraints

### 2.1 Land/Surface Footprint

| Metric | Value | Source/Basis |
|---|---|---|
| **Orca plant footprint** | ~2,400 m² (~0.6 acres) for the collector array | Climeworks disclosures |
| **Orca capture capacity** | 4,000 t CO2/year | Climeworks |
| **Land per ton CO2/year (Orca)** | ~0.6 m²/(t CO2/yr) | Derived: 2,400 m² / 4,000 t/yr |
| **Mammoth plant footprint** | ~6,000-8,000 m² (~1.5-2 acres) estimated for collector array | Estimates based on 9x Orca scale |
| **Mammoth capture capacity** | 36,000 t CO2/year | Climeworks |
| **Land per ton CO2/year (Mammoth)** | ~0.17-0.22 m²/(t CO2/yr) | Derived (improved density) |
| **IEA/literature estimate** | 0.4-1.0 m²/(t CO2/yr) for the capture equipment | IEA DAC reports |
| **Total facility footprint (incl. energy, storage)** | 1-5 m²/(t CO2/yr) | Varies enormously by energy source |

**Key notes on land:**
- The collector array itself is compact. The dominant land-use factor is the **energy supply** — especially if solar PV or wind is used to provide electricity and heat.
- If powered by dedicated solar PV: ~5-10 m²/(t CO2/yr) additional land for electricity alone.
- If powered by geothermal (Iceland): minimal additional surface footprint since geothermal wells are compact.
- **For 10 Gt/year:** At 1 m²/(t CO2/yr), ~10,000 km² of collector arrays (roughly the area of Lebanon or Jamaica). With dedicated renewable energy, total land could reach 50,000-100,000 km² (roughly the size of Costa Rica).

### 2.2 Location Dependency

| Factor | Constraint Level | Notes |
|---|---|---|
| **Air temperature** | Low constraint | Works in cold and warm climates; cold/dry air slightly reduces performance due to lower absolute humidity aiding desorption |
| **Humidity** | Moderate | High humidity can compete for adsorption sites; very low humidity can reduce performance. Optimal range: 20-80% RH |
| **Altitude** | Low constraint | Works at any altitude (CO2 concentration ~420 ppm globally) |
| **CO2 concentration** | Not location-dependent | Atmospheric CO2 is well-mixed globally at ~420 ppm |
| **Wind/Air flow** | Low constraint | Fans provide forced airflow; ambient wind is not required |
| **Energy source** | **High constraint** | Needs low-carbon heat (80-120°C) and electricity. Best locations have geothermal, waste heat, or abundant renewables |
| **CO2 storage proximity** | **High constraint** | If storing underground, needs geological storage formation nearby (basalt, saline aquifer, depleted oil/gas reservoir) |
| **Water availability** | Low-moderate | Some water is co-captured; net water demand is modest |

**Bottom line on location:** The capture technology itself works essentially anywhere on Earth. The binding constraints are: (1) access to **low-carbon, low-cost thermal energy** at 80-120°C, and (2) proximity to **permanent CO2 storage** or transport infrastructure. Iceland is ideal because it has both (geothermal heat + basalt formations). Other promising locations include volcanic regions (East Africa, Pacific Rim), areas near saline aquifers with renewable energy, and industrial sites with waste heat.

### 2.3 Storage Site Requirements

| Requirement | Details |
|---|---|
| **Basalt formations** | Reactive rock that mineralizes CO2 into carbonate minerals in 1-2 years (Carbfix process) |
| **Saline aquifers** | Deep porous rock formations (>800m) where CO2 is stored as supercritical fluid under caprock |
| **Depleted hydrocarbon reservoirs** | Well-characterized geology; proven seal integrity from millions of years of hydrocarbon retention |
| **Depth requirement** | Generally >800m to maintain CO2 in supercritical/dense phase |
| **Injection well spacing** | Typically 0.5-2 km apart depending on formation permeability |
| **Seismicity risk** | Must avoid major fault zones; induced seismicity monitoring required |

---

## 3. Resource Constraints

### 3.1 Energy Intensity

This is the single most critical constraint for solid sorbent DAC. The process requires both **thermal energy** (for sorbent regeneration) and **electrical energy** (for fans, vacuum pumps, controls).

| Energy Component | Value | Notes |
|---|---|---|
| **Thermal energy demand** | 1,500-2,000 kWh_th/t CO2 | For heating sorbent to 80-120°C; this is the dominant energy cost |
| **Electrical energy demand** | 200-300 kWh_e/t CO2 | Fans (~40%), vacuum pumps (~40%), controls/auxiliaries (~20%) |
| **Total primary energy (if all electric)** | 2,000-2,500 kWh/t CO2 | If heat is supplied via electric heaters or heat pumps |
| **Total primary energy (with waste/geothermal heat)** | 200-300 kWh_e/t CO2 (+ "free" heat) | Climeworks Iceland model; heat has near-zero marginal cost |
| **Thermodynamic minimum** | ~125 kWh/t CO2 | Second-law minimum for separating CO2 at 420 ppm from air |
| **Current efficiency vs. minimum** | ~5-8% of theoretical maximum | Significant room for improvement |

**Detailed energy breakdown (Climeworks system):**

| Sub-process | Electrical (kWh_e/t CO2) | Thermal (kWh_th/t CO2) |
|---|---|---|
| Air contacting (fans) | 80-120 | — |
| Vacuum generation | 60-100 | — |
| Sorbent heating/regeneration | — | 1,500-2,000 |
| CO2 compression (to pipeline/storage pressure) | 50-100 | — |
| Auxiliaries (controls, cooling, etc.) | 20-50 | — |
| **Total** | **~250 (range: 200-370)** | **~1,750 (range: 1,500-2,000)** |

**Heat pump scenario:** If a heat pump (COP ~3-4) is used to supply the thermal energy, the electrical demand for heat becomes ~375-670 kWh_e/t CO2, bringing total electrical to ~575-1,000 kWh_e/t CO2. This is being explored for locations without geothermal/waste heat.

**Scaling implications for 10 Gt/year:**
- Thermal energy: 10 Gt x 1,750 kWh_th = 17,500 TWh_th/year (roughly 15% of current global primary energy)
- Electrical energy: 10 Gt x 250 kWh_e = 2,500 TWh_e/year (roughly 9% of current global electricity generation)
- If all-electric with heat pumps: 10 Gt x 750 kWh_e = 7,500 TWh_e/year (roughly 26% of current global electricity)

### 3.2 Water Consumption

| Metric | Value | Notes |
|---|---|---|
| **Gross water co-captured** | 0.8-2.0 t H2O/t CO2 | Water vapor adsorbs alongside CO2 on amine sorbents |
| **Net water consumption** | ~1-2 t H2O/t CO2 | Some recovered, some lost to evaporation/process |
| **Comparison: liquid solvent DAC** | ~4.7 t H2O/t CO2 | Carbon Engineering's aqueous KOH process |
| **Comparison: natural gas power plant** | ~0.5-1.0 t H2O/MWh | For context |
| **Carbfix injection water** | ~25 t H2O/t CO2 | CO2 is dissolved in water before injection into basalt |

**Important:** The Carbfix mineralization process used in Iceland requires substantial water (~25 tons of water per ton of CO2) to dissolve the CO2 before injection. In Iceland, freshwater is abundant, but this is a significant constraint for deployment in water-scarce regions using this storage method. Alternative storage (direct supercritical CO2 injection into saline aquifers) requires much less freshwater.

**For 10 Gt/year:**
- Capture process water: 10-20 Gt water/year (10-20 km³/year, ~0.2-0.5% of global freshwater withdrawals)
- If using Carbfix storage: an additional ~250 km³/year (~6% of current global freshwater withdrawals) — this is a serious constraint

### 3.3 Material Inputs

#### Collector Unit Construction Materials

| Material | Use | Approximate Quantity per Collector | Scarcity Concern |
|---|---|---|---|
| **Steel (structural)** | Frame, housing, ducting | 5-15 tonnes per collector unit | Low — abundant globally |
| **Aluminum** | Heat exchangers, lightweight components | 0.5-2 tonnes | Low-moderate |
| **Concrete/foundations** | Base pads, supports | 10-30 tonnes | Low |
| **Plastics/polymers** | Seals, insulation, ducting components | 0.2-1 tonne | Low |
| **Electric motors** | Fans, vacuum pumps | Contains copper, rare earth magnets | Moderate (copper, neodymium) |
| **Electronics/controls** | Sensors, PLCs, wiring | Standard industrial electronics | Low |

#### Sorbent Materials

| Material | Details | Scarcity Concern |
|---|---|---|
| **Substrate** | Porous silica, alumina, or cellulose-based support structures | Low — silica and alumina are abundant |
| **Amine functionalization** | Polyethylenimine (PEI), aminosilanes, or other amine compounds grafted onto substrate | Low-moderate — amines derived from petrochemicals or bio-based sources |
| **Sorbent mass per collector** | ~1-5 tonnes of sorbent material per collector unit (estimated) | — |
| **Sorbent replacement rate** | Every 2-3 years (~3,000-10,000 adsorption-desorption cycles) | Creates recurring material demand |
| **No precious metals** | Unlike some catalytic processes, no platinum group metals required | Positive for scaling |
| **No rare earth elements in sorbent** | Sorbent itself uses common elements (C, H, N, O, Si) | Positive for scaling |

**Key finding on materials:** Solid sorbent DAC does **not** require rare, scarce, or geopolitically concentrated materials in the sorbent itself. The primary material constraints are:
1. **Steel and concrete** for massive infrastructure build-out (similar to any industrial scale-up)
2. **Copper** for electric motors and wiring
3. **Amine chemicals** at very large scale (would need significant expansion of chemical production)
4. **Fan/motor manufacturing capacity** — each unit needs large industrial fans

**For 10 Gt/year (rough material estimates):**

| Material | Annual Demand for 10 Gt/yr DAC | Current Global Production | DAC as % of Current Production |
|---|---|---|---|
| Steel | ~500-1,500 Mt (construction phase) | ~1,900 Mt/yr | 25-80% (during build-out) |
| Concrete | ~1,000-3,000 Mt (construction phase) | ~4,400 Mt/yr | 23-68% (during build-out) |
| Copper | ~5-15 Mt/yr (motors, wiring) | ~25 Mt/yr | 20-60% |
| Amine sorbent (replacement) | ~50-200 Mt/yr | Currently <1 Mt/yr specialized | >100x scale-up needed |
| Aluminum | ~10-50 Mt (construction phase) | ~70 Mt/yr | 14-71% (during build-out) |

*Note: These are order-of-magnitude estimates with high uncertainty. Actual values depend heavily on final collector design, efficiency improvements, and sorbent longevity.*

---

## 4. Throughput Metrics

### 4.1 Capture Rate per Unit

| Unit/Plant | Annual Capture | CO2 per Day | Number of Collectors |
|---|---|---|---|
| **Single Climeworks collector container** | ~50 t CO2/year | ~135 kg/day | 1 |
| **Orca plant (Iceland)** | 4,000 t CO2/year | ~11 t/day | 8 collector containers (each with multiple modules) |
| **Mammoth plant (Iceland)** | 36,000 t CO2/year (design capacity) | ~100 t/day | 72 collector modules in 18 containers |
| **Hypothetical "Gigaton plant"** | 1 Mt CO2/year | ~2,740 t/day | ~800-1,000+ containers |
| **For 10 Gt/year** | 10,000 Mt CO2/year | ~27.4 Mt/day | ~10,000 "Megaton-scale" plants or equivalent |

### 4.2 Air Processing Volume

To capture 1 ton of CO2 from air at ~420 ppm:

| Parameter | Value |
|---|---|
| CO2 concentration in air | ~420 ppm by volume (~0.06% by mass) |
| Mass of air per ton CO2 | ~1,600-1,800 tonnes of air |
| Volume of air per ton CO2 | ~1.3-1.5 million m³ of air |
| Air velocity through sorbent | ~1-3 m/s (typical) |
| Capture efficiency per pass | ~50-80% of CO2 in contacted air |
| Effective air volume per ton CO2 | ~1.7-3.0 million m³ (accounting for capture efficiency) |

### 4.3 Duty Cycle and Uptime

| Parameter | Value | Notes |
|---|---|---|
| **Adsorption phase duration** | 2-6 hours | Depends on sorbent loading, air conditions |
| **Desorption phase duration** | 1-3 hours | Heating + vacuum + CO2 collection |
| **Full cycle time** | 3-9 hours | Typical: ~4-6 hours |
| **Cycles per day** | 3-6 cycles | Targeting 4-6 for throughput optimization |
| **Effective duty cycle** | ~85-95% | Planned maintenance reduces this |
| **Operational availability** | ~90-95% (target) | ~8,000-8,300 hours/year |
| **24/7 operation** | **Yes** | Operates continuously day and night, all seasons |
| **Weather dependency** | Minimal | Fans force air; not dependent on wind or sun |
| **Seasonal variation** | Minor | Slightly affected by temperature/humidity changes |

**Important:** Unlike solar or wind energy, solid sorbent DAC operates **continuously 24/7/365**. This is a significant advantage over some renewable energy-coupled processes. However, the **energy source** may have intermittency (if solar/wind powered), which would affect actual throughput unless energy storage is provided.

### 4.4 Sorbent Lifecycle and Durability

| Parameter | Value | Notes |
|---|---|---|
| **Sorbent operational lifetime** | 2-3 years (current), targeting 3-5 years | Degrades with thermal cycling |
| **Number of cycles before replacement** | ~3,000-10,000 cycles | Depends on sorbent formulation and conditions |
| **Degradation mechanisms** | Oxidative degradation of amines; thermal sintering; poisoning by SOx/NOx contaminants | Amine oxidation is primary failure mode |
| **Performance decay profile** | Gradual — ~10-30% capacity loss over lifetime | Not sudden failure; gradual decline in CO2 uptake |
| **Sorbent replacement cost** | Significant fraction of OPEX (estimated 15-30%) | Driving research into more durable sorbents |
| **Replacement process** | Modular — swap sorbent cartridges/trays within collectors | Designed for field serviceability |
| **Next-gen sorbent targets** | 5-10 year lifetime, >20,000 cycles | Active research area; MOFs, functionalized polymers |

**Degradation details:**
- **Oxidative degradation:** Amines react with O2 (especially at elevated temperatures during desorption), forming urea linkages and other inactive species. This is the primary degradation pathway.
- **SOx/NOx poisoning:** Trace pollutants in ambient air can irreversibly bind to amine sites. Pre-filtering air helps but adds cost.
- **Humidity effects:** Cycling between wet and dry conditions can cause physical degradation of the support structure.
- **Research directions:** Metal-organic frameworks (MOFs), moisture-swing sorbents, and electrochemically-mediated capture are being explored as alternatives with potentially longer lifetimes.

---

## 5. End Game: Storage

### 5.1 Storage Methods

#### 5.1.1 Basalt Mineralization (Carbfix Process — Climeworks' Primary Method)

| Parameter | Value |
|---|---|
| **Process** | CO2 dissolved in water, injected into basalt rock at 400-800m depth |
| **Mineralization reaction** | CO2 + water + Ca/Mg silicates → CaCO3/MgCO3 (solid carbonates) |
| **Mineralization timeline** | ~2 years for >95% conversion to solid minerals |
| **Permanence** | Effectively permanent (>10,000 years; solid rock) |
| **Reversal risk** | Near-zero once mineralized (would require re-dissolving solid rock) |
| **Monitoring requirement** | Minimal after mineralization confirmation |
| **Water requirement** | ~25 t H2O per t CO2 (for dissolution and injection) |
| **Location requirement** | Basalt formations (Iceland, Pacific Northwest, East Africa, India Deccan Traps, ocean floor) |

#### 5.1.2 Saline Aquifer Injection (Most Globally Abundant Option)

| Parameter | Value |
|---|---|
| **Process** | Supercritical CO2 injected into deep porous saline formations under impermeable caprock |
| **Trapping mechanisms** | Structural (caprock seal), residual (pore trapping), solubility (dissolved in brine), mineral (slow carbonate formation over centuries) |
| **Permanence** | Very high if well-selected sites (>1,000-10,000+ years) |
| **Reversal risk** | Low but non-zero: requires caprock integrity, proper well sealing |
| **Leak rate estimates** | <0.1%/year for well-selected sites; regulatory target often <0.01%/year |
| **Monitoring requirement** | Ongoing seismic, pressure, and surface monitoring required |

#### 5.1.3 Depleted Oil/Gas Reservoirs

| Parameter | Value |
|---|---|
| **Process** | CO2 injection into depleted hydrocarbon reservoirs |
| **Advantage** | Well-characterized geology; proven seal integrity |
| **Permanence** | Very high (reservoirs held hydrocarbons for millions of years) |
| **Risk** | Legacy wellbores may create leakage pathways if not properly sealed |
| **Enhanced Oil Recovery (EOR)** | Can be combined with CO2-EOR, but this produces more oil (climate contradiction) |

### 5.2 Global Storage Capacity

| Storage Type | Estimated Global Capacity | Notes |
|---|---|---|
| **Saline aquifers** | 1,000-10,000+ Gt CO2 | Largest capacity; widely distributed globally |
| **Depleted oil/gas fields** | 200-900 Gt CO2 | Well-characterized but geographically concentrated |
| **Deep basalt formations** | 100,000+ Gt CO2 (theoretical) | Enormous if including ocean floor basalt |
| **Continental basalt** | ~10,000-100,000 Gt CO2 | India Deccan Traps, Columbia River Basalt, etc. |
| **Ocean floor basalt** | Effectively unlimited | Logistically challenging but geologically ideal |
| **Total estimated geological storage** | >10,000 Gt CO2 (conservative) | Far exceeds cumulative anthropogenic CO2 emissions (~2,500 Gt to date) |

**Key finding:** Global geological storage capacity is **not a binding constraint** on DAC scaling. Even conservative estimates of saline aquifer capacity alone (>1,000 Gt) exceed plausible cumulative DAC deployment through 2100. The constraint is characterizing, permitting, and developing individual storage sites.

### 5.3 Permanence and Leakage Risk

| Storage Type | Expected Permanence | Annual Leak Rate | Confidence Level |
|---|---|---|---|
| **Basalt mineralization** | >10,000 years (effectively permanent) | ~0% (solid mineral) | Very high |
| **Well-selected saline aquifers** | >10,000 years | <0.01%/year | High |
| **Depleted oil/gas fields** | >1,000-10,000 years | <0.1%/year | High |
| **CO2-EOR sites** | Variable | Higher uncertainty | Moderate |

**Regulatory frameworks:** Most jurisdictions require demonstration of <0.1% annual leakage, long-term monitoring plans (30-50+ years post-injection), financial assurance for remediation, and transfer of liability to government after monitoring period (e.g., EU CCS Directive: 20 years post-closure).

---

## 6. Economic Friction

### 6.1 Capital Expenditure (CAPEX)

| Item | Estimated Cost | Notes |
|---|---|---|
| **Orca plant (4,000 t/yr)** | ~$10-15 million | First-of-kind; high unit cost |
| **Mammoth plant (36,000 t/yr)** | ~$40-80 million (estimated) | Second generation; some cost reduction |
| **Cost per annual ton capacity (current)** | $1,000-3,000/(t CO2/yr) | Varies by location, energy source |
| **Target cost per annual ton capacity** | $200-500/(t CO2/yr) | At commercial scale (>1 Mt/yr plants) |
| **Plant lifetime** | 20-30 years | With periodic sorbent replacement |
| **CAPEX as fraction of total cost** | ~40-60% of levelized cost | At current scale |

**CAPEX breakdown (approximate):**

| Component | % of CAPEX |
|---|---|
| Collector units (fans, sorbent beds, vacuum systems) | 40-50% |
| Heat integration / energy systems | 15-25% |
| CO2 compression and handling | 10-15% |
| Civil works (foundations, buildings, infrastructure) | 10-15% |
| Engineering, procurement, construction management | 10-15% |

### 6.2 Operating Expenditure (OPEX)

| Item | Estimated Cost (per t CO2) | Notes |
|---|---|---|
| **Energy (electricity)** | $30-80 | At $0.03-0.10/kWh for 250-400 kWh_e/t |
| **Energy (heat, if purchased)** | $50-150 | Zero if using waste geothermal heat |
| **Sorbent replacement** | $30-80 | Every 2-3 years; depends on sorbent cost and lifetime |
| **Maintenance & labor** | $20-50 | Including equipment repair, monitoring |
| **CO2 compression & transport** | $10-30 | To pipeline or storage pressure |
| **Storage costs** | $10-30 | Injection well operation, monitoring |
| **Other (insurance, admin, etc.)** | $10-30 | — |
| **Total OPEX** | $160-450/t CO2 | Highly dependent on energy cost and sorbent life |

### 6.3 Current Cost per Ton CO2

| Source/Estimate | Cost (USD/t CO2) | Year | Notes |
|---|---|---|---|
| **Climeworks (Orca)** | $600-1,000+ | 2021-2024 | First commercial plant; early learning curve |
| **Climeworks stated target** | $400-600 | 2025-2026 | Mammoth-generation plants |
| **Climeworks long-term target** | $200-300 | 2030+ | With further scaling and optimization |
| **IEA estimate (solid sorbent DAC)** | $400-1,000 | 2023 | Range for current technology |
| **Academic literature range** | $250-600 | Projected | At scale with optimized energy supply |
| **Rhodium Group / independent analyses** | $600-1,000+ | 2023-2024 | Current commercial operations |
| **DOE target ("Earthshot")** | $100 | 2032 target | Aspirational; requires breakthroughs |

### 6.4 Learning Rate and Cost Trajectory

| Metric | Value | Basis |
|---|---|---|
| **Observed learning rate** | Very early — insufficient data points | Only 2 commercial plants (Orca, Mammoth) |
| **Analogous technology learning rates** | 15-25% cost reduction per doubling of capacity | Solar PV: ~24%; wind: ~15%; batteries: ~18% |
| **Climeworks projected learning rate** | ~15-20% per doubling | Company and analyst estimates |
| **Current cumulative capacity** | ~44,000 t CO2/year (as of 2024/2025) | Orca + Mammoth (at full capacity) |
| **Doublings needed to reach $100/t** | ~7-10 doublings from current cost | Starting from ~$800/t, 15-20% learning rate |
| **Capacity at $100/t (if 15% learning)** | ~50-500 Mt CO2/year | Requires massive scale-up |
| **Timeline to $100/t** | 2035-2045 (optimistic) to 2050+ (conservative) | Depends on deployment rate and R&D breakthroughs |

**Cost reduction pathways:**

1. **Scale economies:** Larger plants, mass manufacturing of collectors
2. **Sorbent improvement:** Higher capacity, longer lifetime, cheaper synthesis
3. **Energy cost reduction:** Cheaper renewables, better heat integration, heat pumps
4. **Process optimization:** Faster cycles, better vacuum systems, reduced air pressure drop
5. **Modular manufacturing:** Factory-built standardized units vs. bespoke construction
6. **Learning-by-doing:** Operational optimization, reduced downtime

### 6.5 Revenue Streams

| Revenue Source | Current Price Range | Market Size | Notes |
|---|---|---|---|
| **Voluntary carbon market credits** | $600-1,500/t CO2 | Small but growing (<$5B/yr total market) | Premium "removal" credits from DAC command highest prices |
| **Compliance carbon markets (EU ETS)** | ~$50-80/t CO2 (2024) | Large (~$100B+/yr) | DAC not yet fully integrated in most compliance markets |
| **US 45Q tax credit (DAC)** | $180/t CO2 (as of IRA 2022) | Uncapped in theory | Largest government incentive for DAC globally |
| **CO2 utilization sales** | $100-300/t CO2 | Limited at scale | Greenhouses, synthetic fuels, beverages, building materials |
| **Advance market commitments** | $600-1,000+/t CO2 | Growing (Frontier Fund: $925M+) | Microsoft, Stripe, Shopify, Alphabet, Meta pre-purchases |
| **Government procurement** | Varies | DOE DAC Hubs: $3.5B authorized | US DOE funding for DAC hub development |

**Revenue stack example (US-based plant):**
- 45Q credit: $180/t CO2
- Voluntary credit sale: $400-800/t CO2
- **Total potential revenue: $580-980/t CO2** — approaching current costs

---

## 7. Feasibility & Scaling Data

### 7.1 Current Global Installed Capacity

| Year | Global Solid Sorbent DAC Capacity | Cumulative CO2 Removed |
|---|---|---|
| 2017 | ~50 t/yr (Climeworks pilot, Hinwil, Switzerland) | Negligible |
| 2021 | ~4,050 t/yr (Orca online Sept 2021) | ~4,000 t |
| 2022 | ~4,050 t/yr | ~8,000 t |
| 2024 | ~40,000 t/yr (Mammoth coming online in stages) | ~20,000+ t |
| 2025 | ~44,000+ t/yr (target: Mammoth at full capacity) | ~50,000+ t |

**Context:** Global anthropogenic CO2 emissions are ~37-40 Gt/year. Current DAC capacity of ~44,000 t/year removes roughly **0.0001%** of annual emissions. This is approximately one millionth of the 10 Gt/year target.

### 7.2 Major Projects

#### Climeworks Projects

| Project | Location | Capacity | Status | Energy Source | Storage Method |
|---|---|---|---|---|---|
| **Hinwil Pilot** | Hinwil, Switzerland | 900 t CO2/yr | Operational (2017) | Waste heat from incinerator | CO2 sold to greenhouse/Coca-Cola |
| **Orca** | Hellisheidi, Iceland | 4,000 t CO2/yr | Operational (Sept 2021) | Geothermal (Hellisheidi power plant) | Carbfix basalt mineralization |
| **Mammoth** | Hellisheidi, Iceland | 36,000 t CO2/yr | Commissioning 2024-2025 (phased) | Geothermal | Carbfix basalt mineralization |
| **Gen-3 / "Gigaton" roadmap** | Multiple sites (TBD) | 1+ Mt CO2/yr per site | Planning/development (post-2026) | Various | Various |

#### Other Solid Sorbent DAC Projects Globally

| Company | Project | Location | Capacity | Status | Technology |
|---|---|---|---|---|---|
| **Heirloom** | Tracy, CA | 1,000 t CO2/yr | Operational (2023) | Lime-based sorbent (CaO/CaCO3 looping) |
| **Heirloom** | Ruston, LA (Project Cypress) | Up to 17,000 t CO2/yr | Development | Lime-based sorbent |
| **Global Thermostat** | Huntsville, AL (DOE Hub) | Targeting 1 Mt CO2/yr | DOE-funded; early development | Amine-based solid sorbent |
| **Verdox** | Various | Pilot scale | R&D / pilot | Electrochemical swing (faradaic sorbent) |
| **Carbon Collect (Mech. Trees)** | Arizona | Pilot scale | R&D / pilot | Moisture-swing sorbent (passive, no fans) |
| **Svante** | Various | Pilot scale | R&D / pilot | Structured amine sorbent for point-source & DAC |

#### Liquid Solvent DAC (for comparison)

| Company | Project | Location | Capacity | Status |
|---|---|---|---|---|
| **1PointFive (Oxy/Carbon Engineering)** | STRATOS | Permian Basin, TX | 500,000 t CO2/yr (design) | Under construction; expected 2025 |
| **1PointFive** | Future phases | Permian Basin, TX | Up to 1 Mt CO2/yr | Planned |

### 7.3 Planned Capacity Expansions

| Entity | Target | Timeline | Notes |
|---|---|---|---|
| **Climeworks** | Multi-megaton capacity | By 2030 | Requires $bn+ investment; multiple sites |
| **Climeworks** | Gigaton-scale capacity | By 2050 | Company long-term vision |
| **US DOE DAC Hubs** | 4 hubs, each 1 Mt CO2/yr | 2028-2035 | $3.5B authorized under Bipartisan Infrastructure Law |
| **Global industry target (IEA NZE)** | ~60-85 Mt CO2/yr | By 2030 | IEA Net Zero Emissions scenario |
| **IPCC median pathway** | 5-10 Gt CO2/yr CDR total | By 2050-2100 | All CDR methods combined; DAC is one component |

### 7.4 Energy Source Requirements and Constraints

| Energy Source | Suitability | Pros | Cons |
|---|---|---|---|
| **Geothermal** | Excellent | Low-carbon heat + electricity; baseload; low cost | Geographically limited; capacity constraints |
| **Solar PV + heat pump** | Good | Abundant; declining cost | Intermittent; land-intensive; heat pump adds cost |
| **Wind + heat pump** | Good | Low cost in good sites | Intermittent; needs storage or grid |
| **Nuclear** | Excellent | Baseload; low-carbon heat and electricity | High CAPEX; long permitting; public acceptance |
| **Industrial waste heat** | Good (if available) | Very low cost; uses otherwise wasted energy | Limited availability; location-specific |
| **Concentrated Solar Thermal** | Good | Direct heat at right temperature range | Intermittent; geographically limited; storage needed |
| **Natural gas (with CCS)** | Feasible but problematic | Available; reliable | Defeats purpose if CCS isn't near-perfect; upstream methane emissions |
| **Grid electricity** | Depends on grid mix | Convenient | Only low-carbon if grid is mostly decarbonized |

**Critical constraint:** Every kWh of fossil-derived energy used by DAC reduces the net CO2 captured. For solid sorbent DAC to be net-negative, the energy supply must be **very low carbon** (<50-100 g CO2/kWh). Using typical grid electricity in many countries would result in **more CO2 emitted than captured**.

### 7.5 Policy and Subsidy Landscape

| Policy/Program | Jurisdiction | Value | Details |
|---|---|---|---|
| **45Q Tax Credit (IRA enhanced)** | United States | $180/t CO2 for DAC with storage | Inflation Reduction Act (2022); direct pay option; 12-year credit period |
| **DOE DAC Hubs Program** | United States | $3.5 billion total | Bipartisan Infrastructure Law; 4 regional DAC hub awards |
| **DOE Carbon Negative Shot** | United States | R&D funding | Target: $100/t CO2 by 2032 |
| **EU Innovation Fund** | European Union | Multi-billion EUR | Funds CCS/CCU projects including DAC |
| **EU ETS** | European Union | ~$50-80/t CO2 (2024) | DAC inclusion under discussion; would provide compliance credit value |
| **UK CCUS Cluster Sequencing** | United Kingdom | ~GBP 20 billion commitment | Track 1/Track 2 clusters; DAC eligible |
| **Carbon Contracts for Difference** | Germany, Netherlands, others | Varies | Government guarantees revenue floor for carbon capture |
| **Swiss CO2 Ordinance** | Switzerland | CHF 120/t CO2 tax | Climeworks' home market; carbon tax drives voluntary purchases |
| **Article 6 (Paris Agreement)** | International | Varies | Framework for international carbon credit trading; DAC credits eligible |
| **Voluntary market standards** | International | Puro.earth, Verra, Gold Standard | Certification standards for DAC carbon removal credits |

### 7.6 Key Technical Bottlenecks to Scaling

| Bottleneck | Severity | Description | Potential Solutions |
|---|---|---|---|
| **Cost** | Critical | $600-1,000+/t is 6-10x too expensive for climate-relevant scale | Manufacturing scale-up; sorbent R&D; cheaper energy |
| **Energy availability** | Critical | Requires enormous quantities of low-carbon energy | Dedicated renewable build-out; nuclear; geothermal |
| **Sorbent degradation** | High | 2-3 year lifetime creates recurring cost and material demand | New sorbent chemistries (MOFs, etc.); oxidation-resistant amines |
| **Manufacturing scale** | High | Need to mass-produce millions of collector units | Automotive-style factory production; standardization |
| **Storage infrastructure** | High | Need thousands of injection wells and pipelines | Leverage oil/gas industry expertise; CO2 pipeline networks |
| **Supply chain** | Moderate | Steel, copper, amine chemicals at massive scale | Long-term procurement; recycling; material efficiency |
| **Permitting and regulation** | Moderate | Storage site characterization and permitting takes years | Streamlined regulatory frameworks; pre-characterized sites |
| **Financing** | High | High upfront CAPEX with uncertain revenue | Government de-risking; advance market commitments; green bonds |
| **Workforce** | Moderate | Need trained engineers, technicians, geologists | Training programs; technology transfer from oil/gas sector |
| **Public acceptance** | Low-Moderate | Generally high support for DAC; some local opposition to storage | Community engagement; transparent monitoring; benefit sharing |

### 7.7 Environmental Co-benefits and Risks

**Co-benefits:**
- **Net-negative emissions:** Can achieve actual atmospheric CO2 removal (unlike emissions reduction alone)
- **Air co-purification:** Some sorbent systems co-capture other pollutants (though this isn't a primary design goal)
- **Location flexibility:** Can be sited on degraded/non-agricultural land
- **Water production:** Co-captures atmospheric water; potentially net water-positive in some configurations
- **Technology spillovers:** R&D advances sorbent science for other applications (e.g., air purification, gas separation)

**Risks:**
- **Moral hazard / mitigation deterrence:** Risk that DAC promises reduce urgency of emissions cuts (the "techno-fix" concern)
- **Energy opportunity cost:** If DAC consumes renewable energy that could otherwise displace fossil fuels, net climate benefit may be negative in the short term
- **Land use conflicts:** At scale, could compete with agriculture or ecosystems (especially if powered by dedicated solar/wind)
- **Local environmental impacts:** Noise from fans; visual impact; induced seismicity from CO2 injection (low but non-zero)
- **Lifecycle emissions:** Manufacturing, transport, and construction of DAC infrastructure has an embodied carbon footprint (estimated 5-15% of captured CO2)
- **Sorbent waste:** Degraded sorbent material requires disposal or recycling; amine degradation products may be toxic

### 7.8 Timeline Projections to Meaningful Scale

| Scale | CO2 Removed/yr | Approximate Timeline | Assumptions |
|---|---|---|---|
| **Demonstration** | ~10,000-50,000 t/yr | 2021-2025 (current) | Orca + Mammoth |
| **Early commercial** | 1-10 Mt/yr | 2027-2032 | DOE Hubs online; Climeworks Gen-3; 1PointFive STRATOS |
| **Significant** | 100 Mt-1 Gt/yr | 2035-2045 | Requires ~15-20% annual growth rate; costs <$200/t |
| **Climate-relevant** | 1-5 Gt/yr | 2045-2060 | Requires sustained exponential build-out; massive energy supply |
| **Target scale** | 10 Gt/yr | 2060-2080+ (if ever) | Extremely ambitious; may require complementary CDR methods |

**Growth rate context:**
- Solar PV achieved ~40-50% annual growth rate for decades during its scale-up
- Wind power achieved ~20-30% annual growth
- To go from 50,000 t/yr (2025) to 10 Gt/yr (200,000x increase) at 30% annual growth would take ~42 years (reaching target ~2067)
- At 50% annual growth: ~29 years (~2054)
- At 20% annual growth: ~63 years (~2088)

---

## 8. 10 Gt/year Scaling Analysis

### 8.1 Summary Table: What Would 10 Gt/year of Solid Sorbent DAC Require?

| Resource | Requirement for 10 Gt/yr | Global Context | Feasibility Rating |
|---|---|---|---|
| **Land (collectors only)** | ~5,000-10,000 km² | ~0.003-0.007% of Earth's land | Feasible |
| **Land (with dedicated renewables)** | ~50,000-150,000 km² | ~0.03-0.1% of Earth's land (~size of Greece) | Challenging but feasible |
| **Low-carbon electricity** | 2,500-7,500 TWh/yr | 9-26% of current global electricity | Very challenging |
| **Low-grade heat** | 17,500 TWh_th/yr | ~15% of global primary energy | Very challenging |
| **Water (capture process)** | 10-20 km³/yr | ~0.3-0.5% of freshwater withdrawals | Feasible |
| **Water (if Carbfix storage)** | +250 km³/yr | ~6% of freshwater withdrawals | Very challenging |
| **Steel (construction phase)** | ~500-1,500 Mt cumulative | ~25-80% of one year's production | Challenging (spread over decades) |
| **Sorbent material (annual)** | ~50-200 Mt/yr | >100x current production | Very challenging |
| **Collector units** | ~200-500 million units | Comparable to global auto production | Challenging |
| **Storage capacity used per year** | 10 Gt CO2/yr | <0.1% of global storage capacity/yr | Feasible (capacity exists) |
| **Number of large plants (1Mt each)** | ~10,000 | Comparable to global power plant count | Feasible (over decades) |
| **Annual cost (at $200/t)** | $2 trillion/year | ~2% of global GDP (~$100T) | Very challenging |
| **Annual cost (at $100/t)** | $1 trillion/year | ~1% of global GDP | Challenging but precedented |

### 8.2 Critical Feasibility Assessment

| Dimension | Assessment | Key Constraint |
|---|---|---|
| **Physics** | No physical barrier | Thermodynamics allows it; ~420 ppm is dilute but workable |
| **Land** | Feasible | Not a binding constraint even at 10 Gt/yr |
| **Energy** | **Binding constraint** | Requires massive low-carbon energy build-out (comparable to today's entire renewable fleet) |
| **Materials** | Challenging but solvable | No rare materials; but enormous quantities of common materials needed |
| **Storage** | Feasible | Geological capacity vastly exceeds needs |
| **Economics** | **Binding constraint** | $1-2T/yr is enormous; requires dramatic cost reduction + policy support |
| **Manufacturing** | Very challenging | Need automotive-scale mass production of novel equipment |
| **Timeline** | Very challenging | Even aggressive growth rates suggest 2050-2070+ for 10 Gt/yr |

### 8.3 Key Comparisons

| CDR Method | Estimated Cost (2025) | Land Use | Permanence | Max Potential (Gt/yr) |
|---|---|---|---|---|
| **Solid Sorbent DAC** | $600-1,000/t | Low-moderate | Very high (geological) | 10+ Gt (theoretical) |
| **Liquid Solvent DAC** | $250-600/t | Moderate | Very high (geological) | 10+ Gt (theoretical) |
| **BECCS** | $100-300/t | Very high | High (geological) | 5-10 Gt |
| **Enhanced Weathering** | $50-200/t | Moderate-high | High | 2-5 Gt |
| **Afforestation/Reforestation** | $5-50/t | Very high | Low (fire, disease, harvest risk) | 3-5 Gt |
| **Ocean Alkalinity Enhancement** | $50-200/t (uncertain) | Very low | High | 5-10+ Gt (uncertain) |
| **Biochar** | $30-120/t | Moderate | Moderate-high | 1-3 Gt |
| **Soil Carbon Sequestration** | $10-50/t | Very high (agricultural land) | Low (reversible) | 2-5 Gt |

---

## 9. Sources & References

The data in this document is synthesized from the following categories of sources:

### Primary Sources
- **Climeworks AG** — Official company publications, press releases, and investor disclosures (climeworks.com)
- **Carbfix** — Technical reports on basalt mineralization process (carbfix.com)

### Institutional Reports
- **IEA (International Energy Agency)** — "Direct Air Capture: A Key Technology for Net Zero" (2022); Energy Technology Perspectives; World Energy Outlook DAC sections
- **IPCC AR6 Working Group III** — Chapter 12: Cross-sectoral perspectives; CDR assessment
- **US National Academies of Sciences** — "Negative Emissions Technologies and Reliable Sequestration" (2019)
- **US DOE** — "Carbon Negative Shot" program documentation; DAC Hubs program details; Regional DAC Hub selections
- **Global CCS Institute** — Global Status of CCS reports; CO2 storage atlas

### Academic Literature
- Fasihi, M., Efimova, O., & Breyer, C. (2019). "Techno-economic assessment of CO2 direct air capture plants." *Journal of Cleaner Production*, 224, 957-980.
- McQueen, N., et al. (2021). "A review of direct air capture (DAC): scaling up commercial technologies and innovating for the future." *Progress in Energy*, 3(3), 032001.
- Ozkan, M., et al. (2022). "Current status and pillars of direct air capture technologies." *iScience*, 25(4), 103990.
- Keith, D.W., et al. (2018). "A Process for Capturing CO2 from the Atmosphere." *Joule*, 2(8), 1573-1594.
- Sanz-Perez, E.S., et al. (2016). "Direct Capture of CO2 from Ambient Air." *Chemical Reviews*, 116(19), 11840-11876.
- Deutz, S. & Bardow, A. (2021). "Life-cycle assessment of an industrial direct air capture process based on temperature-vacuum swing adsorption." *Nature Energy*, 6, 203-213.

### Industry & Analysis
- **Rhodium Group** — DAC cost and scaling analyses
- **Frontier Fund** (Stripe, Alphabet, Shopify, Meta, McKinsey) — Advance market commitment reports and DAC purchase disclosures
- **BloombergNEF** — Carbon capture and removal market analyses
- **McKinsey & Company** — Decarbonization and CDR technology assessments
- **S&P Global / IHS Markit** — CCS and DAC market intelligence

### Policy Documents
- **US Inflation Reduction Act (2022)** — Section 45Q enhanced tax credit provisions ($180/t for DAC with storage)
- **US Bipartisan Infrastructure Law (2021)** — DAC Hubs program authorization ($3.5B)
- **EU Innovation Fund** — Funding criteria and DAC project awards
- **EU CCS Directive (2009/31/EC)** — CO2 storage regulatory framework

---

*Document compiled: February 2026. Data reflects publicly available information through early 2025. Costs and capacity figures should be verified against latest Climeworks and IEA disclosures, as this is a rapidly evolving field. Note: web access was unavailable during compilation; all figures are based on published literature and reports available through the knowledge cutoff. Some figures (particularly Mammoth operational data and 2025 cost actuals) may have been updated since compilation.*

*Key caveat: Many figures in this document are estimates or ranges from multiple sources. Where sources disagree, ranges are provided. The 10 Gt/year scaling analysis involves significant extrapolation and should be treated as indicative rather than precise.*
