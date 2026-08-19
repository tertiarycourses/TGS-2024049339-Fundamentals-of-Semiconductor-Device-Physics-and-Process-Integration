# Source Coverage - v7.0

## Design reference

- Source: `reference/Master Mobile Photography-v12.0.pptx`
- Source slide count: 140
- Treatment: the v7 deck follows its slide-level design patterns, including the cover composition, left accent rail, kicker/title/rule hierarchy, four-card concepts, process flows, section cards, activity scenario + visual + deliverable pattern, and acceptance-review styling.

## Legacy semiconductor coverage

- Source: `reference/WSQ - Master Trainer Slides - Fundamentals of Semiconductor Device Physics and Process Integration - v5.pptx`
- Source slide count: 446
- Embedded pictures: 411
- Treatment in v7.1: all legacy instructional text and safe embedded instructional pictures are retained, but the old deck layout is not copied. Seventeen image-only source slides plus the standalone packaging-video reference are merged into nearby explanatory slides, eliminating standalone visual/video-reference pages. The optional video URL is kept in Activity 8 rather than the PPT. Images use aspect-preserving contain geometry. Admin, activity and closing slide numbers are generated in `slide_map.json` and drive the LG, LP, activity packs and assessment references.
- Safety exception: the legacy slide 442 cross-course certificate/TRAQOM QR screenshot is intentionally excluded because it exposes another course reference and course-run ID.
- Corrected ranges: LU1 slides 16-298; LU2 slides 299-440; activities slides 441-448.

## Generated visuals

- `semiconductor-cover-hero-v2.png`
- `device-physics-hero-v2.png`
- `wafer-fabrication-hero-v2.png`
- `process-integration-hero-v2.png`
- `reliability-analysis-hero-v2.png`
- `advanced-packaging-hero-v2.png`

All generated visuals contain no text, logos, UI labels or watermarks. The PPT retains editable title and organisation text.

## Cross-artifact alignment

- Trainer deck: v7.0, 454 slides.
- Learner Guide: v4.0, with corrected topic and activity slide references.
- Lesson Plan: v5.0, with corrected Day 1/Day 2 ranges and activity mapping.
- Activities: eight self-contained folders; each README/PDF names its supporting concept range and overview slide.
- Assessment: v2.1; original two-question WA and two-task Case Study retained, with K1-K2 / A1-A5 coverage and explicit activity references on Case Study tasks.

## Deliberate exclusions

- No practice exam.
- No detailed activity procedure in the PPT.
- No stale cross-course QR code, course reference or course-run identifier.
