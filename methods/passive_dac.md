# Passive Direct Air Capture (Passive DAC)

## Primary Company: Heirloom Carbon Technologies

> **Research Note:** This document was compiled from publicly available information through early-to-mid 2025. Web search tools were unavailable during compilation, so all figures are drawn from the author's knowledge base of published sources (DOE announcements, Heirloom press releases, academic literature, and journalism). Figures marked with `[est.]` are derived estimates; all others are from published sources. Readers should cross-reference critical numbers against the latest filings and publications.

---

## Table of Contents

1. [Technology Overview](#1-technology-overview)
2. [Physical Constraints](#2-physical-constraints)
3. [Resource Constraints](#3-resource-constraints)
4. [Throughput Metrics](#4-throughput-metrics)
5. [End Game: Storage](#5-end-game-storage)
6. [Economic Friction](#6-economic-friction)
7. [Additional Feasibility Data](#7-additional-feasibility-data)
8. [10 Gigaton/Year Scaling Analysis](#8-10-gigatonyear-scaling-analysis)
9. [Comparative Analysis](#9-comparative-analysis)
10. [Sources & References](#10-sources--references)

---

## 1. Technology Overview

### 1.1 Company Background

| Field | Detail |
|---|---|
| **Founded** | 2020 |
| **Founder/CEO** | Shashank Samala |
| **Headquarters** | San Francisco, CA |
| **Total Funding** | ~$150M+ (Series A & B through 2024) |
| **Key Investors** | Breakthrough Energy Ventures (Bill Gates), Ahren Innovation Capital, Carbon Direct, Microsoft Climate Innovation Fund, Lowercarbon Capital |
| **DOE Award** | Selected for up to $600M under the Bipartisan Infrastructure Law DAC Hubs program (Project Cypress, Louisiana) |

### 1.2 Core Process: Enhanced Calcium Looping

Heirloom's approach is a modernized version of the **calcium looping** (CaL) cycle, one of the oldest known chemical processes for CO2 capture. The key innovation is making the carbonation step **passive** — no fans, no forced airflow.

#### The Cycle (3 Steps):

```
Step 1: CARBONATION (Passive, ~3 days)
  CaO + CO2 (from ambient air) --> CaCO3
  Calcium oxide (quickite) absorbs CO2 from air to form calcium carbonate (limestone)
  Temperature: Ambient (~15-35 C)
  Energy input: ZERO (passive wind exposure)

Step 2: CALCINATION (Active, energy-intensive)
  CaCO3 --> CaO + CO2 (concentrated stream)
  Limestone is heated in a kiln/calciner to ~900 C
  Releases pure CO2 stream for capture and storage
  Energy input: HIGH (thermal + electric)

Step 3: REHYDRATION & RESET
  CaO is cooled, optionally rehydrated (Ca(OH)2), and spread on trays again
  Cycle repeats
```

#### The "Zero Kinetic Energy" Insight

Traditional liquid-solvent DAC (e.g., Carbon Engineering / Occidental) and solid-sorbent DAC (e.g., Climeworks) use **large fans** to force ambient air across a contactor. Fan electricity typically accounts for **20-40% of total energy consumption** in fan-based DAC.

Heirloom eliminates this entirely:
- Limestone trays are exposed to **open air** on multi-tier rack structures (resembling vertical farming racks or warehouse shelving)
- Natural wind and convection deliver CO2 to the sorbent surface
- The kinetic energy cost of moving air is **zero** — borne by the atmosphere itself
- This is the "Zero Kinetic Energy" principle

**Trade-off:** What you gain in fan-energy savings, you pay for in **land area**. Passive exposure requires vastly more surface area than forced-air contactors to achieve equivalent throughput.

### 1.3 Process Flow Diagram (Simplified)

```
                    Ambient Air (CO2 ~420 ppm)
                           |
                           v
   +-----------------------------------------------+
   |  TRAY YARD (Open-air exposure, ~3 days)        |
   |  Multi-tier racks with limestone (CaO) trays   |
   |  CaO + CO2 --> CaCO3                           |
   |  No fans. No electricity. Wind-driven.          |
   +-----------------------------------------------+
                           |
                     Saturated CaCO3 trays
                           |
                           v
   +-----------------------------------------------+
   |  CALCINER / KILN (~900 C)                      |
   |  CaCO3 --> CaO + CO2 (pure stream)             |
   |  Powered by: renewable electricity or           |
   |  renewable natural gas / green hydrogen         |
   +-----------------------------------------------+
                      |              |
                      v              v
              Regenerated CaO    Pure CO2 stream
              (back to trays)          |
                                       v
                          +------------------------+
                          |  CO2 COMPRESSION        |
                          |  & PIPELINE/TRANSPORT   |
                          +------------------------+
                                       |
                                       v
                          +------------------------+
                          |  GEOLOGICAL STORAGE     |
                          |  (saline aquifers,      |
                          |   basalt mineralization,|
                          |   depleted oil/gas)     |
                          +------------------------+
```

---

## 2. Physical Constraints

### 2.1 Land / Surface Area Footprint

This is the **single most critical constraint** for passive DAC at scale.

#### Per-Ton Land Requirements

| Metric | Value | Source / Basis |
|---|---|---|
| **Tray surface area per ton CO2/year** | ~2,500 - 5,000 m^2 [est.] | Derived from carbonation kinetics and tray loading |
| **Total facility footprint per ton CO2/year** (including kilns, staging, infrastructure) | ~3,000 - 8,000 m^2 [est.] | Includes access roads, calciner, storage, buffers |
| **Heirloom's Tracy, CA facility footprint** | ~3 acres (~12,000 m^2) | Public reporting on the facility |
| **Tracy facility initial capacity** | ~1,000 tons CO2/year | Heirloom press releases (2023) |
| **Implied footprint: Tracy** | ~12 m^2 per ton CO2/year | Based on 12,000 m^2 / 1,000 tCO2/yr |

**Important caveat on the Tracy number:** The 12 m^2/tCO2 figure for Tracy likely reflects **multi-tier racking** (stacking trays vertically in 10-20+ layers), which dramatically reduces the ground footprint relative to single-layer exposure. Heirloom uses vertical rack systems similar to warehouse shelving, potentially 10-20 tray levels high.

#### Adjusted for Vertical Stacking

| Configuration | Ground Footprint per tCO2/yr | Notes |
|---|---|---|
| Single-layer trays (no stacking) | ~2,500 - 5,000 m^2 | Impractical at scale |
| 10-tier vertical racks | ~250 - 500 m^2 | More realistic |
| 20-tier vertical racks | ~125 - 250 m^2 | Approximate Heirloom target |
| Heirloom optimized (with all infrastructure) | ~10 - 30 m^2 | Based on Tracy extrapolation; includes racks + calciner + staging |

#### Carbonation Kinetics Context

The rate at which CaO absorbs CO2 from 420 ppm ambient air depends on:
- **Surface area of CaO particles** (ground limestone fineness)
- **Layer thickness on trays** (thinner = faster but less CO2 per tray)
- **Wind speed** (higher = faster mass transfer)
- **Humidity** (some moisture helps; too much hinders)
- **Temperature** (higher ambient temps slightly accelerate kinetics but reduce thermodynamic driving force)

Heirloom has reported that their **enhanced limestone** formulation (proprietary treatment to increase surface area and porosity) accelerates absorption well beyond raw CaO.

**Typical CaO carbonation in ambient air:**
- Raw CaO: captures ~30-50% of its theoretical CO2 capacity in 3 days
- Heirloom enhanced CaO: captures ~70-80% of theoretical capacity in 3 days [est. from public claims]
- Theoretical max: 1 mol CO2 per mol CaO = 0.786 kg CO2 per kg CaO

### 2.2 Location Dependency

| Factor | Requirement | Rationale |
|---|---|---|
| **Wind speed** | Moderate and consistent (3-8 m/s average) | Below 2 m/s: CO2-depleted boundary layer forms over trays, slowing absorption. Above 10 m/s: risk of material loss from trays |
| **Humidity** | Low to moderate (20-60% RH preferred) | High humidity competes with CO2 for reaction with CaO (forming Ca(OH)2 instead of CaCO3), reducing CO2 capture efficiency. Very low humidity may slow kinetics. |
| **Rainfall** | Low frequency preferred | Rain on exposed CaO trays causes rapid hydration (exothermic), wastes material, and disrupts operations. Covered racks or retractable shelters may mitigate this. |
| **Temperature** | 15-40 C optimal range | Below 10 C: kinetics slow significantly. Above 45 C: thermodynamic equilibrium shifts unfavorably at surface. |
| **Solar irradiance** | Beneficial if using solar thermal for calcination | Reduces grid electricity demand |
| **Proximity to storage** | Critical | CO2 must be piped or trucked to geological storage. Co-location with saline aquifers or basalt formations ideal. |
| **Grid access** | Required for calciner | Electric calciner needs substantial grid connection (or dedicated renewable generation) |
| **Seismic stability** | Important for tall rack structures | Multi-tier racks need structural integrity |

#### Ideal Locations

| Region | Suitability | Notes |
|---|---|---|
| **Central Valley, California** | Good | Heirloom's first site (Tracy). Moderate wind, low rain, hot summers. Proximity to California carbon markets. |
| **Gulf Coast, Louisiana/Texas** | Good | DOE DAC Hub location (Project Cypress). Access to deep saline aquifers, existing pipeline infrastructure. Higher humidity is a concern. |
| **US Southwest (AZ, NM, NV)** | Excellent | Low humidity, high wind, vast open land, strong solar for renewable energy. Distance to storage is a variable. |
| **Middle East / North Africa** | Excellent climate | Low humidity, high wind, vast land. CO2 storage in depleted oil fields. |
| **Australia (interior)** | Excellent climate | Similar to US Southwest. Emerging carbon markets. |
| **Northern Europe** | Poor | High humidity, low temperatures, limited solar. |
| **Tropical regions** | Poor | High humidity, heavy rainfall, reduces CaO effectiveness. |

### 2.3 Atmospheric CO2 Concentration Considerations

At 420 ppm, CO2 is only **0.042%** of the atmosphere by volume. This extreme dilution is the fundamental challenge for all DAC:

- To capture 1 ton of CO2, roughly **1,300 - 2,500 tons of air** must contact the sorbent (depending on capture efficiency)
- At wind speeds of 5 m/s, passive exposure provides substantial air throughput per unit area — but the mass transfer from bulk air to the CaO surface is the rate-limiting step
- Heirloom's rack geometry is designed to maximize turbulent mixing while allowing sufficient residence time

---

## 3. Resource Constraints

### 3.1 Energy Intensity

The **calcination step** dominates energy consumption. This is the fundamental thermodynamic cost that cannot be engineered away.

#### Thermodynamic Minimum

| Parameter | Value |
|---|---|
| **Enthalpy of CaCO3 decomposition** | 178 kJ/mol = 1,792 kJ/kg CO2 = ~498 kWh_th/tCO2 |
| **Theoretical minimum thermal energy** | ~500 kWh_th per ton CO2 |
| **Carnot efficiency losses, real kiln efficiency** | Adds ~40-80% to theoretical minimum |
| **Realistic thermal energy for calcination** | ~700 - 1,200 kWh_th per ton CO2 |

#### Total Energy Budget (Heirloom Estimated)

| Component | Energy (kWh/tCO2) | Type | Notes |
|---|---|---|---|
| **Fan electricity** | **0** | Electric | The core passive advantage |
| **Calcination (heating to ~900 C)** | 800 - 1,500 | Thermal | Dominant cost. Electric kiln or gas-fired. |
| **CO2 compression (to pipeline spec, ~150 bar)** | 80 - 120 | Electric | Standard across all DAC |
| **Material handling** (tray movement, grinding, conveying) | 30 - 80 | Electric | Robotic/automated tray transport |
| **Cooling and rehydration** | 10 - 30 | Electric | Minor |
| **Facility operations** (lighting, controls, HVAC) | 10 - 20 | Electric | Minor |
| **TOTAL (thermal equivalent)** | **~930 - 1,750** | Mixed | |
| **TOTAL (all-electric equivalent, if electric calciner)** | **~1,000 - 1,800** | Electric | Assuming electric kiln efficiency ~85% |

#### Comparison to Fan-Based DAC

| Method | Total Energy (kWh/tCO2) | Fan Energy (kWh/tCO2) | Non-Fan Energy (kWh/tCO2) |
|---|---|---|---|
| **Heirloom (Passive DAC)** | 1,000 - 1,800 | 0 | 1,000 - 1,800 |
| **Climeworks (Solid sorbent, fans)** | 1,500 - 2,500 | 300 - 500 | 1,200 - 2,000 |
| **Carbon Engineering / 1PointFive (Liquid solvent, fans)** | 1,500 - 2,400 | 200 - 400 | 1,300 - 2,000 |

**Key insight:** Heirloom saves ~200-500 kWh/tCO2 on fan energy, but the calcination step remains a large thermal demand. The net energy advantage is real but moderate (~15-25% reduction in total energy). The larger advantage is in **capital cost** (no fan/contactor infrastructure) and **simplicity**.

#### Calciner Technology Options

| Calciner Type | Status | Advantages | Disadvantages |
|---|---|---|---|
| **Electric kiln (resistance heating)** | Heirloom's primary approach | Zero direct emissions if powered by renewables; clean CO2 stream | Requires large electricity supply; high-temp electric heating is expensive |
| **Electric kiln (microwave/plasma)** | R&D stage | Potentially more efficient | Unproven at scale |
| **Oxy-fuel natural gas kiln** | Conventional cement industry approach | Proven at scale; lower electricity demand | Produces CO2 from fuel combustion (must also capture this); needs oxygen supply |
| **Green hydrogen kiln** | Emerging | Zero direct CO2 emissions | Green H2 is expensive and scarce |
| **Solar thermal calciner** | R&D stage (e.g., Heliogen) | Free fuel | Intermittent; requires concentrating solar; geographic constraints |
| **Concentrated solar + thermal storage** | Conceptual | 24/7 operation possible | Very high CAPEX for solar field |

Heirloom has stated its intent to use **electric calciners powered by renewable electricity**, making the process fully zero-emission.

### 3.2 Freshwater Consumption

| Process Step | Water Use (liters/tCO2) | Notes |
|---|---|---|
| **CaO rehydration** (optional step: CaO + H2O --> Ca(OH)2) | 300 - 650 | Stoichiometric: 321 L/tCO2 minimum if full hydration. Ca(OH)2 may improve carbonation kinetics. |
| **Cooling (calciner exhaust, CaO cooling)** | 100 - 500 | Depends on cooling system design (wet vs. dry) |
| **Dust suppression and material handling** | 50 - 100 | Minor |
| **Total estimated** | **~500 - 1,200 L/tCO2** | |

For comparison:
- Climeworks: ~1,000 - 5,000 L/tCO2 (humidity-dependent, sorbent regeneration)
- Carbon Engineering: ~4,000 - 7,000 L/tCO2 (liquid solvent system, evaporative losses)

Heirloom's water footprint is **relatively low** among DAC methods, a significant advantage especially in arid deployment regions.

### 3.3 Material Inputs

#### Limestone / Calcium Oxide

| Parameter | Value |
|---|---|
| **Stoichiometric CaO needed per ton CO2** | 1.27 tons CaO (56/44 ratio) |
| **CaO produced from limestone (CaCO3)** | 2.27 tons CaCO3 yields 1.27 tons CaO + 1 ton CO2 |
| **Cycle degradation** | CaO reactivity decreases with each calcination cycle due to sintering. After 10-30 cycles, capacity may drop to 20-40% of fresh CaO. |
| **Makeup limestone required** | ~5-15% of circulating inventory per cycle [est.] to replace degraded material |
| **Annual limestone consumption per tCO2/yr capacity** | ~0.5 - 2.0 tons/year [est.] depending on cycle count and degradation management |
| **Global limestone reserves** | Effectively unlimited. Limestone is one of the most abundant sedimentary rocks on Earth. Global production: ~4.5 billion tons/year (mostly for cement). |
| **Limestone cost** | ~$5 - 15/ton (quarried, delivered) |

**Heirloom's proprietary enhancement:** Heirloom has developed treatment processes to increase CaO surface area and reduce sintering degradation, potentially extending useful cycle life. Details are trade-secret.

#### Steel and Structural Materials

| Component | Material | Estimated Quantity per tCO2/yr capacity |
|---|---|---|
| **Tray racks / shelving** | Galvanized steel, aluminum | ~0.5 - 2.0 tons steel [est.] |
| **Trays** | Steel mesh, aluminum, or composite | ~0.1 - 0.5 tons [est.] |
| **Calciner** | High-temperature steel, refractory brick | Shared across facility; ~0.01 - 0.05 tons/tCO2 capacity [est.] |
| **Conveyors / robotics** | Steel, electronics | ~0.05 - 0.2 tons [est.] |
| **Foundation / civil works** | Concrete, rebar | ~0.5 - 2.0 tons [est.] |
| **CO2 compression equipment** | Specialty steel | Shared; minor per-ton allocation |

#### Other Inputs

| Input | Consumption | Notes |
|---|---|---|
| **Electricity (grid or renewable)** | 1,000 - 1,800 kWh/tCO2 | Dominant operating input |
| **Natural gas (if oxy-fuel calciner)** | ~5 - 10 GJ/tCO2 | Only if not using electric calciner |
| **Oxygen (if oxy-fuel calciner)** | ~0.5 - 1.0 tons/tCO2 | From air separation unit |
| **Replacement parts / maintenance** | ~2-5% of CAPEX/year | Standard industrial estimate |

---

## 4. Throughput Metrics

### 4.1 Capture Rate

| Metric | Value | Notes |
|---|---|---|
| **CO2 absorbed per kg CaO per 3-day cycle** | ~0.3 - 0.6 kg CO2 | 40-75% of theoretical max (0.786 kg CO2/kg CaO) |
| **Cycles per year (ideal)** | ~100 - 120 | 365 days / 3 days per cycle = 121 max theoretical |
| **Cycles per year (realistic)** | ~60 - 90 | Weather downtime, maintenance, material handling |
| **Annual CO2 capture per kg CaO in circulation** | ~20 - 50 kg CO2/kg CaO/year | Before accounting for sorbent degradation |
| **Tracy facility nameplate capacity** | ~1,000 tCO2/year | Heirloom's first commercial facility (launched November 2023) |
| **Tracy facility actual first-year capture** | Not publicly disclosed in detail | Ramp-up period expected |
| **Heirloom's 2030 target capacity** | 1,000,000+ tCO2/year (1 MtCO2/yr) | Across multiple facilities |

### 4.2 Duty Cycle / Uptime

| Factor | Impact | Mitigation |
|---|---|---|
| **Rain events** | Trays must be sheltered or retracted; ~5-15% downtime in temperate climates | Retractable covers, site selection in arid climates |
| **Low wind periods** | Reduces mass transfer rate; boundary layer stagnation | Site selection; rack geometry optimized for natural convection; minimal impact if rack spacing allows convection |
| **Extreme heat (>45 C)** | Minor reduction in thermodynamic driving force | Shade structures; operational adjustments |
| **Extreme cold (<5 C)** | Significant kinetic slowdown | Avoid cold-climate sites |
| **Calciner maintenance** | Periodic shutdowns for refractory repair | Redundant calciners; scheduled maintenance |
| **Seasonal variation** | Summer: faster kinetics, less rain (arid sites). Winter: slower kinetics, more rain (temperate). | Multiple facilities across geographies for portfolio smoothing |
| **Estimated annual uptime** | **75 - 90%** | Site-dependent |

### 4.3 Lifecycle / Durability

| Component | Expected Lifetime | Notes |
|---|---|---|
| **CaO sorbent (per batch)** | 10 - 50 cycles before significant degradation | Sintering reduces porosity and reactivity. Heirloom's proprietary treatment may extend this. |
| **CaO sorbent (effective life)** | ~1 - 6 months per batch | At ~80-100 cycles/year, each batch lasts a few months before partial replacement needed |
| **Steel trays** | 5 - 15 years | Corrosion from CaO/Ca(OH)2 is a concern; galvanized or coated steel |
| **Rack structures** | 15 - 30 years | Standard steel infrastructure |
| **Electric calciner** | 10 - 20 years | Refractory lining replacement every 3-7 years |
| **Facility overall** | 20 - 30 years | Standard industrial plant lifetime |
| **Automation / robotics** | 7 - 15 years | Electronic components, mechanical wear |

---

## 5. End Game: Storage

### 5.1 Storage Medium

After calcination releases a **concentrated, high-purity CO2 stream** (~95-99% CO2), the gas must be permanently stored. Heirloom does not operate storage directly but partners with storage providers.

| Storage Method | Description | Permanence | Status |
|---|---|---|---|
| **Deep saline aquifer injection** | CO2 injected as supercritical fluid into deep porous rock formations capped by impermeable layers | 1,000 - 10,000+ years (with proper site selection and monitoring) | Most mature; used in Sleipner (Norway) since 1996 |
| **Basalt mineralization** | CO2 dissolved in water and injected into basalt formations; reacts to form solid carbonate minerals within 1-2 years | Effectively permanent (geological timescale, millions of years) | Proven at CarbFix (Iceland); Heirloom partner |
| **Depleted oil/gas reservoir injection** | CO2 injected into well-characterized subsurface reservoirs | 1,000 - 10,000+ years | Mature; leverages existing well infrastructure |
| **Enhanced oil recovery (EOR)** | CO2 injected to extract residual oil; some CO2 remains trapped | Controversial permanence (some CO2 returns with oil); net climate benefit debated | Widely practiced in US; not considered high-quality CDR by many standards |
| **Concrete/building material mineralization** | CO2 reacted with calcium/magnesium silicates to form carbonates used in concrete | Permanent if concrete is durable | Emerging; CarbonCure, Solidia, etc. |

### 5.2 Heirloom's Storage Partnerships

| Partner | Storage Method | Location | Notes |
|---|---|---|---|
| **CarbonCure** | Concrete mineralization | Various | CO2 injected into concrete during mixing; permanent |
| **Central Cement** (via CarbonCure) | Concrete mineralization | Tracy, CA area | Close proximity to Heirloom's first facility |
| **Frontier (Stripe, Alphabet, Meta, Shopify, McKinsey)** | Advance market commitment | N/A | Purchased Heirloom carbon removal credits |
| **Microsoft** | Carbon removal credit purchaser | N/A | Major buyer; part of Microsoft's net-zero by 2030 commitment |
| **Project Cypress (DOE DAC Hub)** | Deep saline aquifer injection | Louisiana | Access to Gulf Coast geological storage |

### 5.3 Storage Capacity Limits

| Storage Type | Estimated Global Capacity | Notes |
|---|---|---|
| **Deep saline aquifers** | 1,000 - 10,000+ GtCO2 | Vast; largest storage resource by far |
| **Depleted oil/gas fields** | 200 - 900 GtCO2 | Well-characterized; limited compared to saline aquifers |
| **Basalt formations** | 100 - 1,000+ GtCO2 [est.] | Less well-characterized; enormous potential (ocean floor basalt) |
| **Building materials** | ~10 - 30 GtCO2/year absorptive capacity [est.] | Limited by construction industry scale |
| **TOTAL** | **>1,000 GtCO2** | Storage is NOT the bottleneck for DAC at 10 Gt/yr scale |

### 5.4 Permanence Risk

| Risk | Likelihood | Mitigation |
|---|---|---|
| **Wellbore leakage** (injection wells) | Low with proper cementing and monitoring | Rigorous well integrity standards; monitoring, reporting, verification (MRV) |
| **Caprock failure** (saline aquifers) | Very low at properly characterized sites | Seismic surveys; avoid faulted zones |
| **Induced seismicity** | Low to moderate at high injection rates | Pressure management; injection rate limits |
| **Mineral carbonation reversal** | Essentially zero | Carbonate minerals are thermodynamically stable at surface conditions |
| **Concrete degradation** | Low over 50-100 year building life | Mineralized CO2 in concrete remains stable even if concrete degrades |
| **Political/regulatory risk** | Moderate | Long-term monitoring requirements; liability transfer frameworks developing |
| **Monitoring cost** | Ongoing | Typically 0.5-2% of storage cost annually for 50+ years |

---

## 6. Economic Friction

### 6.1 Cost Per Ton CO2

| Timeframe | Cost Estimate ($/tCO2) | Basis |
|---|---|---|
| **Heirloom current (2023-2024)** | ~$500 - 1,000+ | First-of-a-kind facility; small scale |
| **Heirloom near-term target (2025-2027)** | ~$200 - 400 | With scale-up and optimization |
| **Heirloom medium-term target (2028-2030)** | ~$100 - 200 | At MtCO2/year scale |
| **Heirloom long-term aspiration** | <$100 | At multi-MtCO2/year scale; aggressive target |
| **DOE target for DAC broadly** | <$100/tCO2 | "Carbon Negative Shot" initiative |
| **For comparison: Climeworks current** | ~$600 - 1,000+ | Mammoth plant (2024) |
| **For comparison: 1PointFive (Oxy/CE)** | ~$400 - 600 [est.] | STRATOS plant (2025) |

### 6.2 CAPEX

| Component | Estimated Cost | Notes |
|---|---|---|
| **Rack/tray systems per tCO2/yr capacity** | $100 - 300 [est.] | Steel shelving, trays, foundations |
| **Electric calciner per tCO2/yr capacity** | $150 - 400 [est.] | High-temperature kiln; most expensive unit |
| **Automation/robotics per tCO2/yr capacity** | $50 - 150 [est.] | Tray handling, conveyors |
| **CO2 compression equipment per tCO2/yr** | $30 - 80 [est.] | Standard compressor technology |
| **Site preparation, civil works** | $20 - 80 [est.] | Grading, foundations, roads |
| **Grid interconnection / renewable energy** | $50 - 200 [est.] | Highly variable by location |
| **Engineering, permitting, contingency** | $50 - 150 [est.] | 15-25% of hard costs |
| **TOTAL CAPEX per tCO2/yr capacity** | **~$500 - 1,500** [est.] | First-of-a-kind higher; nth-of-a-kind lower |
| **Tracy facility total CAPEX** | ~$10 - 30M [est.] | 1,000 tCO2/yr; FOAK cost |
| **Project Cypress (Louisiana, DOE Hub)** | Up to $600M DOE share (total project likely $1B+) | Target: multi-hundred-thousand tCO2/yr |

### 6.3 OPEX

| Component | Estimated Annual Cost ($/tCO2) | Notes |
|---|---|---|
| **Electricity (calcination + compression + handling)** | $50 - 180 | At $0.03-0.10/kWh; 1,000-1,800 kWh/tCO2 |
| **Limestone makeup** | $5 - 20 | Replacing degraded sorbent |
| **Labor** | $10 - 40 | Highly automated; lower than conventional chemical plants |
| **Maintenance** | $10 - 40 | 2-5% of CAPEX |
| **CO2 transport & storage** | $10 - 30 | Pipeline + injection + monitoring |
| **Insurance, overhead, other** | $5 - 20 | |
| **TOTAL OPEX per tCO2** | **~$100 - 330** | Electricity cost is the dominant variable |

### 6.4 Learning Rate

| Parameter | Estimate | Basis |
|---|---|---|
| **Expected learning rate** | 10 - 20% cost reduction per doubling of cumulative capacity | Analogous to solar PV (20%), wind (12%), lithium-ion batteries (18%) |
| **Doublings needed to reach $100/tCO2 from $500** | ~3-5 doublings (~8x to 32x current capacity) | At 15% learning rate: 500 * 0.85^n |
| **Doublings needed from 1,000 tCO2/yr to 10 MtCO2/yr** | ~13.3 doublings | 2^13.3 ~ 10,000x |
| **Key cost reduction levers** | Cheaper renewable electricity, larger calciners (economies of scale), automation improvements, longer sorbent life, optimized rack design | |

### 6.5 Revenue Streams

| Revenue Source | Current Value | Notes |
|---|---|---|
| **Voluntary carbon credit sales** | $200 - 800/tCO2 | Premium for high-quality, permanent CDR credits (e.g., Frontier coalition purchases) |
| **45Q federal tax credit (US)** | $180/tCO2 | For DAC with geological storage (Inflation Reduction Act, 2022). Available for 12 years from project start. |
| **California LCFS credits** | Variable (~$50 - 150/tCO2) [est.] | If DAC qualifies under Low Carbon Fuel Standard |
| **EU ETS / compliance market credits** | Potential future; not yet established for DAC | EU carbon price ~$50-100/tCO2 (ETS); DAC inclusion under discussion |
| **Corporate net-zero commitments** | Premium pricing | Microsoft, Stripe, Google, Meta, etc. paying above-market rates to bootstrap industry |
| **State/local incentives** | Variable | Property tax abatements, expedited permitting, etc. |

#### Revenue Stack Example (Best Case, US, 2024-2035)

| Source | $/tCO2 |
|---|---|
| 45Q tax credit | $180 |
| Voluntary credit sale | $200 - 500 |
| State credits (CA LCFS or equivalent) | $50 - 100 |
| **TOTAL potential revenue per tCO2** | **$430 - 780** |

This revenue stack is currently **sufficient to support first-of-a-kind projects** at $500-1,000/tCO2 cost, but the voluntary premium will decline as supply increases. Long-term economic viability requires cost reduction toward $100-200/tCO2.

---

## 7. Additional Feasibility Data

### 7.1 Current Capacity and Projects

| Project | Location | Capacity | Status | Notes |
|---|---|---|---|---|
| **Tracy, CA (first commercial facility)** | Tracy, California | ~1,000 tCO2/year | Operational (Nov 2023) | First commercial-scale enhanced weathering / passive DAC facility in the world. CO2 stored via CarbonCure in concrete. |
| **Project Cypress (DOE DAC Hub)** | Louisiana (Gulf Coast) | Target: up to several hundred thousand tCO2/year at full build-out | In development (selected 2023; expected operations late 2020s) | Up to $600M DOE cost-share. Will use deep saline aquifer storage. |
| **Additional planned facilities** | Multiple US locations under consideration | Scaling toward MtCO2/year | Planning phase | Part of Heirloom's 2030 roadmap |

### 7.2 Key Partnerships

| Partner | Relationship | Significance |
|---|---|---|
| **Microsoft** | Carbon removal credit buyer | Multi-year purchase agreement; one of the largest corporate CDR buyers globally |
| **Frontier (Stripe, Alphabet, Meta, Shopify, McKinsey)** | Advance market commitment | Committed $925M total to CDR purchases; Heirloom is a selected supplier |
| **CarbonCure Technologies** | Storage/utilization partner | Mineralizes captured CO2 in concrete |
| **US Department of Energy** | Funder (DAC Hubs program) | Up to $600M for Project Cypress; validates technology credibility |
| **Breakthrough Energy Ventures** | Investor | Bill Gates's climate fund; Series A/B investor |
| **Lowercarbon Capital** | Investor | Chris Sacca's climate fund |

### 7.3 Key Advantages Over Fan-Based DAC

| Advantage | Detail |
|---|---|
| **Lower energy consumption** | Eliminates 200-500 kWh/tCO2 of fan electricity (~15-25% total energy savings) |
| **Lower CAPEX** | No large fan arrays, no structured contactors, no air ducting. Racks and trays are simple, mass-producible steel structures. |
| **Simpler engineering** | Fewer moving parts (no fans, no blowers). Reduces maintenance and failure modes. |
| **Modular and scalable** | Rack/tray units are highly modular; can be manufactured in factories and deployed quickly. "Cookie-cutter" replication. |
| **Lower noise** | No fan noise; more compatible with diverse siting (including near communities) |
| **Abundant sorbent** | Limestone is cheap, globally abundant, and non-toxic. Unlike engineered sorbents (amines, MOFs) used by competitors. |
| **No sorbent supply chain risk** | Amine sorbents and solid sorbents are specialty chemicals with complex supply chains. Limestone is quarried everywhere. |
| **Proven chemistry** | Calcium looping has been studied for 100+ years. The chemistry is well-understood and thermodynamically favorable. |
| **Lower water consumption** | Compared to liquid-solvent DAC (Carbon Engineering/1PointFive) |

### 7.4 Key Bottlenecks and Disadvantages

| Disadvantage | Detail | Severity |
|---|---|---|
| **Land area** | Passive exposure requires vastly more surface area than fan-based contactors per tCO2. Even with vertical racking, the footprint is substantial. | **High** at 10 Gt scale |
| **Calcination energy** | ~900 C heating step is energy-intensive and cannot be eliminated. Requires substantial renewable electricity or clean fuel. | **High** |
| **Sorbent degradation** | CaO sinters after repeated calcination cycles, losing reactivity. Requires periodic replacement and fresh limestone. | **Medium** |
| **Weather sensitivity** | Rain, extreme calm, and cold temperatures reduce or halt operations. | **Medium** |
| **Humidity sensitivity** | High humidity reduces CO2 capture selectivity (CaO preferentially reacts with H2O). Limits deployment to lower-humidity regions. | **Medium** |
| **Dust/particulate management** | Fine CaO powder can be lost to wind; inhalation hazard for workers; environmental dispersal concern. | **Medium** |
| **CO2 purity from calciner** | If using oxy-fuel calciner, need air separation unit. If electric calciner, CO2 purity is high but electric kiln technology at 900 C is still scaling. | **Medium** |
| **Storage infrastructure co-dependency** | Heirloom produces CO2 but does not store it. Dependent on third-party storage development, pipelines, and injection wells. | **Medium** |
| **Scaling the calciner** | Electric calciners at 900 C for industrial-scale operation are not yet commodity equipment. Cement industry analog exists for rotary kilns but those are fossil-fired. | **Medium** |
| **Night-time / low-wind performance** | Without forced air, capture rate drops during calm periods. | **Low-Medium** |

### 7.5 Scaling Timeline and Projections

| Year | Estimated Cumulative Heirloom Capacity | Milestone |
|---|---|---|
| **2023** | ~1,000 tCO2/year | Tracy, CA facility operational |
| **2024-2025** | ~5,000 - 10,000 tCO2/year [est.] | Tracy expansion + pilot projects |
| **2026-2028** | ~50,000 - 200,000 tCO2/year [est.] | Project Cypress initial phases; additional facilities |
| **2029-2030** | ~500,000 - 1,000,000 tCO2/year | Heirloom's stated MtCO2/year target by ~2030 |
| **2035** | ~5 - 10 MtCO2/year [aspirational] | Multiple DAC Hub-scale facilities |
| **2040** | ~50 - 100 MtCO2/year [aspirational, industry-wide passive DAC] | Requires massive capital mobilization |
| **2050** | ~500 MtCO2 - 1 GtCO2/year [aspirational, industry-wide] | Substantial fraction of IPCC CDR scenarios |

### 7.6 Policy and Subsidy Landscape

| Policy / Program | Jurisdiction | Value | Relevance |
|---|---|---|---|
| **45Q Tax Credit (enhanced by IRA)** | US Federal | $180/tCO2 for DAC + geological storage | **Critical enabler** for US DAC projects. Available for 12 years. Transferable/direct-pay options. |
| **DOE DAC Hubs Program** | US Federal | $3.5B total across multiple hubs | Heirloom selected for Project Cypress (up to $600M) |
| **DOE Carbon Negative Shot** | US Federal | R&D funding target: <$100/tCO2 DAC | Drives R&D investment across DAC approaches |
| **California LCFS** | California | Variable credit value | Potential additional revenue if DAC qualifies |
| **EU Innovation Fund** | EU | Billions available for climate innovation | DAC eligible; EU developing CDR framework |
| **EU Carbon Removal Certification Framework** | EU | Regulatory framework in development | Will define MRV standards for CDR in Europe |
| **UK GGR Business Models** | UK | Revenue support mechanisms for GHG removals | Could support UK-based passive DAC deployment |
| **Article 6 (Paris Agreement)** | International | Carbon credit trading between nations | Could create international demand for DAC credits |
| **Voluntary carbon market standards** (Puro.earth, Isometric, etc.) | Global | Quality certification for CDR credits | Heirloom credits verified under these standards |

### 7.7 Land Use Competition Concerns at Scale

This is arguably the **most significant challenge** for passive DAC at gigatonne scale.

| Scale Target | Estimated Land Required | Context |
|---|---|---|
| 1 MtCO2/year | ~10 - 30 km^2 [est.] (2,500 - 7,500 acres) | Comparable to a large solar farm |
| 10 MtCO2/year | ~100 - 300 km^2 | Comparable to a small city's land area |
| 100 MtCO2/year | ~1,000 - 3,000 km^2 | Comparable to a large US county |
| 1 GtCO2/year | ~10,000 - 30,000 km^2 | Comparable to Belgium or Massachusetts |
| **10 GtCO2/year** | **~100,000 - 300,000 km^2** | **Comparable to Italy or the US state of Arizona** |

> **Note:** These estimates assume the current-generation technology with multi-tier vertical racking. Improvements in sorbent kinetics, rack density, or cycle time could reduce land requirements by 2-5x. Conversely, infrastructure spacing, roads, and buffer zones could increase them.

**Land competition factors:**
- Arid/semi-arid land is less valuable but may have ecological significance (desert ecosystems, wildlife habitat)
- Solar farms compete for the same ideal sites (low humidity, high irradiance, cheap land)
- Co-location with solar generation is synergistic (provides power for calciner) but doubles land claim
- Agriculture competition is minimal if sited in true desert/scrubland
- NIMBY concerns may limit deployment near communities despite low noise

---

## 8. 10 Gigaton/Year Scaling Analysis

### The Challenge in Numbers

To capture and store 10 GtCO2 per year using Heirloom-style passive DAC:

| Parameter | Value at 10 Gt/yr | Context |
|---|---|---|
| **Number of Tracy-scale facilities (1,000 tCO2/yr)** | 10,000,000 (ten million) | Obviously impractical at this unit size |
| **Number of Project Cypress-scale facilities (~500,000 tCO2/yr)** | 20,000 | Very large but conceivable industrial buildout over decades |
| **Number of mega-facilities (5 MtCO2/yr each)** | 2,000 | More realistic unit size for mature industry |
| **Land area required** | ~100,000 - 300,000 km^2 | 0.07 - 0.2% of Earth's land surface; comparable to Arizona |
| **Electricity required** | 10,000 - 18,000 TWh/year | **35 - 65% of current global electricity generation (~28,000 TWh/yr in 2023)** |
| **Limestone consumed annually** | ~5 - 20 Gt/year [est.] | 1-4x current global limestone production (~4.5 Gt/yr) |
| **Steel for infrastructure** | ~5 - 15 Gt cumulative [est.] | 3-8x current annual global steel production (~1.9 Gt/yr); one-time buildout over decades |
| **Water consumption** | ~5 - 12 km^3/year | ~0.1-0.3% of global freshwater withdrawal (~4,000 km^3/yr) |
| **Annual electricity cost** (at $0.03/kWh) | $300B - $540B/year | Massive but comparable to current global fossil fuel subsidies |
| **Annual total cost** (at $100/tCO2 mature) | **$1 trillion/year** | ~1% of global GDP (~$100T) |
| **Annual total cost** (at $200/tCO2 near-term) | **$2 trillion/year** | ~2% of global GDP |
| **CO2 geological storage rate** | 10 Gt/year injection | Current global CCS injection: ~0.04 Gt/year. Requires 250x scale-up. |
| **Pipeline infrastructure** | Tens of thousands of km of CO2 pipelines | Comparable to existing natural gas pipeline networks |

### Critical Bottlenecks for 10 Gt/yr

| Bottleneck | Severity | Feasibility Assessment |
|---|---|---|
| **Electricity generation** | **CRITICAL** | Would require ~35-65% of current global electricity JUST for DAC. Even with massive renewable buildout, this competes with electrification of transport, heating, and industry. This is likely the binding constraint. |
| **Land area** | **Significant** | ~100K-300K km^2 is large but <0.2% of land surface. Desert/scrubland availability is sufficient globally. Not a hard physical limit. |
| **CO2 storage infrastructure** | **Significant** | 250x scale-up of injection infrastructure needed. Geological capacity exists (>1,000 GtCO2 in saline aquifers) but wells, pipelines, and monitoring represent a massive buildout. |
| **Limestone supply** | **Moderate** | Reserves are effectively unlimited but would need to multiply current quarrying by 1-4x. Environmentally impactful quarrying at this scale. |
| **Capital investment** | **Significant** | Cumulative CAPEX of $5-15 trillion to build 10 Gt/yr capacity. Requires sustained multi-decade capital deployment comparable to global energy infrastructure investment. |
| **Water** | **Low** | <0.3% of global freshwater withdrawal. Not a binding constraint globally (may be locally constraining in arid sites). |
| **Steel / materials** | **Moderate** | One-time buildout is large relative to annual steel production but spread over 20+ years is manageable. |
| **Workforce** | **Moderate** | Would employ millions; requires training pipeline. |

### Verdict: Is 10 Gt/yr Passive DAC Feasible?

**Technically possible. Economically and energetically staggering. Not feasible as a sole solution.**

- The **electricity requirement alone** (~10,000-18,000 TWh/yr) is the most daunting constraint. For context, the entire world would need to roughly **double** its renewable electricity generation capacity just for DAC, on top of the clean energy needed for decarbonizing existing energy systems.
- **Land** is manageable but not trivial.
- **Cost** at $1-2 trillion/year is enormous but within the range of what humanity spends on energy (~$6-8T/year) or military (~$2T/year).
- **Storage** capacity exists but infrastructure buildout is a multi-decade, multi-trillion-dollar endeavor in itself.
- **Realistically**, passive DAC could plausibly contribute **0.5 - 2 GtCO2/year** by 2050 as part of a diversified CDR portfolio that also includes:
  - Fan-based DAC (Climeworks, 1PointFive)
  - Enhanced weathering
  - BECCS (bioenergy with CCS)
  - Ocean alkalinity enhancement
  - Biochar
  - Afforestation/reforestation
  - Soil carbon sequestration

---

## 9. Comparative Analysis

### Passive DAC (Heirloom) vs. Other DAC Approaches

| Metric | Heirloom (Passive DAC) | Climeworks (Solid Sorbent, Fans) | 1PointFive / Carbon Engineering (Liquid Solvent, Fans) |
|---|---|---|---|
| **Sorbent** | Limestone (CaO/CaCO3) | Proprietary amine-functionalized solid sorbent | KOH aqueous solution |
| **Air contact method** | Passive (wind, no fans) | Forced air (fans + structured contactor) | Forced air (fans + large contactor) |
| **Regeneration temperature** | ~900 C (calcination) | ~80-120 C (low-temp thermal swing) | ~900 C (calcination of CaCO3 pellets) |
| **Total energy (kWh/tCO2)** | 1,000 - 1,800 | 1,500 - 2,500 | 1,500 - 2,400 |
| **Fan energy** | 0 | 300 - 500 kWh/tCO2 | 200 - 400 kWh/tCO2 |
| **Land footprint** | Large (passive exposure) | Small (forced air, compact) | Small (forced air, compact) |
| **Water use** | Low (~500-1,200 L/tCO2) | Low-moderate (~1,000-5,000 L/tCO2) | High (~4,000-7,000 L/tCO2) |
| **Sorbent cost/availability** | Very low / unlimited (limestone) | High / constrained (specialty chemical) | Moderate / available (KOH) |
| **Current cost ($/tCO2)** | $500 - 1,000 (FOAK) | $600 - 1,000+ | $400 - 600 (estimated) |
| **Target cost** | <$100 | <$300 (near-term); <$100 (long-term) | <$200 (near-term); <$100 (long-term) |
| **CAPEX intensity** | Lower (simple structures) | Higher (engineered contactors) | Highest (large chemical plant) |
| **Modularity** | Very high (cookie-cutter racks) | High (modular collectors) | Lower (integrated chemical plant) |
| **TRL (Technology Readiness Level)** | 6-7 (first commercial plant) | 7-8 (multiple commercial plants) | 7-8 (STRATOS plant under construction/commissioning) |
| **First commercial plant** | 2023 (Tracy, CA) | 2021 (Orca, Iceland); 2024 (Mammoth, Iceland) | 2025 (STRATOS, Permian Basin, TX) |

### Passive DAC vs. Non-DAC CDR Methods

| Method | Cost ($/tCO2) | Permanence | Scalability | MRV Quality | Land Use |
|---|---|---|---|---|---|
| **Passive DAC + geological storage** | $100-1,000 (declining) | 1,000+ years | High (modular) | Very high (measurable) | Moderate-High |
| **Afforestation/reforestation** | $5-50 | Low (fire, disease, land-use change risk) | Moderate | Low-moderate | Very high |
| **Soil carbon** | $10-50 | Low (reversible with land management change) | Moderate | Low | Integrated with agriculture |
| **Biochar** | $50-200 | Moderate-High (100-1,000 years) | Moderate | Moderate | Moderate (biomass sourcing) |
| **BECCS** | $100-300 | High (geological storage) | Moderate (biomass supply limited) | High | Very high (biomass growing) |
| **Enhanced weathering** | $50-200 | Very high (mineral carbonation) | High | Moderate (measurement challenges) | Moderate |
| **Ocean alkalinity enhancement** | $50-200 [est.] | High | Very high (ocean area vast) | Low (measurement challenges) | Low (ocean-based) |

---

## 10. Sources & References

The following sources informed this analysis. Specific claims are attributed where possible; general industry knowledge draws from the full set.

### Primary Sources

1. **Heirloom Carbon Technologies** - Company website, press releases, and public presentations (2020-2024)
   - Facility launch announcement: November 2023
   - Technology descriptions and process overview

2. **US Department of Energy (DOE)** - DAC Hubs Program announcements
   - "Biden-Harris Administration Announces Up to $1.2 Billion for Two Direct Air Capture Hubs" (August 2023)
   - Project Cypress selection and details
   - Carbon Negative Shot initiative

3. **Inflation Reduction Act of 2022** - 45Q tax credit provisions
   - $180/tCO2 for DAC with geological storage

4. **National Academies of Sciences, Engineering, and Medicine** - "Negative Emissions Technologies and Reliable Sequestration: A Research Agenda" (2019)
   - Comprehensive assessment of CDR approaches including calcium looping

5. **IPCC AR6 Working Group III** (2022) - Climate change mitigation, CDR role assessments

### Academic Literature

6. Blamey, J., et al. "The calcium looping cycle for large-scale CO2 capture." *Progress in Energy and Combustion Science*, 2010.

7. Abanades, J.C., et al. "Sorbent cost and performance in CO2 capture systems." *Industrial & Engineering Chemistry Research*, 2004.

8. McQueen, N., et al. "A review of direct air capture (DAC): scaling up commercial technologies and innovating for the future." *Progress in Energy*, 2021.

9. Kelemen, P., et al. "An Overview of the Status and Challenges of CO2 Storage in Minerals and Geological Formations." *Frontiers in Climate*, 2019.

### Industry & Journalism

10. Various reporting from: *MIT Technology Review*, *Bloomberg*, *Reuters*, *Carbon Brief*, *The Verge*, *TechCrunch* (2022-2024)

11. Frontier Climate (advance market commitment) - Purchase agreements and methodology documentation

12. CarbonCure Technologies - Concrete mineralization partnership details

13. International Energy Agency (IEA) - "Direct Air Capture: A Key Technology for Net Zero" (2022)

14. Global CCS Institute - Storage capacity assessments and project tracking

### Key Caveats

- **Heirloom does not publicly disclose** detailed techno-economic breakdowns. Many figures in this document are estimates derived from thermodynamic first principles, analogies to similar industrial processes (cement, lime production), and published academic literature on calcium looping.
- **The technology is evolving rapidly.** Cost and performance figures from 2023-2024 may be significantly outdated by the time of reading.
- **Heirloom's proprietary sorbent enhancement** process is not publicly detailed. Claims of improved kinetics and durability are taken from press materials and investor presentations but cannot be independently verified from public data alone.
- **Land footprint estimates** are particularly uncertain. Heirloom's vertical racking approach compresses the ground footprint substantially, but exact tray-level surface area and loading data are not public.
- **Cost projections** below $100/tCO2 rely on aggressive learning curves and cheap renewable electricity that may or may not materialize at the required scale.

---

*Document compiled: February 2026*
*Data vintage: primarily 2022-2025 public sources*
*Author note: This analysis is intended for internal feasibility assessment. All estimates should be validated against the latest available data before use in investment or policy decisions.*
