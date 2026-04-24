# ISOTRACE Changelog

All notable changes to this project are documented in this file. This project follows semantic versioning principles for research documentation updates.

## [Unreleased]

### Added
- Infrastructure files (CLAUDE.md, .gitignore, CONTRIBUTING.md, CHANGELOG.md)
- Codebase documentation and contribution guidelines
- Git configuration for version control

## [0.2.0] — 2026-04-24

### Added
- **BUSINESS_PLAN.md**: Comprehensive 30+ page strategic business plan covering:
  - Market analysis (tritium fuel cycle challenges, fusion fleet projection)
  - Complete 12-product portfolio across 3 development tiers
  - Go-to-market strategy (nuclear facilities first, then commercial fusion)
  - Financial projections and capital requirements
  - Risk assessment and mitigation strategies
  - Customer segment analysis and sales strategy

### Changed
- Merged from draft branch `claude/draft-business-plan-xligf` to main
- Integrated with existing research artifacts

## [0.1.0] — 2026-04-20

### Added
- **README.md**: Executive summary with:
  - Problem statement (tritium instrumentation gap)
  - Key findings on measurement technologies, patents, and market TAM ($380M)
  - Research methodology and caveats
  - High-level commercial opportunity statement

- **tritium_measurement_technologies.md**: Comprehensive survey of tritium measurement approaches:
  - Calorimetry (batch, 5-20 hour cycle, high accuracy)
  - Pressure-Volume-Temperature (PVT) method (batch, hours)
  - Raman spectroscopy (emerging, real-time, IS-Instruments commercializing)
  - Ionization chambers (real-time, indirect)
  - Mass spectrometry (batch, laboratory-based)
  - Liquid scintillation counting (batch, lab-based gold standard)
  - **Key finding**: No real-time tritium flow meter exists in commercial market

- **tritium_flow_measurement_patent_analysis.md**: Patent landscape covering:
  - Patent state-of-the-art for tritium flow measurement
  - Zero patents on tritium-specific Coriolis flow measurement
  - Graphene isotope separation published science with no instrumentation patents
  - Five identified patent opportunities:
    1. Isotope-compensated Coriolis flow + composition (highest value)
    2. Graphene-based tritium separator
    3. Speed-of-sound composition with drift correction
    4. Permeation barrier validation sensor
    5. Digital tritium accountability platform
  - Freedom-to-operate (FTO) analysis for each opportunity

- **tritium_instrumentation_portfolio.html**: Interactive visual portfolio containing:
  - 12 instruments organized by tritium fuel cycle subsystem
  - 3-tier development roadmap (Tier 1: launch-ready; Tier 2: fusion-validation; Tier 3: emerging)
  - Per-product market sizing and TAM contribution
  - Technology maturity assessment (TRL levels)
  - Commercial timeline projections

### Initial Upload (2026-04-19)
- Core research artifacts uploaded to repository
- Initial git repository initialization

---

## Version Numbering

This project uses semantic versioning adapted for research documentation:

- **MAJOR (X.0.0)**: Fundamental shift in product portfolio, market analysis, or strategic direction
- **MINOR (x.Y.0)**: Significant new content (new products, markets, or research areas)
- **PATCH (x.y.Z)**: Corrections, updates, or clarifications to existing content

## Update Cadence

- **Quarterly**: Market data review (TAM estimates, company timelines, fleet projections)
- **As-needed**: Patent landscape updates (new filings), technical assessments (new research)
- **Annual**: Comprehensive review and validation of all assumptions

## Notable Future Milestones

**Expected additions (not yet committed)**:
- Structured data assets (CSV/JSON for instruments, competitors, patents)
- Technical specification sheets for Tier 1 products
- Visual diagrams (tritium cycle, product hierarchy, market timeline)
- Detailed go-to-market playbook
- Quarterly market data updates

---

**Last Updated**: April 2026
