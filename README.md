# Carbon Capture at Scale: A Feasibility Survey

This project collects data on active carbon dioxide removal ([CDR](#glossary)) approaches — what they cost, what they consume, and what it would take to scale each one to a level that matters for the climate.

The short version: global CO2 emissions are around 42 gigatons per year.[^1] [IPCC](#glossary) scenarios that keep warming under 2°C require somewhere between 6 and 20 gigatons per year of carbon removal by mid-century, depending on how fast emissions fall.[^2] Current removal capacity across all methods is about 0.04 gigatons.[^3] So we're looking at a roughly 250x scale-up in 25 years.

Each method has different constraints — energy, land, water, materials, cost — and different failure modes. The point of this project is to lay out the numbers side by side so it's easier to see where the real bottlenecks are and where additional research or investment would do the most good.

---

## Table of Contents

- [The Numbers](#the-numbers)
- [How Much Capture Do We Need?](#how-much-capture-do-we-need)
- [What the Planet Has to Work With](#what-the-planet-has-to-work-with)
- [The Methods](#the-methods)
- [Inputs Per Ton of CO2](#inputs-per-ton-of-co2)
- [Bottleneck Analysis](#bottleneck-analysis)
  - [How crazy is 1 Gt/yr, actually?](#how-crazy-is-1-gtyr-actually)
- [A Portfolio, Not a Silver Bullet](#a-portfolio-not-a-silver-bullet)
- [Where Research Might Help Most](#where-research-might-help-most)
- [Method Deep Dives](#method-deep-dives)
- [Glossary](#glossary)
- [Data Sources](#data-sources)

---

## The Numbers

Global CO2 emissions are approximately **42 [GtCO2](#glossary)/year** (2025), broken down roughly as:[^1]

| Source | GtCO2/year |
|---|---|
| Coal | ~15.5 |
| Oil | ~12.1 |
| Natural gas | ~8.5 |
| Cement | ~1.6 |
| Land-use change (deforestation, etc.) | ~4.1 |
| **Total** | **~42** |

Since 1850, cumulative emissions total roughly **2,650 GtCO2**.[^4] About 40% (~1,050 Gt) remains in the atmosphere; the rest has been absorbed by oceans and land sinks.[^4]

Atmospheric CO2 is now **~426 [ppm](#glossary)**, up from a pre-industrial baseline of 280 ppm.[^5] The remaining carbon budget for 1.5°C (50% probability) is about **170 GtCO2** — around four years at current rates. At 83% probability, the budget is essentially gone.[^6]

Even if emissions dropped to zero tomorrow, ~1,050 GtCO2 of excess atmospheric carbon would continue driving warming. Getting back to 350 ppm (a level many climate scientists consider safe[^7]) would mean removing **200-300 GtCO2** on top of eliminating emissions. We need both sharp emission reductions and large-scale removal of what's already up there.

---

## How Much Capture Do We Need?

Every IPCC AR6 pathway that limits warming to 1.5-2°C includes significant CDR:[^2]

| Timeframe | CDR Needed | Source |
|---|---|---|
| By 2030 | 1-1.5 GtCO2/year | State of CDR 2024[^3] |
| By 2050 | 6-9 GtCO2/year | IPCC AR6 WG III[^2] |
| By 2100 | 6-17 GtCO2/year | IPCC AR6 WG III[^2] |
| Overshoot correction (cumulative) | ~1,000 GtCO2 total | IPCC moderate-overshoot pathways[^2] |
| National Academies recommendation | 10 Gt/yr by 2050, 20 Gt/yr by 2100 | NAS 2019[^8] |

For this project, we use a working target of **10-20 GtCO2/year**, sustained for decades, alongside emissions reduction. That range comes from mainstream IPCC scenarios and the [National Academies (NAS)](#glossary).[^2][^8]

To put the gap in perspective: total current CDR capacity (natural and engineered) is about **0.04 GtCO2/year**.[^3] Engineered CDR specifically — [DAC](#glossary), biochar, [BECCS](#glossary) — is around **0.01 GtCO2/year**.[^9] The scale-up required is roughly 250-500x.

---

## What the Planet Has to Work With

Every capture method consumes some combination of energy, land, water, and materials. Here's what's available.

### Energy

| Metric | Value |
|---|---|
| Global electricity generation (2024) | ~30,000 [TWh](#glossary)/year[^10] |
| Global primary energy consumption | ~620 [EJ](#glossary)/year (~172,000 TWh)[^11] |
| New renewable capacity added (2024) | 582 [GW](#glossary) (452 GW solar, 114 GW wind)[^12] |
| Solar [LCOE](#glossary) (best markets) | $28-37/MWh[^13] |
| Nuclear capacity (2024) | 377 GW across 417 reactors[^14] |
| Nuclear construction pipeline | 63 reactors / ~65 GW[^14] |

Energy is the binding constraint for mechanical capture. Pulling 1 GtCO2 out of the air via DAC takes roughly **1,100-2,550 TWh**[^15] — about 4-8% of global electricity generation. At 10 Gt, that's 40-80% of current global electricity, or the equivalent output of 3,000-7,000 new nuclear reactors dedicated to nothing but carbon capture.

That math is why DAC alone can't do this, and why the cost trajectory of solar power matters so much for CDR. At $28/MWh and falling,[^13] cheap renewables make methods viable that would have been absurd a decade ago. But the sheer volume of new generation needed is still enormous.

#### Thermodynamic floor

There's a hard physics limit on how little energy CO2 capture can require. Separating CO2 from air (at ~420 ppm) is fundamentally an entropy-of-mixing problem. The Second Law minimum — the absolute theoretical floor — is about **125 kWh per ton of CO2**.[^39] Add compression to pipeline/storage pressure (~150 bar) and it rises to roughly **190 kWh/tCO2**.[^39] No process, no matter how cleverly engineered, can beat this.

Current DAC systems operate at roughly **1,100-2,500 kWh/tCO2** — about 4-7% of thermodynamic efficiency.[^39] That's typical for industrial separations (distillation, desalination, etc. run at 5-20% of their thermodynamic limits). Realistic engineering projections put the long-term floor at **500-1,000 kWh/tCO2** — maybe 3-5x improvement from today, but not 10x.[^39][^40]

This matters for scale-up math. Even a hypothetical "perfect" DAC system at the thermodynamic floor would need **125 TWh to capture 1 GtCO2** — about 0.4% of global electricity. Achievable. But real engineering will land somewhere between 300 and 1,000 kWh/tCO2, meaning 1 Gt of DAC will always require **300-1,000 TWh** of dedicated clean energy. At 10 Gt, that's 3,000-10,000 TWh — 10-33% of current global generation. The thermodynamic floor confirms that energy supply is a permanent constraint for mechanical CDR, not just a temporary cost problem.

### Land

| Metric | Value |
|---|---|
| Total Earth land area | 14.9 billion hectares |
| Degraded land | ~6 billion ha (40%)[^16] |
| Land with restoration potential | ~2 billion ha[^16] |
| Current arable land in use | ~1.5 billion ha[^17] |

The land constraint is method-dependent and regionally specific. DAC equipment is compact (~0.2-1 m² per ton/yr),[^18] but powering it with solar adds 5-10 m²/ton for panels. Reforestation is land-hungry: at ~5-15 tCO2/ha/year for mature forest, even 5 GtCO2/year of forest-based removal would need roughly **500 million hectares** — about the size of the Amazon basin.

It's worth noting that "land" is not a single resource. Tropical land suitable for reforestation is different from coastal desert suitable for algae ponds, which is different from basalt formations for carbon storage. Many of these don't compete with each other, but they all compete with agriculture, housing, and existing ecosystems.

### Water

| Metric | Value |
|---|---|
| Total renewable freshwater | ~43,000 km³/year[^19] |
| Current human withdrawals | ~3,880 km³/year[^19] |
| Agriculture's share | ~70%[^19] |
| Surplus vs. planetary boundary | ~1,400 km³/year[^20] |

Globally, the numbers look manageable. Regionally, they don't. DAC uses 1-7 tons of water per ton of CO2.[^15] At 10 GtCO2/year, that's 10-70 km³/year — fine as a global average, potentially devastating in already water-stressed areas. Methods that use seawater (ocean alkalinity enhancement, microalgae ponds, direct ocean capture) avoid this constraint entirely.

### Materials

| Material | Global Annual Production | Notes |
|---|---|---|
| Steel | ~1.9 billion tonnes[^21] | Structural material for most approaches |
| Cement | ~4.2 billion tonnes[^21] | |
| Lithium | ~240,000 tonnes[^21] | Energy storage |
| Nickel | ~3.7 million tonnes[^21] | |
| Platinum group metals | ~550 tonnes[^21] | Some electrochemical methods |
| Rare earth oxides | ~390,000 tonnes[^21] | 69% from China |
| Olivine | Limited mining, vast reserves | Key for ocean alkalinity enhancement |

One gigaton of DAC capacity requires an estimated **17-36 million tonnes of steel, concrete, copper, and aluminum**[^22] — roughly 1-3% of current US production. That's doable for a single gigaton. At ten, material demands start competing with the solar panel, wind turbine, EV, and construction buildouts happening in parallel. The raw materials generally exist (olivine reserves, for instance, are effectively unlimited), but mining, refining, and manufacturing capacity would need to grow substantially.

---

## The Methods

We organize CDR approaches along two axes — the capture mechanism (mechanical vs. biological) and the medium (land vs. ocean):

|  | **Land-based** | **Ocean-based** |
|---|---|---|
| **Mechanical** | Direct Air Capture (solid sorbent, liquid solvent, passive, electrochemical) | Direct Ocean Capture, Ocean Alkalinity Enhancement |
| **Biological** | Reforestation, Engineered Trees, Bamboo Construction, Biochar, C4 Photosynthesis | Kelp Forests, Iron Fertilization, Microalgae Ponds |

Each is, at a basic level, a machine (biological or mechanical) that takes inputs (energy, water, materials, land) and produces sequestered carbon plus some byproducts. The detailed data for each is in the [`methods/`](methods/) directory. What follows is a comparative overview.

---

## Inputs Per Ton of CO2

The central question for each method: what does it take — in energy, land, water, money, and time — to remove one ton of CO2 and keep it removed?

### Machine / Land (Direct Air Capture)

| Method | Energy (kWh/tCO2) | Land (m²/tCO2/yr) | Water (t/tCO2) | Cost ($/tCO2) | Permanence | [TRL](#glossary) |
|---|---|---|---|---|---|---|
| **Solid Sorbent DAC** (Climeworks) | 1,500-2,500[^23] | 0.2-1.0 (equipment)[^18] | 1-2[^23] | 600-1,000[^24] | 10,000+ yr (mineralization)[^25] | 7-8 |
| **Liquid Solvent DAC** (1PointFive) | 1,100-1,800[^26] | 0.2-0.4 km²/100kt[^26] | 4.7[^26] | 250-600 (claimed)[^26] | 10,000+ yr (geological) | 6-7 |
| **Passive DAC** (Heirloom) | 500-1,200 (calcination)[^27] | Large (tray arrays) | Low | 250-500 (target)[^27] | 10,000+ yr (geological) | 5-6 |
| **Electrochemical DAC** (Verdox, Mission Zero) | 400-1,000 (theoretical)[^28] | Compact | Low | Unknown (early) | 10,000+ yr (geological) | 3-5 |

There's a clear generational progression here. Liquid solvent requires 900°C heat (typically natural gas).[^26] Solid sorbent drops that to ~100°C (geothermal, waste heat).[^23] Passive capture eliminates fans entirely (zero kinetic energy cost).[^27] Electrochemical methods eliminate the thermal step altogether, using electricity directly.[^28] Each generation attacks the dominant cost of the one before it. Electrochemical approaches could potentially be 3-4x cheaper than current DAC — but they're still at lab scale, and electrode durability remains an open question.

### Machine / Water (Marine CDR)

| Method | Energy (kWh/tCO2) | Footprint | Water | Cost ($/tCO2) | Permanence | TRL |
|---|---|---|---|---|---|---|
| **[DOC](#glossary)** (Captura) | 500-1,500[^29] | Coastal/platform | Seawater | 300-500 (projected)[^29] | Centuries (re-equilibration) | 4-5 |
| **[OAE](#glossary)** (Vesta, Ebb) | 50-500 (grinding/electrolysis)[^30] | Coastlines, beaches | Seawater | 50-200 (projected)[^30] | 10,000+ yr (bicarbonate)[^30] | 3-5 |

Ocean-based mechanical methods exploit a physical advantage: seawater holds CO2 at roughly 140x the concentration of ambient air. Less fluid to process per ton means less energy. OAE is especially interesting because the ocean already sequesters ~0.3 GtCO2/year through natural alkalinity cycling[^30] — OAE accelerates an existing process by adding alkaline minerals (olivine, magnesium hydroxide) that react with dissolved CO2 to form stable bicarbonate, which persists for ~10,000 years. One ton of olivine sequesters roughly 0.8-1.0 tons of CO2.[^30] Vesta's approach — dumping crushed olivine on beaches and letting waves do the grinding — is elegantly low-energy, though proving it works at scale remains the core challenge.

The difficulties are measurement (how do you verify diffuse chemistry changes across open ocean?) and ecology (what happens to marine life when you alter ocean chemistry at scale?).

### Bio / Land (Terrestrial)

| Method | Energy (kWh/tCO2) | Land (ha/tCO2/yr) | Water | Cost ($/tCO2) | Permanence | TRL |
|---|---|---|---|---|---|---|
| **Reforestation** | ~0 (solar) | 0.07-0.2[^31] | Rainfall | 5-50[^31] | Decades (fire risk) | 9 |
| **Engineered Trees** (Living Carbon) | ~0 (solar) | 0.05-0.13 (if claims hold)[^32] | Rainfall | 10-50 | Decades (fire risk) | 4-5 |
| **Bamboo Construction** | Low (processing) | 0.03-0.07[^33] | Rainfall + some irrigation | Net negative (product sales) | 50-100 yr (buildings) | 7-8 |
| **Biochar** | Net negative (produces energy)[^34] | Minimal (waste feedstock) | Low | 80-200[^34] | 100-1,000+ yr[^34] | 7-8 |
| **C4 Photosynthesis** | ~0 (solar) | ~2x better than C3 (theoretical)[^35] | ~50% less (theoretical)[^35] | Unknown | Application-dependent | 3-4 |

Biological methods have an inherent energy advantage: they run on sunlight. The constraints are land and permanence. Forests sequester carbon well until they burn, get logged, or die of disease. Biochar addresses permanence — charcoal in soil is stable for centuries to millennia[^34] — but is limited by feedstock. Global agricultural residue production is large (several billion tons/year of dry biomass), but it's distributed, bulky, and already has competing uses.

Bamboo stands out because it's one of the few CDR methods with a profitable product. Processed bamboo replaces steel and timber in construction; the carbon stays locked in the building for its lifespan. No subsidies needed. The bottleneck is building code adoption — most jurisdictions don't yet recognize bamboo as a structural material.[^33]

The C4 photosynthesis project at Oxford/[IRRI](#glossary) is a genuine moonshot. C4 plants (corn, sugarcane) are roughly twice as photosynthetically efficient as C3 plants (rice, wheat, all trees) because they've evolved a CO2-concentrating mechanism that eliminates photorespiration — a process that wastes 25-30% of the carbon C3 plants fix.[^35] C4 plants also use about 50% less water per unit of biomass.[^35] The project aims to transfer this pathway into rice (and eventually other crops and trees) by introducing ~12-15 genes and re-engineering leaf anatomy (Kranz anatomy).[^35] It's been running since ~2008, is currently in Phase IV, and faces an extraordinarily difficult biology problem: Kranz anatomy involves specialized cell types and spatial organization that hasn't been fully replicated in the lab. If it works, it roughly doubles the carbon capture efficiency of all plant-based CDR. Realistic timeline for deployment: 2035-2045 at the earliest.[^35]

### Bio / Water (Marine Biomass)

| Method | Energy (kWh/tCO2) | Footprint | Water | Cost ($/tCO2) | Permanence | TRL |
|---|---|---|---|---|---|---|
| **Kelp Forests** (Phathom, SOS Carbon) | Low | Open ocean | Seawater | 50-300[^36] | Centuries (>1000m depth)[^36] | 3-5 |
| **Iron Fertilization** (ExOIS) | Very low | [HNLC](#glossary) zones (~92M km²)[^37] | Seawater | 2-20 (theoretical)[^37] | Centuries (deep ocean)[^37] | 2-3 |
| **Microalgae Ponds** (Brilliant Planet) | Low (pumping, drying) | Coastal desert | Seawater | 50-150 (projected)[^38] | Centuries-millennia (buried in desert)[^38] | 4-5 |

This category contains some of the most promising and most uncertain methods.

**Kelp/sargassum sinking** grows macroalgae (either purpose-farmed or wild-harvested invasive sargassum) and sinks it below 1,000 meters, where decomposition is slow and the carbon is isolated from the atmosphere for centuries.[^36] SOS Carbon's approach — a device that attaches to existing fishing boats, harvests invasive sargassum, and pumps it to depth — is notable because it combines CDR with a cleanup service (sargassum is a growing ecological nuisance on Caribbean and West African beaches). The key unknowns: how much of the sunk carbon actually stays sequestered vs. getting remineralized and returning to the surface? What are the effects on deep-ocean ecosystems? Running Tide, an early pioneer in this space, shut down its ocean CDR operations[^36] — a cautionary data point about the difficulty of making open-ocean farming work reliably.

**Iron fertilization** has the most extreme numbers of any method. The stoichiometry suggests 1 ton of iron could catalyze the fixation of 13,000-130,000+ tons of CO2 (the range is wide because it depends on how completely the bloom consumes available nutrients).[^37] Over a dozen mesoscale experiments (SOFeX, LOHAFEX, IronEx, SERIES, etc.) have confirmed that adding iron to HNLC waters does trigger blooms.[^37] The problem is "export efficiency" — only about 1-10% of the carbon fixed at the surface actually sinks below 1,000 meters.[^37] The rest gets eaten, respired, or recycled back to the surface. Realistic estimates put the effective ratio closer to 1 ton iron : 1,000-10,000 tons CO2, which is still remarkable.[^37] The obstacles are ecological risk (toxic blooms, deoxygenation, nutrient robbing from downstream ecosystems), governance (a de facto moratorium under the London Protocol since 2013[^37]), and MRV (verifying what sank and stayed down in open ocean is extremely difficult). ExOIS is a scientific consortium trying to establish a responsible research framework, but large-scale experiments remain politically fraught.

**Microalgae ponds** (Brilliant Planet) take a different approach: grow algae on land, in seawater, on otherwise useless coastal desert. The algae capture CO2 via photosynthesis, are solar-dried on-site, and buried in hyper-arid desert soil where lack of moisture prevents decomposition — potentially locking carbon away for millennia.[^38] The claimed capture rate is ~30-80 tCO2/ha/year, roughly 5-10x faster than forests.[^38] The setup avoids most of the constraints that limit other methods: no freshwater (seawater only), no arable land (barren desert), no ocean ecosystem disruption, and easier [MRV](#glossary) (contained system on land). Brilliant Planet has been running a 30-hectare pilot in Morocco on the Saharan coast.[^38] The open questions are about scaling: can you build and maintain millions of hectares of ponds? How much energy does seawater pumping actually require at scale? What happens with brine discharge? Available coastal desert globally (Saharan coast, Atacama, Arabian Peninsula, Namibia, parts of Australia) is substantial, but this approach hasn't been tested beyond pilot scale.

---

## Bottleneck Analysis

For each method, we can identify the primary constraint — the thing most likely to prevent it from reaching gigaton scale — and what would need to change.

| Method | Primary Bottleneck | Secondary Bottleneck | What 1 Gt/yr Looks Like | What Needs to Happen |
|---|---|---|---|---|
| **Solid Sorbent DAC** | Energy supply | Cost ($600-1,000/t) | ~28,000 Mammoth-sized plants | 3-5x cost reduction; dedicated clean energy |
| **Liquid Solvent DAC** | Energy (900°C heat) | Natural gas dependency | ~2,000 STRATOS plants | Electrify calcination; remove fossil input |
| **Passive DAC** | Land for tray arrays | Calcination energy | Early data, unclear | Faster absorption; more efficient regeneration |
| **Electrochemical DAC** | Technology maturity | Electrode durability | Not yet determined | Lab to commercial; electrode lifespan >10k cycles |
| **Direct Ocean Capture** | Technology maturity | Membrane lifespan | TBD | Membranes that survive seawater for years |
| **[OAE](#glossary)** | MRV (proving it works) | Mining scale | ~10-12 Gt of mineral/yr | Ocean chemistry monitoring; 10x mining scale-up |
| **Reforestation** | Land availability | Permanence (fire) | ~500 million hectares | Fire management; governance; patience (30+ yrs) |
| **Engineered Trees** | Regulatory (GMO) | Scientific validation | Same land as reforestation | GMO approval; long-term field data |
| **Bamboo Construction** | Building code adoption | Tropical land | ~30-70 million hectares | Code recognition; processing infrastructure |
| **Biochar** | Feedstock supply | Logistics | ~3-5 Gt dry biomass/yr | Distributed pyrolysis; more feedstock sources |
| **C4 Photosynthesis** | Fundamental biology | Regulation + time | Decades away | Engineer Kranz anatomy in C3 plants |
| **Kelp Forests** | Ocean farming durability | MRV | ~7+ million hectares ocean | Storm-resistant designs; deep-ocean tracking |
| **Iron Fertilization** | Ecological risk + governance | MRV (export efficiency) | Iron across millions of km² | Controlled safety trials; international agreement |
| **Microalgae Ponds** | Scaling infrastructure | Pumping energy | Millions of hectares coastal desert | Cheaper ponds; gravity-fed seawater systems |

### How crazy is 1 Gt/yr, actually?

The bottleneck table says "what needs to happen." This section tries to give a feel for _how much_ needs to happen — what 1 GtCO2/year of removal actually demands for each method, compared to what exists today.

**Solid Sorbent DAC:** Current capacity is ~44,000 tCO2/yr (Climeworks' Orca + Mammoth plants). 1 Gt would require **~1,000 megaton-scale plants**, consuming **250-750 TWh of electricity** plus **1,750 TWh of low-grade heat** per year — roughly 2-7% of global electricity generation. Construction would require 50-150 Mt of steel and concrete (2-8% of one year's global production), and the amine sorbents that do the actual capturing would need **5-20 Mt/yr** of replacement material, against current production of less than 1 Mt/yr. Multiplication factor from today: **~22,700x**.

**Liquid Solvent DAC:** 1 Gt means **~2,000 STRATOS-scale chemical plants** (each 500 kt/yr). The 900°C calciners would burn **80-135 billion m³ of natural gas per year** (2-3% of global production) — and for every ton of CO2 captured from air, the gas combustion produces another ~0.3-0.5 tons that must also be captured. Electrifying the calciner would eliminate this paradox but hasn't been demonstrated at scale. KOH make-up alone would consume **25-100% of current global production**.[^26]

**Passive DAC:** Heirloom's current capacity is ~1,000 tCO2/yr. 1 Gt requires **10,000-30,000 km² of tray arrays** (Belgium to Massachusetts) and **0.5-2 Gt/yr of limestone** — 11-44% of current global quarrying. The electricity for calcination alone would be **1,000-1,800 TWh/yr** (3.5-6.5% of global generation). Multiplication factor: **~1,000,000x**.

**Electrochemical DAC:** Currently at lab scale (~kg/day). The energy numbers are the best of any DAC method — **300-800 TWh/yr** for 1 Gt, or 1-3% of global electricity — but the technology needs to go from benchtop to 1,000 commercial facilities. Bipolar membrane production would need to scale **100-1,000x**. If it works, it's the most promising DAC path. If electrode durability can't be solved, it's a dead end.

**Ocean Alkalinity Enhancement (olivine route):** 1 Gt of OAE requires mining **1.0-1.3 Gt of olivine per year** — building a new mining industry roughly half the size of global iron ore. That olivine would need to be crushed and distributed via **1,000-3,000 bulk carrier ships** (8-25% of the global fleet) or spread across **50,000-200,000 km of coastline** (3-12% of global coastline). One wrinkle: olivine contains nickel, and the weathering process would release **2-4 Mt of nickel per year** into the ocean — roughly equal to total global nickel production. The ecological implications of that are unknown.[^30]

**Direct Ocean Capture:** Captura's pilot captures ~100 tCO2/yr. 1 Gt needs **~1,000 coastal plants**, **500-2,000 TWh/yr of energy**, and a **25x scale-up of global CO2 geological storage** (from 0.04 Gt/yr to 1 Gt/yr). Bipolar membrane manufacturing would need to scale 100-1,000x, same as electrochemical DAC. Multiplication factor from today: **~10,000,000x**.

**Reforestation:** At an average ~10 tCO2/ha/yr (blending tropical and temperate), 1 Gt requires **~100 million hectares** — roughly the area of Egypt. Current net global reforestation is ~0.5 Mha/yr, so the planting rate would need to increase **20-40x** and sustain that for 5-10 years. Then you wait 15-30 years for the trees to reach full sequestration rates. Global nursery capacity would need to go from ~10-15 billion seedlings/yr to **50-100+ billion/yr**. Total restorable land (~2 billion ha) isn't the hard limit; time is.

**Bamboo Construction:** This is one of the more plausible paths. Current bamboo area is ~37 Mha; 1 Gt in durable products requires **40-83 Mha** (only 1.1-2.2x current area — bamboo grows fast and regrows from roots). The real bottleneck: the global construction market would need to go from **<0.1% bamboo** to **10-15% bamboo** — a 100-150x increase in market share. That means **600-1,200 large processing facilities** (vs. ~200-500 today) and building codes that recognize bamboo as structural material. Cost per tCO2 is **negative** (-$85 to -$410) because you're selling a building product. Of all methods reviewed, this is the only one that's profitable without subsidies.[^33]

**Biochar:** Current production removes ~0.3-0.5 MtCO2/yr. 1 Gt requires **~1 Gt/yr of dry biomass feedstock** (20-40% of global sustainable waste biomass supply) processed through **~20,000 large pyrolysis facilities** or **~600,000 modular containerized units** distributed at farms and sawmills within a 15-40 km collection radius. The good news: the process is net energy-positive (produces 200-700 kWh per tCO2 removed), permanence is 500-5,000+ years, and projected cost at scale is $20-100/tCO2. The constraint is purely logistical — getting billions of tons of bulky agricultural residue to pyrolysis units.[^34]

**Kelp Forests:** 1 Gt of kelp-based CDR requires farming **5-20 million km² of ocean** (1.4-5.5% of total ocean surface, or roughly India-to-Russia in area), producing **~900 Mt/yr of dry biomass** — a **150x increase** over all current global seaweed production. The farms would consume **13-27 Mt of nitrogen per year** (12-25% of global synthetic N production) and require a fleet of **10,000-50,000 harvesting vessels**. Net CDR is only 25-50% of gross fixation due to grazing, DOC release, and remineralization losses. Sargassum harvesting alone caps out at ~1.5-7 MtCO2/yr — useful, but two orders of magnitude short of a gigaton.[^36]

**Iron Fertilization:** The materials are trivial — **0.1-1 Mt of iron per year**, delivered by **100-500 ships** (small vs. the global fleet of ~60,000). The cost could be as low as **$5-50/tCO2**. The problem isn't logistics; it's that only 1-10% of the carbon fixed at the surface actually sinks below 1,000 meters, and the "nutrient robbing" effect (stealing nutrients from downstream ecosystems) may offset 70-90% of the apparent benefit. Models suggest the hard ceiling is about **0.5-2 GtCO2/yr** even with unlimited iron — and the London Protocol has effectively blocked large-scale experiments since 2013.[^37]

**Microalgae Ponds:** Brilliant Planet's concept needs **12.5-33 million hectares of coastal desert** to reach 1 Gt — and total suitable coastal desert globally is only about **20-45 million hectares**. That means 1 Gt would consume **28-100% of all suitable land on Earth** for this method. Each facility (~1,000 ha) requires massive seawater pumping infrastructure; at scale, nitrogen supplementation alone would be **15-30 Mt N/yr** (10-20% of global fertilizer production). The method has excellent permanence (desert burial, 1,000-10,000+ years) and good MRV (contained land-based system), but it's hard-capped by geography at roughly **1-2.25 GtCO2/yr theoretical maximum**.[^38]

### Patterns

A few things stand out from these numbers:

- **Mechanical methods** are generally bottlenecked by **energy and cost**. The technology works; powering and paying for it at scale is the problem. Every DAC variant at 1 Gt requires hundreds to thousands of TWh/yr of clean energy — and the thermodynamic floor guarantees this never goes away entirely.
- **Biological land methods** are bottlenecked by **land and permanence**. Plants capture carbon well, but forests burn, and there's only so much land. Bamboo and biochar partly solve the permanence problem by locking carbon into buildings and soil.
- **Ocean methods** are bottlenecked by **measurement and governance**. In many cases the chemistry and biology are sound, but we can't yet reliably verify results, and the regulatory frameworks for modifying ocean chemistry at scale don't exist.
- **Nearly every method at 1 Gt consumes a non-trivial fraction of some global resource** — electricity, land, minerals, fertilizer, coastline, shipping capacity. This is why no single method can do it alone, and why a portfolio approach isn't just convenient, it's physically necessary.

This suggests that effective research investment looks different for each category: cheaper energy and better materials for machines, permanence solutions for biology, and monitoring/verification technology for the ocean.

---

## A Portfolio, Not a Silver Bullet

No single method can reach 10-20 GtCO2/year. The constraints are too varied. The realistic path is a portfolio — multiple methods in parallel, each contributing in proportion to what its constraints allow.

Here's one rough allocation to illustrate how the numbers might add up (this is a framework, not a prediction):

| Category | Plausible 2050 Range | Limiting Factor |
|---|---|---|
| Reforestation + soil carbon | 2-4 GtCO2/year | Land; already underway; permanence caps the ceiling |
| Biochar | 1-2 GtCO2/year | Feedstock; but proven and profitable |
| Ocean Alkalinity Enhancement | 1-3 GtCO2/year | Huge theoretical potential; MRV and governance lag behind |
| Direct Air Capture (all types) | 1-3 GtCO2/year | Energy; cost needs to fall 5-10x |
| Bamboo / timber construction | 0.5-1 GtCO2/year | Market adoption; building codes |
| Marine biomass (kelp, algae ponds) | 0.5-2 GtCO2/year | Early-stage; durability and MRV |
| BECCS (bioenergy + CCS) | 1-2 GtCO2/year | Biomass; competes with biochar for feedstock |
| Other (DOC, iron fertilization, etc.) | 0.5-1 GtCO2/year | High uncertainty and risk; high potential |
| **Total** | **~8-18 GtCO2/year** | |

Even under optimistic assumptions across every category, hitting 20 Gt/year by 2050 is very difficult. This is a useful reminder that emissions reduction remains the most important lever. Every ton not emitted is a ton that doesn't need to be captured.

---

## Where Research Might Help Most

Based on the bottleneck analysis, here's where additional funding or effort seems most likely to increase total CDR capacity — organized roughly by how soon results could matter.

### Near-term, high leverage

1. **Electrochemical DAC scale-up.** If the thermal bypass works at industrial scale, it cuts DAC energy costs by 3-4x.[^28] That's probably the single highest-leverage engineering problem in the CDR space right now. Verdox, Mission Zero, and RepAir are the main players. The key technical question is electrode durability — current lab prototypes degrade faster than economics require.

2. **OAE measurement and verification.** Ocean alkalinity enhancement has the best cost profile ($50-200/ton)[^30] and essentially unlimited storage capacity (the ocean holds ~38,000 Gt of dissolved inorganic carbon already[^30]). What's missing is the ability to reliably measure how much carbon was actually sequestered after minerals are added. Investment in ocean chemistry monitoring — autonomous sensors, satellite-based alkalinity tracking, tracer studies — would directly unlock deployment.

3. **Biochar distributed infrastructure.** Biochar is proven, permanent, generates energy as a byproduct, and improves soil.[^34] It's limited mainly by the logistics of getting biomass waste to pyrolysis facilities. Small-scale, containerized pyrolysis units deployable at farms, sawmills, and waste processing sites could tap into distributed feedstock that's currently uneconomical to transport.

### Medium-term, high leverage

4. **Next-generation sorbent materials.** Solid sorbent DAC costs are dominated by sorbent replacement cycles and regeneration energy.[^23] A cheaper sorbent that lasts longer and releases CO2 at lower temperatures shifts the entire cost curve. This is a materials science problem with a clear target.

5. **Bamboo and timber building codes.** More a policy problem than a technology problem. Bamboo sequesters carbon faster than any tree, produces structural material that can replace steel, and regrows from its roots.[^33] The bottleneck is that most building codes don't recognize it. Funding for testing, certification, and code development could unlock a CDR pathway that pays for itself.

6. **Forest permanence solutions.** Reforestation is cheap and well-understood, but fire risk devalues forest carbon credits and caps the effective permanence. Integrating forest management with biochar production (converting undergrowth and debris to biochar rather than letting it become fuel) could improve both the fire resilience and the permanence of forest carbon.

### Longer-term, potentially transformative

7. **C4 photosynthesis engineering.** If the C4 Rice Project succeeds and the pathway transfers to trees, it roughly doubles the carbon capture rate of plant-based CDR.[^35] The core challenge — engineering Kranz anatomy — is one of the harder unsolved problems in plant biology. The [RIPE](#glossary) Project at University of Illinois is tackling related photosynthetic efficiency problems from a different angle. Timeline: 10-20 years if it works.[^35]

8. **Controlled iron fertilization trials.** Iron fertilization has the most extreme leverage ratio of any CDR method and potentially the lowest cost.[^37] The ecological risks are real but poorly characterized because responsible large-scale experiments have been effectively blocked since the 2012 Haida Gwaii controversy and the 2013 London Protocol amendment.[^37] Funding for controlled, well-monitored, transparent ocean trials — with clear ecological baselines and stopping criteria — would provide data that's currently missing from the CDR portfolio.

9. **Microalgae desert farms at scale.** Brilliant Planet's concept sidesteps most of the constraints that limit other biological methods: no freshwater, no arable land, no ocean ecosystem disruption, relatively straightforward MRV.[^38] The question is whether it works beyond pilot scale. Morocco results are encouraging but limited. Demonstrating a 1,000+ hectare facility with reliable cost data would significantly de-risk the approach.

---

## Method Deep Dives

Each method has a detailed data file covering physical constraints, resource requirements, throughput metrics, storage, economics, company profiles, and scaling analysis:

### Machine / Land (Direct Air Capture)
- [Solid Sorbent DAC](methods/solid_sorbent_dac.md) — Climeworks (Orca, Mammoth); temperature-vacuum swing adsorption
- [Liquid Solvent DAC](methods/liquid_solvent_dac.md) — Carbon Engineering / 1PointFive (Occidental); KOH solution + calcination
- [Passive DAC](methods/passive_dac.md) — Heirloom Carbon; limestone tray weathering, no fans
- [Electrochemical DAC](methods/electrochemical_dac.md) — Verdox, Mission Zero, RepAir; electricity replaces heat

### Machine / Water (Marine CDR)
- [Direct Ocean Capture](methods/direct_ocean_capture.md) — Captura (Caltech spinoff); membrane-based CO2 stripping from seawater
- [Ocean Alkalinity Enhancement](methods/ocean_alkalinity_enhancement.md) — Vesta, Ebb Carbon, Limenet; mineral dissolution

### Bio / Land (Terrestrial)
- [Reforestation](methods/reforestation.md) — Drone planting (Flash Forest), native species restoration
- [Engineered Trees](methods/engineered_trees.md) — Living Carbon; photorespiration bypass via gene editing
- [Bamboo Construction](methods/bamboo_construction.md) — BamCore, ReNuTeq, dasso; structural bamboo replacing steel
- [Biochar](methods/biochar.md) — Exomad Green, Carboneers, Wakefield Biochar; pyrolysis of agricultural waste
- [C4 Photosynthesis](methods/c4_photosynthesis.md) — Oxford/IRRI C4 Rice Project; rewiring photosynthesis (research stage)

### Bio / Water (Marine Biomass)
- [Kelp Forests](methods/kelp_forests.md) — Phathom, SOS Carbon; macroalgae farming and deep-ocean sinking
- [Iron Fertilization](methods/iron_fertilization.md) — ExOIS; phytoplankton bloom stimulation in HNLC regions
- [Microalgae Ponds](methods/microalgae_ponds.md) — Brilliant Planet; land-based saltwater algae cultivation and burial

---

## Summary

A few things that seem clear from the data:

1. **The gap is large.** Current CDR capacity needs to grow 250-500x.[^3] No single method can close it alone.

2. **Energy is the limiting factor for machines.** 10 GtCO2 of DAC would consume more electricity than the world currently generates.[^15] Cheap solar helps, but the scale of new generation required is still immense.

3. **Land is the limiting factor for biology.** 5 Gt/year of reforestation-based removal would require planting an area the size of the Amazon. Every hectare has competing uses.

4. **The ocean is underexplored.** Ocean methods (OAE, kelp, iron fertilization, DOC) benefit from seawater's ~140x CO2 concentration advantage and the ocean's massive natural carbon cycling. The barriers are governance and measurement, not physics or chemistry.

5. **Cost trajectories matter more than current costs.** DAC at $600/ton is not viable at scale. DAC at $100/ton changes the picture significantly. The learning rate — how fast costs fall per doubling of deployment — is the most important variable for long-term feasibility.

6. **Permanence varies enormously.** Basalt mineralization: 10,000+ years.[^25] Biochar: centuries to millennia.[^34] Buried desert algae: potentially millennia.[^38] Forest: until the next fire. These differences should be reflected in how removal is valued.

7. **Methods that generate revenue have an easier path to scale.** Bamboo construction, biochar (energy + soil amendment + credits), and microalgae (potential byproducts) don't depend entirely on carbon credit markets or government subsidies. That makes them more robust as long-term bets.

---

## Glossary

| Term | Definition |
|---|---|
| **BECCS** | Bioenergy with Carbon Capture and Storage — burning biomass for energy while capturing and storing the CO2 released |
| **CAPEX** | Capital expenditure — the upfront cost to build a facility or unit |
| **CDR** | Carbon dioxide removal — any process that pulls CO2 out of the atmosphere and stores it durably |
| **DAC** | Direct air capture — using machines to filter CO2 directly from ambient air |
| **DOC** | Direct ocean capture — extracting dissolved CO2 from seawater rather than air |
| **EJ** | Exajoule — 10¹⁸ joules; a unit of energy. Global primary energy consumption is ~620 EJ/year |
| **GtCO2** | Gigatons of CO2 — one billion metric tons. Global emissions are ~42 GtCO2/year |
| **GW** | Gigawatt — one billion watts of power capacity |
| **HNLC** | High-nutrient, low-chlorophyll — ocean regions with abundant nutrients but little phytoplankton growth, typically due to iron deficiency. Covers ~92 million km² |
| **IPCC** | Intergovernmental Panel on Climate Change — the UN body that synthesizes climate science |
| **IRRI** | International Rice Research Institute — co-lead of the C4 Rice Project, based in the Philippines |
| **LCOE** | Levelized cost of energy — the average cost per unit of electricity over a generator's lifetime, in $/MWh |
| **MRV** | Measurement, reporting, and verification — the process of proving that carbon was actually removed and stayed removed |
| **NAS / NASEM** | National Academies of Sciences, Engineering, and Medicine (US) |
| **OAE** | Ocean alkalinity enhancement — adding alkaline minerals to the ocean to accelerate natural CO2 sequestration as bicarbonate |
| **OIF** | Ocean iron fertilization — adding iron to nutrient-rich ocean regions to stimulate phytoplankton blooms that capture CO2 |
| **OPEX** | Operating expenditure — the ongoing cost to run a facility per year |
| **ppm** | Parts per million — the standard measure of atmospheric CO2 concentration. Pre-industrial: 280 ppm; current: ~426 ppm |
| **RIPE** | Realizing Increased Photosynthetic Efficiency — a research project at the University of Illinois aimed at improving crop photosynthesis |
| **TRL** | Technology readiness level — a 1-9 scale measuring how close a technology is to commercial deployment. TRL 1 = basic research; TRL 9 = proven at scale |
| **TWh** | Terawatt-hour — one billion kilowatt-hours. Global electricity generation is ~30,000 TWh/year |

---

## Data Sources

[^1]: Global Carbon Budget 2025. Fossil fuel CO2 emissions: ~38.1 GtCO2; land-use change: ~4.1 GtCO2. [Global Carbon Project](https://globalcarbonbudget.org/), [ESSD](https://essd.copernicus.org/articles/17/965/2025/).
[^2]: IPCC AR6 WG III, Chapter 12 and CDR Factsheet. CDR requirements range from 6-17 GtCO2/yr depending on pathway and overshoot scenario. [IPCC AR6 WG III](https://www.ipcc.ch/report/ar6/wg3/).
[^3]: State of CDR 2024 (IIASA/Oxford). Total CDR ~41 MtCO2/yr; 2030 alignment need: 1-1.5 GtCO2/yr. [stateofcdr.org](https://www.stateofcdr.org/).
[^4]: Our World in Data, cumulative CO2 emissions since 1850: ~2,650 GtCO2. Airborne fraction ~40%. [Our World in Data](https://ourworldindata.org/grapher/cumulative-co-emissions).
[^5]: NOAA Climate.gov. 2024 annual average: 422.7 ppm; 2025 projected ~425.7 ppm. [NOAA](https://www.climate.gov/news-features/understanding-climate/climate-change-atmospheric-carbon-dioxide).
[^6]: Global Carbon Budget 2025. Remaining budget for 1.5°C at 50%: ~170 GtCO2; at 83%: ~30 GtCO2. [Global Carbon Project](https://globalcarbonbudget.org/).
[^7]: Hansen et al. (2008), "Target atmospheric CO2: Where should humanity aim?" — proposed 350 ppm as safe limit. [Open Atmos. Sci. J.](https://doi.org/10.2174/1874282300802010217).
[^8]: National Academies of Sciences (2019), "Negative Emissions Technologies and Reliable Sequestration." Recommended 10 GtCO2/yr by 2050, 20 GtCO2/yr by 2100. [NAP](https://www.nap.edu/catalog/25259/).
[^9]: CDR.fyi 2024 Year in Review. Engineered CDR annual capacity ~12 MtCO2/yr; delivered volume dominated by biochar (86%). [CDR.fyi](https://www.cdr.fyi/blog/2024-year-in-review).
[^10]: Ember Global Electricity Review 2025. Global generation exceeded 30,000 TWh for the first time in 2024. [Ember](https://ember-energy.org/latest-insights/global-electricity-review-2025/).
[^11]: Energy Institute Statistical Review of World Energy 2025. Primary energy consumption ~620 EJ. [Energy Institute](https://www.energyinst.org/statistical-review).
[^12]: IRENA Renewable Capacity Statistics 2025. 582 GW added in 2024 (452 GW solar, 114 GW wind). [CarbonCredits.com](https://carboncredits.com/solar-surge-and-wind-wins-2024s-renewable-energy-boom-breaks-all-record/).
[^13]: IRENA Renewable Power Generation Costs in 2024. Utility-scale solar LCOE: $28-37/MWh in best markets. [IRENA](https://www.irena.org/-/media/Files/IRENA/Agency/Publication/2025/Jul/IRENA_TEC_RPGC_in_2024_Summary_2025.pdf).
[^14]: IAEA Nuclear Energy Projections 2025. 417 operational reactors, 377 GW; 63 under construction. [IAEA](https://www.iaea.org/newscenter/pressreleases/iaea-raises-nuclear-power-projections-for-fifth-consecutive-year).
[^15]: Nature Communications (2020), Chatterjee & Huang. DAC energy intensity: 1,100-2,550 kWh/tCO2; water: 1-7 t/tCO2. At 30 GtCO2/yr, DAC would require 46-191% of global energy. [Nature Comms](https://www.nature.com/articles/s41467-020-17203-7).
[^16]: UNCCD Global Land Outlook 2. ~40% of Earth's land degraded (~6 billion ha); ~2 billion ha with restoration potential. [UNCCD](https://www.unccd.int/news-stories/press-releases/chronic-land-degradation-un-offers-stark-warnings-and-practical).
[^17]: FAO. Current arable land in use: ~1.5 billion hectares. [Carbon Brief / UN](https://www.carbonbrief.org/un-land-report-five-key-takeaways-for-climate-change-food-systems-and-nature-loss/).
[^18]: Climeworks disclosures. Mammoth plant: ~0.17-0.22 m²/(tCO2/yr); IEA/literature range: 0.4-1.0 m²/(tCO2/yr) for equipment only. See [methods/solid_sorbent_dac.md](methods/solid_sorbent_dac.md).
[^19]: FAO AQUASTAT. Total renewable freshwater: ~43,000 km³/yr; withdrawals: ~3,880 km³/yr; agriculture: ~70%. [FAO](https://www.fao.org/aquastat/en/overview/methodology/water-use/).
[^20]: Rockström et al. (2009), planetary boundary for freshwater use: ~4,000 km³/yr. Surplus vs. current use: ~1,400 km³/yr.
[^21]: USGS Mineral Commodity Summaries 2025. [USGS](https://pubs.usgs.gov/publication/mcs2025).
[^22]: Nature Communications (2020). 1 GtCO2/yr DAC requires 17-36 Mt of steel, concrete, copper, aluminum. [Nature Comms](https://www.nature.com/articles/s41467-020-17203-7).
[^23]: Climeworks / IEA DAC reports. Solid sorbent energy: 1,500-2,500 kWh/tCO2 (thermal + electric); water: 1-2 t/tCO2. See [methods/solid_sorbent_dac.md](methods/solid_sorbent_dac.md).
[^24]: Climeworks pricing. Current contracts: $600-1,000+/tCO2. IEA projects $125-335/tCO2 at scale. [IEA DAC](https://www.iea.org/energy-system/carbon-capture-utilisation-and-storage/direct-air-capture).
[^25]: Carbfix / Matter et al. (2016). CO2 injected into basalt mineralizes to carbonate within 2 years; stable for 10,000+ years. [Science](https://doi.org/10.1126/science.aad8132).
[^26]: Keith et al. (2018), "A Process for Capturing CO2 from the Atmosphere," Joule. Energy: 1,100-1,800 kWh/tCO2; water: 4.7 t/tCO2; cost: $94-232/tCO2 at scale (claimed). STRATOS plant: 500 ktCO2/yr on ~100 acres. See [methods/liquid_solvent_dac.md](methods/liquid_solvent_dac.md).
[^27]: Heirloom Carbon disclosures. Passive limestone carbonation eliminates fan energy; calcination at ~900°C still required. Target cost: $250-500/tCO2. See [methods/passive_dac.md](methods/passive_dac.md).
[^28]: Voskian & Hatton (2019), "Faradaic electro-swing reactive adsorption," Energy & Environmental Science. Theoretical energy: 400-1,000 kWh/tCO2; potential 3-4x improvement over thermal DAC. See [methods/electrochemical_dac.md](methods/electrochemical_dac.md).
[^29]: Captura Corp / Caltech. Electrochemical ocean CO2 removal. Projected cost: $300-500/tCO2 at scale. See [methods/direct_ocean_capture.md](methods/direct_ocean_capture.md).
[^30]: NASEM Ocean CDR Report (2022); Vesta, Ebb Carbon, Limenet disclosures. Olivine yield: ~0.8-1.0 tCO2/t olivine; ocean holds ~38,000 Gt dissolved inorganic carbon; natural weathering sequesters ~0.3 GtCO2/yr. Projected cost: $50-200/tCO2. See [methods/ocean_alkalinity_enhancement.md](methods/ocean_alkalinity_enhancement.md).
[^31]: IPCC SRCCL; Bastin et al. (2019). Forest sequestration: ~5-15 tCO2/ha/yr for mature forest. Cost: $5-50/tCO2. See [methods/reforestation.md](methods/reforestation.md).
[^32]: Living Carbon claims 53% more biomass via photorespiration bypass. Peer review status uncertain. See [methods/engineered_trees.md](methods/engineered_trees.md).
[^33]: BamCore, dasso, ReNüTeq disclosures. Bamboo sequesters ~15-35 tCO2/ha/yr; building code recognition limited to a few jurisdictions. See [methods/bamboo_construction.md](methods/bamboo_construction.md).
[^34]: IPCC SRCCL; Fuss et al. (2018); NAS (2019). Biochar permanence: 100-1,000+ years; net energy positive via pyrolysis co-generation; cost: $80-200/tCO2. See [methods/biochar.md](methods/biochar.md).
[^35]: C4 Rice Consortium (Oxford/IRRI). C3 vs C4 efficiency: ~3% vs ~6% solar conversion; photorespiration wastes 25-30% of C3 fixed carbon; C4 uses ~50% less water; ~12-15 genes needed; Kranz anatomy is central challenge. See [methods/c4_photosynthesis.md](methods/c4_photosynthesis.md).
[^36]: NASEM Ocean CDR Report (2022); Phathom, SOS Carbon disclosures. Sequestration requires sinking below ~1,000m. Running Tide ceased ocean CDR operations. See [methods/kelp_forests.md](methods/kelp_forests.md).
[^37]: Martin (1988); Boyd et al. (2007) review of 13+ mesoscale experiments; ExOIS consortium. Theoretical iron:CO2 ratio up to 1:130,000 (molar); realistic export-adjusted ratio ~1:1,000-10,000. Export efficiency: 1-10% of surface production reaches >1,000m. London Protocol amendment 2013. See [methods/iron_fertilization.md](methods/iron_fertilization.md).
[^38]: Brilliant Planet disclosures. 30-hectare Morocco pilot; claimed 30-80 tCO2/ha/yr; burial in hyper-arid desert for millennial permanence. See [methods/microalgae_ponds.md](methods/microalgae_ponds.md).

[^39]: House et al. (2011), "Economic and energetic analysis of capturing CO2 from ambient air," PNAS. Thermodynamic minimum for CO2 separation from 400 ppm air: ~20 kJ/mol (~125 kWh/tCO2). With compression to 150 bar: ~30.6 kJ/mol (~191 kWh/tCO2). Current DAC operates at 4-7% of thermodynamic efficiency. [PNAS](https://doi.org/10.1073/pnas.1012253108).
[^40]: Socolow et al. (2011), "Direct Air Capture of CO2 with Chemicals," APS Physics. Engineering floor for practical DAC: ~500-1,000 kWh/tCO2, consistent with typical industrial separation efficiencies of 5-20% of thermodynamic minimum. [APS](https://www.aps.org/policy/reports/assessments/direct-air-capture).

---

*This is a living document. Method files contain more detailed data, sources, and scaling analyses. Corrections and additional data are welcome.*
