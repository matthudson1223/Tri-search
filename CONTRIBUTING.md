# Contributing to ISOTRACE

Thank you for your interest in contributing to ISOTRACE! This document outlines how to contribute research findings, corrections, and improvements.

## Code of Conduct

- Be respectful and constructive in all discussions
- Assume good faith in feedback and contributions
- Focus on the research quality and accuracy, not personalities

## How to Contribute

### Reporting Inaccuracies or Gaps

If you find factual errors, outdated market data, or research gaps:

1. **Open an issue** describing:
   - What is inaccurate or missing
   - Supporting evidence (citations, sources, links)
   - Suggested correction if you have one
   - Date the issue was identified

2. **Title the issue** clearly:
   - `[Correction] ...` for factual errors
   - `[Gap] ...` for missing research areas
   - `[Data Update] ...` for outdated market projections

### Adding or Revising Research

For substantive contributions (market analysis, patent findings, technical assessments):

1. **Fork the repository** and create a feature branch:
   ```bash
   git checkout -b feature/your-research-topic
   ```

2. **Add or revise content** following the style guide below

3. **Cite your sources** inline:
   - Use markdown links `[Source Name](URL)` for web sources
   - Include publication dates where relevant
   - For patents, use full patent number format (e.g., US Patent 10,234,567)

4. **Commit with a clear message**:
   ```
   Add market analysis for tritium storage systems
   
   - Added TAM estimate for dedicated tritium storage
   - Reviewed 5 academic sources + 3 industry reports
   - Cross-checked with ITER tritium inventory requirements
   ```

5. **Submit a pull request** with:
   - Title describing the change
   - Detailed description of what was added/revised
   - Supporting sources and evidence
   - Any assumptions or caveats

### Content Style Guide

**Markdown Formatting**:
- Use clear headers (H1 for sections, H2 for subsections)
- Keep paragraphs short (2-4 sentences)
- Use bullet points for lists of items
- Use tables for comparative data (technology, products, etc.)

**Source Attribution**:
- Quote directly only when precise wording matters; otherwise paraphrase
- Always include source URLs or citations
- Note publication date (especially important for fusion/market research)
- Indicate if information is from conference talks vs. peer-reviewed literature

**Language**:
- Write in clear, technical English
- Avoid marketing language; stick to factual assessment
- Distinguish between:
  - **Established fact** ("ITER ... is projected to...")
  - **Informed estimate** ("Market analysis suggests ~$380M TAM")
  - **Opinion/speculation** ("We believe the first patent to...")

**Data Accuracy**:
- Verify fusion fleet projections against latest company announcements
- Check patent claims against USPTO/Google Patents directly
- Cross-reference TAM estimates with multiple sources
- Note when data becomes outdated (e.g., company timelines change)

## Pull Request Review Process

1. **Initial check**: Does the PR follow the style guide and cite sources?
2. **Fact verification**: Are claims supported by evidence?
3. **Scope check**: Does it fit ISOTRACE's mission (tritium instrumentation, fusion context)?
4. **Merge**: Once approved, the PR is merged to `main`

### When PRs May Not Be Merged

- Speculation or opinion without clear evidence
- Marketing/promotional content (ISOTRACE is research, not sales)
- Out-of-scope topics (e.g., general fusion physics without instrumentation context)
- Unverified market data without source citations

## Updating Market Data

Market projections and TAM estimates should be refreshed quarterly:

1. **Before updating**:
   - Verify latest fusion company announcements
   - Check EUROfusion technical reports for ITER/DEMO updates
   - Review recent conference proceedings (Tritium 2025, etc.)
   - Update competitor landscape if companies announced new products

2. **Document changes**:
   - Update CHANGELOG.md with date and what changed
   - Note which projections increased/decreased and why
   - Flag if external assumptions changed (e.g., fusion fleet timeline slip)

3. **Communicate uncertainty**:
   - If TAM is uncertain, state the range and assumptions
   - Note if any company's timeline has slipped recently
   - Highlight when external data (e.g., ITER schedules) changed

## Questions?

- Review [CLAUDE.md](CLAUDE.md) for project structure and context
- Check existing issues for similar questions
- Review BUSINESS_PLAN.md Section 1 for market/technical background

---

**Last Updated**: April 2026
