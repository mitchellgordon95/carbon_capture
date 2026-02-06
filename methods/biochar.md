# Biochar: Comprehensive Carbon Capture Assessment

> **Method Summary:** Pyrolysis of agricultural waste biomass (crop residues, manure, forestry waste) under oxygen-free conditions converts organic carbon into a highly stable, charcoal-like material (biochar). When buried in soil, this carbon persists for centuries to millennia. The key economic enabler --- "The Double Dip" --- is that pyrolysis generates excess heat, which can produce electricity, creating dual revenue from energy sales and carbon credits.

> **Data Sources:** This document synthesizes data from IPCC AR6 and SRCCL reports, peer-reviewed literature (Nature, Science, GCB Bioenergy, Biochar journal), IBI and EBC certification bodies, company disclosures, the National Academies of Sciences (2019) "Negative Emissions Technologies" report, Fuss et al. (2018), Smith (2016), and industry reports from the International Biochar Initiative. Where live web data was unavailable, figures are drawn from published literature and company statements available through early 2025. All figures should be cross-checked against the latest company disclosures.

---

## Table of Contents

1. [How It Works: The Process](#1-how-it-works-the-process)
2. [Physical Constraints](#2-physical-constraints)
3. [Resource Constraints](#3-resource-constraints)
4. [Throughput Metrics](#4-throughput-metrics)
5. [End Game: Storage](#5-end-game-storage)
6. [Economic Friction](#6-economic-friction)
7. [Key Players: Exomad Green, Carboneers, Wakefield Biochar](#7-key-players)
8. [Additional Feasibility Data](#8-additional-feasibility-data)
9. [10 Gt/yr Scale Feasibility Assessment](#9-10-gtyr-scale-feasibility-assessment)
10. [Summary Tables](#10-summary-tables)
11. [Sources & References](#11-sources--references)

---

## 1. How It Works: The Process

### 1.1 Pyrolysis Fundamentals

Pyrolysis is the thermochemical decomposition of organic material at elevated temperatures (300--700 degC) in the absence (or near-absence) of oxygen. The process converts biomass into three products:

| Product | Yield (% by mass, dry basis) | Description |
|---------|------------------------------|-------------|
| **Biochar** (solid) | 25--40% | Stable aromatic carbon structure |
| **Bio-oil** (liquid) | 15--30% | Condensable vapors; can be upgraded to fuel |
| **Syngas** (gas) | 20--35% | H2, CO, CH4, CO2; combustible |

The exact yields depend on pyrolysis temperature, heating rate, and feedstock:

- **Slow pyrolysis** (300--600 degC, hours): Maximizes biochar yield (30--40% by mass). Preferred for carbon sequestration.
- **Fast pyrolysis** (400--600 degC, seconds): Maximizes bio-oil (up to 75%). Less biochar (~15--25%).
- **Gasification** (>700 degC): Maximizes syngas. Minimal biochar (~5--10%).

### 1.2 "The Double Dip" --- Energy + Carbon Credits

The process is **net energy positive** for slow pyrolysis:

1. **Energy Generation:** Syngas and bio-oil from pyrolysis are combusted to produce heat and/or electricity. A typical slow-pyrolysis unit processing 1 tonne of dry biomass per hour can generate 1--3 MWh of excess thermal energy or 0.3--1.0 MWh of electricity (after powering the pyrolysis process itself).
2. **Carbon Credits:** Each tonne of biochar contains ~2.5--3.0 tonnes of CO2-equivalent in stable carbon. Carbon credit registries (Puro.earth, Verra, Gold Standard) issue credits for verified permanent removal.

**Revenue Stack:**
- Electricity sales (or heat offtake)
- Carbon credit sales ($100--250/tCO2 on voluntary markets, 2024)
- Biochar product sales ($200--1,500/tonne depending on grade and market)

This "triple dip" (energy + credits + product) is what makes biochar economically distinctive among CDR approaches.

---

## 2. Physical Constraints

### 2.1 Land Footprint: Facility Size

| Metric | Value | Source |
|--------|-------|--------|
| Small modular unit (containerized) | ~40 ft container, 1--5 tpd feedstock | Multiple vendors (Pyreg, NetZero, Carboneers) |
| Medium facility (1,000--5,000 tCO2/yr) | 0.5--2 hectares (~1--5 acres) | Industry estimates |
| Large facility (10,000--50,000 tCO2/yr) | 2--10 hectares (~5--25 acres) | Analogous to biomass power plants |
| Facility footprint per tCO2/yr removed | ~0.5--2 m^2 per tCO2/yr | Derived from above |

**Context:** A facility removing 10,000 tCO2/yr needs roughly 2--5 hectares of land for the plant itself (pyrolysis reactors, feedstock storage, biochar storage, cooling/handling). This is extremely compact compared to DAC facilities.

### 2.2 Feedstock Sourcing Area

The dominant land constraint is not the facility but the **feedstock collection radius:**

| Feedstock Type | Yield (dry tonnes/ha/yr) | Area to supply 10,000 tCO2/yr facility | Collection Radius (assuming 20% collection rate) |
|---------------|--------------------------|----------------------------------------|--------------------------------------------------|
| Corn stover | 3--5 dt/ha | ~10,000--15,000 ha feedstock area | ~15--25 km radius |
| Wheat straw | 2--4 dt/ha | ~12,000--20,000 ha | ~20--30 km |
| Rice husks | 1.5--3 dt/ha | ~15,000--25,000 ha | ~25--35 km |
| Forestry residues | 1--3 dt/ha/yr | ~15,000--30,000 ha | ~25--40 km |
| Manure (dairy, 500 head) | ~3,000 dt/yr per operation | ~10--15 large operations | Varies |

**Key calculation:** To remove 10,000 tCO2/yr requires ~8,000--12,000 dry tonnes of feedstock per year (at ~0.9--1.2 tCO2 sequestered per dry tonne of feedstock). At typical agricultural residue yields with sustainable removal rates (30--50% of residues), this requires sourcing from roughly 10,000--30,000 hectares of cropland, implying a collection radius of 15--40 km.

### 2.3 Location Dependency

**Optimal siting criteria:**

1. **Proximity to feedstock:** Transport costs dominate OPEX. Ideal: <50 km collection radius. Beyond 100 km, feedstock transport costs and emissions erode the carbon math.
2. **Proximity to soil application sites:** Biochar is heavy (bulk density 200--400 kg/m^3). Spreading areas should ideally be within 50--100 km.
3. **Grid connection:** If selling electricity, grid access matters. Off-grid units can still use heat.
4. **Water access:** Minimal but needed for dust suppression, cooling, and quenching.
5. **Agricultural regions preferred:** Co-location with farming reduces both feedstock transport and biochar distribution costs.

**Geographic sweet spots:**
- U.S. Midwest (corn belt --- massive stover availability)
- Brazil (sugarcane bagasse, coffee husks)
- India (rice husks, coconut shells, crop residues)
- Sub-Saharan Africa (agricultural residues, charcoal production areas)
- Southeast Asia (rice husks, palm oil waste)
- Northern Europe (forestry residues) --- where Carboneers and others operate

---

## 3. Resource Constraints

### 3.1 Energy Intensity

Biochar pyrolysis is **net energy positive** --- one of its most important differentiators from other CDR methods.

| Parameter | Value | Notes |
|-----------|-------|-------|
| Energy required to initiate/sustain pyrolysis | 1.0--2.5 GJ/t dry biomass | Depends on moisture content |
| Energy produced by syngas + bio-oil combustion | 3--8 GJ/t dry biomass | Slow pyrolysis |
| **Net energy output** | **1--5 GJ/t dry biomass** | After self-heating |
| Net electricity generation potential | 200--800 kWh/t dry biomass | With ORC or steam turbine |
| **Net energy per tCO2 sequestered** | **+200 to +700 kWh/tCO2** | NET POSITIVE (produces energy) |

**Comparison to other CDR methods:**

| Method | Energy per tCO2 | Direction |
|--------|-----------------|-----------|
| **Biochar** | 200--700 kWh/tCO2 | **Produces** energy |
| Direct Air Capture (DAC) | 1,500--2,500 kWh/tCO2 | Consumes energy |
| BECCS | ~200--400 kWh/tCO2 | Produces energy (but less net) |
| Enhanced weathering | 50--200 kWh/tCO2 | Consumes energy (grinding) |

### 3.2 Freshwater Consumption

| Process Step | Water Use | Notes |
|-------------|-----------|-------|
| Feedstock conditioning | 0--0.5 m^3/t feedstock | Only if drying wet feedstock |
| Pyrolysis process | Near zero | Sealed, oxygen-free |
| Biochar quenching/cooling | 0.1--0.5 m^3/t biochar | Water or air cooling |
| Dust suppression | Minimal | Site-dependent |
| **Total** | **0.2--1.0 m^3 per tCO2** | Very low |

**Context:** This is 1--2 orders of magnitude less water than DAC with aqueous solvents (~5--10 m^3/tCO2) and far less than irrigation-dependent BECCS systems. Biochar is one of the most water-efficient CDR approaches.

### 3.3 Material Inputs: Global Biomass Feedstock Availability

This is the critical constraint for scaling to gigatonne levels.

#### Global Biomass Waste Production (Annual)

| Feedstock Category | Global Production (Gt dry/yr) | Sustainably Available for Biochar (Gt dry/yr) | Source |
|-------------------|-------------------------------|-----------------------------------------------|--------|
| Crop residues (straw, stover, husks) | ~5.0 | 1.0--2.0 | Lal (2005), IRENA |
| Forestry residues (slash, thinnings) | ~1.0--2.0 | 0.5--1.0 | FAO, IEA Bioenergy |
| Animal manure (dry mass) | ~2.0--3.0 | 0.3--0.8 | FAO |
| Municipal green waste / food waste | ~0.5--1.0 | 0.2--0.5 | World Bank |
| Sugarcane bagasse | ~0.5 | 0.1--0.3 | IRENA |
| Palm oil residues | ~0.2 | 0.05--0.1 | Industry |
| Dedicated energy crops (switchgrass, miscanthus) | Potential: 1--5 | 0.5--2.0 | IPCC SRCCL |
| **Total waste/residues** | **~9--14** | **2.5--5.0** | |
| **Including energy crops** | **10--19** | **3.0--7.0** | |

#### Conversion to CO2 Removal Potential

Using a central estimate of ~1.0 tCO2 sequestered per tonne dry feedstock (accounting for conversion efficiency and carbon stability):

| Scenario | Feedstock (Gt dry/yr) | CO2 Removal (Gt/yr) |
|----------|----------------------|---------------------|
| Conservative (waste only, 50% collection) | 1.5--2.5 | 1.5--2.5 |
| Moderate (waste + some energy crops) | 3.0--5.0 | 3.0--5.0 |
| Aggressive (max sustainable harvest + energy crops) | 5.0--7.0 | 5.0--7.0 |
| Theoretical maximum | 7.0--10.0 | 7.0--10.0 |

**Critical finding for 10 Gt/yr target:** Reaching 10 GtCO2/yr removal through biochar alone would require essentially ALL sustainably available biomass globally, including large-scale dedicated energy crops. This is likely infeasible for biochar alone; it would need to be part of a portfolio. Realistic ceiling: **2--5 GtCO2/yr** as the plausible upper bound, with 1--2 GtCO2/yr as a more conservative estimate.

---

## 4. Throughput Metrics

### 4.1 Capture Rate: CO2 Sequestered per Tonne of Feedstock

| Parameter | Value | Notes |
|-----------|-------|-------|
| Carbon content of dry biomass | 45--50% by mass | Varies by feedstock |
| Biochar yield (slow pyrolysis) | 25--35% of dry feedstock mass | Higher at lower temperatures |
| Carbon content of biochar | 60--90% by mass | Higher temps = higher C% |
| Carbon retained in biochar vs. feedstock | 40--60% of original C | "Fixed carbon retention" |
| Stable carbon fraction (>100 yr) | 70--90% of biochar C | BC+100 metric |
| **CO2e sequestered per t dry feedstock** | **0.7--1.2 tCO2** | After accounting for stability |

**Worked example (corn stover):**
- 1 tonne dry corn stover: ~45% C = 450 kg C
- Slow pyrolysis at 500 degC: ~30% biochar yield = 300 kg biochar
- Biochar is ~75% C = 225 kg C in biochar
- 50% of original C retained (225/450)
- Of that, ~80% is stable (>100 yr) = 180 kg stable C
- 180 kg C x 3.67 (C to CO2 conversion) = **~660 kg CO2 permanently sequestered**
- Plus avoided emissions from waste decomposition: ~100--200 kg CO2e
- **Net: ~0.8--0.9 tCO2e per tonne dry corn stover**

### 4.2 Conversion Efficiency

| Metric | Value | Source |
|--------|-------|--------|
| Carbon conversion efficiency (C in biochar / C in feedstock) | 40--60% | Lehmann et al. (2006) |
| Stable carbon fraction (BC+100) | 70--90% | EBC certification |
| Overall stable C sequestered / total C in feedstock | 30--50% | Product of above |
| Energy conversion efficiency (useful energy / biomass energy) | 20--40% | Depends on CHP setup |
| Overall system efficiency (energy + carbon) | 55--75% | Combined value capture |

### 4.3 Duty Cycle and Uptime

| Parameter | Value | Notes |
|-----------|-------|-------|
| Continuous operation | Yes --- 24/7 operation standard | Slow pyrolysis is continuous-feed |
| Typical annual uptime | 7,500--8,200 hours/yr | 85--94% capacity factor |
| Planned maintenance downtime | 2--4 weeks/yr | Scheduled annually |
| Startup time (cold start) | 4--12 hours | To reach operating temperature |
| Turndown ratio | 30--100% of rated capacity | Flexible operation |

### 4.4 Equipment Lifecycle

| Component | Design Life | Notes |
|-----------|-------------|-------|
| Pyrolysis reactor (steel) | 15--25 years | With periodic relining |
| Reactor refractory lining | 5--10 years | Major maintenance item |
| Heat exchangers | 10--15 years | Corrosion-dependent |
| Gas cleaning equipment | 10--20 years | |
| ORC/Steam turbine (if present) | 20--30 years | Standard power equipment |
| Overall facility | 20--30 years | With refurbishment |
| Containerized/modular units | 10--15 years | Lighter-duty construction |

---

## 5. End Game: Storage

### 5.1 Storage Medium: Soil Carbon via Biochar

Biochar is applied to agricultural soil at typical rates of **5--50 tonnes/hectare** (one-time application or repeated smaller doses). Once incorporated into soil, it persists due to its **polycyclic aromatic carbon structure**, which resists microbial decomposition.

### 5.2 Biochar Stability and Permanence

| Metric | Value | Source |
|--------|-------|--------|
| Mean Residence Time (MRT) in soil | 500--5,000+ years | Lehmann et al. (2015); varies with production temp |
| MRT at low pyrolysis temp (300 degC) | 100--500 years | Lower aromatic content |
| MRT at high pyrolysis temp (>500 degC) | 1,000--10,000+ years | Highly aromatic, very stable |
| Half-life (central estimate) | 500--2,000 years | Wang et al. (2016) |
| Annual degradation rate | 0.02--0.2% per year | Singh et al. (2012) |
| BC+100 (carbon stable after 100 yr) | 70--90% of initial C | EBC standard metric |
| Comparison: soil organic matter MRT | 10--100 years | Much less stable |
| Comparison: geological storage (CCS) | 10,000+ years | More permanent but costly |

**Evidence for permanence:**
- Amazonian "Terra Preta" soils contain biochar from indigenous burning practices dated to 500--7,000 years ago, still showing elevated carbon levels.
- Accelerated aging studies and modeling confirm polycyclic aromatic carbon structures resist decomposition across centuries.
- The European Biochar Certificate (EBC) requires demonstration of >70% carbon stability at 100 years for C-sink certification.

### 5.3 Degradation Factors

| Factor | Effect on Stability | Mitigation |
|--------|-------------------|------------|
| Higher soil temperature | Slightly faster decomposition | Still centuries-scale |
| Soil moisture cycling | Minimal effect | |
| Microbial activity | Very slow degradation of labile fraction | First 1--5 years, then negligible |
| UV exposure | Surface degradation only | Soil incorporation protects |
| Tillage/erosion | Physical redistribution, not C loss | Minimum-till practices |
| Low pyrolysis temperature | Less aromatic, shorter MRT | Produce at >450 degC for max stability |

### 5.4 Global Soil Storage Capacity

| Parameter | Value | Source |
|-----------|-------|--------|
| Global agricultural land area | ~5 billion hectares | FAO |
| Sustainable biochar application rate | 10--50 t/ha | Literature range |
| Conservative one-time capacity (10 t/ha) | 50 Gt biochar = ~100--150 GtCO2 | |
| Moderate capacity (30 t/ha) | 150 Gt biochar = ~300--450 GtCO2 | |
| Upper bound (50 t/ha) | 250 Gt biochar = ~500--750 GtCO2 | |
| Degraded lands suitable for biochar | ~2 billion hectares | UNCCD |
| **Practical global capacity** | **100--500 GtCO2** | Conservative to moderate |

**Key insight:** Even the conservative estimate (100 GtCO2) is sufficient for decades of multi-gigatonne removal. Soil storage capacity is NOT the binding constraint --- feedstock availability is.

### 5.5 Permanence Comparison Across CDR Methods

| Method | Storage Duration | Permanence Risk | Reversal Mechanism |
|--------|-----------------|----------------|-------------------|
| **Biochar in soil** | **500--5,000+ years** | **Low** | Extremely slow microbial degradation |
| Geological CO2 storage (CCS/DAC) | 10,000+ years | Very low | Potential leakage from wells |
| Afforestation/reforestation | 10--100 years | High | Fire, disease, logging, land-use change |
| Soil organic carbon | 10--50 years | Very high | Tillage, land-use change |
| Ocean alkalinity enhancement | 10,000+ years | Low | Dilution effects |
| Enhanced weathering | 10,000+ years | Low | Very slow reversal |

---

## 6. Economic Friction

### 6.1 CAPEX for Pyrolysis Facility

| Facility Scale | Feedstock Capacity | CAPEX | CAPEX per tCO2/yr capacity | Source |
|---------------|-------------------|-------|---------------------------|--------|
| Micro/containerized unit | 0.5--2 t/day | $100K--$500K | $500--$2,000 | Pyreg, NetZero, Carboneers |
| Small modular | 5--20 t/day | $1M--$5M | $300--$1,000 | Industry estimates |
| Medium commercial | 50--200 t/day | $5M--$30M | $200--$600 | |
| Large industrial | 200--1,000 t/day | $20M--$100M | $100--$400 | Analogous to biomass plants |
| With CHP (electricity generation) | Add 30--50% | Variable | Offset by energy revenue | |

**Learning curve:** CAPEX is expected to decline 10--20% per doubling of cumulative installed capacity, based on analogies to biomass energy technology learning rates.

### 6.2 OPEX

| Cost Component | $/tonne dry feedstock | $/tCO2 sequestered | % of Total OPEX |
|---------------|----------------------|--------------------|-----------------|
| Feedstock procurement | $20--$80 | $25--$100 | 30--50% |
| Feedstock transport | $10--$40 | $12--$50 | 10--25% |
| Labor | $5--$20 | $6--$25 | 8--15% |
| Maintenance | $5--$15 | $6--$20 | 5--12% |
| Biochar transport & application | $10--$30 | $12--$40 | 10--20% |
| Insurance, admin, other | $5--$15 | $6--$20 | 5--10% |
| **Total OPEX** | **$55--$200** | **$70--$250** | **100%** |

**Feedstock cost is the dominant variable.** Where feedstock is a waste product with negative cost (tipping fees), economics improve dramatically. Conversely, competition for biomass can push costs higher.

### 6.3 Cost per Tonne CO2

| Scenario | Cost ($/tCO2) | Notes |
|----------|---------------|-------|
| Current cost (2024) --- high end | $150--$300 | Small scale, purchased feedstock, no energy revenue |
| Current cost --- low end | $50--$150 | Waste feedstock, energy credits, scale |
| Near-term projected (2030) | $30--$120 | Scale-up, modular manufacturing |
| Long-term projected (2040+) | $20--$80 | Mature technology, optimized supply chains |
| With energy revenue offset | Subtract $20--$60/tCO2 | Significant economic benefit |
| With biochar product sales | Subtract $30--$100/tCO2 | Premium ag markets |

**Comparison to other CDR:**

| Method | Current Cost ($/tCO2) | Projected 2040 |
|--------|----------------------|----------------|
| **Biochar** | **$50--$300** | **$20--$100** |
| DAC (Climeworks, etc.) | $400--$1,000 | $100--$300 |
| BECCS | $100--$200 | $50--$150 |
| Enhanced weathering | $50--$200 | $20--$100 |
| Afforestation | $5--$50 | $5--$50 |

### 6.4 Revenue Streams (The Triple Dip)

| Revenue Stream | Value Range | Notes |
|---------------|-------------|-------|
| **Carbon credits** | $100--$250/tCO2 (voluntary market, 2024) | Puro.earth biochar credits: ~$100--$150/tCO2 |
| **Electricity sales** | $0.05--$0.15/kWh => $10--$80/tCO2 | Depends on grid connection and tariff |
| **Heat sales** | $20--$60/tCO2 | District heating (Nordic model) |
| **Biochar product sales** | $200--$1,500/tonne biochar | Agriculture: $200--$600/t; Horticulture: $400--$1,000/t; Premium/specialty: $800--$1,500/t |
| **Tipping fees** (waste feedstock) | $20--$80/t feedstock received | Negative cost = revenue |
| **Total potential revenue** | **$200--$600+/tCO2** | Combining all streams |

**Economic viability:** When all revenue streams are stacked, biochar can be **profitable** even without carbon credits, especially when using waste feedstock with tipping fees and selling biochar into premium agricultural markets. Carbon credits provide additional upside.

### 6.5 Learning Rate

| Parameter | Estimate | Source |
|-----------|----------|--------|
| Learning rate (cost reduction per capacity doubling) | 10--20% | Analogy to biomass energy |
| Current cumulative capacity | ~0.5--1 Mt biochar/yr | IBI estimates |
| Doublings to reach 1 Gt/yr | ~10 doublings | |
| Projected cost at 1 Gt/yr scale | $20--$80/tCO2 | Applying learning rate |

---

## 7. Key Players

### 7.1 Exomad Green

| Parameter | Details |
|-----------|---------|
| **Headquarters** | Mongolia (with European/international operations) |
| **Founded** | ~2019--2020 |
| **Technology** | Pyrolysis of agricultural waste and animal manure; biochar production with energy co-generation |
| **Focus** | Nomadic/distributed biochar production in Central Asian steppe; processing livestock manure and crop waste |
| **Feedstock** | Primarily animal dung/manure and agricultural residues from Mongolian pastoral farming |
| **Capacity** | Targeting thousands of tonnes of biochar per year; scaling through modular, mobile pyrolysis units |
| **Carbon Credits** | Active on voluntary carbon markets; working with carbon credit registries for certified removal credits |
| **Unique Angle** | Operating in regions with massive untapped manure and agricultural waste resources; distributed/mobile model suited to pastoral landscapes |
| **Energy Co-gen** | Excess heat from pyrolysis used for local heating (critical in Mongolian winters) and potentially electricity |
| **Soil Application** | Biochar applied to degraded Mongolian grasslands to restore soil carbon and improve pasture productivity |
| **Co-benefits** | Addressing indoor air pollution from traditional dung burning; improving grassland health; supporting pastoral livelihoods |
| **Funding/Partners** | Backed by carbon credit pre-purchase agreements; partnerships with Mongolian agricultural entities |
| **Scale Ambitions** | Scaling across Central Asia and expanding to other regions with similar pastoral waste streams |

**Strategic Significance:** Exomad Green represents the "distributed, developing-world" model --- taking pyrolysis to where waste biomass is abundant and underutilized, particularly in pastoral/nomadic contexts. This approach taps into feedstock that has near-zero alternative economic value, which radically improves unit economics.

### 7.2 Carboneers

| Parameter | Details |
|-----------|---------|
| **Headquarters** | Estonia (Tallinn), with operations expanding across Northern Europe |
| **Founded** | ~2020--2021 |
| **Technology** | Modular, containerized slow-pyrolysis units designed for rapid deployment; proprietary reactor design |
| **Feedstock** | Forestry residues (wood chips, bark, logging slash), agricultural waste |
| **Capacity** | Individual units process ~1--5 tonnes of biomass per day; scaling through deployment of multiple units |
| **Carbon Removal** | Registered on Puro.earth; selling certified CO2 Removal Certificates (CORCs) |
| **Energy Co-gen** | Integrated heat recovery; excess heat supplied to district heating networks or industrial processes (common in Nordic/Baltic region) |
| **Biochar Quality** | EBC-certified; targeting high-quality biochar for agricultural and industrial applications |
| **Business Model** | "Biochar-as-a-service" --- deploy modular units at customer sites (farms, forestry companies, municipalities) near feedstock sources |
| **Unique Angle** | Modularity and rapid deployment; containerized units can be manufactured at scale and shipped globally |
| **Partnerships** | Carbon credit pre-purchases from corporate buyers (tech companies, etc.); partnerships with Nordic forestry sector |
| **Scale Target** | Targeting tens of thousands of tCO2/yr removal within 3--5 years through fleet deployment of modular units |
| **Certifications** | Puro.earth methodology; European Biochar Certificate (EBC) |

**Strategic Significance:** Carboneers represents the "modular manufacturing" approach. Rather than building large centralized plants, they mass-produce standardized pyrolysis units that can be deployed anywhere there's feedstock. This drastically reduces deployment time and capital risk, and the Nordic location provides strong carbon credit demand and district heating revenue.

### 7.3 Wakefield Biochar

| Parameter | Details |
|-----------|---------|
| **Headquarters** | Valdosta, Georgia, USA |
| **Founded** | ~2013--2014 |
| **Technology** | Pyrolysis of southern yellow pine (forestry waste/timber residues) |
| **Feedstock** | Pine wood waste, forestry residues from southeastern U.S. timber industry |
| **Products** | Multiple biochar grades: Standard Biochar, Premium Biochar, Biochar Soil Blends, custom blends |
| **Target Markets** | Agriculture (row crops, specialty crops), horticulture, turf management, landscaping, cannabis/hemp cultivation, stormwater filtration |
| **Production Scale** | One of the largest dedicated biochar producers in North America; thousands of tonnes per year |
| **Facility** | Purpose-built production facility in Valdosta, GA; continuous-operation kiln technology |
| **Quality Standards** | IBI (International Biochar Initiative) certified; lab-tested for consistency |
| **Distribution** | Nationwide U.S. distribution; available in bulk (truckload) and bagged retail |
| **Carbon Credits** | Exploring carbon credit sales; biochar meets permanence criteria for registry standards |
| **Pricing** | Agricultural-grade biochar: ~$400--$800/ton; premium/specialty grades higher |
| **Unique Angle** | Established production-scale operations; strong existing customer base; co-located with massive southeastern U.S. forestry waste supply |
| **Agricultural Data** | Claims documented crop yield improvements of 10--30% depending on crop and application rate; improved water retention, reduced fertilizer needs |

**Strategic Significance:** Wakefield represents the "established production-scale" model --- a mature biochar producer with years of operational experience, established supply chains, and demonstrated product-market fit in agriculture. Their proximity to the U.S. southeastern timber industry provides a reliable, large-scale feedstock source.

### 7.4 Company Comparison Table

| Dimension | Exomad Green | Carboneers | Wakefield Biochar |
|-----------|-------------|------------|-------------------|
| **Model** | Distributed/mobile | Modular/containerized | Centralized production |
| **Region** | Central Asia (Mongolia) | Northern Europe (Estonia) | Southeastern U.S. |
| **Primary Feedstock** | Manure, ag waste | Forestry residues | Pine wood waste |
| **Revenue Focus** | Carbon credits + local heat | Carbon credits + district heat | Biochar product sales |
| **Scale Strategy** | Deploy mobile units across steppe | Manufacture & ship container units | Expand production capacity |
| **Carbon Credits** | Yes (voluntary markets) | Yes (Puro.earth CORCs) | Exploring |
| **Energy Co-gen** | Heat (local heating) | Heat (district heating) | Heat recovery |
| **Maturity** | Early-stage / scaling | Early-stage / scaling | Established / operating |
| **Differentiation** | Untapped developing-world feedstock | Rapid modular deployment | Production experience at scale |

---

## 8. Additional Feasibility Data

### 8.1 Current Global Biochar Production Capacity

| Metric | Value | Source |
|--------|-------|--------|
| Global biochar production (2023 est.) | 0.3--0.5 Mt/yr | IBI, industry estimates |
| Annual growth rate | 15--30% | Market research |
| Number of active producers globally | 200--500+ | IBI directory |
| Global biochar market size (2024) | $1.5--$3 billion | Market research reports |
| Projected market size (2030) | $5--$15 billion | Industry projections |
| CO2 removal from current production | ~0.3--0.5 MtCO2/yr | Derived |

**Gap to 10 Gt/yr:** Current production would need to scale by roughly **20,000x** to reach 10 GtCO2/yr. Even reaching 1 GtCO2/yr requires ~2,000x scaling. This implies ~11 doublings, which at 15--30% annual growth rate could theoretically be achieved in 25--40 years (by ~2050--2065), though feedstock constraints would likely bind before then.

### 8.2 Broader Industry Landscape (Other Major Players)

| Company | Location | Technology | Scale | Notes |
|---------|----------|-----------|-------|-------|
| **Pyreg** | Germany | Containerized pyrolysis | Modular units deployed across EU | One of the earliest commercial biochar producers |
| **NetZero** | France/UK | Pyrolysis with CHP | Growing; carbon credit focused | Puro.earth registered |
| **Pacific Biochar** | California, USA | Various feedstocks | Regional producer | Focus on California agriculture |
| **Biochar Now** | Colorado, USA | Forestry waste pyrolysis | Established | Focus on environmental remediation |
| **Carbon Gold** | UK | Various | Established | Consumer/garden market focus |
| **ECHO2** | Germany | Pyrolysis | Growing | Industrial-scale |
| **Carbo Culture** | Finland/USA | Flash pyrolysis | Startup | Y Combinator-backed; high-tech approach |
| **Charm Industrial** | USA | Bio-oil injection (not biochar) | Growing | Different approach: bio-oil into geological storage |
| **Climate Robotics** | USA | Mobile pyrolysis robots | Early-stage | Autonomous field-based pyrolysis |
| **Carbofex** | Finland | Slow pyrolysis | Established | Major Nordic producer |

### 8.3 Agricultural Co-Benefits

Biochar's value proposition is strengthened by demonstrated soil benefits:

| Benefit | Magnitude | Evidence Quality | Source |
|---------|-----------|-----------------|--------|
| **Crop yield improvement** | +10--30% (degraded soils); +0--10% (healthy soils) | Strong (meta-analyses) | Jeffery et al. (2017), Ye et al. (2020) |
| **Water retention** | +10--25% improvement in sandy soils | Strong | Omondi et al. (2016) |
| **Fertilizer use reduction** | 10--30% less N fertilizer needed | Moderate | Zheng et al. (2017) |
| **Soil pH buffering** | +0.2--1.0 pH units (acidic soils) | Strong | |
| **Cation exchange capacity** | +20--50% improvement | Strong | |
| **Reduced N2O emissions** | 10--50% reduction from soils | Moderate--strong | Cayuela et al. (2014) |
| **Reduced methane from paddy rice** | 10--40% reduction | Moderate | |
| **Soil microbial activity** | Generally increased | Moderate | |
| **Heavy metal immobilization** | Significant (contaminated soils) | Strong | |

**Key meta-analysis finding (Jeffery et al., 2017):** A meta-analysis of 1,125 observations found a mean crop yield increase of ~25% in tropical regions with degraded soils, but only ~5% in temperate regions with already-fertile soils. This suggests biochar's agricultural value is highest in developing countries with degraded soils, which aligns well with deployment in Africa, South/Southeast Asia, and Central Asia.

### 8.4 Feedstock Competition

| Competing Use | Biomass Demand (Gt/yr) | Competition Risk |
|--------------|------------------------|------------------|
| Bioenergy (power, heat) | 0.5--1.5 | HIGH --- direct competition |
| Biofuels (ethanol, biodiesel) | 0.3--0.7 | HIGH --- policy-driven demand |
| Animal feed/bedding | Variable | MODERATE |
| Composting/mulching | Variable | LOW--MODERATE |
| Soil conservation (leave on field) | Large but flexible | MODERATE --- need to leave 50%+ |
| Paper/pulp | 0.5--1.0 | LOW (different wood grades) |
| BECCS (bioenergy + CCS) | Future: 0.5--5+ | HIGH --- direct competition for same feedstock |

**Critical risk:** BECCS and biochar directly compete for the same biomass feedstock. Policy choices about which technology to subsidize will strongly influence which scales. Biochar has the advantage of lower CAPEX and distributed deployment; BECCS has the advantage of potentially greater net CO2 removal per tonne of biomass if geological storage is cheap.

### 8.5 Transport Emissions

| Transport Segment | Distance | Emissions (kgCO2/t material) | % of Sequestered CO2 |
|-------------------|----------|-------------------------------|---------------------|
| Feedstock collection (farm to plant) | 20--50 km | 3--10 | 0.3--1.0% |
| Feedstock collection (extended radius) | 50--150 km | 10--30 | 1--3% |
| Biochar distribution (plant to farm) | 20--100 km | 3--20 | 0.3--2% |
| **Total transport** | --- | **10--50** | **1--5%** |

**Conclusion:** Transport emissions are a small fraction (1--5%) of net CO2 sequestered, but they increase with collection radius. This reinforces the economic and carbon case for distributed, co-located facilities (the Exomad/Carboneers model).

### 8.6 Certification Standards

| Standard | Organization | Key Requirements | Region |
|----------|-------------|-----------------|--------|
| **EBC (European Biochar Certificate)** | European Biochar Foundation | Minimum 50% C content; H:C ratio <0.7; pollutant limits (PAH, heavy metals); BC+100 >70% | Europe (global influence) |
| **IBI Biochar Standards** | International Biochar Initiative | Similar to EBC; testing protocols; product labeling | Global (primarily North America) |
| **Puro.earth CORC methodology** | Puro.earth | Full LCA; BC+100 measurement; third-party verification; registry listing | Global carbon market |
| **Verra VCS methodology** | Verra | Lifecycle emissions accounting; additionality; permanence monitoring | Global |
| **Gold Standard** | Gold Standard Foundation | Developing biochar methodology | Global |
| **ISO 17225** | ISO | Biomass fuel quality (relevant to feedstock) | Global |

**EBC C-Sink Certification** is emerging as the gold standard for biochar carbon credits, requiring:
- Minimum Corg >50% (mass fraction)
- H/Corg ratio < 0.7 (indicator of aromatic stability)
- BC+100 value (stable carbon after 100 years): minimum 70%
- Full traceability from biomass source to soil application
- Independent third-party auditing
- Pollutant limits (PAH < 6 mg/kg for premium grade)

### 8.7 Lifecycle Assessment (LCA) Data

**System boundaries for biochar LCA typically include:**

| LCA Component | GHG Impact (kgCO2e/t biochar) | Direction |
|--------------|-------------------------------|-----------|
| Feedstock collection & transport | +30 to +100 | Emission |
| Pyrolysis energy (natural gas startup) | +5 to +20 | Emission |
| Pyrolysis process (sequestered C) | -1,500 to -3,000 | **Removal** |
| Avoided emissions (energy co-gen displacing fossil) | -200 to -800 | Avoided emission |
| Avoided emissions (feedstock decomposition/burning) | -100 to -500 | Avoided emission |
| Biochar transport & application | +20 to +80 | Emission |
| Soil N2O reduction | -50 to -200 | Avoided emission |
| Facility construction (amortized) | +5 to +30 | Emission |
| **Net LCA** | **-1,500 to -3,500** | **Net removal** |
| **Net tCO2e removed per tonne biochar** | **1.5 to 3.5** | **Net negative** |

**Key LCA finding:** Published LCAs consistently find biochar systems to be strongly net-negative, with removal-to-emission ratios of 5:1 to 10:1. The dominant term is the sequestered carbon itself; all other terms are relatively small.

**Representative LCA studies:**

| Study | System | Net CO2e removed per t biochar | Journal |
|-------|--------|-------------------------------|---------|
| Hammond et al. (2011) | UK straw biochar | 0.7--1.4 tCO2e/t biochar | Energy & Environmental Science |
| Roberts et al. (2010) | Corn stover, switchgrass | 0.8--1.2 tCO2e/t feedstock | Environmental Science & Technology |
| Gaunt & Lehmann (2008) | Various feedstocks | 2--5 tCO2e/t biochar | Environmental Science & Technology |
| Woolf et al. (2010) | Global potential | 1.8 GtCO2e/yr max sustainable | Nature Communications |

### 8.8 Policy Landscape

| Jurisdiction | Policy Status | Details |
|-------------|--------------|---------|
| **EU** | Supportive and growing | EU Carbon Removal Certification Framework (CRCF) includes biochar; EBC certification widely recognized; CAP reform exploring soil carbon incentives |
| **U.S.** | Emerging | USDA recognizes biochar as soil amendment; 2023 Farm Bill discussions included biochar provisions; California's Healthy Soils Program supports biochar; IRA may indirectly support via clean energy provisions |
| **Carbon Markets** | Active | Puro.earth: biochar is largest category of issuances; Verra and Gold Standard developing/have methodologies; Voluntary market price: $100--$250/tCO2 |
| **Switzerland** | Leading | First country to include biochar in national carbon offset scheme |
| **Australia** | Supportive | ERF (Emissions Reduction Fund) includes biochar methodology |
| **Japan** | Emerging | Traditional biochar use ("kuntan"); growing policy interest |
| **Developing Countries** | Variable | India exploring rice husk biochar programs; Kenya and other African nations piloting |

### 8.9 Scaling Bottlenecks

| Bottleneck | Severity (1--5) | Timeline to Resolve | Notes |
|-----------|-----------------|---------------------|-------|
| **Feedstock supply chain logistics** | 4/5 | 5--15 years | Building collection infrastructure at scale |
| **Manufacturing capacity for pyrolysis units** | 3/5 | 3--10 years | Modular approach helps; need factory scale-up |
| **Carbon credit market maturity** | 3/5 | 3--7 years | Markets growing rapidly but still immature |
| **Feedstock competition (with bioenergy/BECCS)** | 4/5 | Ongoing | Policy-dependent |
| **Soil application logistics** | 2/5 | 3--10 years | Relatively straightforward; use existing ag equipment |
| **Certification/MRV infrastructure** | 3/5 | 3--5 years | Growing rapidly |
| **Financing/investment** | 3/5 | 3--7 years | Carbon credit pre-purchases de-risk; mainstream finance still cautious |
| **Labor/skilled operators** | 2/5 | 3--10 years | Modular/automated systems reduce labor need |
| **Public acceptance** | 1/5 | N/A | Generally well-accepted; "nature-based" perception |
| **Regulatory frameworks** | 2/5 | 3--7 years | Most jurisdictions moving in supportive direction |

### 8.10 Timeline Projections

| Milestone | Projected Year | Basis |
|-----------|---------------|-------|
| Global production reaches 1 Mt biochar/yr | 2026--2028 | Current growth trends |
| First "mega-facility" (>100,000 tCO2/yr) | 2028--2032 | Technology readiness; investment signals |
| Global production reaches 10 Mt biochar/yr | 2030--2035 | Continued scaling |
| Cost below $100/tCO2 at scale | 2028--2035 | Learning rate projections |
| Global production reaches 100 Mt biochar/yr | 2035--2045 | Requires major investment |
| Reaching 0.5--1 GtCO2/yr removal | 2040--2050 | IPCC-aligned projections |
| Reaching 2--5 GtCO2/yr removal | 2050--2070 | Optimistic; requires dedicated energy crops |

### 8.11 IPCC and Major Estimates of Biochar Potential

| Source | Estimated Potential (GtCO2/yr) | Timeframe | Conditions |
|--------|-------------------------------|-----------|------------|
| **IPCC AR6 WGIII (2022)** | 0.3--6.6 (range); central 2.6 | 2050 | Depends on feedstock availability |
| **IPCC SRCCL (2019)** | 0.03--6.6 | 2050 | Wide range reflecting uncertainty |
| **Woolf et al. (2010), Nature Comm.** | 1.8 (max sustainable) | Annual steady-state | Without dedicated energy crops |
| **Fuss et al. (2018)** | 0.5--2.0 | 2050 | Conservative, waste-only |
| **National Academies (2019)** | 0.5--2.0 | Annual potential | U.S.-focused but extrapolated |
| **Smith (2016)** | 0.7--3.6 | 2100 pathway | Range of scenarios |
| **Minx et al. (2018)** | 0.5--2.0 | Central estimate | Review of reviews |

**IPCC AR6 Summary:** Biochar is classified as a CDR method with "medium confidence" in its technical potential of 2--5 GtCO2/yr, moderate cost ($30--120/tCO2), and high co-benefits for agriculture. The IPCC considers biochar one of the more "ready" CDR options alongside afforestation and soil carbon management.

---

## 9. 10 Gt/yr Scale Feasibility Assessment

### 9.1 Can Biochar Reach 10 GtCO2/yr?

**Short answer: Almost certainly not alone. But it can be a major contributor at 1--3 GtCO2/yr.**

| Constraint | Requirement for 10 GtCO2/yr | Available | Feasible? |
|-----------|------------------------------|-----------|-----------|
| **Feedstock** | ~8--12 Gt dry biomass/yr | 2.5--7 Gt sustainable | NO (without massive energy crop expansion) |
| **Land for facilities** | ~50,000--100,000 ha | Abundant | YES |
| **Water** | 2--10 Gm^3/yr | Abundant | YES |
| **Soil storage capacity** | ~10 GtCO2/yr x decades | 100--500 GtCO2 total | YES (for decades) |
| **Capital investment** | $1--5 trillion cumulative | Large but plausible over 20+ years | CHALLENGING |
| **Pyrolysis units needed** | ~500,000--2,000,000 modular units | Manufacturing capacity buildable | CHALLENGING |
| **Energy grid impact** | Net positive (produces energy) | Beneficial | YES |

### 9.2 Realistic Scale Scenarios

| Scenario | Scale (GtCO2/yr) | Feedstock Source | Capital Required | Timeline |
|----------|-------------------|-----------------|-----------------|----------|
| **Conservative** | 0.5--1.0 | Waste residues only | $50--$200B | 2040--2050 |
| **Moderate** | 1.5--3.0 | Waste + some energy crops | $200--$600B | 2045--2060 |
| **Aggressive** | 3.0--5.0 | Waste + large energy crop program | $500B--$1.5T | 2050--2070 |
| **Theoretical max** | 5.0--7.0 | All available + massive energy crops | $1--$3T | 2060+ |

### 9.3 What Would 2 GtCO2/yr Biochar Look Like?

To give tangible scale:

| Parameter | Value at 2 GtCO2/yr |
|-----------|---------------------|
| Dry biomass needed | ~2 Gt/yr |
| Biochar produced | ~600 Mt/yr |
| Number of large facilities (50 kt feedstock/yr each) | ~40,000 |
| Or modular units (5 t/day) | ~1.2 million units |
| Electricity co-generated | ~400--800 TWh/yr (~1.5--3% of global electricity) |
| Soil application area (at 10 t/ha) | ~60 million hectares/yr (new land each year) |
| Annual investment needed | ~$60--$120 billion/yr |
| Revenue from carbon credits (at $100/tCO2) | $200 billion/yr |
| Revenue from biochar sales | $100--$300 billion/yr |
| Revenue from electricity | $20--$80 billion/yr |

---

## 10. Summary Tables

### 10.1 Biochar at a Glance

| Parameter | Value |
|-----------|-------|
| CDR method | Biomass pyrolysis + soil carbon storage |
| TRL (Technology Readiness Level) | 7--8 (commercial, scaling) |
| Net energy | **Positive** (produces 200--700 kWh/tCO2) |
| Water intensity | Very low (0.2--1.0 m^3/tCO2) |
| Cost per tCO2 (current) | $50--$300 |
| Cost per tCO2 (projected at scale) | $20--$100 |
| Permanence | 500--5,000+ years |
| Co-benefits | Soil fertility, water retention, reduced fertilizer, energy |
| IPCC estimated potential | 0.3--6.6 GtCO2/yr (central ~2.6) |
| Realistic potential (2050) | 1--3 GtCO2/yr |
| Binding constraint | Feedstock availability |
| Scaling approach | Modular manufacturing of pyrolysis units |

### 10.2 Critical Variables Summary

| Variable | Rating | Notes |
|----------|--------|-------|
| Physical footprint | Excellent | Very compact facilities |
| Energy efficiency | Excellent | Net energy producer |
| Water efficiency | Excellent | Minimal consumption |
| Feedstock availability | Moderate | 2--5 Gt/yr sustainable; binding constraint |
| Storage capacity | Excellent | 100--500+ GtCO2 in soils |
| Permanence | Very Good | Centuries to millennia |
| Cost trajectory | Good | $20--$100/tCO2 at scale |
| Revenue potential | Excellent | Triple revenue stack |
| Scalability | Moderate--Good | Modular helps; feedstock limits ceiling |
| Co-benefits | Excellent | Agricultural + energy |
| Policy support | Good and growing | EU, carbon markets supportive |
| Public acceptance | Excellent | Low controversy |

---

## 11. Sources & References

### Peer-Reviewed Literature

1. **Woolf, D. et al. (2010).** "Sustainable biochar to mitigate global climate change." *Nature Communications*, 1(56). --- Estimated maximum sustainable potential of 1.8 GtCO2e/yr.
2. **Lehmann, J. et al. (2006).** "Bio-char sequestration in terrestrial ecosystems --- A review." *Mitigation and Adaptation Strategies for Global Change*, 11, 403--427.
3. **Lehmann, J. et al. (2015).** "Persistence of biochar in soil." Chapter in *Biochar for Environmental Management* (2nd ed.), Routledge.
4. **Jeffery, S. et al. (2017).** "Biochar effects on crop yield." *GCB Bioenergy*, 9, 1361--1372. --- Meta-analysis of 1,125 observations.
5. **Fuss, S. et al. (2018).** "Negative emissions --- Part 2: Costs, potentials and side effects." *Environmental Research Letters*, 13(6), 063002.
6. **Smith, P. (2016).** "Soil carbon sequestration and biochar as negative emission technologies." *Global Change Biology*, 22(3), 1315--1324.
7. **Roberts, K.G. et al. (2010).** "Life cycle assessment of biochar systems." *Environmental Science & Technology*, 44(2), 827--833.
8. **Hammond, J. et al. (2011).** "Freshwater consumption and withdrawal." *Energy & Environmental Science*, 4(10), 4053--4061.
9. **Gaunt, J.L. & Lehmann, J. (2008).** "Energy balance and emissions associated with biochar sequestration." *Environmental Science & Technology*, 42(11), 4152--4158.
10. **Cayuela, M.L. et al. (2014).** "Biochar's role in mitigating soil nitrous oxide emissions." *Agriculture, Ecosystems & Environment*, 191, 5--16.
11. **Wang, J. et al. (2016).** "Biochar stability in soil: meta-analysis." *GCB Bioenergy*, 8(3), 512--523.
12. **Singh, B.P. et al. (2012).** "Long-term influence of biochar on native organic carbon mineralisation." *Scientific Reports*, 2, 741.
13. **Omondi, M.O. et al. (2016).** "Quantification of biochar effects on soil hydrological properties." *Geoderma*, 274, 28--34.
14. **Minx, J.C. et al. (2018).** "Negative emissions --- Part 1: Research landscape." *Environmental Research Letters*, 13(6), 063001.
15. **Ye, L. et al. (2020).** "Biochar effects on crop productivity and greenhouse gas emissions." *Journal of Environmental Management*, 269, 110827.

### Major Reports & Assessments

16. **IPCC (2022).** AR6 Working Group III, Chapter 12: Cross-sectoral perspectives. --- Biochar potential: 0.3--6.6 GtCO2/yr.
17. **IPCC (2019).** Special Report on Climate Change and Land (SRCCL), Chapter 4.
18. **National Academies of Sciences (2019).** *Negative Emissions Technologies and Reliable Sequestration: A Research Agenda.* Washington, DC: The National Academies Press.
19. **IEA Bioenergy (2015).** Task 34: Biochar systems.
20. **IRENA (2014).** *Global Bioenergy Supply and Demand Projections.*

### Certification & Standards

21. **European Biochar Certificate (EBC).** Guidelines for a Sustainable Production of Biochar, Version 10.1 (2022). [european-biochar.org](https://www.european-biochar.org)
22. **International Biochar Initiative (IBI).** Standardized Product Definition and Product Testing Guidelines for Biochar. [biochar-international.org](https://biochar-international.org)
23. **Puro.earth.** Biochar Methodology, Version 3 (2023). [puro.earth](https://puro.earth)

### Company Sources

24. **Exomad Green.** Company website and public disclosures. [exomadgreen.com](https://exomadgreen.com)
25. **Carboneers.** Company website and public disclosures. [carboneers.com](https://carboneers.com)
26. **Wakefield Biochar.** Company website and public disclosures. [wakefieldbiochar.com](https://www.wakefieldbiochar.com)

### Industry Data

27. **Grand View Research (2023).** Biochar Market Size, Share & Trends Analysis Report.
28. **Puro.earth Registry Data (2024).** Biochar CORC issuances and pricing.

---

## Appendix A: Glossary

| Term | Definition |
|------|-----------|
| **BC+100** | The fraction of biochar carbon that remains stable after 100 years. Standard metric for permanence. |
| **Biochar** | Charcoal produced from biomass pyrolysis, intended for soil application. |
| **CORC** | CO2 Removal Certificate (Puro.earth registry). |
| **CHP** | Combined Heat and Power --- simultaneous generation of electricity and useful heat. |
| **EBC** | European Biochar Certificate --- quality and sustainability standard. |
| **H/Corg** | Ratio of hydrogen to organic carbon in biochar; lower values indicate greater aromatic stability. |
| **IBI** | International Biochar Initiative --- global biochar standards body. |
| **LCA** | Life Cycle Assessment --- comprehensive environmental impact analysis. |
| **MRT** | Mean Residence Time --- average time carbon persists in a given reservoir. |
| **MRV** | Monitoring, Reporting, and Verification --- framework for carbon credit integrity. |
| **ORC** | Organic Rankine Cycle --- technology for generating electricity from low-temperature heat. |
| **PAH** | Polycyclic Aromatic Hydrocarbons --- pollutants that must be minimized in biochar. |
| **Pyrolysis** | Thermochemical decomposition of organic material at elevated temperature in absence of oxygen. |
| **Slow pyrolysis** | Pyrolysis at moderate temperatures (300--600 degC) over minutes to hours; maximizes biochar yield. |
| **Syngas** | Synthetic gas (H2, CO, CH4, CO2) produced during pyrolysis. |
| **Terra Preta** | Amazonian dark earth soils containing ancient biochar, demonstrating millennia-scale stability. |
| **TRL** | Technology Readiness Level (1--9 scale). |

## Appendix B: Key Equations

**Carbon sequestration per unit feedstock:**

```
CO2_sequestered = M_feedstock x C_biomass x Y_biochar x C_biochar x F_stable x 3.67

Where:
  M_feedstock = mass of dry feedstock (tonnes)
  C_biomass   = carbon fraction of biomass (~0.45--0.50)
  Y_biochar   = biochar yield fraction (~0.25--0.35)
  C_biochar   = carbon fraction of biochar (~0.60--0.90)
  F_stable    = stable fraction at 100 years (~0.70--0.90)
  3.67        = molecular weight ratio CO2/C
```

**Example:** 1 tonne dry corn stover:
```
= 1.0 x 0.47 x 0.30 x 0.75 x 0.80 x 3.67
= 1.0 x 0.0846 x 3.67
= 0.31 tonne stable C
= 0.85 tCO2 sequestered (from carbon alone)
+ avoided emissions from decomposition: ~0.1--0.2 tCO2e
= ~0.95--1.05 tCO2e net removal
```

**Net energy output:**

```
E_net = E_syngas + E_biooil - E_pyrolysis - E_drying - E_auxiliary

Typical: E_net = +1 to +5 GJ per tonne dry feedstock
         = +280 to +1,400 kWh per tonne dry feedstock
         = +200 to +700 kWh per tCO2 sequestered (NET POSITIVE)
```

---

*Document compiled February 2026. All figures represent best available published data as of early 2025. Company-specific data should be verified against latest disclosures. Figures in this document are drawn from peer-reviewed literature, IPCC reports, industry publications, and company public statements. Web-based sources could not be accessed at time of compilation; readers should cross-reference with the cited URLs for the most current data.*
