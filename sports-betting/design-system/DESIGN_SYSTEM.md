# Apex Sportsbook design system (v1)
Source: apex-sportsbook-homepage.html (2026-10-16, Angelo's brief "Website Design Brief: Sports Betting Platform"). Verified = read from the source CSS/JS. Inferred = judgement, marked.

## Principles
- Dark, sports-broadcast feel: scorebug rows, ticker, big condensed-weight scores. Restrained: one accent (#36D399).
- Readability over decoration: ruled lists, no card-per-row, no glass, no blobs.
- Trust: simulated data always labeled; estimated returns never "guaranteed"; no default stake; responsible-gambling links on slip, homepage, footer.
- Never rely on colour alone: live = dot + "LIVE" word; selected odd = fill + "Selected" word.

## Foundations
See tokens.json and styles.css (:root). Depth: bg (#10141C) < surface (#191F2B) < card (#222A38), 1px #30394A borders, no shadows. Radius 8 controls / 12 panels. Type: Inter stack, tabular numerals for all numbers, heavy uppercase display headline. Green = selected/positive UI only, never "winning".

## Imagery
Photography: dark, moody, floodlit sport (Magnific, Seedream), no text/logos, shown with dark gradient overlay (hero 90% opacity under left-to-right dark gradient; cards bottom gradient). Product images: the UI itself (slip, odds rows). Icons: 22px outline, 1.8 stroke, currentColor (sport icons inline SVG).

## Files
components.md, page-patterns.md, responsive-and-interactions.md, design-qa.md, styles.css, assets/ (3 photos, jpeg; originals in Magnific).
