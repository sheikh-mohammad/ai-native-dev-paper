<!--
  SYNC IMPACT REPORT
  ==================
  Version change: 1.1.1 → 1.2.0
  Modified principles: None
  Added sections:
    - Changelog section for version history tracking
  Removed sections: None
  Templates requiring updates:
    - .specify/templates/plan-template.md ✅ No changes needed
    - .specify/templates/spec-template.md ✅ No changes needed
    - .specify/templates/tasks-template.md ✅ No changes needed
    - .specify/templates/checklist-template.md ✅ No changes needed
  Follow-up TODOs: None
-->

# AI-Native Software Development Research Paper Constitution

## Core Principles

### I. Primary Source Verification

All factual claims MUST be verified against primary sources. Secondary sources may be
used for context but MUST trace back to primary research. Every assertion requires
documented evidence from original research papers, official documentation, or direct
empirical data.

**Rationale**: Ensures accuracy and prevents propagation of misinterpreted or diluted
information through citation chains.

### II. Academic Clarity

Writing MUST target a computer science academic audience with clarity standards
maintaining Flesch-Kincaid grade level 10-12. Technical terminology is acceptable
when precise, but prose MUST remain accessible to readers with undergraduate CS
backgrounds. Complex concepts MUST be explained with structured logic and concrete
examples.

**Rationale**: Balances technical depth with readability, ensuring research reaches
its intended audience without unnecessary obscurity.

### III. Reproducibility & Traceability

All claims MUST be cited and traceable to their sources. Every methodology described
MUST include sufficient detail for independent reproduction. Data collection processes,
analysis methods, and interpretation frameworks MUST be documented with precision
enabling verification by peer researchers.

**Reproducibility Standard**: Methodology sections MUST include:
- Input data specifications (format, size, source)
- Step-by-step procedures (numbered, no skipped steps)
- Expected outputs or success criteria
- Tools/versions used (exact version numbers)

**Test**: A peer researcher can replicate results following only the documented steps.

**Rationale**: Scientific rigor requires that findings can be independently verified
and built upon by the research community.

### IV. Peer-Review Rigor

Sources MUST be evaluated for methodological quality, recency, and relevance. 
Conference papers, journal articles, and formally reviewed preprints are preferred 
over informal publications, blog posts, or uncensored sources.

**Source Tier System**:
- **Tier 1 (Required, 40%+)**: Peer-reviewed articles, conference papers
- **Tier 2 (Allowed, 30%+)**: Official documentation, technical reports, verified preprints
- **Tier 3 (Limited, ≤30%)**: Authoritative blog posts, recorded talks, industry whitepapers
  - Must be from recognized experts/organizations
  - Must be archived (Wayback Machine or institutional repository)
  - Maximum 5 Tier 3 sources total

**Rationale**: Peer review provides quality assurance. AI-native development is emerging;
some concepts exist only in practitioner literature while maintaining academic rigor.

## Academic Writing Standards

**Citation Format**: APA style (7th edition) mandatory for all references.

**Citation Accuracy**: 100% of citations must pass verification spot-check
(10 random citations verified against original sources with zero mismatches).

**Source Requirements**:
- Minimum 15 total sources
- Tier 1 (Peer-reviewed): 40%+ (6+ sources)
- Tier 2 (Technical docs/reports): 30%+ allowed
- Tier 3 (Practitioner sources): ≤30%, maximum 5 sources total

**Plagiarism Policy**: Zero tolerance (0%). All borrowed ideas, phrases, or data
MUST be properly attributed. Paraphrasing MUST substantially rephrase and cite.
Direct quotations MUST use quotation marks and page numbers.

**Document Specifications**:
- Word count: 5,000-7,000 words (excluding references and appendices)
- Format: PDF with embedded citations and reference list
- Structure: Abstract, Introduction, Methodology, Results, Discussion, Conclusion,
  References

## Research Quality Gates

**Pre-Submission Checklist**:
- [ ] All factual claims verified against primary sources
- [ ] Citation format consistent (APA 7th edition)
- [ ] Citation accuracy spot-check passed (10 random, 0 mismatches)
- [ ] Source tier thresholds met (Tier 1: 40%+, Tier 3: ≤5 sources)
- [ ] Plagiarism check passed (0% similarity before submission)
- [ ] Writing clarity validated (Flesch-Kincaid grade 10-12)
- [ ] Word count within range (5,000-7,000)
- [ ] Minimum 15 sources documented
- [ ] PDF format with embedded citations

**Review Process**:
1. **Fact-Checking Review**: Independent verification of all claims against sources
2. **Plagiarism Scan**: Automated similarity check before submission
3. **Clarity Review**: Readability assessment targeting CS academic audience
4. **Format Compliance**: APA style and document structure validation

## Governance

**Amendment Process**: Constitution amendments require documentation of proposed
changes, rationale for modification, and approval before implementation. All
amendments MUST preserve the core principles of accuracy, clarity, reproducibility,
and rigor.

**Versioning Policy**: Semantic versioning (MAJOR.MINOR.PATCH):
- MAJOR: Changes to core principles or removal/addition of principles
- MINOR: New sections, expanded guidance, or material changes to standards
- PATCH: Clarifications, wording improvements, typo fixes

**Compliance Review**: All research outputs MUST be evaluated against this
constitution before submission. Deviations require explicit justification and
documentation.

**Supersession**: This constitution supersedes all other writing practices and
standards for this research project.

## Changelog

All notable changes to this constitution are documented in this section.

### Version [1.2.0] - 2026-03-20
**Added**:
- Changelog section for tracking version history

### Version [1.1.1] - 2026-03-20
**Fixed**:
- Replaced non-English characters with "uncensored" for consistency

### Version [1.1.0] - 2026-03-20
**Changed**:
- Reproducibility standard: Added testable criteria (inputs, steps, outputs, versions)
- Source requirements: Replaced rigid 50% peer-reviewed with tier-based system (40/30/30)
- Added citation accuracy spot-check requirement (10 random, 0 mismatches)

### Version [1.0.0] - 2026-03-20
**Added**:
- Initial constitution with 4 core principles
- Academic Writing Standards section
- Research Quality Gates with Pre-Submission Checklist
- Governance framework with amendment process and versioning policy

---

**Version**: 1.2.1 | **Ratified**: 2026-03-20 | **Last Amended**: 2026-03-20
