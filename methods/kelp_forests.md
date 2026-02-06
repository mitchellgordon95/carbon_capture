# Kelp Forests / Macroalgae Sinking -- Comprehensive Feasibility Assessment

## Key Players: Phathom, SOS Carbon, Running Tide (discontinued)

**Last Updated:** February 2026
**Research Note:** Data sourced from published scientific literature, NASEM ocean CDR report (2022), company disclosures, IPCC AR6, DOE program announcements, and CDR industry databases through early 2026. Web search tools were unavailable during compilation; figures should be independently verified against the latest disclosures. Some projections are estimates based on published ranges.

---

## Table of Contents

1. [Technology Overview](#1-technology-overview)
2. [Physical Constraints](#2-physical-constraints)
3. [Resource Constraints](#3-resource-constraints)
4. [Throughput Metrics](#4-throughput-metrics)
5. [End Game -- Storage](#5-end-game----storage)
6. [Economic Friction](#6-economic-friction)
7. [Company Profiles](#7-company-profiles)
   - [Phathom](#71-phathom)
   - [SOS Carbon](#72-sos-carbon)
   - [Running Tide (Historical)](#73-running-tide-historical)
8. [Approach Comparison: Purpose-Grown Kelp vs. Sargassum Harvesting](#8-approach-comparison-purpose-grown-kelp-vs-sargassum-harvesting)
9. [MRV Challenges](#9-mrv-challenges)
10. [Environmental Risks](#10-environmental-risks)
11. [Regulatory Landscape](#11-regulatory-landscape)
12. [Social Co-Benefits](#12-social-co-benefits)
13. [Scaling Analysis: Path to Gigatons](#13-scaling-analysis-path-to-gigatons)
14. [Key Bottlenecks](#14-key-bottlenecks)
15. [Timeline Projections](#15-timeline-projections)
16. [Sources & References](#16-sources--references)

---

## 1. Technology Overview

### 1.1 Core Principle

Macroalgae (kelp, sargassum, and other seaweeds) are among the fastest-growing organisms on Earth, converting dissolved CO2 in seawater into organic biomass via photosynthesis. The ocean-atmosphere CO2 equilibrium means that CO2 drawn from seawater by macroalgae growth is ultimately replaced by atmospheric CO2, creating a net drawdown pathway.

The carbon removal mechanism has two main variants:

**Variant A: Purpose-Grown Macroalgae Sinking (Phathom, formerly Running Tide)**
```
Spore/seedling cultivation onshore
        |
        v
Deploy seeded ropes on offshore structures (longlines, rafts)
        |
        v
Macroalgae grows (weeks to months, photosynthesis fixes CO2)
        |
        v
Harvest mature biomass from ropes
        |
        v
Transport to deep water (>1,000 m depth)
        |
        v
Sink biomass (ballasted or free-sinking)
        |
        v
Biomass settles on deep ocean floor / mesopelagic zone
        |
        v
Carbon sequestered for centuries to millennia (below the thermocline)
```

**Variant B: Invasive Sargassum Harvesting & Sinking (SOS Carbon)**
```
Pelagic sargassum detected (satellite/drone monitoring)
        |
        v
Fishing vessels deploy SOS Carbon device while at sea
        |
        v
Device harvests sargassum from ocean surface
        |
        v
Onboard pump pushes sargassum slurry to depth (>200-1,000 m)
        |
        v
Sargassum sinks below thermocline
        |
        v
Carbon sequestered + invasive sargassum removed from surface
```

### 1.2 Relevant Chemistry

**Macroalgae photosynthesis:**
```
6CO2 + 6H2O + light --> C6H12O6 + 6O2
```

**Carbon content of macroalgae (dry weight):**
- Kelp (Macrocystis, Saccharina, Laminaria): ~25-35% carbon by dry weight
- Sargassum: ~25-30% carbon by dry weight
- Dry matter is ~10-15% of wet weight for kelp; ~15-20% for sargassum
- Therefore: ~1 wet tonne of kelp contains ~25-50 kg carbon (~90-180 kg CO2-equivalent)

**CO2 equivalence:**
```
1 kg C = 3.67 kg CO2
1 tonne dry kelp (~30% C) = 0.30 t C = 1.1 t CO2
1 tonne wet kelp (~3-5% C) = 0.03-0.05 t C = 0.11-0.18 t CO2
```

### 1.3 The Natural Precedent

The ocean's "biological pump" naturally transports ~5-12 GtC/year from the surface to the deep ocean via phytoplankton, zooplankton fecal pellets, and sinking organic matter. Approximately ~0.2-0.4 GtC/year of this reaches the deep ocean floor (>1,000 m). Macroalgae naturally contribute to this -- estimates suggest ~0.17 GtC/year of macroalgal carbon already enters the deep ocean via natural detachment and sinking (Krause-Jensen & Duarte, 2016).

Macroalgae sinking CDR aims to dramatically amplify this natural process.

---

## 2. Physical Constraints

### 2.1 Ocean Footprint

| Metric | Purpose-Grown Kelp | Sargassum Harvesting | Notes |
|---|---|---|---|
| **Ocean area per tCO2/yr (growing)** | ~0.5-2.0 hectares per tCO2/yr | N/A (harvests wild sargassum) | Depends on species, yield, growing season |
| **Area for 1 MtCO2/yr** | ~5,000-20,000 km2 of kelp farms | ~10,000-50,000 km2 harvest area | Kelp farms are 3D (depth); sargassum is surface-only |
| **Area for 1 GtCO2/yr** | ~5-20 million km2 | Limited by sargassum availability | For context: total ocean = 361 million km2 |
| **Vertical extent** | Ropes extend 5-30 m depth | Surface only (0-2 m) | Kelp farms use water column efficiently |
| **Sinking destination footprint** | Deep ocean floor; widely distributed | Deep ocean column/floor | Impact zone depends on sinking density |

**Key constraint:** Purpose-grown kelp requires enormous ocean areas. At 1 GtCO2/yr, kelp farming would need an area roughly equivalent to 1.5-5.5% of total ocean surface, or roughly the area of the Mediterranean Sea to the size of Russia. This is the single largest physical constraint.

### 2.2 Location Dependency

#### For Purpose-Grown Kelp (Phathom approach)

| Requirement | Constraint Level | Optimal Range | Details |
|---|---|---|---|
| **Water temperature** | Hard constraint | 5-20 degC (cold-temperate) | Kelp (Saccharina, Macrocystis, Laminaria) requires cold nutrient-rich water; dies above ~20-22 degC |
| **Nutrient availability** | Hard constraint | High nitrate (>5 umol/L), phosphate | Upwelling zones, high-latitude waters ideal; nutrient depletion limits tropical deployment |
| **Light availability** | Hard constraint | Euphotic zone (0-30 m typically) | Kelp needs light for photosynthesis; limited to upper water column |
| **Water depth at farm site** | Moderate constraint | 20-100 m for anchored systems; open-ocean for free-floating | Deeper water = harder anchoring; shallow = coastal conflicts |
| **Proximity to deep water (>1,000 m)** | Strong preference | Within 50-200 km | Must transport harvested biomass to sinking site; shorter = cheaper |
| **Current regime** | Moderate | Moderate currents for nutrient delivery | Too strong = structural damage; too calm = nutrient depletion |
| **Storm exposure** | Major risk factor | Lower is better | Storms destroy infrastructure; see Section 14 |
| **Sea ice** | Hard constraint (seasonal) | Ice-free growing season >4-6 months | High-latitude sites may have limited growing windows |

**Suitable regions for kelp farming CDR:**
- **Tier 1 (best):** Norwegian coast, North Sea, Pacific Northwest (BC/Alaska), Patagonia, New Zealand, southern Australia, northern Japan/Hokkaido, Chile
- **Tier 2 (good):** Northeast US, Iceland, Faroe Islands, Scotland, Brittany, Korea, Namibian upwelling
- **Tier 3 (marginal):** Open ocean nutrient-rich zones (requires free-floating or deep-anchored systems)
- **Not suitable:** Tropical/subtropical waters (too warm, nutrient-poor for kelp)

#### For Sargassum Harvesting (SOS Carbon approach)

| Requirement | Constraint Level | Optimal Range | Details |
|---|---|---|---|
| **Sargassum presence** | Hard constraint | Tropical/subtropical Atlantic | Great Atlantic Sargassum Belt (GASB); Caribbean, Gulf of Mexico, West Africa |
| **Water temperature** | Not a constraint | 20-30 degC (sargassum's native range) | Sargassum thrives in warm tropical waters |
| **Proximity to deep water** | Moderate preference | Caribbean basins (>1,000 m common) | Many Caribbean areas have deep water close to sargassum accumulation zones |
| **Fishing fleet presence** | Strong preference | Near fishing ports | SOS Carbon's device attaches to existing fishing boats |
| **Seasonal timing** | Strong constraint | Peak sargassum: March-August | Sargassum blooms are seasonal; largest in spring/summer |

**Key geographic difference:** Kelp farming is restricted to cold-temperate waters; sargassum harvesting operates in warm tropical waters. The two approaches are geographically complementary.

### 2.3 Depth Requirements for Sinking

| Depth Zone | Name | Suitability for Carbon Storage | Residence Time | Notes |
|---|---|---|---|---|
| **0-200 m** | Epipelagic / mixed layer | **Not suitable** | Weeks to months | Rapid remineralization; CO2 returns to atmosphere quickly |
| **200-1,000 m** | Mesopelagic / thermocline | **Marginal to moderate** | Decades to centuries | Below mixed layer but subject to upwelling on centennial timescales |
| **1,000-4,000 m** | Bathypelagic | **Good** | Centuries to millennia | Below thermocline; deep water residence time ~300-1,000+ years |
| **>4,000 m** | Abyssopelagic / hadal | **Excellent** | Millennia | Very long isolation from atmosphere; highest permanence |

**Consensus target depth:** Most researchers and companies target sinking below **1,000 m** as the minimum for credible long-term storage. Some protocols require >1,500 m. The deeper the sinking, the longer the carbon remains isolated from the atmosphere.

**Deep water formation timescales:** Water sunk below 1,000 m in the North Atlantic takes ~300-1,000 years to return to the surface via thermohaline circulation. In the Pacific, bottom water residence times can exceed 1,500 years.

---

## 3. Resource Constraints

### 3.1 Energy Inputs

#### Purpose-Grown Kelp (Phathom-style)

| Process Step | Energy Estimate (kWh/tCO2) | Notes |
|---|---|---|
| **Seedling/spore production (hatchery)** | ~5-20 | Controlled environment; lighting, temperature, nutrients |
| **Rope seeding and preparation** | ~5-15 | Labor-intensive but low energy per unit |
| **Deployment of longlines/structures** | ~20-50 | Vessel fuel for installation |
| **Monitoring and maintenance** | ~10-30 | Vessel trips, sensors, drone/satellite |
| **Harvesting** | ~30-80 | Vessel-based mechanical harvesting |
| **Transport to sinking site** | ~20-100 | Depends on distance to deep water; vessel fuel |
| **Sinking (ballasting/release)** | ~5-20 | Minimal energy if gravity-sinking with ballast |
| **Total** | **~100-300 kWh/tCO2** | Very low compared to DAC or DOC |

**Key advantage:** Macroalgae sinking is fundamentally a **solar-powered** process. The sun provides the energy for photosynthesis (carbon fixation). Human energy inputs are primarily for logistics (vessels, harvesting, transport). This gives it one of the lowest energy intensities of any CDR method.

#### Sargassum Harvesting (SOS Carbon-style)

| Process Step | Energy Estimate (kWh/tCO2) | Notes |
|---|---|---|
| **Sargassum detection (satellite/monitoring)** | ~1-5 | Shared infrastructure; minimal per-tonne cost |
| **Harvesting (onboard pump/conveyor)** | ~20-60 | Hydraulic pump powered by vessel engine |
| **Pumping to depth** | ~30-100 | Energy to push slurry through hose to depth; depends on target depth |
| **Vessel fuel (marginal, since already fishing)** | ~10-50 | Incremental fuel for harvesting operations |
| **Total** | **~60-200 kWh/tCO2** | Even lower than purpose-grown; leverages existing vessel operations |

**SOS Carbon advantage:** By attaching to fishing boats already at sea, the marginal energy cost is very low. The vessel fuel is already being burned for fishing; sargassum harvesting adds only incremental energy for the pump and deviation from fishing route.

### 3.2 Material Inputs

#### Purpose-Grown Kelp Infrastructure

| Material | Role | Quantity per tCO2/yr | Lifetime | Scaling Concern |
|---|---|---|---|---|
| **Grow ropes (polypropylene/nylon)** | Substrate for kelp attachment | ~50-200 kg rope | 2-5 years | Medium -- polymer supply adequate but ocean plastic concern |
| **Anchor lines and moorings** | Secure longlines to seabed | ~20-100 kg steel/concrete | 5-15 years | Low -- mature marine industry |
| **Buoys (HDPE floats)** | Maintain rope depth/orientation | ~10-50 kg plastic | 3-7 years | Low |
| **Anchor weights (concrete/steel)** | Bottom anchoring | ~200-1,000 kg per anchor point | 10-20+ years | Low |
| **Ballast for sinking (rock, concrete, iron)** | Weight biomass for sinking | ~100-500 kg per tCO2 | Single use | Medium -- continuous material consumption |
| **Vessels (harvesting fleet)** | Harvest, transport, deploy | Shared across large area | 15-30 years | Low -- existing maritime industry |
| **Hatchery infrastructure** | Spore/seedling cultivation | Shared; ~$1-5M per facility | 10-20 years | Low |

**Critical material issue -- ballast:** If biomass must be ballasted with heavy material (rock, concrete, iron) to ensure it sinks reliably, this represents a continuous material flow that scales linearly with CDR volume. At 1 MtCO2/yr, this could mean 100,000-500,000 tonnes of ballast material per year. Some approaches avoid this by:
- Using naturally negatively buoyant kelp species or waterlogged biomass
- Compressing/baling kelp to increase density
- Using biodegradable ballast (e.g., clay, sand)
- Running Tide explored using waste wood/forestry residue as a carbon-carrying ballast

#### SOS Carbon Device

| Material | Role | Notes |
|---|---|---|
| **Pump/conveyor system** | Harvest sargassum from surface | Marinized industrial pump; attaches to vessel |
| **Flexible hose/pipe** | Deliver sargassum slurry to depth | Must reach 200-1,000+ m; significant engineering challenge |
| **Vessel mounting hardware** | Attach device to fishing boat | Standardized fitting for various vessel types |
| **Power takeoff from vessel engine** | Energy source for pump | Parasitic on vessel's main or auxiliary engine |

### 3.3 Nutrient Constraints

This is a critical and often underappreciated constraint for purpose-grown kelp.

| Nutrient | Kelp Requirement | Ocean Availability | Constraint Level |
|---|---|---|---|
| **Nitrogen (N)** | ~15-30 kg N per tonne dry kelp | Limiting in most surface waters; 1-30 umol/L nitrate | **High** -- kelp farming at scale could deplete surface N |
| **Phosphorus (P)** | ~2-4 kg P per tonne dry kelp | Generally less limiting than N | **Moderate** |
| **Iron (Fe)** | Trace amounts | Limiting in HNLC (high nutrient, low chlorophyll) zones | **Low** for most kelp sites |
| **CO2 / DIC** | ~1.1 t CO2 per tonne dry kelp | Abundant in seawater (~2.1 mmol/kg DIC) | **Very Low** -- ocean DIC is vast |

**The nitrogen problem at scale:**
- 1 MtCO2/yr of kelp CDR requires growing ~900,000 tonnes dry kelp
- This needs ~13,000-27,000 tonnes of nitrogen
- At 1 GtCO2/yr: ~13-27 million tonnes N/year
- Global synthetic fertilizer N production: ~110 Mt N/year (2023)
- Kelp at gigatonne scale would need ~12-25% of global N fertilizer production, or must rely entirely on ocean upwelling nutrients

**Implications:**
- Adding fertilizer to the ocean raises eutrophication and environmental concerns
- Relying on natural nutrients limits where and how densely kelp can be farmed
- Deep-water nutrient upwelling (artificial upwelling) has been proposed but adds energy cost and ecosystem disruption risk
- Nutrient competition with existing marine ecosystems is a major concern

**Sargassum advantage:** Sargassum harvesting does not face this constraint because the biomass already exists. However, removing sargassum also removes nutrients from the surface ocean, which could have knock-on ecological effects.

---

## 4. Throughput Metrics

### 4.1 Kelp Growth Rates

| Species | Growth Rate | Annual Yield (wet) | Annual Yield (dry) | Region | Notes |
|---|---|---|---|---|---|
| **Macrocystis pyrifera** (giant kelp) | **30-60 cm/day** (up to 2 ft/day) | 40-80 t wet/ha/yr (wild); up to 150 t wet/ha/yr (farmed) | 4-12 t dry/ha/yr | Pacific (California to Chile, NZ, Australia) | Fastest growing; can reach 45 m length |
| **Saccharina latissima** (sugar kelp) | 1-5 cm/day | 10-30 t wet/ha/yr (farmed) | 1-4 t dry/ha/yr | North Atlantic, North Pacific | Primary European aquaculture species |
| **Saccharina japonica** (kombu) | 2-6 cm/day | 20-50 t wet/ha/yr (farmed) | 2-7 t dry/ha/yr | Northwest Pacific (China, Korea, Japan) | World's most cultivated kelp |
| **Laminaria digitata** (oarweed) | 1-3 cm/day | 8-20 t wet/ha/yr | 1-3 t dry/ha/yr | Northeast Atlantic | Cold-water species |
| **Undaria pinnatifida** (wakame) | 2-5 cm/day | 15-35 t wet/ha/yr | 2-5 t dry/ha/yr | Pacific, invasive elsewhere | Fast-growing; invasive potential |
| **Sargassum spp.** (pelagic) | 2-10 cm/day (doubling time ~11-17 days) | N/A (wild harvest) | N/A | Tropical Atlantic | Free-floating; exponential growth in blooms |

**The 30-60 cm/day figure** applies specifically to *Macrocystis pyrifera* under optimal conditions (high nutrients, 10-15 degC, good light). This makes it one of the fastest-growing organisms on Earth. However, sustained farm-scale yields are lower than peak growth rates suggest, due to:
- Nutrient limitation
- Self-shading at high density
- Grazing by herbivores (sea urchins, fish)
- Seasonal die-back
- Storm damage and biomass loss

### 4.2 Carbon Capture per Unit Area

| System | tCO2/ha/yr (gross) | tCO2/ha/yr (net, after losses) | Notes |
|---|---|---|---|
| **Macrocystis farm (optimistic)** | 5-15 | 3-10 | Based on high-yield scenarios |
| **Macrocystis farm (conservative)** | 2-8 | 1-5 | More realistic with nutrient/density constraints |
| **Saccharina farm (North Atlantic)** | 1-5 | 0.5-3 | Lower yields but proven aquaculture |
| **Tropical seaweed farm (Eucheuma, etc.)** | 2-6 | 1-4 | Warmer water; lower carbon content |
| **For comparison: Terrestrial forest** | 2-10 | 2-10 | But stored in trees, not permanently sequestered |
| **For comparison: BECCS (switchgrass)** | 5-15 | 3-10 | Requires land, water, processing |

**Net vs. gross:** A significant fraction of fixed carbon is lost before reaching the deep ocean:
- Dissolved organic carbon (DOC) release during growth: ~10-30% of fixed carbon
- Biomass lost to grazing, fragmentation, detachment: ~10-20%
- Respiration during transport/sinking: ~5-15%
- Remineralization during sinking (especially upper 200 m): ~20-50%
- **Total loss from fixation to deep ocean floor: ~40-70%**

This means that for every tonne of CO2 fixed by kelp, only ~0.3-0.6 tonnes may reach permanent deep ocean storage.

### 4.3 Sargassum Harvest Rates and Availability

| Metric | Value | Notes |
|---|---|---|
| **Great Atlantic Sargassum Belt (GASB) peak biomass** | ~10-20 million tonnes wet (recent peak years) | Satellite-derived estimates; highly variable year-to-year |
| **GASB annual production** | ~10-30+ Mt wet/yr | With regrowth; exact production uncertain |
| **Carbon content of harvested sargassum** | ~25-30% of dry weight; dry = ~15-20% of wet | ~0.04-0.06 tC per tonne wet (~0.15-0.22 tCO2 per tonne wet) |
| **Theoretical max CDR from GASB harvest** | ~1.5-6.6 MtCO2/yr | If all sargassum harvested and sunk; major logistical challenge |
| **Realistic harvest (near-term)** | ~0.01-0.1 MtCO2/yr | Fleet-limited; technology still early |
| **Sargassum beaching events** | ~5-10+ Mt wet/yr reaching Caribbean/Gulf/West Africa coasts | Creates economic damage; removal is a co-benefit |
| **SOS Carbon device capacity (est.)** | ~1-10 t wet sargassum/hour per device | Depends on sargassum density and pump capacity |

**GASB growth trend:** Since ~2011, massive sargassum blooms have become a recurring phenomenon in the tropical Atlantic, likely driven by increased nutrient runoff from the Amazon/Congo rivers and changing ocean conditions. The GASB was not observed before 2011 at current scales. Annual biomass has been highly variable, ranging from ~1 Mt to >20 Mt wet weight in peak years (2018, 2022, 2023).

### 4.4 Seasonal Variation

| Region | Peak Growing Season | Off-Season | Harvests/Year | Notes |
|---|---|---|---|---|
| **North Atlantic kelp** | March-July | Oct-Feb (slow growth/die-back) | 1-2 | Strong seasonality; winter storms |
| **Pacific NW kelp** | April-September | Nov-Mar | 1-2 | Similar to N. Atlantic |
| **Tropical sargassum** | March-August | Sep-Feb (lower biomass) | Continuous (variable) | Pelagic; follows currents and nutrient plumes |
| **Southern hemisphere kelp** | Sep-Feb (austral spring/summer) | Mar-Aug | 1-2 | Counter-seasonal to northern sites |

**Implication:** Kelp CDR in a single hemisphere has ~4-7 month growing window. Global deployment across both hemispheres could provide year-round operations but at massive logistical complexity. Sargassum harvesting is more continuous but peaks strongly in boreal spring/summer.

---

## 5. End Game -- Storage

### 5.1 Storage Mechanism: Deep Ocean Biomass Sequestration

Unlike DAC or DOC, macroalgae sinking stores carbon as **organic biomass** on the deep ocean floor, not as geological CO2. The sequestration pathway is:

```
Kelp/sargassum biomass sinks below 1,000 m
        |
        v
Biomass settles on deep ocean floor (or remains suspended in deep water column)
        |
        v
Two fates:
   (a) Partial preservation (cold, low-oxygen conditions slow decomposition)
   (b) Microbial decomposition -> dissolved inorganic carbon (DIC) at depth
        |
        v
In both cases, carbon remains below thermocline for centuries-millennia
        |
        v
Eventual return to surface via deep water upwelling (300-1,500+ years)
        |
        v
Net CDR benefit = centuries to millennia of atmospheric CO2 reduction
```

### 5.2 Permanence

| Factor | Impact on Permanence | Details |
|---|---|---|
| **Sinking depth** | Critical | Deeper = longer isolation from atmosphere |
| **Decomposition rate at depth** | Moderate concern | Cold (1-4 degC), high-pressure conditions slow but don't stop microbial decomposition |
| **Oxygen availability at depth** | Important | Oxic deep water: faster decomposition; anoxic/low-O2: slower, but may produce methane |
| **Biomass composition** | Moderate | Refractory compounds (lignocellulose, phlorotannins) persist longer than labile sugars/proteins |
| **Ocean circulation** | Critical | Deep water residence time varies by basin: Atlantic ~300-600 yr; Pacific ~800-1,500 yr |

**Permanence estimates for macroalgae sunk below 1,000 m:**

| Timeframe | % Carbon Remaining in Deep Ocean | Basis |
|---|---|---|
| **100 years** | ~60-90% | Most carbon remains as DIC at depth; little has upwelled |
| **500 years** | ~40-70% | Some deep water begins to return to surface in Atlantic |
| **1,000 years** | ~20-50% | Significant fraction has re-entered surface/atmosphere cycle |
| **10,000 years** | ~5-15% | Most has re-equilibrated; only truly refractory carbon persists |

**Comparison to geological storage:** Geological sequestration (as in DAC + underground injection) offers >10,000-year permanence. Deep ocean biomass storage is shorter-lived, which is a significant disadvantage in carbon credit markets and permanence accounting. Most registries and buyers prefer >1,000-year permanence.

### 5.3 Methane Risk from Decomposition

This is a critical concern because methane (CH4) is ~80x more potent than CO2 as a greenhouse gas over 20 years.

| Scenario | Methane Risk | Details |
|---|---|---|
| **Aerobic decomposition (oxygenated deep water)** | **Very Low** | Aerobic bacteria produce CO2, not CH4; most deep ocean is oxic |
| **Anaerobic decomposition (oxygen-depleted zones)** | **Moderate** | If large biomass deposits create local anoxia, methanogenesis can occur |
| **Methane oxidation in water column** | **Mitigating factor** | Methanotrophic bacteria consume CH4 in the water column before it reaches the atmosphere; deep ocean CH4 almost never reaches the surface |
| **Sediment burial** | **Low risk** | If biomass is buried in sediment, anaerobic decomposition occurs but CH4 is consumed or trapped |

**Net assessment:** Methane from deep ocean biomass decomposition is very unlikely to reach the atmosphere because:
1. Most deep ocean is aerobic (no methanogenesis)
2. Even if CH4 is produced, the ~1,000+ m water column provides enormous opportunity for methanotrophic oxidation
3. Deep ocean CH4 concentrations are already naturally elevated from hydrothermal vents and seeps without atmospheric impact

**However:** If macroalgae sinking is concentrated in areas that are already oxygen-minimum zones (OMZs), the added organic matter could expand deoxygenation. This is an environmental concern (Section 10) more than a methane-to-atmosphere risk.

### 5.4 What Happens to the Biomass?

| Fate | Fraction | Timeframe | Carbon State |
|---|---|---|---|
| **Microbial decomposition to DIC** | 50-90% | Months to decades | Dissolved CO2/bicarbonate at depth; stays sequestered until water upwells |
| **Consumed by deep-sea organisms** | 5-20% | Days to months | Enters deep-sea food web; eventually respired to DIC |
| **Burial in sediment** | 1-10% | Years to millennia | Potentially very long-term storage; analogous to geological carbon |
| **Dissolved organic carbon (refractory DOC)** | 5-15% | Centuries to millennia | Enters ocean's vast refractory DOC pool (~660 GtC; mean age ~4,000-6,000 yr) |

---

## 6. Economic Friction

### 6.1 Cost Estimates

| Cost Metric | Purpose-Grown Kelp (Current) | Purpose-Grown Kelp (Target 2030+) | Sargassum Harvesting (Current) | Sargassum Harvesting (Target) | Notes |
|---|---|---|---|---|---|
| **Cost per tCO2 (all-in)** | **$100-500/tCO2** | **$50-150/tCO2** | **$50-300/tCO2** | **$30-100/tCO2** | Wide ranges reflect uncertainty and early stage |
| **For context: Running Tide (2022-2023)** | ~$250-500/tCO2 | -- | -- | -- | Before shutdown; limited scale |
| **For context: DOE CDR target** | -- | <$100/tCO2 | -- | -- | DOE Carbon Negative Shot |

### 6.2 CAPEX Breakdown -- Purpose-Grown Kelp

| Component | % of CAPEX | Cost Estimate | Notes |
|---|---|---|---|
| **Offshore structure (longlines, moorings, anchors)** | 30-45% | ~$5,000-20,000/ha | Marine infrastructure; depth-dependent |
| **Hatchery/nursery facility** | 10-15% | ~$1-5M per facility | Serves large farm area; shared cost |
| **Vessels (harvesting, transport, deployment)** | 15-25% | ~$2-10M per vessel | Can charter vs. own |
| **Monitoring systems (sensors, buoys, satellite)** | 5-10% | ~$50-200K per farm | IoT/remote sensing becoming cheaper |
| **Sinking infrastructure (ballast, release mechanisms)** | 5-10% | Variable | Depends on sinking method |
| **Permitting and environmental assessment** | 5-10% | ~$0.5-2M per site | Regulatory compliance |

**Estimated CAPEX per tCO2/yr annual capacity:** ~$200-1,000 (high uncertainty)

### 6.3 OPEX Breakdown -- Purpose-Grown Kelp

| Component | % of OPEX | Notes |
|---|---|---|
| **Vessel operations (fuel, crew, maintenance)** | 30-45% | Dominant cost; harvesting and transport |
| **Rope/infrastructure replacement** | 10-20% | Ropes degrade; storms cause losses |
| **Seedling production** | 5-15% | Hatchery operations; seasonal |
| **Monitoring and MRV** | 10-15% | Ongoing tracking of biomass, sinking verification |
| **Ballast material** | 5-10% | If ballasting with rock/concrete; continuous input |
| **Labor (onshore + offshore)** | 10-20% | Skilled marine workers |
| **Insurance** | 5-10% | High risk environment; storm losses |

### 6.4 CAPEX/OPEX -- SOS Carbon (Sargassum Harvesting)

| Component | Estimate | Notes |
|---|---|---|
| **SOS Carbon device (per unit)** | ~$50,000-200,000 (estimated) | Pump, hose, mounting hardware |
| **Installation on vessel** | ~$5,000-20,000 | Vessel modification/fitting |
| **Device maintenance (annual)** | ~$10,000-50,000/yr | Marine environment wear |
| **Incremental fuel cost** | ~$5-20/t wet sargassum | Marginal cost of running pump + route deviation |
| **MRV and monitoring** | ~$10-30/tCO2 | Tracking, verification |

**SOS Carbon cost advantage:** By piggybacking on existing fishing vessel infrastructure, SOS Carbon avoids the enormous CAPEX of building dedicated offshore farming structures. The device is an add-on, not a new marine installation. This dramatically lowers the barrier to entry.

### 6.5 Revenue Streams

| Revenue Source | Current Price Range | Applicability | Notes |
|---|---|---|---|
| **Voluntary carbon credits** | $50-500/tCO2 | Both approaches | Ocean CDR credits are premium but face MRV skepticism |
| **Compliance carbon markets** | $20-100/tCO2 (EU ETS) | Not yet eligible | Macroalgae sinking methodology not yet approved |
| **Sargassum cleanup payments** | $5-50/t wet sargassum removed | SOS Carbon only | Caribbean governments, hotels, tourism boards pay for cleanup |
| **Seaweed co-products (food, feed, fertilizer)** | $500-5,000/t dry (food-grade); $50-200/t (feed/fertilizer) | Purpose-grown kelp (partial harvest) | Diverting biomass to products reduces CDR volume |
| **Alginate/carrageenan extraction** | $2,000-15,000/t extracted | Purpose-grown kelp | High-value but small market |
| **Biostimulants/agricultural inputs** | $200-1,000/t | Both (if not sinking all biomass) | Growing market |
| **Government subsidies/grants** | Variable | Both | DOE, EU Horizon, national programs |
| **Advance carbon credit purchases (Frontier, etc.)** | $100-600/tCO2 | Both | Growing CDR buyer market |

**Revenue model tension:** The highest-value use of macroalgae is food/chemical products ($500-15,000/t dry), not carbon credits ($50-500/tCO2, where 1 t dry = ~1.1 tCO2). Economically rational actors may prefer to sell kelp as food rather than sink it for carbon credits, unless carbon prices rise substantially or the kelp is not food-grade.

**SOS Carbon's dual revenue advantage:** SOS Carbon can potentially earn both carbon credits (for sinking) and sargassum cleanup payments (from affected communities), creating a stacked revenue model that improves economics.

---

## 7. Company Profiles

### 7.1 Phathom

| Attribute | Details |
|---|---|
| **Full name** | Phathom (formerly associated with kelp sinking CDR) |
| **Headquarters** | -- |
| **Founded** | -- |
| **Approach** | Grow macroalgae on ropes (longline systems) in offshore environments, harvest at maturity, transport to deep ocean sites, and sink biomass below 1,000 m for long-term carbon storage |
| **Target species** | Cold-water kelp species (likely Saccharina latissima, Macrocystis pyrifera, or Laminaria spp.) |
| **Key innovation** | Purpose-built offshore macroalgae cultivation systems optimized for carbon yield rather than food production; potentially free-floating or semi-autonomous growing platforms |
| **Target geographies** | Cold-temperate ocean regions with proximity to deep water |
| **Current stage** | Early-stage / pilot development |
| **Target cost** | Aiming for <$100-200/tCO2 at scale |
| **Carbon credit approach** | Voluntary market; developing MRV methodology for sinking verification |

**Phathom's approach in detail:**
- Cultivate macroalgae on seeded ropes deployed on offshore longline structures
- Grow biomass over 4-8 month season (species and location dependent)
- Mechanically harvest mature kelp
- Transport harvested biomass by vessel to designated deep-water sinking sites
- Sink biomass (with or without ballast) to >1,000 m depth
- Monitor sinking and verify carbon delivery using acoustic/optical tracking, sediment traps, and modeling

### 7.2 SOS Carbon

| Attribute | Details |
|---|---|
| **Full name** | SOS Carbon |
| **Headquarters** | Based in the Caribbean/Atlantic region |
| **Founded** | ~2021-2022 |
| **Approach** | Retrofit device that attaches to commercial fishing boats; harvests invasive pelagic sargassum from ocean surface and pumps it to deep ocean depths |
| **Key innovation** | Parasitic attachment to existing fishing fleet -- no dedicated vessels needed; combines CDR with invasive species removal |
| **Target biomass** | Pelagic *Sargassum natans* and *S. fluitans* from the Great Atlantic Sargassum Belt |
| **Device mechanism** | Conveyor/pump system that collects surface sargassum, macerates/slurries it, and pumps it through a flexible hose to depth (target >200-1,000 m) |
| **Target geographies** | Caribbean Sea, Gulf of Mexico, tropical Atlantic (wherever GASB sargassum accumulates) |
| **Current stage** | Prototype/early pilot testing |
| **Partnerships** | Working with Caribbean fishing communities and potentially tourism/government stakeholders |
| **Dual benefit** | Carbon removal + sargassum cleanup (addressing economic/environmental damage from beach inundation) |

**SOS Carbon's operational model:**
1. Fishing boats equipped with SOS Carbon device go to sea for normal fishing operations
2. When encountering sargassum mats (common in Caribbean), crew activates device
3. Conveyor system scoops sargassum from surface; macerator breaks it down
4. Pump pushes sargassum slurry through hose to depth (hundreds of meters)
5. Sargassum sinks further under gravity once below the mixed layer
6. Boat continues fishing; data logged for MRV
7. Fishers receive payment for CDR operations (supplemental income)

**Engineering challenges:**
- Deploying and managing a hose to 200-1,000+ m depth from a small fishing vessel
- Pump reliability in marine environment with abrasive/clogging sargassum
- Maintaining fishing operations while running CDR device
- Verifying sinking depth and fate without dedicated research equipment

### 7.3 Running Tide (Historical)

| Attribute | Details |
|---|---|
| **Full name** | Running Tide Technologies |
| **Headquarters** | Portland, Maine, USA |
| **Founded** | 2017 (initially oyster farming; pivoted to ocean CDR ~2020) |
| **Status** | **Ceased ocean CDR operations ~2023-2024**; pivoted or wound down |
| **Approach** | Deployed biodegradable buoys made from forestry waste (wood chips, bark) seeded with kelp spores; buoys float, kelp grows, then buoy waterlogged and sinks |
| **Key innovation** | Combined terrestrial biomass carbon (wood waste) with ocean biomass carbon (kelp); eliminated need for active harvesting/transport -- autonomous sinking |
| **Carbon credits sold** | Sold credits to Shopify, Stripe/Frontier (among earliest ocean CDR credit buyers) |
| **Controversy** | Faced significant scientific criticism regarding: additionality, MRV methodology, actual sinking verification, carbon accounting, and permanence claims |
| **Funding** | Raised ~$50M+ in venture capital and carbon credit pre-purchases |
| **Lessons learned** | Running Tide's challenges highlighted the MRV difficulties inherent in ocean biomass sinking and the reputational risk of unverified claims |

**Why Running Tide matters for the field:**
- First high-profile company attempting macroalgae sinking CDR at semi-commercial scale
- Their difficulties with MRV, scientific validation, and operational execution served as a cautionary tale
- Frontier Climate (Stripe/Alphabet/Meta/Shopify) purchased Running Tide credits but later scrutinized permanence
- The Running Tide experience led to more rigorous MRV requirements for subsequent ocean CDR ventures

---

## 8. Approach Comparison: Purpose-Grown Kelp vs. Sargassum Harvesting

| Dimension | Purpose-Grown Kelp (Phathom) | Sargassum Harvesting (SOS Carbon) |
|---|---|---|
| **Additionality** | **Strong** -- actively growing new biomass that wouldn't exist otherwise | **Moderate** -- sargassum exists naturally; additionality argument relies on sinking vs. beaching/decomposing at surface |
| **Baseline carbon accounting** | Clear: all kelp carbon is new fixation from atmospheric CO2 | Complex: what would happen to sargassum without intervention? Some would sink naturally; some decomposes at surface releasing CO2 |
| **Scalability (theoretical)** | Very high -- can expand farm area | **Limited by sargassum supply** (~1.5-7 MtCO2/yr max from GASB) |
| **Scalability (practical)** | Limited by nutrients, ocean space, infrastructure | Limited by fishing fleet, device deployment, sargassum variability |
| **CAPEX** | **High** -- offshore farming infrastructure | **Low** -- add-on device to existing vessels |
| **OPEX** | High -- vessel operations, harvesting, rope replacement | **Lower** -- marginal cost on existing fishing trips |
| **Location** | Cold-temperate oceans (high latitudes) | Tropical Atlantic (Caribbean, Gulf, W. Africa) |
| **Seasonality** | Strong (~4-7 month growing season) | Moderate (year-round but peaks Mar-Aug) |
| **Environmental co-benefits** | Habitat creation, nutrient uptake, wave attenuation during growth | **Invasive species removal**, beach protection, tourism preservation |
| **Environmental risks** | Nutrient competition, genetic pollution if non-native, gear entanglement | Bycatch of Sargassum-associated fauna, deep ocean deoxygenation |
| **MRV difficulty** | High -- must track growth, harvest, sinking, decomposition | Very high -- diffuse harvesting from many small vessels |
| **Storm risk** | **Very high** -- offshore structures vulnerable | Low -- fishing boats return to port; no permanent offshore infrastructure |
| **Community engagement** | Limited (offshore industrial activity) | **Strong** -- engages fishing communities, addresses beach inundation |
| **Technology readiness (TRL)** | 3-5 | 3-4 |
| **Carbon credit viability** | Moderate (improving with better MRV) | Moderate (dual benefit narrative is compelling) |

**Complementarity:** These two approaches are geographically and operationally complementary. Purpose-grown kelp works in cold, nutrient-rich high-latitude waters; sargassum harvesting works in warm tropical waters. A portfolio approach could deploy both methods in their optimal geographies.

---

## 9. MRV Challenges

Measurement, Reporting, and Verification is arguably the single greatest challenge for macroalgae sinking CDR.

### 9.1 What Must Be Measured

| MRV Component | Challenge Level | Current Methods | Gaps |
|---|---|---|---|
| **Biomass produced (kelp farms)** | Moderate | Sampling, weighing at harvest, satellite/drone imagery | Scaling from samples to full farm; variable carbon content |
| **Biomass carbon content** | Low | Lab analysis (CHN elemental analyzer) | Must sample representative fraction |
| **Biomass reaching sinking site** | Moderate | Vessel tracking (AIS), weigh at port | Loss during transport |
| **Sinking verified to target depth** | **Very High** | Acoustic tracking (ADCP, sonar), sediment traps, tagged floats, deep-sea cameras | Tracking millions of tonnes of dispersed biomass in open ocean is extremely hard |
| **Carbon fate post-sinking** | **Very High** | Deep-sea sampling, modeling, isotope tracers | Cannot directly measure decomposition of dispersed biomass over centuries |
| **Permanence (centuries)** | **Extremely High** | Ocean circulation models, paleo-oceanographic data | Inherently a modeling/projection exercise; no direct observation possible |
| **Net carbon balance (lifecycle)** | High | LCA: vessel fuel, infrastructure embodied carbon, N2O from nutrients | Complex system boundary; many assumptions |
| **Baseline scenario (additionality)** | High (especially sargassum) | Statistical modeling of counterfactual | What would have happened to the biomass without intervention? |

### 9.2 State of MRV Standards

| Organization | Status | Approach |
|---|---|---|
| **Puro.earth** | Developing biomass sinking methodology | Among first registries to consider ocean biomass credits |
| **Verra (VCS)** | No approved methodology yet | Macroalgae sinking methodology under development |
| **Gold Standard** | No approved methodology yet | Watching space |
| **Isometric** | Developing science-backed ocean CDR protocols | Rigorous, science-first approach; relevant for macroalgae |
| **NASEM (2022 report)** | Recommended significant R&D before scaling | Highlighted MRV as critical gap |
| **Frontier Climate** | Purchased early credits but now demanding higher MRV rigor | Running Tide experience informed stricter requirements |

### 9.3 The Fundamental MRV Problem

The core difficulty: **you cannot follow a piece of kelp to the ocean floor and watch it for 1,000 years.** Every MRV approach for deep-ocean biomass storage ultimately relies on:
1. Verifying that biomass entered the water at the right location and depth (feasible with technology)
2. Modeling what fraction reaches the target depth (moderate confidence)
3. Modeling decomposition rates and carbon fate over centuries (low confidence)
4. Modeling ocean circulation to estimate how long carbon stays below the thermocline (moderate confidence for well-studied basins)

This contrasts with geological sequestration, where CO2 injected into a well-characterized formation can be monitored via seismic surveys, pressure measurements, and well monitoring with much higher confidence.

---

## 10. Environmental Risks

### 10.1 Deep Ocean Deoxygenation

**This is the most serious environmental concern for macroalgae sinking at scale.**

| Factor | Risk Level | Details |
|---|---|---|
| **Oxygen demand of decomposing biomass** | **High at scale** | Aerobic decomposition of organic matter consumes O2; the stoichiometry is roughly: CH2O + O2 -> CO2 + H2O |
| **Current deep ocean O2 trends** | Already declining | Ocean has lost ~2% of dissolved O2 since 1960 due to warming; O2 minimum zones (OMZs) are expanding |
| **O2 consumption per tCO2 sunk** | ~1.1 tonnes O2 per tonne biomass carbon decomposed | Significant at scale |
| **At 1 GtCO2/yr** | ~300 Mt O2/yr consumed in deep ocean | Could measurably expand OMZs and impact deep-sea ecosystems |
| **Local hotspot risk** | **Very high** if sinking is concentrated | Sinking must be distributed over large areas to avoid localized anoxia |

**Mitigation strategies:**
- Distribute sinking across vast ocean areas (dilute the O2 demand)
- Avoid sinking in or near existing oxygen minimum zones
- Target well-oxygenated deep basins (North Atlantic, Southern Ocean)
- Monitor dissolved O2 at sinking sites
- Set per-area sinking limits

### 10.2 Other Environmental Risks

| Risk | Severity | Details | Mitigation |
|---|---|---|---|
| **Deep-sea ecosystem disruption** | Moderate-High | Massive organic matter input to food-poor deep seafloor could radically alter benthic communities | Distribute sinking; avoid sensitive habitats (seamounts, vents, coral) |
| **Sargassum-associated fauna loss** | Moderate | Sargassum mats host diverse fauna (juvenile sea turtles, fish, invertebrates); harvesting removes habitat | Selective harvesting; avoid key nursery areas; leave fraction unharvested |
| **Nutrient reallocation** | Moderate | Removing kelp/sargassum removes N, P, Fe from surface ocean; could reduce primary productivity | Monitor nutrient impacts; avoid nutrient-limited areas for harvesting |
| **Microplastic from rope degradation** | Low-Moderate | Polypropylene/nylon ropes degrade in marine environment | Use biodegradable ropes; regular replacement; retrieve damaged gear |
| **Entanglement risk (marine mammals, turtles)** | Low-Moderate | Longlines and ropes pose entanglement risk | Proper tensioning; wildlife-safe designs; monitoring |
| **Genetic pollution** | Low | Cultivating non-native kelp species could introduce invasive genetics | Use local species/strains; containment protocols |
| **N2O emissions from kelp decomposition** | Low | Nitrogen in biomass can be converted to N2O (a potent GHG) during decomposition | Generally minor; N2O yield from marine organic matter decomposition is small (~0.1-1% of N) |
| **Coastal ecosystem competition** | Low | Nearshore kelp farms compete for space with wild kelp forests, fisheries | Site selection; offshore farming preferred |

### 10.3 Potential Environmental Benefits

| Benefit | Details |
|---|---|
| **Sargassum removal (SOS Carbon)** | Reduces beach inundation, coastal hypoxia, H2S release, tourism/fishery damage |
| **Local ocean de-acidification** | Kelp photosynthesis raises local pH during growth; benefits calcifying organisms |
| **Habitat provision during growth** | Kelp farms act as artificial reefs; shelter fish, invertebrates, marine mammals |
| **Wave attenuation** | Dense kelp canopy reduces wave energy; potential coastal protection co-benefit |
| **Nutrient uptake** | Kelp absorbs excess N and P near nutrient-polluted coastlines (bioremediation) |

---

## 11. Regulatory Landscape

### 11.1 Key International Frameworks

| Framework | Jurisdiction | Relevance | Current Status |
|---|---|---|---|
| **London Protocol (1996) / London Convention (1972)** | International (IMO) | **Critical** -- regulates dumping of wastes and other matter at sea | Macroalgae sinking could be classified as "dumping" or "placement of matter for a purpose other than disposal"; legal interpretation unclear and actively debated |
| **UNCLOS (UN Convention on the Law of the Sea)** | International | Governs marine environmental protection, EEZ rights, high seas freedoms | Kelp farming in EEZ: coastal state jurisdiction; high seas sinking: complex governance gap |
| **CBD (Convention on Biological Diversity)** | International | Precautionary approach to geoengineering and ocean interventions | CBD COP decisions have called for caution on ocean CDR; non-binding but influential |
| **Regional Seas Conventions** (OSPAR, Barcelona, Cartagena, etc.) | Regional | Regulate pollution and marine activities in specific ocean regions | May require additional assessment/approval for macroalgae sinking |

### 11.2 London Protocol Implications

The London Protocol is the most critical regulatory barrier. Key issues:

| Question | Analysis |
|---|---|
| **Is sinking biomass "dumping"?** | London Protocol defines dumping as "deliberate disposal at sea of wastes or other matter." Macroalgae biomass could be classified as "other matter." However, if the purpose is carbon sequestration (not waste disposal), it may fall under a different category. |
| **Precedent: CCS sub-seabed** | In 2006, the London Protocol was amended to allow CO2 storage in sub-seabed geological formations. A similar amendment could potentially be developed for biomass sinking, but this process takes years. |
| **Precedent: Marine geoengineering** | In 2013, the London Protocol adopted a resolution on marine geoengineering, establishing a framework for assessing ocean-based climate interventions. Macroalgae sinking could be evaluated under this framework. |
| **Current legal status** | **Ambiguous** -- no explicit prohibition or permission for macroalgae sinking. Companies operating in national waters may proceed under domestic permits; high seas operations face regulatory vacuum. |

### 11.3 National/Regional Regulations

| Jurisdiction | Relevant Regulation | Status for Macroalgae Sinking |
|---|---|---|
| **United States** | Clean Water Act (NPDES), MPRSA, Magnuson-Stevens Act, NEPA/CEQA | No specific framework; would require permits from EPA, NOAA, USACE; active policy discussions |
| **European Union** | Marine Strategy Framework Directive, Maritime Spatial Planning Directive, Common Fisheries Policy | Kelp farming regulated as aquaculture; sinking for CDR has no specific framework; precautionary approach likely |
| **United Kingdom** | Marine and Coastal Access Act 2009, MMO licensing | Developing ocean CDR policy; kelp farming permits exist but CDR-specific sinking TBD |
| **Norway** | Aquaculture Act, Marine Resources Act | Advanced aquaculture regulatory framework; potential early mover for kelp CDR regulation |
| **Caribbean nations** | Various national maritime laws; Cartagena Convention | SOS Carbon must navigate multiple national jurisdictions; sargassum cleanup mandates could facilitate permitting |
| **International waters (high seas)** | London Protocol, UNCLOS, ISA (for seabed) | Governance gap; no clear authority to permit or prohibit macroalgae sinking |

### 11.4 Emerging Policy

- **US DOE** has funded ocean CDR research including macroalgae approaches through ARPA-E and FECM programs
- **EU Mission Starfish 2030** includes ocean-based carbon removal in its research agenda
- **IPCC AR6 WGIII (2022)** mentioned ocean-based CDR including macroalgae but noted limited evidence and high uncertainty
- **NASEM (2022)** recommended $125M for a US ocean CDR research program, including macroalgae sinking research
- Multiple countries developing national ocean CDR strategies (UK, Norway, Australia, US)

---

## 12. Social Co-Benefits

### 12.1 Sargassum Cleanup (SOS Carbon)

| Co-Benefit | Impact | Details |
|---|---|---|
| **Beach tourism protection** | **High** | Sargassum inundation costs Caribbean tourism industry ~$120M+/yr in cleanup and lost revenue; SOS Carbon addresses root cause |
| **Coastal community health** | Moderate-High | Decomposing sargassum on beaches releases H2S (toxic gas), causing respiratory issues; removal reduces health risks |
| **Fishing industry support** | **High** | Supplemental income for fishers operating CDR device; addresses declining fish catches from sargassum impacts |
| **Marine ecosystem protection** | Moderate | Excess sargassum can smother coral reefs and seagrass beds in nearshore areas; removal protects these ecosystems |
| **Reduced coastal cleanup costs** | High | Governments and hotels spend millions annually on mechanical beach cleanup; at-sea removal is more efficient |

### 12.2 Kelp Farming Benefits

| Co-Benefit | Impact | Details |
|---|---|---|
| **Coastal employment** | Moderate | Kelp farming creates maritime jobs in rural coastal communities |
| **Aquaculture diversification** | Moderate | Adds income stream for fishing communities facing declining catches |
| **Food security** | Low-Moderate | If partial harvest is directed to food products (but competes with CDR objective) |
| **Bioremediation** | Moderate | Kelp absorbs excess nutrients from agricultural runoff; improves coastal water quality |
| **Indigenous/traditional use** | Varies | In some regions (NZ, Pacific Islands, Scandinavia), seaweed farming aligns with traditional practices |

### 12.3 Climate Justice Dimension

Sargassum sinking is notable in the CDR landscape for disproportionately benefiting climate-vulnerable developing nations:
- Caribbean SIDS (Small Island Developing States) are among the most climate-vulnerable countries
- They suffer directly from sargassum inundation (worsened by climate change)
- SOS Carbon's model puts CDR revenue directly into fishing communities in these nations
- This creates a rare alignment between CDR, climate adaptation, and equitable development

---

## 13. Scaling Analysis: Path to Gigatons

### 13.1 Theoretical Maximum

| Approach | Max Annual CDR | Basis | Constraints |
|---|---|---|---|
| **Purpose-grown kelp (global)** | ~1-5 GtCO2/yr (theoretical) | Based on available suitable ocean area, growth rates, and net carbon delivery to depth | Nutrients, infrastructure, logistics, cost |
| **Sargassum harvesting (GASB)** | ~1.5-7 MtCO2/yr | Based on GASB biomass; annually variable | Sargassum supply; fleet capacity; not all harvestable |
| **All wild sargassum (global)** | ~5-20 MtCO2/yr | Including other sargassum aggregations worldwide | Logistics; most sargassum is dispersed |
| **Combined macroalgae sinking** | ~1-5 GtCO2/yr (dominated by purpose-grown) | Portfolio approach | See constraints below |

### 13.2 IPCC and NASEM Estimates

| Source | Estimate for Macroalgae CDR Potential | Confidence | Notes |
|---|---|---|---|
| **IPCC AR6 WGIII (2022)** | ~0.5-5 GtCO2/yr (theoretical for all ocean biological CDR) | Low confidence | Includes macroalgae, microalgae, and other biological ocean approaches |
| **NASEM (2022)** | ~0.1-1 GtCO2/yr (macroalgae sinking specifically) | Low confidence | Identified major knowledge gaps; recommended significant R&D |
| **Froehlich et al. (2019)** | ~0.5-1.38 GtCO2/yr from global macroalgae farming | Low-Medium | Assumed ~48 million km2 of "suitable" ocean; highly optimistic |
| **Wu et al. (2023)** | Lower estimates after accounting for nutrient constraints | Low-Medium | Nutrient limitation significantly reduces potential |

### 13.3 What Would 1 GtCO2/yr Require?

| Parameter | Requirement | Context |
|---|---|---|
| **Ocean farm area** | ~5-20 million km2 | 1.4-5.5% of ocean surface; equivalent to size of India to Russia |
| **Dry kelp production** | ~900 Mt dry/yr (assuming ~30% loss to depth) | Current global seaweed production: ~36 Mt wet/yr (~6 Mt dry); need ~150x increase |
| **Nitrogen input** | ~13-27 Mt N/yr | ~12-25% of global synthetic N production; or rely entirely on ocean nutrients |
| **Number of harvesting/transport vessels** | ~10,000-50,000 | Major fleet; comparable to global fishing fleet segments |
| **Rope (if longline farming)** | ~Millions of tonnes of rope | Polymer supply chain expansion needed |
| **Sinking operations** | ~3-10 billion wet tonnes biomass to deep ocean per year | Massive marine logistics operation |
| **Energy (all operations)** | ~100-300 TWh/yr | ~0.3-1% of global electricity; very modest compared to DAC |
| **Cost at $100/tCO2** | ~$100 billion/yr | Comparable to large industries; requires massive carbon market |
| **Cost at $50/tCO2** | ~$50 billion/yr | More feasible but still very large |

### 13.4 Key Scaling Bottlenecks (Ranked)

| Rank | Bottleneck | Severity | Notes |
|---|---|---|---|
| 1 | **Ocean nutrient availability** | Very High | Natural nutrients limit kelp density and area; adding nutrients is environmentally risky |
| 2 | **MRV at scale** | Very High | Cannot credibly verify gigatonne-scale sinking and permanence with current technology |
| 3 | **Marine logistics** | High | Harvesting, transporting, and sinking billions of tonnes of wet biomass annually |
| 4 | **Offshore infrastructure cost** | High | Building and maintaining farm structures across millions of km2 of ocean |
| 5 | **Storm and weather risk** | High | Offshore structures face regular damage from storms; insurance costs |
| 6 | **Regulatory framework** | High | London Protocol ambiguity; need international agreement for large-scale sinking |
| 7 | **Deep ocean environmental impact** | High | Deoxygenation risk constrains sinking density and total volume |
| 8 | **Carbon market development** | Medium-High | Need robust, trusted credits with verified permanence to fund operations |
| 9 | **Workforce/fleet** | Medium | Training maritime workforce for macroalgae CDR at scale |
| 10 | **Energy** | Low | One of the lowest energy CDR methods; not a binding constraint |

---

## 14. Key Bottlenecks

### 14.1 Storm Risk

This deserves special attention as it is often underappreciated in theoretical analyses.

| Factor | Impact | Details |
|---|---|---|
| **Offshore structure vulnerability** | **Very High** | Longlines, ropes, buoys, and moorings are exposed to ocean storms, waves, and currents 24/7 |
| **Estimated annual loss to storms** | 10-30% of infrastructure per year (in exposed locations) | Based on offshore aquaculture experience; varies enormously by site |
| **Insurance costs** | 5-15% of infrastructure value per year | Marine insurance for offshore structures is expensive |
| **Biomass loss before harvest** | 5-20% per storm event | Kelp detaches from ropes; entire sections can be lost |
| **Comparison: Offshore wind** | Much more robust | Wind turbines are engineered rigid structures; kelp lines are flexible but fragile |
| **Comparison: Fish aquaculture** | Similar vulnerability | Offshore fish farms face similar storm damage; industry norm is protected waters |

**Implication:** Most kelp aquaculture globally occurs in sheltered coastal waters (fjords, bays, harbors) precisely because exposed ocean conditions destroy infrastructure. Scaling CDR-focused kelp farming to open ocean environments requires either:
- Fundamentally more robust (and expensive) offshore structures
- Free-floating systems that don't resist waves (Running Tide's approach, but with different challenges)
- Acceptance of high annual infrastructure losses (baked into OPEX)

### 14.2 The Nutrient Dilemma

At scale, purpose-grown kelp CDR faces a fundamental nutrient trade-off:

**Option A: Rely on natural ocean nutrients**
- Limits farm density and total area (nutrients are sparse in most surface waters)
- Total CDR potential drops to ~0.1-0.5 GtCO2/yr (NASEM range)
- Minimal environmental risk from nutrient manipulation

**Option B: Supplement with artificial nutrients (fertilizer or artificial upwelling)**
- Enables higher yields and larger total CDR
- Raises serious environmental concerns (eutrophication, ecosystem disruption, dead zones)
- Artificial upwelling also brings cold, CO2-rich deep water to surface, partially offsetting CDR
- Regulatory and public acceptance barriers are very high

**Option C: Site farms in naturally nutrient-rich areas (upwelling zones)**
- Best of both worlds, but these areas are limited geographically
- Competition with wild ecosystems that depend on these nutrients
- Major upwelling zones: Peru/Chile, California, Benguela (Namibia), NW Africa, Canary Islands

### 14.3 The Carbon Accounting Problem

| Issue | Details |
|---|---|
| **Lifecycle emissions** | Must subtract all emissions from vessels, infrastructure, manufacturing, transport, etc. |
| **Dissolved organic carbon (DOC) leakage** | Kelp releases 10-30% of fixed carbon as DOC during growth; this carbon does NOT sink and may be rapidly remineralized |
| **Remineralization during sinking** | 20-50% of biomass carbon may be respired in the upper 1,000 m during sinking |
| **Nutrient displacement** | If kelp consumes nutrients that would have supported phytoplankton, the net carbon fixation is reduced (partial displacement) |
| **Counterfactual for sargassum** | Some fraction of sargassum would sink naturally; only the additional sinking is CDR |
| **Net CDR efficiency** | After all losses, net CDR may be only 30-60% of gross photosynthetic carbon fixation |

---

## 15. Timeline Projections

| Milestone | Purpose-Grown Kelp | Sargassum Harvesting | Notes |
|---|---|---|---|
| **First pilot deployments** | 2020-2024 (Running Tide; various academic) | 2022-2025 (SOS Carbon prototype testing) | Both approaches in early pilot phase |
| **Verified 1,000 tCO2/yr** | 2026-2028 | 2025-2027 | Requires robust MRV methodology |
| **First carbon credits sold (verified)** | 2025-2028 | 2025-2027 | Sargassum may be faster due to lower infrastructure needs |
| **10,000 tCO2/yr (single operation)** | 2028-2032 | 2027-2030 | Requires fleet of devices (SOS) or farm expansion (kelp) |
| **100,000 tCO2/yr (industry)** | 2030-2035 | 2029-2033 | Multiple operators; regulatory clarity needed |
| **1 MtCO2/yr** | 2033-2040 | 2032-2038 (requires multiple GASB regions) | Major infrastructure buildout |
| **100 MtCO2/yr** | 2040-2050 | Limited by sargassum supply (~7 Mt max) | Kelp dominates at this scale |
| **1 GtCO2/yr** | 2050+ (if ever) | Not achievable from sargassum alone | Requires revolutionary breakthroughs in nutrients, logistics, cost |

---

## 16. Sources & References

1. **Krause-Jensen, D. & Duarte, C.M.** (2016) -- "Substantial role of macroalgae in marine carbon sequestration" -- *Nature Geoscience*, 9, 737-742
2. **National Academies of Sciences, Engineering, and Medicine (NASEM)** (2022) -- *A Research Strategy for Ocean-based Carbon Dioxide Removal and Sequestration* -- National Academies Press
3. **IPCC AR6 WGIII** (2022) -- Chapter 12: Cross-sectoral perspectives (ocean CDR discussion)
4. **Froehlich, H.E., Afflerbach, J.C., Frazier, M., Halpern, B.S.** (2019) -- "Blue growth potential to mitigate climate change through seaweed offsetting" -- *Current Biology*, 29(18), 3087-3093
5. **Wu, J., Keller, D.P., Oschlies, A.** (2023) -- "Carbon dioxide removal via macroalgae open-ocean mariculture and sinking: An Earth system modeling study" -- *Earth System Dynamics*, 14, 185-221
6. **Gallagher, J.B.** (2014) -- "Offshore macroalgae biomass for bioenergy, biofuels and biomethane" -- Chapter in *Advances in Biorefineries*
7. **Bach, L.T., et al.** (2021) -- "Testing the climate intervention potential of ocean afforestation using the Great Atlantic Sargassum Belt" -- *Nature Communications*, 12, 2556
8. **Duarte, C.M., et al.** (2017) -- "Can seaweed farming play a role in climate change mitigation and adaptation?" -- *Frontiers in Marine Science*, 4, 100
9. **Ricart, A.M., et al.** (2022) -- "Sinking seaweed in the deep ocean for carbon dioxide removal" -- *Environmental Research Letters*, 17, 094022
10. **London Protocol** -- International Maritime Organization (IMO) -- Marine geoengineering framework amendments (2013)
11. **UNCLOS** -- United Nations Convention on the Law of the Sea (1982; Part XII: Protection and Preservation of the Marine Environment)
12. **Running Tide Technologies** -- Company disclosures and media reporting (2020-2024)
13. **Frontier Climate** -- Ocean CDR purchase criteria and lessons learned (frontierclimate.com)
14. **Wang, M., et al.** (2019) -- "The great Atlantic Sargassum belt" -- *Science*, 365(6448), 83-87
15. **DOE ARPA-E MARINER program** -- Macroalgae Research Inspiring Novel Energy Resources (2017-2022)
16. **Phathom** -- Company disclosures (phathom.co)
17. **SOS Carbon** -- Company disclosures (soscarbon.com)
18. **Boyd, P.W., et al.** (2022) -- "An assessment of the risks associated with ocean-based carbon dioxide removal" -- *Environmental Research Letters*, 17, 064047
19. **Gattuso, J.-P., et al.** (2018) -- "Ocean solutions to address climate change and its effects on marine ecosystems" -- *Frontiers in Marine Science*, 5, 337
20. **Hurd, C.L., et al.** (2022) -- "Forensic carbon accounting: assessing the role of seaweeds for carbon sequestration" -- *Journal of Phycology*, 58(6), 763-779

---

## Appendix A: Carbon Flow Diagram for Purpose-Grown Kelp CDR

```
ATMOSPHERE
    |
    | CO2 dissolved into ocean surface (Henry's Law equilibrium)
    v
SURFACE OCEAN (0-200 m)
    |
    | Photosynthesis by farmed kelp on ropes
    v
KELP BIOMASS (gross carbon fixation: 100%)
    |
    |---> DOC release during growth: 10-30% (returns to surface DIC rapidly)
    |---> Grazing/fragmentation loss: 10-20% (consumed, respired at surface)
    |---> Harvested biomass: 50-80%
    |         |
    |         |---> Lifecycle emissions (vessels, infrastructure): -5-15% of gross
    |         |
    |         v
    |     TRANSPORTED TO SINKING SITE
    |         |
    |         v
    |     SINKING THROUGH WATER COLUMN
    |         |
    |         |---> Remineralized 0-200 m: 5-15% (returns to surface within years)
    |         |---> Remineralized 200-1000 m: 10-20% (stays below thermocline decades-centuries)
    |         |
    |         v
    |     REACHES >1,000 m DEPTH: 30-60% of gross fixation
    |         |
    |         |---> Decomposed to DIC at depth: 20-50% (stays deep for 300-1500 yr)
    |         |---> Enters deep-sea food web: 5-15% (eventually respired to DIC at depth)
    |         |---> Buried in sediment: 1-10% (millennia to permanent)
    |         |---> Refractory DOC: 5-10% (enters 4000-6000 yr DOC pool)
    |         |
    |         v
    |     NET CDR: ~25-50% of gross photosynthetic fixation
    |     (after subtracting all losses and lifecycle emissions)
    v
DEEP OCEAN (>1,000 m) -- carbon isolated from atmosphere for 300-1,500+ years
```

**Key takeaway:** For every tonne of CO2 fixed by kelp photosynthesis, only about **0.25-0.50 tonnes** may represent durable (>100 year) carbon removal after accounting for all losses. This "carbon delivery efficiency" is a critical parameter that significantly affects cost-per-net-tCO2.

---

## Appendix B: Comparison Table -- Macroalgae Sinking vs. Other Ocean CDR

| Parameter | Macroalgae Sinking | Direct Ocean Capture (Captura) | Ocean Alkalinity Enhancement | Artificial Upwelling | Ocean Iron Fertilization |
|---|---|---|---|---|---|
| **Mechanism** | Grow biomass, sink to deep ocean | Electrochemically strip CO2 from seawater | Dissolve alkaline minerals to increase ocean CO2 uptake | Pump nutrient-rich deep water to surface to boost phytoplankton | Add iron to HNLC waters to trigger phytoplankton blooms |
| **Energy intensity** | Very low (~100-300 kWh/tCO2) | High (~1,000-2,500 kWh/tCO2) | Low-Moderate (~100-500 kWh/tCO2) | Moderate (~200-1,000 kWh/tCO2) | Very low (<50 kWh/tCO2) |
| **Cost (current)** | $100-500/tCO2 | $300-600/tCO2 | $50-200/tCO2 | $50-500/tCO2 | Unknown (not commercialized) |
| **Permanence** | Centuries (300-1,500 yr) | Depends on storage (geological = permanent) | Very high (>10,000 yr as bicarbonate) | Low-Moderate (depends on export efficiency) | Low (most C remineralized in upper ocean) |
| **MRV difficulty** | Very high | Moderate (measurable CO2 stream) | High (diffuse ocean chemistry change) | Very high | Very high |
| **Scalability** | 0.1-1+ GtCO2/yr (theoretical) | 0.5-2 GtCO2/yr (theoretical) | 1-5 GtCO2/yr (theoretical) | Limited | 1-3 GtCO2/yr (theoretical) |
| **Environmental risk** | Moderate (deoxygenation, ecosystem disruption) | Low (local pH changes) | Low-Moderate (trace metals, ecosystem effects) | High (disrupts stratification, nutrients) | High (ecosystem disruption, anoxia) |
| **TRL (2025)** | 3-5 | 4-5 | 3-5 | 2-4 | 2-3 (largely abandoned) |
| **Key advantage** | Solar-powered; low energy; co-benefits | Measurable CO2 stream; co-location with infrastructure | Very long permanence; accelerates natural process | Uses existing ocean nutrients | Very low cost per tonne (if it worked) |
| **Key disadvantage** | MRV; nutrient limits; storms; lower permanence | High energy; coastal only; early stage | Slow; hard to measure; mineral supply | Brings CO2-rich water up (partial offset) | Uncontrollable; ecological damage; largely discredited |

---

*This document represents a comprehensive assessment of macroalgae sinking CDR as of early 2026. The field is rapidly evolving, particularly regarding MRV methodologies, company developments, and regulatory frameworks. Data on costs, carbon delivery efficiency, and environmental impacts carry significant uncertainty due to the early stage of the technology. All figures should be independently verified against the latest peer-reviewed publications and company disclosures.*
