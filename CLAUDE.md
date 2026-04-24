# ISOTRACE — Codebase Documentation

## Project Overview

ISOTRACE is a strategic research initiative mapping the commercial opportunity in tritium instrumentation for fusion energy. This repository contains comprehensive research artifacts analyzing market gaps, patent landscapes, technology assessment, and a product portfolio strategy.

**Core thesis**: Every fusion company building a deuterium-tritium (D-T) reactor needs dozens of tritium-compatible instruments that don't exist in the commercial off-the-shelf (COTS) market. The first company to build a complete, fusion-qualified instrumentation suite—integrated with a regulatory-compliant digital accountability platform—will become the sector's dominant supplier.

## Repository Structure

```
.
├── README.md                                  # Project overview and key findings
├── BUSINESS_PLAN.md                           # 30+ page strategic business plan
├── tritium_measurement_technologies.md        # Survey of measurement techniques & gaps
├── tritium_flow_measurement_patent_analysis.md # Patent landscape & 5 opportunities
├── tritium_instrumentation_portfolio.html     # Visual product portfolio (12 products, 3 tiers)
├── CLAUDE.md                                  # This file — codebase documentation
├── CHANGELOG.md                               # Version history
├── CONTRIBUTING.md                            # Contribution guidelines
└── .gitignore                                 # Git configuration
```

## Key Documents

### README.md
Executive summary with:
- One-paragraph problem statement
- Research methodology  
- Major findings on measurement, patents, and market TAM ($380M)
- Timeline to revenue (Y1-2 nuclear market, Y2-3 fusion validation, Y3-5 commercial inflection)

### BUSINESS_PLAN.md
Comprehensive 30+ page strategic document covering:
- **Section 1**: Market context (tritium challenges, fusion fleet projection, customer segments)
- **Section 2**: Product portfolio (12 instruments across Tier 1/2/3 by maturity)
- **Section 3**: Go-to-market strategy (nuclear first, then fusion)
- **Section 4**: Financial projections and capital requirements
- **Section 5**: Risk assessment and mitigation

### tritium_measurement_technologies.md
Technical survey of all current tritium measurement approaches:
- **Calorimetry**: batch, slow, high accuracy (reference standard)
- **Pressure-Volume-Temperature (PVT)**: batch, hours, composition inference
- **Raman spectroscopy**: emerging, real-time, IS-Instruments commercializing
- **Ionization chambers**: real-time, indirect, deployed at ITER
- **Mass spectrometry**: batch, precise, slow
- **Liquid scintillation counting (LSC)**: batch, lab-based, gold standard

Key gap: **No real-time tritium flow meter exists**. All commercial approaches are batch processes.

### tritium_flow_measurement_patent_analysis.md
Patent landscape analysis identifying:
- **Zero patents** on tritium-specific Coriolis flow measurement
- **Graphene isotope separation** (published science, H/T separation factor ~30 vs. ~1.8 for cryo) has no instrumentation patents
- **5 high-value patent opportunities** identified:
  1. Isotope-compensated Coriolis flow + composition (strongest)
  2. Graphene-based tritium separator
  3. Speed-of-sound composition with real-time drift correction
  4. Permeation barrier validation sensor
  5. Digital tritium accountability platform (software/firmware)

### tritium_instrumentation_portfolio.html
Interactive HTML visualization showing:
- **12 products** organized by subsystem (storage, processing, injection, extraction, safety, digital)
- **3 development tiers**:
  - Tier 1 (4 products): Launch-ready, nuclear market addressable now
  - Tier 2 (4 products): Needs fusion validation, available 2027-2028
  - Tier 3 (4 products): Emerging tech, 2029+
- **Market sizing**: Per-plant instrument counts, fleet projections, TAM per product
- **Development roadmap**: Timeline, technical risks, commercialization path

## Research Methodology

All artifacts produced using:
- Patent database searches (Google Patents, OSTI, USPTO)
- Literature review of ITER, DEMO, UNITY-2 technical docs
- Tritium 2025 conference abstracts
- EU Fusion Fuel Cycle Technology Mapping Report (F4E/EUROfusion, 2025)
- DOE EPRI Fusion Fuel Cycles Workshop report (2024)
- Public announcements from Kyoto Fusioneering, Air Squared, Pfeiffer Vacuum, IS-Instruments

**Caveats**:
- TAM estimates are bottom-up order-of-magnitude approximations, not financial projections
- TRL assessments reflect public information as of April 2026
- Patent assessments are indicative; formal FTO opinions require legal counsel

## Key Findings Summary

### Market Opportunity
- **$380M combined TAM** across 12 products
- **Near-term revenue** ($20-30M, 2026-2028): Existing nuclear tritium facilities (ITER, TLK, CNL, SRNL)
- **Medium-term** ($50-100M, 2028-2032): First fusion plants operational, validation on UNITY-2 (Kyoto Fusioneering, late 2026)
- **Long-term** ($200M+, 2032+): 15-30+ commercial plants online

### Competitive Advantage
The **digital twin/accountability platform (ISO-DA09)** is the long-term moat:
- Every hardware sensor becomes a data node
- Regulatory requirement (tritium inventory tracking)
- SaaS recurring revenue model
- Creates switching cost for customers (regulatory compliance lock-in)

### Critical Success Factors
1. **Tier 1 execution**: Ship 4 products to nuclear market by 2027 (proves technology, generates cash)
2. **UNITY-2 validation**: Demonstrate fusion-grade reliability on Kyoto Fusioneering's reactor (late 2026)
3. **Digital platform integration**: Couple hardware with proprietary accountability software (creates moat)
4. **Patent portfolio**: File 5 identified patent opportunities (protect IP, create licensing revenue)

## What's Next

### Planned Extensions (Not Yet Implemented)
- **`data/`** directory: Structured CSV/JSON for instruments, competitors, patent opportunities
- **`assets/`** directory: Diagrams of tritium fuel cycle, product portfolio hierarchy, market timeline
- **Technical specifications**: Detailed specs for Tier 1 products (pressure range, accuracy, radiation tolerance)
- **Roadmap.md**: Explicit 5-year development timeline with engineering milestones
- **Market analysis deep-dives**: TAM by geography, customer segment sensitivity analysis

### How to Contribute

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Adding or revising research findings
- Updating market data and projections
- Expanding technical analyses
- Improving documentation

## Document Generation Notes

The HTML portfolio is manually created and maintained separately from markdown docs. To sync changes:
1. Update product details in BUSINESS_PLAN.md or this file
2. Regenerate the HTML portfolio (template-based; contact repo owner for tooling)
3. Commit both markdown and HTML together

## Questions & Contact

For technical questions about the research:
- Review the Caveats section in README.md
- Check BUSINESS_PLAN.md Section 1 for market context
- Review patent_analysis.md for FTO questions (not legal advice)

For contributions or feedback:
- Submit issues or PRs per CONTRIBUTING.md
- Contact: isotrace@research.lab (listed in BUSINESS_PLAN.md)

---

**Last Updated**: April 2026  
**Status**: Active research, quarterly updates planned
