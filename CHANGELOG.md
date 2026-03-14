# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.5.1] - 2026-03-14

### Changed

- `speckit.forge.design-system` — added Design Principles section, component status overview table, Figma MCP support, handoff metadata, and Spec-Driven Integration guidance. Cross-referenced from Supernova (component health, design principles), Figma MCP server (design context extraction), and Spec Kit core commands (handoff patterns).
- `speckit.forge.component` — added component health status (Draft/In Progress/Ready/Deprecated), "Also known as" alternative names, Related Components section, Content Guidelines section, Figma MCP support, handoff metadata, and Spec-Driven Integration guidance. Cross-referenced from Supernova (health dimensions), UI Guideline (cross-system naming from 20 top systems), Component Gallery (alternative names from 95 systems), and Figma MCP server.
- `speckit.forge.design-tokens` — added token modes concept (beyond light/dark), Figma MCP support (variable extraction), handoff metadata, and Spec-Driven Integration guidance. Cross-referenced from Figma MCP server (variable/style extraction) and Supernova (arbitrary modes).

## [0.5.0] - 2026-03-14

### Added

- `speckit.forge.design-system` command — initialize or update a project design system specification with guided questions, constitution alignment, semantic versioning, and cross-platform support (iOS, Android, Web). Adapted from r-a-f-a/spec-kit PR #1526 (execution flow, versioning rules) and HugoPalomares/design-intent-for-sdd (design intent concept).
- `speckit.forge.component` command — design and spec a reusable component with full documentation: anatomy, variants, sizes, states, props/API, accessibility, platform notes, usage guidelines, and code examples. Cross-referenced from Supernova component docs (8-section structure) and Storybook autodocs (code example patterns).
- `speckit.forge.design-tokens` command — manage design tokens in a 3-tier hierarchy (primitive → semantic → component) with platform-specific code blocks. Token taxonomy follows W3C DTCG specification (2025.10); naming follows Style Dictionary CTI hierarchy.

## [0.4.0] - 2026-03-14

### Added

- `speckit.forge.review-design` command — design system compliance reviewer supporting Apple HIG, Material Design 3, and Web (WCAG 2.2) with auto-detection, 6 review dimensions, `DESIGN.md` customization, and confidence scoring. Cross-referenced from raintree-technology/hig-doctor (review categories, scoring model) and HugoPalomares/design-intent-for-sdd (design intent concept, project config).
- `speckit.forge.review-ux` command — UX heuristic evaluator based on Nielsen's 10 usability heuristics adapted for code-reviewable checks, with confidence scoring and constitution-aware severity.

## [0.3.0] - 2026-03-14

### Added

- `speckit.forge.review-code` command — code review with confidence scoring, 8 review dimensions, constitution-aware severity, and `REVIEW.md` customization support. Cross-referenced from ismaelJimenez/spec-kit-review (confidence thresholds, severity grouping), Claude Code Review (REVIEW.md pattern), and industry best practices (8 pillars).

## [0.2.0] - 2026-03-14

### Added

- `speckit.forge.retrospective` command — merged best of existing workflow (interactive gates, proposed edits, experiments) with emi-dm patterns (quantitative spec adherence, drift analysis, severity classification, self-assessment checklist, file persistence)

## [0.1.0] - 2026-03-14

### Added

- Initial release of the Forge extension
- `speckit.forge.roadmap` command for creating and updating multi-file product roadmaps
