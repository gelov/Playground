# Design QA: findings on the reference page (not changed in the source)
Inconsistencies and proposed fixes:
1. Colours outside tokens (warning #f0b94a, error text #ff8a8e, warning/success surfaces, form chips) are hardcoded in places; fix: promote to CSS variables (already listed in tokens.json).
2. Inline styles on a few elements (sections' padding, tennis card min-height, select labels); fix: utility classes.
3. Dead rule `.slip-x`; remove.
4. Hero lead text sits over a bright floodlight on mobile, contrast not measured; fix: stronger overlay under text at <=860, then measure.
5. Inter not embedded (system sans fallback); fix: bundle woff2 for Inter + tabular numerals.
6. Competition and team marks are text placeholders; fix: licensed assets.
7. Breakpoints (1100/860/600) are defined in CSS only; keep as tokens.
8. Slip bottom sheet, lower sections and keyboard flow were not visually reviewed; Impeccable and Taste inspector did not run.
