# Liquid Solvent Direct Air Capture (DAC)

## Method Overview

**Primary Developer:** Carbon Engineering (founded 2009 by David Keith, acquired by Occidental Petroleum in 2023 for ~$1.1B)
**Commercial Vehicle:** 1PointFive (Occidental subsidiary)
**Mechanism:** Ambient air is drawn through large contactors containing an aqueous potassium hydroxide (KOH) solution. The KOH reacts with CO2 to form potassium carbonate (K2CO3). A series of chemical regeneration steps -- the "calcium caustic recovery loop" -- regenerates the KOH solvent and produces a concentrated stream of pure CO2 for compression and storage.

### Process Chemistry (Simplified)

| Step | Reaction | Temperature | Purpose |
|------|----------|-------------|---------|
| 1. Air Contactor | 2 KOH + CO2 -> K2CO3 + H2O | Ambient (~20 C) | Capture CO2 from air |
| 2. Pellet Reactor (Causticizer) | K2CO3 + Ca(OH)2 -> 2 KOH + CaCO3 | ~70 C | Regenerate KOH, transfer CO2 to CaCO3 pellets |
| 3. Calciner | CaCO3 -> CaO + CO2 | ~900 C | Release pure CO2 stream |
| 4. Slaker | CaO + H2O -> Ca(OH)2 | ~100 C | Regenerate calcium hydroxide for Step 2 |

The process is essentially a modified version of the Kraft pulp mill caustic recovery loop, adapted for atmospheric CO2 capture. The calcination step at ~900 C is the most energy-intensive component and represents the dominant cost and emissions challenge.

---

## 1. Physical Constraints

### 1.1 Land / Surface Area Footprint

| Metric | Value | Source / Basis |
|--------|-------|----------------|
| Air contactor footprint | ~0.5 - 2 km2 per MtCO2/year | Carbon Engineering design estimates; Keith et al. (2018) Joule paper |
| STRATOS Plant (Phase 1) | ~100 acres (~0.4 km2) for 500 ktCO2/year | 1PointFive project filings, Ector County TX |
| Normalized land use | ~0.2 - 0.4 km2 per 100 ktCO2/year | Derived from STRATOS footprint |
| For 1 GtCO2/year | ~2,000 - 4,000 km2 | Linear extrapolation (45 km x 45 km to 63 km x 63 km) |
| For 10 GtCO2/year | ~20,000 - 40,000 km2 | Linear extrapolation |
| Comparison: 10 Gt via BECCS | ~400,000 - 1,200,000 km2 of biomass plantation | IPCC AR6 estimates |
| Comparison: 10 Gt via afforestation | ~5,000,000 - 10,000,000 km2 | Rough estimates for mature forests |

**Key Insight:** Land footprint is one of liquid solvent DAC's strongest advantages. At 10 Gt/year, the ~20,000-40,000 km2 is roughly the size of New Jersey to Switzerland -- large but manageable compared to biological approaches. However, this does NOT include land for energy generation (solar/wind farms, natural gas infrastructure) or CO2 storage wells, which can multiply the effective footprint significantly.

**Air contactor design:** Carbon Engineering uses large, modular fan-driven contactors resembling cooling towers. Each contactor unit processes roughly 1-2 million tons of air per day. Air must pass through at ~1.5-3 m/s. Because atmospheric CO2 concentration is only ~420 ppm, enormous volumes of air must be processed -- roughly 1.4 million cubic meters of air per ton of CO2 captured (at ~420 ppm, ~0.04% CO2 by volume, and assuming ~75% capture efficiency on a single pass).

### 1.2 Location Dependency

| Factor | Assessment | Notes |
|--------|------------|-------|
| Climate sensitivity | Low-moderate | Works in most climates; performance slightly better in warm, dry conditions (less humidity interference). Cold climates reduce reaction kinetics but still viable. |
| Humidity tolerance | Moderate | KOH solution absorbs water from air in humid climates, diluting the solvent. This increases energy for water evaporation but doesn't prevent operation. |
| Altitude / pressure | Minor effect | Lower pressure at altitude slightly reduces air density, requiring marginally more fan energy. |
| CO2 concentration | Uniform (~420 ppm) | Unlike point-source capture, ambient CO2 is well-mixed globally. No concentration advantage by location. |
| Proximity to storage | Critical | Must be near deep saline aquifers or depleted oil/gas reservoirs for geological sequestration. Piping CO2 long distances is expensive ($1-5/tCO2 per 100 km). |
| Proximity to energy | Critical | Requires large, reliable energy supply. Co-location with natural gas or renewable energy is essential. |
| Water availability | Important | Requires significant freshwater. Arid regions (like West Texas) face trade-offs. |

**STRATOS location rationale (Permian Basin, TX):** Chosen for (a) proximity to Occidental's existing oil/gas infrastructure, (b) abundant deep saline aquifer storage (Permian Basin geological formations), (c) availability of natural gas, (d) 45Q tax credit eligibility, (e) potential for enhanced oil recovery (EOR) revenue, (f) favorable permitting environment in Texas.

**Theoretical optimal siting:** Coastal or near-coastal locations with access to renewable energy, geological storage, and water supply. However, practical deployment is driven more by policy, existing infrastructure, and permitting than by atmospheric conditions.

---

## 2. Resource Constraints

### 2.1 Energy Intensity

This is the single most critical constraint for liquid solvent DAC at scale.

| Energy Component | Value | Notes |
|-----------------|-------|-------|
| **Total thermal energy** | **5.25 GJ/tCO2 (1,458 kWh_th/tCO2)** | Keith et al. (2018) Joule; dominated by calciner at 900 C |
| **Total electrical energy** | **366 kWh_e/tCO2** | Fans, pumps, compressors, auxiliaries |
| **Combined primary energy (gas-fired)** | **~8.81 GJ/tCO2 (~2,447 kWh/tCO2)** | Assuming gas-fired calciner + grid electricity |
| Calciner thermal demand | ~4.0 GJ/tCO2 | ~900 C; CaCO3 decomposition endotherm |
| Slaker + pellet reactor | ~0.7 GJ/tCO2 | Lower-grade heat (~70-100 C) |
| Air contactor fans | ~100 kWh_e/tCO2 | Moving ~1.4M m3 of air per tCO2 |
| CO2 compression (to 150 bar) | ~150 kWh_e/tCO2 | For pipeline transport / injection |
| Pumps and auxiliaries | ~116 kWh_e/tCO2 | Solvent circulation, water management |

**Breakdown of where energy goes:**

```
Thermal Energy (1,458 kWh_th/tCO2):
  [=======================================] Calciner (900 C)     ~76%
  [========]                                 Slaker/Pellet Reactor ~13%
  [======]                                   Steam/Other          ~11%

Electrical Energy (366 kWh_e/tCO2):
  [===========]                              CO2 Compression      ~41%
  [=========]                                Fans                 ~27%
  [=========]                                Pumps/Auxiliaries     ~32%
```

#### Energy at 10 Gt/year Scale

| Metric | Value | Context |
|--------|-------|---------|
| Thermal energy for 10 Gt/year | 52,500 PJ/year (14,580 TWh_th/year) | Global primary energy consumption is ~600 EJ/year (~167,000 TWh) |
| Electrical energy for 10 Gt/year | 3,660 TWh_e/year | Global electricity generation is ~29,000 TWh/year (2023) |
| As % of global electricity | ~12.6% | Just for the electrical component |
| Natural gas (if gas-fired calciners) | ~1,350 billion m3/year | Global gas production is ~4,000 billion m3/year (2023) |
| As % of global gas supply | ~34% | Clearly infeasible with gas alone |

**The gas combustion paradox:** Carbon Engineering's current design burns natural gas (methane) in an oxy-fired calciner to reach 900 C. This combustion produces CO2, which is captured in the same stream (since it's oxy-fired, no nitrogen dilution). The process captures roughly 1 ton of atmospheric CO2 per 0.3-0.5 tons of CO2 generated from gas combustion. Net capture ratio is approximately 0.5-0.7 tCO2 net per tCO2 gross captured -- meaning you must capture ~1.4-2.0 tons gross to sequester 1 ton net. This significantly increases the true energy cost per net ton.

**Electrification pathway:** Replacing the gas-fired calciner with electric calcination (using renewable electricity) is a major R&D priority. Electric calciners operating at 900 C are technically possible but not yet commercially proven at scale for this application. This would eliminate the gas combustion penalty and could reduce net energy to ~1,800-2,200 kWh_e/tCO2 (all-electric).

### 2.2 Water Consumption

| Metric | Value | Notes |
|--------|-------|-------|
| Net water consumption | **4.7 - 6.0 tonnes H2O per tCO2** | Keith et al. (2018); evaporative losses from contactor |
| Evaporative loss from contactors | ~3-5 t H2O/tCO2 | Dominant loss mechanism; air passing through aqueous solution carries moisture |
| Process water (slaker, cooling) | ~1-2 t H2O/tCO2 | Chemical process needs |
| For 1 MtCO2/year | ~5-6 million m3/year | Comparable to a small city's water supply |
| **For 10 GtCO2/year** | **~50-60 billion m3/year** | ~1.2% of global freshwater withdrawals (~4,000 billion m3/year) |

**Context:** 50-60 billion m3/year is significant but not prohibitive globally. However, locally it can be a severe constraint -- the Permian Basin is already water-stressed. Occidental has explored using produced water (from oil/gas operations) and brackish water sources to reduce freshwater dependency.

**Humidity matters:** In humid climates, the contactor may actually gain water from the air. In arid climates (like West Texas), evaporative losses are higher, exacerbating water stress.

### 2.3 Material Inputs and Supply Chain

| Material | Consumption Rate | Role | Supply Chain Risk |
|----------|-----------------|------|-------------------|
| **KOH (Potassium Hydroxide)** | Make-up: ~0.5-2 kg/tCO2 (steady state) | Capture solvent (recycled in loop) | Low-moderate. Global KOH production ~2 Mt/year. At scale, solvent losses are small due to recycling. Initial fill for 10 Gt/year capacity would require significant ramp. |
| **CaCO3 / CaO (Limestone/Lime)** | Make-up: ~1-5 kg/tCO2 (steady state) | Calcium loop reagent (recycled) | Low. Limestone is abundant globally (~340 Gt known reserves). Make-up needed due to calcium loop degradation. |
| **Natural Gas (CH4)** | ~3.2-5.0 GJ/tCO2 (~80-130 m3/tCO2) | Calciner fuel (oxy-fired) | Moderate-High at scale. At 10 Gt/year, would consume ~34% of global gas supply. Electric alternatives needed. |
| **Oxygen** | ~0.3-0.5 t O2/tCO2 | Oxy-fired calciner | Moderate. Requires air separation unit (ASU). Energy-intensive to produce. |
| **Steel and concrete** | Large for initial construction | Contactors, piping, structures | Moderate. Each plant requires tens of thousands of tonnes of steel. At 10 Gt scale, ~20,000 plants would need massive construction capacity. |
| **Specialty equipment** | Calciners, ASUs, compressors | Core process units | High. Limited global manufacturing capacity for 900 C calciners and large ASUs. |

#### Supply Chain Scaling Analysis for 10 Gt/year

| Resource | Annual Requirement at 10 Gt/year | Current Global Production | Ratio |
|----------|----------------------------------|--------------------------|-------|
| Natural gas (if gas-fired) | ~800-1,300 billion m3 | ~4,000 billion m3 | 20-33% |
| Electricity | ~3,660 TWh | ~29,000 TWh | 12.6% |
| Water | ~50-60 billion m3 | ~4,000 billion m3 withdrawals | ~1.4% |
| Steel (construction, amortized over 25 yr) | ~20-40 Mt/year during buildout | ~1,900 Mt/year | 1-2% |
| KOH (make-up) | ~5-20 Mt/year | ~2 Mt/year | 2.5-10x |
| Limestone (make-up) | ~10-50 Mt/year | ~8,000 Mt/year (cement industry) | <1% |

**Critical bottleneck:** Natural gas consumption is the showstopper for gas-fired designs at gigatonne scale. Electrification of the calciner is essential. Even with electrification, the electricity demand (~3,660 TWh/year for 10 Gt) would require ~1,200-1,500 GW of dedicated solar capacity or ~900-1,100 GW of wind capacity -- a massive but theoretically achievable build-out over decades.

---

## 3. Throughput Metrics

### 3.1 Capture Rate Per Unit

| Metric | Value | Notes |
|--------|-------|-------|
| Single air contactor module | ~1,500-2,500 tCO2/year | Carbon Engineering modular design |
| STRATOS Plant (full build) | 500,000 tCO2/year (0.5 MtCO2/year) | Largest DAC facility ever attempted |
| Carbon Engineering pilot (Squamish, BC) | ~1 tCO2/day (~365 tCO2/year) | Operating since 2015; proof of concept |
| Air processed per contactor | ~1.5 million m3/day | At ~420 ppm CO2 |
| CO2 capture efficiency (single pass) | ~75% of CO2 in contacted air | Not all CO2 is absorbed in one pass |
| Number of contactors for 1 Mt/year | ~200-400 units | Modular, parallel deployment |

### 3.2 Duty Cycle / Uptime

| Metric | Value | Notes |
|--------|-------|-------|
| Design availability | 85-95% | Target for commercial operation |
| Contactor uptime | ~95%+ | Simple mechanical systems (fans, liquid flow) |
| Calciner uptime | ~85-90% | High-temperature equipment needs periodic maintenance; refractory lining degradation |
| Overall plant capacity factor | ~80-90% | Accounting for planned and unplanned downtime |
| Weather sensitivity | Low | Operates in rain, moderate wind; may shut down in extreme weather events |
| Seasonal variation | ~10-15% swing | Slightly lower performance in cold weather (slower reaction kinetics) |

**Continuous operation:** Unlike solid sorbent DAC (which operates in batch cycles of adsorption/desorption), liquid solvent DAC operates as a continuous flow process. Air flows through contactors continuously; solvent circulates in a steady-state loop. This is an advantage for throughput predictability.

### 3.3 Equipment Lifecycle and Durability

| Component | Expected Lifetime | Degradation Mechanism | Replacement Cost Significance |
|-----------|-------------------|----------------------|-------------------------------|
| Air contactors (structure) | 20-30 years | Corrosion from KOH (highly caustic) | Moderate |
| Contactor packing material | 5-10 years | Degradation from caustic solution, fouling | Moderate (replaceable) |
| Calciner (refractory lining) | 10-15 years (lining replacement every 3-5 years) | Thermal cycling at 900 C degrades refractory | High |
| Pumps and piping | 10-20 years | Caustic corrosion, erosion | Moderate |
| Fans/blowers | 15-25 years | Mechanical wear | Low-moderate |
| CO2 compressors | 20-30 years | Mechanical wear | High |
| Overall plant design life | 25-30 years | Consistent with large chemical plants | -- |
| KOH solvent | Recycled indefinitely (make-up for losses) | Contamination, evaporative losses | Low |
| Calcium loop reagents | Recycled (make-up for degradation) | CaO sintering reduces reactivity over cycles | Low |

**Comparison advantage:** The liquid solvent approach benefits from using well-understood industrial chemistry. The calcium caustic recovery loop has been used in the pulp and paper industry for over a century. The calciner technology derives from the cement/lime industry. This means equipment lifetime and maintenance requirements are relatively well-characterized compared to newer solid sorbent approaches.

---

## 4. End Game: CO2 Storage

### 4.1 Storage Medium

| Storage Method | Applicability to Liquid Solvent DAC | Notes |
|----------------|-------------------------------------|-------|
| **Deep saline aquifer injection** | Primary target | CO2 compressed to supercritical state (>73.8 bar, >31.1 C) and injected into porous sandstone formations capped by impermeable rock. This is Occidental/1PointFive's primary strategy. |
| **Depleted oil/gas reservoirs** | Secondary target | Well-characterized geology from decades of extraction. Occidental has extensive Permian Basin reservoir data. |
| **Enhanced Oil Recovery (EOR)** | Current revenue strategy | CO2 injected into aging oil fields to increase production. Occidental is the largest EOR operator in the US. Each ton of CO2 injected can yield ~0.3-0.6 additional barrels of oil. Controversial: burning that oil re-releases CO2. |
| **Basalt mineralization** | Emerging option | CO2 reacts with basaltic rock to form stable carbonate minerals. CarbFix project in Iceland demonstrated this. Very permanent but geographically limited and slow. |
| **Ocean storage** | Not pursued | Regulatory barriers (London Protocol), ecological concerns, public opposition. |
| **Utilization (synthetic fuels)** | Carbon Engineering's "Air to Fuels" pathway | CO2 + green hydrogen -> synthetic hydrocarbons. Not net-negative (carbon is re-released when fuel is burned) but can be carbon-neutral if displacing fossil fuels. |

### 4.2 Storage Capacity Limits

| Storage Type | Global Estimated Capacity | Sufficient for 10 Gt/year? | Confidence |
|-------------|--------------------------|---------------------------|------------|
| Deep saline aquifers | 1,000 - 10,000+ GtCO2 | Yes, for centuries at 10 Gt/year | Medium (lower bound more certain) |
| Depleted oil/gas reservoirs | 900 - 1,200 GtCO2 | Yes, for ~90-120 years at 10 Gt/year | High (well-characterized) |
| Unmineable coal seams | 3 - 200 GtCO2 | Insufficient alone | Low |
| Basalt formations | Potentially 10,000s GtCO2 | Yes, but injection rates are slow | Low |
| **Total geological storage** | **~2,000 - 11,000+ GtCO2** | **Yes, storage is not the binding constraint** | Medium |

**Key point:** Global geological CO2 storage capacity is almost certainly sufficient for centuries of gigatonne-scale injection. The constraint is not total capacity but rather:
- **Injectivity:** How fast can CO2 be pumped into a given formation? Each well has a maximum injection rate (~0.5-2 MtCO2/year per well depending on geology).
- **Well density:** For 10 Gt/year, you would need ~5,000-20,000 active injection wells globally.
- **Monitoring and verification:** Each storage site requires long-term monitoring for leakage.
- **Characterization:** Only a fraction of theoretical storage capacity has been assessed in sufficient detail for actual injection.

### 4.3 Permanence Risk

| Risk Factor | Assessment | Mitigation |
|-------------|------------|------------|
| Well integrity (leakage through injection wells) | Primary risk; ~0.1-1% leakage probability per century per well | Proper well completion, cement integrity, monitoring |
| Caprock failure | Very low for well-selected sites | Seismic assessment, pressure management |
| Fault reactivation / induced seismicity | Low-moderate | Injection pressure limits, seismic monitoring |
| Dissolution and migration | Very slow (~mm to m per century) | Site characterization, pressure management |
| Mineral trapping (long-term) | Beneficial: CO2 reacts with rock to form stable carbonite minerals over centuries | Passive; improves permanence over time |
| **Overall permanence** | **>99% retention over 1,000 years** for well-selected and managed sites | IPCC SR CCS (2005): "likely >99% over 1,000 years" |

**Regulatory framework:** The US EPA Underground Injection Control (UIC) program, Class VI wells, provides the regulatory framework for CO2 injection. Sites must demonstrate containment for an undefined but effectively permanent timeframe. Post-injection monitoring period is typically 50 years.

---

## 5. Economic Friction

### 5.1 CAPEX (Capital Expenditure)

| Metric | Value | Source / Basis |
|--------|-------|----------------|
| STRATOS Plant (Phase 1: 500 ktCO2/yr) | ~$1.1-1.3 billion | Occidental investor presentations (2022-2024); some estimates range up to $1.8B |
| Capital intensity (per annual tCO2) | ~$2,200 - $3,600 per tCO2/year capacity | Derived from STRATOS estimates |
| Carbon Engineering theoretical (nth plant) | ~$800-1,200 per tCO2/year capacity | Keith et al. (2018) Joule; assumes learning rate and economies of scale |
| For 1 GtCO2/year capacity | ~$0.8 - 3.6 trillion | Range from nth-plant optimistic to STRATOS-derived |
| For 10 GtCO2/year capacity | ~$8 - 36 trillion | Over ~20-30 year buildout; ~$270B - $1.2T per year |

**Context:** Global annual energy investment is ~$2.8 trillion/year (2023, IEA). Building 10 Gt/year of DAC capacity over 25 years at the optimistic end ($8T total = $320B/year) would be comparable to ~11% of current global energy investment. At the pessimistic end ($36T / 25 years = $1.4T/year), it would represent ~50% of global energy investment -- likely infeasible without massive cost reductions.

### 5.2 OPEX (Operating Expenditure)

| Cost Component | Estimated $/tCO2 | % of Total OPEX |
|----------------|-------------------|-----------------|
| Energy (natural gas + electricity) | $100-200 | 40-55% |
| Maintenance and labor | $30-60 | 15-20% |
| Chemical make-up (KOH, CaO) | $10-25 | 5-10% |
| Water | $2-10 | 1-3% |
| CO2 compression and transport | $10-20 | 5-8% |
| CO2 injection and monitoring | $5-15 | 3-6% |
| Insurance, overhead, permitting | $10-30 | 5-10% |
| **Total OPEX** | **$170-360/tCO2** | -- |

### 5.3 Levelized Cost Per Ton CO2

| Estimate Source | Cost ($/tCO2 net removed) | Year | Assumptions |
|----------------|--------------------------|------|-------------|
| Keith et al. (2018) Joule paper | $94-232 | 2018 | Theoretical, nth-plant, natural gas at ~$3.50/GJ |
| Carbon Engineering (company claims) | $100-150 (target) | 2019-2021 | "At scale" with learning |
| National Academies (2019) | $200-600+ | 2019 | Broader assessment of liquid solvent DAC |
| Rhodium Group / independent estimates | $400-600+ | 2023 | Based on STRATOS first-of-a-kind costs |
| IEA (2022) | $125-335 | 2022 | Range for liquid solvent DAC |
| Occidental/1PointFive (implied) | $400-500+ | 2023-2024 | First-of-a-kind STRATOS plant |
| **Long-term target (with learning)** | **$100-200** | 2040+ | Assumes 15-20% learning rate, electrification, scale |

**The cost debate:** There is significant disagreement between Carbon Engineering's published estimates ($94-232/tCO2) and independent assessments ($400-600+). The Keith et al. (2018) paper was peer-reviewed but assumed mature, nth-of-a-kind plant economics. Real-world first-of-a-kind costs at STRATOS are substantially higher. The true long-run cost will depend on learning rates, energy prices, and technology improvements (especially calciner electrification).

### 5.4 Learning Rate and Cost Projections

| Metric | Value | Notes |
|--------|-------|-------|
| Assumed learning rate | 10-20% cost reduction per doubling of cumulative capacity | Analogous to solar PV (which achieved ~24% learning rate) |
| Current cumulative capacity | ~0.001 MtCO2/year (pilot + early STRATOS) | Extremely early on the learning curve |
| Doublings to reach 1 MtCO2/year | ~10 doublings from current | Each doubling: 10-20% cost reduction |
| Potential cost at 10 Mt cumulative | $200-350/tCO2 | If 15% learning rate |
| Potential cost at 100 Mt cumulative | $150-250/tCO2 | Significant but uncertain |
| Potential cost at 1 Gt cumulative | $100-200/tCO2 | Very speculative; requires major R&D wins |

**Solar analogy (optimistic case):** Solar PV went from ~$76/W in 1977 to ~$0.20/W in 2023 -- a 99.7% cost reduction over ~20 doublings of capacity. If DAC follows a similar trajectory (it likely won't -- chemical plants don't benefit from semiconductor-like scaling), costs could fall dramatically. However, DAC is more analogous to chemical process industries where learning rates are typically 5-15%, not 20-25%.

**Pessimistic case:** Some analysts argue that liquid solvent DAC costs are bounded by thermodynamic minimums (the minimum energy to separate CO2 from air is ~250 kWh/tCO2, and real systems operate at 5-10x this) and commodity input costs (energy, steel, concrete). Floor cost may be ~$100-150/tCO2 even at massive scale.

### 5.5 Revenue Streams

| Revenue Source | Value | Status | Net Climate Impact |
|---------------|-------|--------|-------------------|
| **45Q Tax Credit (US)** | $180/tCO2 (DAC + saline storage) | Available since IRA (2022); 12-year credit period | Positive (incentivizes genuine removal) |
| **45Q Tax Credit (EOR)** | $130/tCO2 (DAC + EOR) | Available since IRA (2022) | Debatable (oil extracted re-emits CO2) |
| **Voluntary carbon credits** | $200-1,200/tCO2 | Frontier Advance Market Commitment; corporate buyers (Stripe, Microsoft, etc.) | Positive if verified |
| **California LCFS credits** | $50-200/tCO2 equivalent | If DAC qualifies under Low Carbon Fuel Standard | Positive |
| **Enhanced Oil Recovery (EOR)** | ~$15-40/tCO2 (from incremental oil revenue) | Occidental's core business; ~0.3-0.6 bbl oil per tCO2 injected | Controversial: burning oil offsets removal |
| **Synthetic fuels ("Air to Fuels")** | Negative (costs more to produce than revenue) | Carbon Engineering demonstrated; not yet commercial | Carbon-neutral, not negative |
| **Compliance carbon markets (EU ETS)** | EUR 50-100/tCO2 (2023-2025) | DAC not yet fully integrated into EU ETS | Positive when recognized |

**Revenue stacking:** Occidental's near-term business case relies heavily on stacking 45Q credits ($180/tCO2) with voluntary carbon credit sales ($200-600+/tCO2) and potential EOR revenue. At $180 (45Q) + $200-400 (voluntary credits) = $380-580/tCO2 total revenue, the STRATOS plant may be viable despite high first-of-a-kind costs.

---

## 6. Additional Feasibility Data

### 6.1 Current and Planned Capacity

| Facility | Developer | Capacity | Status | Location | Technology |
|----------|-----------|----------|--------|----------|------------|
| Squamish Pilot | Carbon Engineering | ~365 tCO2/year | Operating since 2015 | Squamish, BC, Canada | Liquid solvent |
| **STRATOS (Phase 1)** | **1PointFive / Oxy** | **500,000 tCO2/year** | **Under construction; operational ~2025** | **Ector County, TX** | **Liquid solvent (CE technology)** |
| STRATOS (potential expansion) | 1PointFive / Oxy | Up to 1 MtCO2/year | Planned | Ector County, TX | Liquid solvent |
| South Texas DAC Hub | 1PointFive / Oxy | 500,000 tCO2/year | Early development (announced 2022, paused/slowed 2024) | Kleberg County, TX | Liquid solvent |
| Additional 1PointFive projects | 1PointFive / Oxy | Multiple Mt-scale plants | Announced intent for 70+ plants by 2035 | Various US locations | Liquid solvent |

**STRATOS timeline:**
- 2022: Construction begins on STRATOS in Ector County, TX
- 2023: Occidental completes acquisition of Carbon Engineering for ~$1.1B
- 2024: Construction continues; some reports of delays and cost overruns
- 2025: Expected initial operations (Phase 1: 500 ktCO2/year target)
- If successful, would be by far the largest DAC facility in the world (current largest: Climeworks Mammoth in Iceland at ~36 ktCO2/year using solid sorbent)

### 6.2 Occidental / 1PointFive Strategy

| Strategic Element | Detail |
|-------------------|--------|
| **Corporate integration** | Oxy acquired Carbon Engineering (Aug 2023, ~$1.1B) to vertically integrate DAC technology with its oil/gas and EOR operations |
| **CEO vision (Vicki Hollub)** | Described as building "an entire DAC industry"; targets 70+ DAC plants by 2035 (aspirational) |
| **EOR synergy** | Oxy is the largest CO2-EOR operator in the US (~300,000+ bbl/day from EOR in Permian Basin). DAC-sourced CO2 can supplement declining natural CO2 sources. |
| **Carbon credit strategy** | Selling high-quality DAC carbon credits to corporations (Microsoft, Airbus, Amazon signed offtake agreements) |
| **45Q dependency** | STRATOS economics are heavily dependent on $180/tCO2 45Q tax credit (IRA). Changes to IRA or 45Q would significantly impact viability. |
| **Debt and investment** | Oxy has allocated $800M-1.3B+ to STRATOS; additional billions planned for expansion. BlackRock invested $550M in 1PointFive (2022). |
| **Political risk (2025)** | The Inflation Reduction Act (IRA) faces potential rollback threats from changing political administrations. 45Q is a tax credit rather than a direct spending program, which may provide some insulation, but uncertainty persists. |
| **Scaling ambition** | 1PointFive's stated goal: multiple MtCO2/year of capacity by 2030; potentially 1+ GtCO2/year by 2040 (very aspirational). |

**Key investor concern:** Occidental took on significant debt for the Carbon Engineering acquisition and STRATOS construction. If STRATOS underperforms or IRA incentives are reduced, the financial viability of the broader DAC strategy is at risk. Oxy's stock and credit rating are partially tied to DAC execution.

### 6.3 Energy Source Requirements and Natural Gas Concerns

| Concern | Detail |
|---------|--------|
| **Natural gas combustion in process** | The oxy-fired calciner burns natural gas directly. For every 1 tCO2 captured from air, ~0.3-0.48 tCO2 is generated from gas combustion. This CO2 IS captured (oxy-firing enables this), but it means ~30-48% of the gross captured CO2 comes from fossil fuel combustion, not from the atmosphere. |
| **Net capture efficiency** | Net removal = Gross capture - Embodied emissions (gas extraction, transport, construction, etc.). True net removal is ~0.5-0.8 tCO2 per gross tCO2 captured, depending on system boundaries. |
| **Methane leakage** | Upstream methane leakage from natural gas supply chain (~1-3% leakage rate) further erodes net climate benefit. At 2.5% leakage rate and GWP-20 of ~80x CO2, this can be significant. |
| **Electrification imperative** | Replacing gas-fired calciners with electric heating (powered by renewables) would eliminate direct process emissions and methane leakage concerns. This is the critical R&D challenge. |
| **Grid electricity emissions** | If grid electricity is used for fans/compressors and the grid is fossil-heavy, additional indirect emissions reduce net removal. Clean electricity is essential. |

**Net lifecycle emissions assessment (gas-fired scenario):**

```
Gross CO2 captured from atmosphere:           1.00 tCO2
+ CO2 from gas combustion (captured):        +0.40 tCO2
= Total CO2 captured and stored:              1.40 tCO2

Emissions:
- Gas combustion CO2 (captured, so net 0):    0.00 tCO2
- Upstream methane leakage (CO2-equivalent):  -0.05 to -0.15 tCO2e
- Electricity (if fossil grid):              -0.05 to -0.20 tCO2e
- Construction / embodied emissions:          -0.02 to -0.05 tCO2e

Net CO2 removed from atmosphere:              0.60 - 0.93 tCO2e per tCO2 gross
```

### 6.4 Policy Landscape

| Policy | Jurisdiction | Value to DAC | Status (as of early 2025) |
|--------|-------------|--------------|---------------------------|
| **45Q Tax Credit (enhanced by IRA)** | US | $180/tCO2 for DAC + saline storage; $130/tCO2 for DAC + EOR | Active; 12-year credit period per project. Single most important policy driver for US DAC. |
| **Inflation Reduction Act (IRA)** | US | Broader clean energy framework supporting DAC supply chain | Enacted 2022; faces political uncertainty with administration changes |
| **DOE DAC Hubs Program** | US | $3.5 billion for 4 regional DAC hubs | Awarded 2023; includes Project Cypress (Climeworks/Heirloom) and South Texas DAC Hub (1PointFive) |
| **EU Innovation Fund** | EU | Grants for DAC demonstration projects | Active; several hundred million EUR allocated |
| **UK CCUS Cluster Sequencing** | UK | Support for CCUS including DAC | Early stage |
| **Article 6 (Paris Agreement)** | Global | Framework for international carbon credit trading | Evolving; could enable DAC credit transfers between countries |
| **California LCFS** | California | Credits for low-carbon fuels; DAC-derived fuels may qualify | Active; value fluctuates |
| **Voluntary carbon market standards** | Global | Verification standards (Puro.earth, Verra, Gold Standard) for DAC credits | Growing; Puro.earth has certified several DAC removals |

**Policy dependency risk:** The entire near-term economic case for liquid solvent DAC in the US rests on the $180/tCO2 45Q tax credit. Without it, even optimistic cost estimates ($200-300/tCO2) exceed revenue from current carbon credit markets for most buyers. If 45Q is reduced or eliminated, the industry would face a severe funding crisis.

### 6.5 Key Bottlenecks to Scaling

| Bottleneck | Severity | Timeframe to Resolve | Notes |
|-----------|----------|---------------------|-------|
| **Cost per ton** | Critical | 10-20 years | Must fall from ~$400-600 to <$200/tCO2 for large-scale deployment without massive subsidies |
| **Energy supply (clean)** | Critical | 15-30 years | 10 Gt/year requires ~3,660 TWh_e + 14,580 TWh_th. Electrification of calciner is essential. Massive renewable energy buildout needed. |
| **Calciner electrification** | High | 5-15 years | No proven commercial electric calciner at 900 C for this application. R&D underway. Potential alternatives: concentrated solar thermal, green hydrogen combustion. |
| **Natural gas dependency** | High | 5-15 years | Current design locks in fossil fuel dependency. Transition to electric/renewable heat is non-trivial. |
| **CO2 storage characterization** | Moderate | 10-20 years | Need to identify and characterize thousands of injection sites globally for 10 Gt/year. Current characterized capacity is far below what's needed. |
| **Injection well drilling** | Moderate | 10-30 years | Need 5,000-20,000 injection wells globally. Rate-limited by drilling rig availability and geological assessment. |
| **Water supply** | Moderate (regional) | Ongoing | 50-60 billion m3/year at 10 Gt scale. Manageable globally but severe constraint in arid regions. |
| **Manufacturing supply chain** | Moderate | 10-20 years | Need to manufacture ~10,000-20,000 large chemical plants (contactors, calciners, ASUs). Current chemical plant construction rate globally is ~100s/year. |
| **Policy and financing** | High | Ongoing | Requires sustained $100B+/year public subsidy or carbon price at ~$150-200+/tCO2 for decades. Political will is uncertain. |
| **Public acceptance** | Low-Moderate | Ongoing | Less controversial than CCS at fossil fuel plants. Some opposition to EOR coupling and natural gas use. |
| **Workforce** | Moderate | 10-20 years | Need hundreds of thousands of skilled chemical engineers, construction workers, geologists for 10 Gt deployment. |

### 6.6 Environmental Concerns

| Concern | Severity | Detail |
|---------|----------|--------|
| Natural gas combustion | High | Locks in fossil fuel infrastructure; upstream methane emissions; undermines climate credibility |
| Water consumption | Moderate-High | 5-6 tonnes water per tCO2; problematic in water-stressed regions |
| KOH handling | Low-Moderate | KOH is highly caustic (pH ~13-14); spills could damage local ecosystems |
| Land use change | Low | Relatively small footprint compared to bio-based approaches |
| Noise | Low | Large fan arrays produce continuous noise; may affect local communities |
| Induced seismicity | Low | CO2 injection can cause minor seismic events; requires monitoring |
| EOR coupling | High (ethical/climate) | Using captured CO2 for enhanced oil recovery yields additional fossil fuel production, partially or fully negating climate benefit |
| Visual impact | Low | Industrial facilities; aesthetic concern for some locations |

### 6.7 Timeline to Meaningful Scale

| Milestone | Target Date | Confidence | Capacity |
|-----------|-------------|------------|----------|
| STRATOS Phase 1 operational | 2025-2026 | Medium-High | 0.5 MtCO2/year |
| Multiple plants operational | 2028-2032 | Medium | 2-5 MtCO2/year |
| 10+ MtCO2/year industry | 2030-2035 | Low-Medium | 10-50 MtCO2/year |
| 100 MtCO2/year | 2035-2045 | Low | 100 MtCO2/year |
| 1 GtCO2/year | 2040-2060 | Very Low | 1,000 MtCO2/year |
| 10 GtCO2/year | 2060-2080+ | Extremely speculative | 10,000 MtCO2/year |

**Reality check:** Getting from 0.5 MtCO2/year (STRATOS) to 10 GtCO2/year requires a 20,000x scale-up. For comparison, the global solar PV industry took ~25 years to scale from 1 GW to 1,200+ GW (a 1,200x increase). A 20,000x increase for DAC would likely require 30-50+ years even under aggressive deployment scenarios, and only if costs fall dramatically, clean energy is abundant, and policy support is sustained.

### 6.8 Comparison: Liquid Solvent vs. Solid Sorbent DAC

| Dimension | Liquid Solvent (Carbon Engineering / 1PointFive) | Solid Sorbent (Climeworks, Global Thermostat, Heirloom) |
|-----------|--------------------------------------------------|--------------------------------------------------------|
| **Capture mechanism** | KOH solution absorbs CO2 continuously | Solid amine-functionalized sorbents adsorb CO2 in batch cycles |
| **Regeneration temperature** | ~900 C (calciner) | ~80-120 C (low-grade heat) |
| **Energy type needed** | High-grade heat (natural gas or electric) + electricity | Low-grade heat (geothermal, waste heat, electric) + electricity |
| **Total energy** | ~1,820 kWh/tCO2 (thermal + electrical) | ~1,500-2,500 kWh/tCO2 (depends on sorbent) |
| **Water consumption** | ~5-6 t H2O/tCO2 | ~0-2 t H2O/tCO2 (some processes are net-positive on water) |
| **Process mode** | Continuous flow | Batch (adsorption/desorption cycles) |
| **Scaling philosophy** | Large centralized plants (500 kt+) | Modular units; many small units in parallel |
| **Technology readiness** | TRL 6-7 (STRATOS approaching TRL 8) | TRL 6-8 (Climeworks Mammoth operational) |
| **Current largest facility** | STRATOS: 500 ktCO2/year (under construction) | Climeworks Mammoth: 36 ktCO2/year (operational 2024) |
| **Cost (current)** | $400-600+/tCO2 (first-of-kind) | $600-1,000+/tCO2 (Climeworks); Heirloom claims lower |
| **Cost (target, at scale)** | $100-200/tCO2 | $100-300/tCO2 |
| **Key advantage** | Higher throughput per plant; proven chemistry; continuous operation | Lower temperature; compatible with waste heat; modular deployment; lower water use |
| **Key disadvantage** | 900 C heat requirement; natural gas dependency; water intensive; large CAPEX per plant | Sorbent degradation; batch cycling limits throughput; sorbent cost; lower TRL for some |
| **Material risk** | KOH, limestone (abundant) | Specialty amine sorbents (supply chain less established) |
| **Primary developers** | Carbon Engineering / 1PointFive (Oxy) | Climeworks (Switzerland), Heirloom (US), Global Thermostat (US) |

---

## 7. Feasibility Assessment: 10 GtCO2/year via Liquid Solvent DAC

### 7.1 Summary Scorecard

| Dimension | Feasibility at 10 Gt/year | Rating | Binding Constraint? |
|-----------|--------------------------|--------|-------------------|
| Land footprint | 20,000-40,000 km2 (manageable) | Feasible | No |
| Location flexibility | Works most places; needs storage proximity | Feasible | No |
| Energy (thermal) | 14,580 TWh_th/year (~8.7% of global primary energy) | Very Challenging | **Yes** |
| Energy (electrical) | 3,660 TWh/year (~12.6% of global electricity) | Very Challenging | **Yes** |
| Water | 50-60 billion m3/year (~1.4% of global withdrawals) | Challenging | Regionally yes |
| Materials (KOH, limestone) | Scalable with investment | Feasible | No |
| Natural gas (if not electrified) | ~34% of global production -- infeasible | Infeasible without electrification | **Yes (if gas-fired)** |
| CO2 storage capacity | 2,000-11,000+ GtCO2 globally | Feasible | No |
| Storage injection rate | 5,000-20,000 wells needed | Challenging | Potentially |
| Cost (at current prices) | $4-6 trillion/year OPEX alone | Infeasible at current costs | **Yes** |
| Cost (at target $150/tCO2) | $1.5 trillion/year OPEX | Very Challenging but conceivable | Borderline |
| Manufacturing/construction rate | ~20,000 large chemical plants | Very Challenging | **Yes** |
| Policy/financing | Requires sustained global carbon price of $150+/tCO2 | Very Challenging | **Yes** |
| Timeline | 2060-2080+ at earliest | Very Challenging | Constraining |

### 7.2 Bottom Line

Liquid solvent DAC is a **technically proven** approach to removing CO2 from the atmosphere. Carbon Engineering / 1PointFive has the most advanced large-scale implementation (STRATOS). However, achieving 10 GtCO2/year faces five binding constraints:

1. **Energy:** The 900 C calcination step demands enormous high-grade heat. Electrification is essential but unproven at scale.
2. **Cost:** Must fall from ~$400-600/tCO2 to <$200/tCO2. Requires aggressive learning rates and R&D breakthroughs.
3. **Manufacturing scale-up:** Building ~20,000 large chemical plants is a multi-decade, multi-trillion-dollar industrial mobilization.
4. **Sustained policy:** Requires decades of $150+/tCO2 carbon pricing or equivalent subsidies globally.
5. **Clean energy availability:** Requires dedicated clean energy supply equivalent to ~12% of today's global electricity generation plus massive thermal energy.

**Liquid solvent DAC alone cannot deliver 10 Gt/year removal.** It is likely one component of a portfolio that also includes solid sorbent DAC, enhanced weathering, BECCS, ocean-based CDR, and forestry/soil approaches. A realistic contribution from liquid solvent DAC might be 0.1-1 GtCO2/year by 2050 and potentially 1-5 GtCO2/year by 2070+ under optimistic scenarios.

---

## 8. Key Sources and References

| Source | Year | Key Contribution |
|--------|------|-----------------|
| Keith, D.W., Holmes, G., St. Angelo, D., Heidel, K. "A Process for Capturing CO2 from the Atmosphere." *Joule*, 2(8), 1573-1594. | 2018 | Foundational techno-economic analysis; $94-232/tCO2 estimate |
| National Academies of Sciences. "Negative Emissions Technologies and Reliable Sequestration." | 2019 | Comprehensive assessment of DAC and other NETs |
| IEA. "Direct Air Capture: A Key Technology for Net Zero." | 2022 | Global status, costs, policy needs |
| IPCC AR6 Working Group III, Chapter 12 (CDR) | 2022 | Role of DAC in climate mitigation pathways |
| IPCC Special Report on CCS | 2005 | CO2 storage permanence and capacity estimates |
| Occidental Petroleum Investor Presentations | 2022-2024 | STRATOS project details, corporate strategy |
| Fasihi, M., Efimova, O., Breyer, C. "Techno-economic assessment of CO2 direct air capture plants." *Journal of Cleaner Production*, 224, 957-980. | 2019 | Independent cost and energy analysis |
| McQueen, N., et al. "A review of direct air capture (DAC): scaling up commercial technologies and innovating for the future." *Progress in Energy*, 3(3). | 2021 | Comprehensive technical review |
| Realmonte, G., et al. "An inter-model assessment of the role of direct air capture in deep mitigation pathways." *Nature Communications*, 10, 3277. | 2019 | Scaling analysis and energy system implications |
| US DOE. "DAC Hubs: Regional Direct Air Capture Hubs." | 2023 | $3.5B program details |
| Hanna, R., et al. "Emergency deployment of direct air capture as a response to the climate crisis." *Nature Communications*, 12, 368. | 2021 | Emergency scaling analysis |

---

*Note: All figures in this document are drawn from published peer-reviewed literature, government agency reports (IEA, DOE, IPCC), and publicly available corporate disclosures through early 2025. Actual costs and performance for the STRATOS plant will not be known until it reaches steady-state operations. Many figures at 10 Gt/year scale are extrapolations and should be treated as order-of-magnitude estimates subject to significant uncertainty.*

*Last updated: February 2025*
