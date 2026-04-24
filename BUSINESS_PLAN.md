# ISOTRACE BUSINESS PLAN
## Tritium Fuel Cycle Instrumentation for Commercial Fusion Energy

**Document Date**: April 2026  
**Status**: Strategic Framework  
**Contact**: isotrace@research.lab

---

## EXECUTIVE SUMMARY

**The Opportunity**: Fusion energy's critical unsolved bottleneck is tritium fuel cycle instrumentation. Every deuterium-tritium (D-T) fusion plant requires instrumentation—valves, pressure gauges, temperature sensors, composition analyzers, flow controllers, safety monitors—but the entire commercial off-the-shelf (COTS) supply chain fails in tritium environments. Beta decay destroys organic seals within weeks; tritium permeates through metals; electronics degrade in radiation fields.

**The Market**: 40+ fusion companies (Kyoto Fusioneering, Commonwealth Fusion Systems, STEP, TAE, Helion, General Fusion, and others) are building commercial D-T fusion plants. ITER represents the largest single customer opportunity. Each plant needs dozens of tritium-compatible instruments across storage, processing, monitoring, and safety systems.

**The Solution**: ISOTRACE proposes a complete, fusion-qualified instrumentation suite—12 products across 3 development tiers—integrated into a regulatory-compliant digital accountability platform. The first company to execute this roadmap will become the Endress+Hauser of fusion energy.

**Market Size**: $380M combined total addressable market (TAM) across all 12 products, with near-term revenue ($50-100M) available from existing nuclear tritium facilities *before* commercial fusion plants are proven operational.

**Key Advantage**: The digital twin/accountancy platform (ISO-DA09) creates long-term competitive moat through regulatory lock-in and SaaS recurring revenue model. Every hardware sensor becomes a data node in a proprietary system.

**Timeline to Revenue**: 
- **Year 1-2**: Launch Tier 1 products in nuclear market ($20-30M revenue)
- **Year 2-3**: First fusion validation on UNITY-2 (Kyoto Fusioneering, late 2026)
- **Year 3-5**: Commercial fusion plants come online (revenue inflection, $100-200M+)

---

## 1. BUSINESS CONTEXT & MARKET ANALYSIS

### 1.1 The Tritium Fuel Cycle Problem

Deuterium-tritium fusion is the leading physics architecture for commercial fusion reactors because:
- **Well-understood physics**: D-T cross-section (5.1 barns) is 100× higher than D-D
- **Achievable temperature**: Ignition point ~200 keV (vs. 500+ keV for D-D)
- **Tritium breeding**: Lithium-lead blanket breeds 1.05+ tritium per reaction (fuel self-sustaining)

**However**, tritium creates severe engineering challenges:

| Challenge | Impact | Current Status |
|-----------|--------|-----------------|
| **Beta decay (half-life 12.3 years)** | Destroys organic materials (seals, lubricants) in weeks | All COTS seals fail; custom materials required |
| **Tritium permeation** | Diffuses through metals at elevated T; volatile contamination | All COTS gaskets/joints leak at 100°C+ |
| **Radiation effects** | Electronics degrade; neutron activation of surrounding materials | Sensors must be shielded or hardened |
| **Inventory accountability** | Regulatory requirement; tritium loss = safety/compliance risk | No real-time flow measurement exists |
| **Measurement gap** | No commercial tritium flow meter; only batch/snapshot methods | Indirect inference from calorimetry, PVT, mass spec |

**Result**: The entire COTS instrument supply chain is incompatible with tritium. Every fusion company must develop custom instrumentation or operate without real-time process control.

### 1.2 The Fusion Market Expansion

**Current Fusion Landscape (2024-2026)**:
- **40+ private fusion companies** actively building D-T plants
- **ITER** (France): $20B+ international project, operational target 2030s
- **First commercial validation**: UNITY-2 (Kyoto Fusioneering + CNL), commissioning late 2026
- **Commercial plants in design phase**:
  - Commonwealth Fusion Systems (SPARC, 2028-2030 target)
  - TAE Technologies (Field-Reversed Configuration, 2030s)
  - Helion Energy (Polaris, 2030+)
  - STEP (UK national program, DEMO-scale, 2030s)
  - General Fusion (Piston-driven, 2030+)

**Fusion Fleet Projection**:
- 2030: 2-3 operational plants (validation phase)
- 2035: 5-10 commercial plants (early market)
- 2040: 15-30 plants (growth phase)
- 2050: 50-100+ plants (mature market)

**Instruments Per Plant**:
- Storage system: 4-6 instruments
- Processing/ISS: 8-12 instruments
- Injection/fuel delivery: 6-10 instruments
- Blanket tritium extraction: 4-6 instruments
- Safety/monitoring: 6-8 instruments
- **Total per plant: 30-50 instruments**

### 1.3 Target Customer Segments

#### Segment A: Existing Nuclear Tritium Facilities (Immediate Market)

**Market Size**: ~15 facilities worldwide  
**Current Instruments Per Facility**: 10-20  
**Total TAM**: $20-30M (near-term revenue, 2026-2028)  

**Facilities**:
- ITER Storage and Delivery System (SDS)
- Tritium Laboratory Karlsruhe (Germany)
- Canadian Nuclear Laboratories (Chalk River)
- Savannah River National Laboratory (USA)
- Japanese tritium processing facilities
- EU Fusion Fuel Cycle facilities

**Customer Profile**:
- Regulatory compliance mandated
- Long product lifespans (15-30 year deployments)
- High reliability requirements
- Conservative purchasing (proven technology)

**Sales Strategy**: Direct to facility operators; emphasize regulatory compliance and lifecycle cost reduction

#### Segment B: Fusion Companies (Growth Market)

**Market Size**: $150-200M (2030-2040)  
**Customers**: 40+ companies; highest priority are:
- **Tier 1A**: Kyoto Fusioneering, Commonwealth Fusion Systems, TAE, Helion (validation customers, 2026-2030)
- **Tier 1B**: STEP, General Fusion, Type One Energy, Marvel Fusion (near-commercial, 2030-2035)
- **Tier 2**: Earlier-stage companies requiring pilot-scale systems (2035+)

**Customer Needs**:
- Real-time tritium flow measurement (eliminates model-based prediction)
- Isotope-aware sensors (accounts for H/D/T isotope effects)
- Radiation-hardened electronics
- Regulatory-compliant accountability system
- Integration with plant control systems

**Sales Strategy**: Embedded customer partnerships; technical co-development for first-mover advantage; reference designs for commercial standardization

#### Segment C: ITER & International Mega-Projects (Strategic Anchor)

**Market Size**: $50-100M (single customer, but strategic validation)  
**Timeline**: Design finalization 2026-2028; procurement 2028-2032  

**ITER's Known Instrumentation Gaps**:
- **Analytical System (ANS)**: Composition monitoring (Raman + speed-of-sound + mass spec)
- **Storage & Delivery System**: Real-time inventory + flow measurement
- **Tokamak Exhaust Processing (TEP)**: Tritium recovery + efficiency monitoring
- **Water Detritiation System (WDS)**: Tritium removal verification

**Sales Strategy**: Position as ITER vendor; leverage regulatory approval for commercial plants; reference design for other international projects (DEMO, JT-60SA)

---

## 2. PRODUCT PORTFOLIO & ROADMAP

### 2.1 Portfolio Overview

**Total Products**: 12  
**Development Tiers**: 3 (Tier 1 = Launch-Ready; Tier 3 = 5-10 year development)  
**Combined TAM**: $380M

#### **TIER 1: LAUNCH-READY (Year 1-2)**

**Products suitable for existing nuclear market + early fusion validation**

| Product | Description | TRL | TAM | Comments |
|---------|-------------|-----|-----|----------|
| **TRI-TEMP-01** | Tritium-resistant temperature sensors (±0.5°C, -250 to +150°C) | 8 | $15M | RTD/thermocouple variants; ceramic coatings for radiation hardening |
| **TRI-PRESS-01** | Pressure transducers for tritium lines (0.01-1000 Pa range) | 8 | $20M | Sealed diaphragm; getter beds inside cavity for tritium capture |
| **TRI-FLOW-01A** | Thermal mass flow meter adapted for H/D/T (±2% accuracy, low-cost variant) | 7 | $25M | MEMS-based; software isotope correction; 100-300 μmol/s range |
| **ISO-SEAL-01** | Tritium-compatible seals & dynamic gasket kit | 9 | $30M | PTFE, FEP, elastomer compounds; compatible with ZrCo getter beds |

**Tier 1 Revenue Projection**: $50-70M over 24 months (nuclear market primarily)

---

#### **TIER 2: DEVELOPMENT-STAGE (Year 2-4)**

**Products requiring 2-3 years R&D; validation on UNITY-2 test bed**

| Product | Description | TRL | TAM | Development Need |
|---------|-------------|-----|-----|-------------------|
| **TRI-FLOW-02** | Coriolis mass flow meter for tritium (±0.5% accuracy, isotope compensation) | 5 | $80M | Novel: requires dual-measurement system + software isotope correction algorithm |
| **TRI-COMP-01** | Speed-of-sound composition monitor (real-time H/D/T ratio, ±0.1%) | 6 | $40M | Inline acoustic measurement + pressure/temp crosscheck |
| **TRI-HOLD-01** | Advanced tritium storage vessel (cryogenic + room-temp variants) | 7 | $25M | Getter-lined; passive safety; integrated pressure relief |
| **TRI-SAFETY-01** | Integrated safety shutdown system (detects tritium leaks, auto-isolation) | 7 | $35M | Fiber-optic tritium detector + solenoid valve cluster |

**Tier 2 Revenue Projection**: $100-150M over 3-5 years (fusion market acceleration, 2028-2031)

---

#### **TIER 3: LONG-TERM STRATEGIC (Year 4-10)**

**Products creating sustainable competitive advantage; digital platform core**

| Product | Description | TRL | TAM | Strategic Value |
|---------|-------------|-----|-----|-------------------|
| **ISO-DA09** | Tritium Accountancy & Digital Twin Platform (SaaS) | 4 | $130M | **Regulatory lock-in**; every sensor becomes data node; recurring revenue; plant-wide tritium tracking |
| **TRI-FIBER-01** | Fiber-optic tritium detector (remote sensing, multi-location) | 4 | $20M | Novel: non-invasive; radiation-hard fiber; enables distributed monitoring |
| **TRI-BLANKET-01** | Tritium extraction system from Li-Pb blanket (integrated sensor) | 3 | $25M | Long-lead item; partnered with lithium supplier; critical for fuel self-sustainability |

**Tier 3 Revenue Projection**: $150-200M+ annually by 2035+ (moat establishment; recurring SaaS revenue)

---

### 2.2 Flagship Product: ISO-DA09 (Tritium Accountancy Platform)

**Why This Is the Moat**:

The ISO-DA09 is not just a sensor platform—it's a regulatory compliance system. Every major fusion/tritium facility will be required to maintain continuous, auditable tritium inventory records. A company that builds the standard tritium accountability software *becomes* the critical infrastructure.

**Platform Features**:

1. **Real-Time Data Integration**
   - Connects to all 12 hardware sensors across the facility
   - Unified interface for temperature, pressure, flow, composition, radiation
   - Cloud-based or on-premises deployment

2. **Regulatory Compliance Module**
   - Automatic IAEA/DOE/EU reporting (tritium inventory, loss tracking, breeding verification)
   - Audit trail; tamper-proof logging
   - Regulatory pre-approval from ITER (fastest path to credibility)

3. **Digital Twin Simulation**
   - Real-time model of tritium flow through entire fuel cycle
   - Predictive analytics (remaining breeding margin, equipment failure risk)
   - Optimization recommendations (minimize losses, maximize extraction efficiency)

4. **SaaS Recurring Revenue**
   - Per-facility subscription: $500k-$1M annually (regulatory compliance = non-negotiable cost)
   - Plant fleet: 50-100 plants × $500k-$1M = $25-100M annual recurring revenue by 2050

**Competitive Moat**:
- Regulatory bodies (IAEA, DOE, EU) typically approve ONE preferred system per technology area
- Once locked in, switching cost = complete facility re-instrumentation (prohibitively expensive)
- Network effects: every fusion company adopting same platform = stronger standard → harder to displace

**Development Investment**: $10-15M over 4-5 years (modest relative to TAM)

---

## 3. GO-TO-MARKET STRATEGY

### 3.1 Phase 1: Nuclear Market Validation (Year 1-2)

**Objective**: Prove technical competence in tritium environment; generate proof-of-concept revenue

**Actions**:
1. **Partner with Canadian Nuclear Laboratories (CNL)**
   - Deploy Tier 1 instruments on UNITY-2 tritium facility (commissioning late 2026)
   - Published validation data = credibility for fusion customers
   - Reference design for other nuclear facilities

2. **Direct Sales to Existing Facilities**
   - Target Tritium Laboratory Karlsruhe (Germany), ITER interim systems, Savannah River
   - Sales value: $5-10M per facility × 5 facilities = $25-50M revenue

3. **Standards Development**
   - Engage ISO/ASTM working groups on tritium instrumentation standards
   - Early participation → favorable standard definition → competitive advantage

**Revenue Target**: $30-50M

---

### 3.2 Phase 2: Fusion Validation (Year 2-3)

**Objective**: Establish credibility with first-mover fusion customers; win design-in on commercial plants

**Actions**:
1. **Kyoto Fusioneering Partnership (UNITY-2)**
   - Embedded engineering team on UNITY-2 commissioning (late 2026)
   - Real-time measurement validation → published case study
   - Kyoto becomes reference customer for all other fusion companies

2. **Technical Roadshow**
   - Present at Tritium 2027, Fusion Energy 2027, IAEA conferences
   - White papers: "Real-Time Tritium Flow Measurement: UNITY-2 Validation Results"
   - Target: Commonwealth Fusion Systems, TAE, Helion design teams

3. **Prototype Testing Programs**
   - Offer Tier 2 products for beta testing (subsidized or free) to 3-5 major fusion companies
   - Generates technical feedback; builds customer relationships; future lock-in

**Revenue Target**: $40-70M (mostly Tier 1 continuation + early Tier 2 orders)

---

### 3.3 Phase 3: Commercial Fusion Takeoff (Year 3-5)

**Objective**: Dominant market position as standard instrumentation provider; SaaS platform adoption

**Actions**:
1. **ITER Procurement (2028-2032)**
   - Position as preferred vendor for Analytical System (ANS), Storage & Delivery (SDS), Exhaust Processing (TEP)
   - ITER approval = international legitimacy
   - $50-100M contract value

2. **Commercial Fusion Fleet Sales**
   - Commonwealth Fusion Systems (SPARC, 2028-2030): $20-30M
   - TAE Technologies: $15-20M
   - Helion, STEP, General Fusion: $15-25M each
   - **Total: $100-150M+ annually**

3. **ISO-DA09 Platform Rollout**
   - Mandatory for all new plants (regulatory requirement by 2028-2030)
   - Recurring revenue: $500k-$1M per facility
   - 10-20 plants operational by 2032 = $5-20M annual SaaS revenue (growing)

**Revenue Target**: $150-250M+ annually

---

## 4. FINANCIAL PROJECTIONS

### 4.1 5-Year Revenue Forecast

| Year | Tier 1 Products | Tier 2 Products | Tier 3 Products | Total Revenue | Cumulative |
|------|-----------------|-----------------|-----------------|----------------|-----------|
| 2026 | $10M | $0M | $0M | $10M | $10M |
| 2027 | $25M | $5M | $0M | $30M | $40M |
| 2028 | $40M | $30M | $2M | $72M | $112M |
| 2029 | $45M | $60M | $8M | $113M | $225M |
| 2030 | $50M | $100M | $25M | $175M | $400M |

**Assumptions**:
- Tier 1: Steady-state $50M annual (nuclear market + fusion replacement cycle)
- Tier 2: Ramps as fusion plants design-in; inflection 2028 with ITER procurement
- Tier 3: Late start but rapid scaling 2029+; ISO-DA09 SaaS recurring component
- Blended gross margin: 60-70% (hardware) + 85%+ (SaaS)

### 4.2 Profitability Timeline

| Metric | Year 2 | Year 3 | Year 4 | Year 5 |
|--------|--------|--------|--------|--------|
| **Operating Expenses** | $8M | $15M | $25M | $35M |
| **R&D Investment** | $5M | $8M | $10M | $12M |
| **Sales & Marketing** | $2M | $4M | $8M | $12M |
| **EBITDA** | -$5M | +$2M | +$32M | +$90M |

**Path to Profitability**: Break-even late Year 2 (2027); strong profitability by Year 4+ (2029+)

### 4.3 Capital Requirements

| Item | Amount | Timing | Purpose |
|------|--------|--------|---------|
| **Initial R&D** | $5-8M | Year 1-2 | Tier 1 products; UNITY-2 validation |
| **Manufacturing Scale-Up** | $3-5M | Year 2 | Pilot production line (Tier 1, Tier 2) |
| **SaaS Platform Development** | $8-12M | Year 2-4 | ISO-DA09 full build; regulatory approval |
| **Working Capital** | $4-6M | Year 1 | Inventory, receivables, operational buffer |
| **Total Funding Need** | **$20-31M** | | |

**Funding Strategy**:
- Series A: $10-15M (Year 1, proving Tier 1 feasibility)
- Series B: $10-15M (Year 2, UNITY-2 validation + Tier 2 development)
- Growth Equity / Strategic Investment: Post-profitability (Year 4+)

---

## 5. COMPETITIVE LANDSCAPE & POSITIONING

### 5.1 Competitive Analysis

| Competitor | Strength | Weakness | Position |
|---|---|---|---|
| **Established OEMs (Endress+Hauser, Emerson, ABB)** | Manufacturing scale; customer relationships | No tritium expertise; slow innovation | Will eventually build tritium line; 2-3 year lag |
| **National Labs (Savannah River, SRNL)** | Tritium expertise; credibility | Government-focused; slow commercialization | Potential acquirer or technology partner |
| **Academic Groups (TU Kaiserslautern, UKAEA)** | Recent publications on Raman/SoS | No commercialization path | Could file patents; slower execution |
| **IS-Instruments (UK)** | £9.6M UKAEA funding for Raman tritium detection | Single-technology focus (composition only, not flow) | Niche player; potential acquisition target |

**ISOTRACE's Competitive Advantage**:
- ✓ **Portfolio breadth**: 12 products vs. competitors' 1-2 specialties
- ✓ **End-to-end integration**: Hardware + SaaS platform (creates lock-in)
- ✓ **First-mover positioning**: UNITY-2 validation before competitors
- ✓ **Regulatory focus**: Built for compliance from day 1 (not an afterthought)
- ✓ **Real-time flow measurement**: Addresses critical gap no competitor has solved

**Risk**: Large OEMs (Emerson, ABB) could enter market in Year 3-4 with capital advantage. **Mitigation**: Lock in early customers through embedded partnerships; establish ISO-DA09 as regulatory standard before competitors can build alternative platforms.

---

## 6. IMPLEMENTATION ROADMAP

### 6.1 Year 1 (2026) — Foundation & Validation

**Q1 2026**:
- Establish legal entity and secure founding capital ($5-8M)
- Hire core team: VP Engineering (tritium expertise), Chief Scientist (patent/IP strategy), VP Sales
- Begin Tier 1 prototype development (TRI-TEMP-01, TRI-PRESS-01)

**Q2-Q3 2026**:
- Partner formalization with Kyoto Fusioneering / CNL
- UNITY-2 commissioning support begins
- First Tier 1 prototypes delivered to nuclear facilities for testing
- Patent filings: Coriolis + isotope correction (Opportunity #1)

**Q4 2026**:
- Tier 1 products ready for commercial sale
- UNITY-2 comes online; real-time data collection begins
- Revenue: $5-10M from pilot customers

**Milestones**:
- ✓ First tritium measurement data from UNITY-2
- ✓ Patent filings complete for core IP (Coriolis flow meter)
- ✓ Strategic partnerships established with CNL, Kyoto Fusioneering

---

### 6.2 Year 2 (2027) — Scale Tier 1, Begin Tier 2

**Q1-Q2 2027**:
- Tier 1 manufacturing ramping (aim for $30-40M revenue run rate)
- UNITY-2 validation data published (white paper + conference presentations)
- Tier 2 R&D accelerates (TRI-FLOW-02 Coriolis development)

**Q3 2027**:
- Major trade show presence (Tritium 2027 conference)
- First ITER procurement discussions; begin ANS system integration study
- ISO-DA09 platform architecture finalized

**Q4 2027**:
- Tier 1 revenue reaches $25M+ annualized run rate
- Patent prosecution advances; non-provisional filings
- Tier 2 prototypes ready for next phase testing

**Milestones**:
- ✓ Profitable on Tier 1 products
- ✓ ITER vendor qualification process begins
- ✓ Series B funding round ($10-15M)

---

### 6.3 Year 3-5 (2028-2030) — Commercial Fusion Growth

**2028-2029**:
- Tier 2 products (Coriolis flow meter) ready for production
- ITER procurement orders materialize ($20-50M)
- Commonwealth Fusion Systems, TAE, Helion design-in ISOTRACE sensors
- ISO-DA09 beta deployments on first fusion plants

**2030+**:
- Tier 3 products in advanced development
- SaaS revenue becomes meaningful ($5-20M annually)
- 10+ fusion plants operational, equipped with ISOTRACE instrumentation
- Market leadership position established

---

## 7. ORGANIZATIONAL STRUCTURE & KEY HIRES

### 7.1 Core Team (Year 1)

| Role | Seniority | Key Qualifications | Hiring Priority |
|------|-----------|-------------------|-----------------|
| **VP Engineering** | Director+ | 10+ years tritium/nuclear; hardware development | Critical, Hire Q1 |
| **Chief Scientist** | PhD+ | Fusion fuel cycle expertise; patent strategy | Critical, Hire Q1 |
| **VP Sales** | Director+ | Nuclear/aerospace equipment sales; B2B experience | High, Hire Q2 |
| **Product Manager** | Manager+ | Instrumentation; regulatory experience (ISO/ASME) | High, Hire Q2 |
| **SaaS Platform Lead** | Tech Lead | Cloud architecture; regulatory compliance software | Medium, Hire Q2-Q3 |
| **Manufacturing/Operations** | Manager | Semiconductor/cleanroom process management | Medium, Hire Q3 |

**Total Year 1 Headcount**: 8-12 people  
**Estimated Payroll + Benefits**: $1.5-2M

### 7.2 Board & Advisors (Establish Year 1)

**Board Seats** (4-5 people):
- CEO (founder or hired)
- Investor representative (Series A lead)
- Chair/Independent: Former ITER director or major lab tritium lead
- Optional: Major customer representative (Kyoto Fusioneering)

**Advisory Board** (5-7 people):
- Tritium scientist (Savannah River National Lab or equivalent)
- Fusion industry expert (Commonwealth Fusion Systems technical advisor or similar)
- IP/Patent strategist (deep tech commercialization)
- Regulatory expert (ITER procurement, DOE NNSA background)
- OEM partner representative (Coriolis flow meter manufacturer, e.g., ABB)

---

## 8. RISKS, MITIGATION & CONTINGENCY

### 8.1 Technical Risks

| Risk | Severity | Mitigation |
|------|----------|-----------|
| **Real-time tritium flow measurement is fundamentally difficult** | HIGH | Start with speed-of-sound (proven 2023) + thermal mass flow backup; outsource Coriolis development to established OEM partner (ABB) |
| **Radiation hardening of electronics is costly** | MEDIUM | Partner with aerospace vendors (already proven on NASA/DOD) for electronics; use modular approach (separate rad-hard vs. standard components) |
| **UNITY-2 delay or cancellation** | MEDIUM | Identify backup validation site (Savannah River, TLK Germany); begin nuclear facility deployments in parallel |
| **Isotope separation/permeation more complex than anticipated** | MEDIUM | Deep collaboration with Kyoto Fusioneering engineering team; publish jointly if technical challenges emerge |

### 8.2 Market Risks

| Risk | Severity | Mitigation |
|------|----------|-----------|
| **Fusion commercialization delayed beyond 2030** | MEDIUM | Sustained nuclear facility market (steady-state $30-50M/year); European/Japanese government funding for ITER-related work |
| **Large OEM (Emerson/ABB) enters market with capital advantage** | HIGH | Establish regulatory/customer lock-in by Year 3 (ITER approval + early plant design-ins); license IP to OEMs rather than compete directly |
| **Patent invalidation or design-around by competitors** | MEDIUM | File broad claims + continuation patents; patent prosecution strategy includes defensive claims spanning multiple measurement approaches |
| **Customer consolidation (fewer, larger fusion companies)** | MEDIUM | Shift to per-plant SaaS licensing (recurring revenue less sensitive to customer count) |

### 8.3 Regulatory & Compliance Risks

| Risk | Severity | Mitigation |
|------|----------|-----------|
| **IAEA tritium standards more restrictive than anticipated** | MEDIUM | Proactive engagement with IAEA working groups (Year 1-2); regulatory expertise hire; white papers on tritium measurement best practices |
| **Export controls on tritium technology** | MEDIUM | Legal review Year 1; possible geographic market restrictions (US, EU, Japan = accessible; China/Russia limited); licensing model for non-US markets |
| **Environmental liability if tritium release** | MEDIUM | Product design emphasizes passive safety; liability insurance; legal disclaimers; non-destructive measurement philosophy minimizes tritium loss |

---

## 9. SUCCESS METRICS & KPIs

### 9.1 Business Metrics

| KPI | Year 1 Target | Year 3 Target | Year 5 Target |
|-----|---------------|---------------|---------------|
| **Annual Revenue** | $10-15M | $70-100M | $175M+ |
| **Gross Margin** | 55% | 62% | 68% (SaaS lowers COGS) |
| **Operating Margin** | -40% | +5% | +30% |
| **Customer Count** | 3-5 | 15-20 | 40-50+ |
| **SaaS MRR / ARR** | $0 | $200k-$500k | $5-20M |

### 9.2 Technical/Product Metrics

| Metric | Target | Validation Method |
|--------|--------|-------------------|
| **Tier 1 products in field** | 4/4 launched | Sales data |
| **UNITY-2 validation successful** | ±2% accuracy achieved | Published white paper |
| **Coriolis prototype TRL** | TRL 5 by end Year 2 | Prototype testing data |
| **ISO-DA09 early adopters** | 2-3 fusion plants | Customer references |
| **Patent portfolio** | 3-5 patents filed | USPTO/WIPO filings |

### 9.3 Customer Satisfaction & Retention

| Metric | Target | Method |
|--------|--------|--------|
| **Customer NPS** | >50 | Annual surveys |
| **Renewal Rate (SaaS)** | >95% | Subscription analytics |
| **Time-to-Value** | <3 months | Customer interviews |
| **Support Satisfaction** | >90% | Help desk surveys |

---

## 10. APPENDICES

### 10.1 Product Specifications Summary

**Tier 1 Launch Roadmap**:

**TRI-TEMP-01** (Temperature Sensors)
- Range: -250°C to +150°C
- Accuracy: ±0.5°C (RTD) or ±1°C (thermocouple)
- Housing: Stainless steel 316 + PTFE insulation
- Radiation tolerance: 10^6 Gy (gamma)
- Price target: $800-1,500 per unit

**TRI-PRESS-01** (Pressure Transducers)
- Range: 0.01 Pa to 1,000 Pa (spans full fuel cycle)
- Accuracy: ±1% full scale
- Output: 4-20 mA or digital (I²C)
- Tritium barrier: Internal getter bed + sealed diaphragm
- Price target: $2,000-3,500 per unit

**TRI-FLOW-01A** (Thermal Mass Flow Meter, Low-Cost)
- Range: 10-300 μmol/s (equivalent to 0.1-2.4 mg/min tritium mass flow)
- Accuracy: ±2% (achievable with isotope correction software)
- Response time: 5-10 seconds
- Power: <1 W (battery-operable)
- Price target: $5,000-8,000 per unit

**ISO-SEAL-01** (Tritium-Compatible Seal Kit)
- Materials: PTFE, FEP, FFKM (Viton-resistant alternatives)
- Compatibility: ZrCo getter beds, stainless steel bodies
- Lifecycle: 5-10 years in tritium service (vs. 1-2 weeks for COTS seals)
- Price target: $3,000-5,000 per complete system kit

---

### 10.2 Patent Filing Timeline

**Year 1 (2026)**:
- **Provisional**: "Coriolis Mass Flow Meter with Hydrogen Isotope Compensation Algorithm" (Opportunity #1)
- **Target**: File by Q3 2026

**Year 2 (2027)**:
- **Non-Provisional**: Coriolis continuation + experimental data from UNITY-2
- **Provisional**: "Speed of Sound + Pressure/Temperature Real-Time Flow Monitor" (Opportunity #2)
- **Provisional**: "Thermal Mass Flow Meter Adapted for Tritium with Isotope Correction" (Opportunity #4)

**Year 3+ (2028-2030)**:
- **Design Patents**: Hardware configurations for key products
- **International PCT**: Extend protection to EU, Japan, Canada, Australia
- **Continuation Patents**: Narrow claims for specific variations (Raman hybrid, fiber-optic variants)

**Patent Budget**: $50-100k/year (prosecution + maintenance)

---

### 10.3 Regulatory & Compliance Roadmap

**Year 1-2**:
- ISO/ASTM standards working group engagement
- ITER ANS (Analytical System) vendor qualification application
- IAEA regulatory consultation (tritium measurement best practices)
- DoE NNSA security review (for US export control classification)

**Year 2-3**:
- ITER procurement bid preparation
- National Certification (UL, CSA, or equivalent)
- EU Fusion Nuclear Safety Committee sign-off
- Quality system development (ISO 9001 / nuclear-grade equivalent)

**Year 3+**:
- International regulatory alignment (IAEA, US, EU, Japan)
- Customer-specific regulatory pre-approvals
- Digital twin platform regulatory validation (most critical for ISO-DA09)

---

### 10.4 Customer Acquisition Timeline

**Immediate Prospects** (Year 1-2):

1. **Kyoto Fusioneering / CNL** (UNITY-2)
   - Contact: Already established partnership
   - Timeline: Instruments deployed Q3-Q4 2026
   - Value: $2-5M + validation data

2. **Tritium Laboratory Karlsruhe** (Germany)
   - Contact: TLK Director (recommendation from literature)
   - Timeline: Sales cycle Q2-Q4 2026
   - Value: $1-3M

3. **Savannah River National Laboratory** (USA)
   - Contact: SRNL Tritium Programs Manager
   - Timeline: Q3 2026 - Q2 2027
   - Value: $2-4M

4. **Canadian Nuclear Laboratories** (Chalk River)
   - Contact: Already partnered via UNITY-2
   - Timeline: Parallel opportunity Q4 2026 - Q2 2027
   - Value: $1-2M

**Medium-Term** (Year 2-3):

5. **ITER Organization** (France)
   - Contact: ANS System Manager (procurement team)
   - Timeline: Vendor qualification Q2-Q3 2027; initial orders 2028-2029
   - Value: $20-50M over 3 years

6. **Commonwealth Fusion Systems** (Massachusetts, USA)
   - Contact: VP of Engineering (SPARC project)
   - Timeline: Design-in decision Q1-Q2 2027; procurement 2028-2029
   - Value: $15-30M

---

## 11. CONCLUSION

**ISOTRACE represents a rare convergence**: 

- **Technical opportunity** (real-time tritium measurement is unsolved; solutions exist but untried)
- **Market timing** (40+ fusion companies building plants; regulatory requirement creates moat)
- **Capital efficiency** (early revenue from nuclear market; growth from fusion; SaaS for scale)
- **IP strength** (five patentable innovations; first-mover advantage in patent landscape)

The company that builds the complete tritium instrumentation suite *and integrates it into a regulatory-compliant digital platform* will achieve market leadership. ISOTRACE's $20-30M capital requirement is modest relative to a $380M TAM and achievable 5-year revenue run rate of $175M+.

**Path Forward**:
1. **Secure founding capital** ($5-8M Series A) by Q1-Q2 2026
2. **Validate on UNITY-2** (late 2026) — prove technical credibility
3. **Scale Tier 1 products** (2027) — build revenue while developing Tier 2
4. **Win ITER procurement** (2028-2030) — anchor customer + regulatory approval
5. **Establish ISO-DA09 standard** (2029-2030) — create long-term moat
6. **Become fusion energy's instrumentation leader** (2030+) — $175M+ annual revenue

---

**Document Prepared**: April 2026  
**Next Review**: Q3 2026 (post UNITY-2 commissioning)  
**Classification**: Strategic Planning (Confidential)
