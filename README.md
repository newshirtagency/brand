New Shirt Agency - Web Logo Kit
================================
Clean, web-ready exports generated from the vector masters in this folder's parent.
Naming: nsa-<lockup|icon|wordmark>[-stacked]-<color|navy|white>.<svg|png>

- Prefer the .svg for anything that scales (web, docs, print). PNGs are 1024px wide, transparent.
- -color = full brand (Navy #313D66 + Ash #A5B7CA). -navy = single-color navy. -white = for dark backgrounds.
- See _contact-sheet.png for a visual index.

WORDMARK-ONLY (added 2026-08-09): nsa-wordmark-<color|navy|white>.<svg|png> - the two-line
"New Shirt / Agency" type with the chevron icon removed, viewBox tightened to the type.
Derived from nsa-lockup-color.svg, so the letterforms are identical to the lockup by
construction. Use it where the icon is already present or where the lockup's left margin
wastes horizontal space. PNGs are 1200x509. -color puts Agency in Ash; -navy and -white are
single-colour, matching the lockup convention.

Recommended hosting: sync this folder to your website at /assets/brand/ so files resolve at
stable public URLs (e.g. https://newshirt.agency/assets/brand/nsa-lockup-color.svg) for use in
HTML, email signatures, and documents. SharePoint remains the master.

CLIENT MARKS live in clients/ - see clients/README.md and, canonically,
NSA SharePoint 00_KnowledgeBase/04_Operations/STANDARD - Client Logo Library.md

FETCHING FROM AUTOMATION: use raw.githubusercontent.com, NOT a CDN mirror.
jsDelivr is unreachable from the report-building sandbox (no route) and a run that reaches for
it silently falls back to plain text. Verified 2026-08-09.
  https://raw.githubusercontent.com/newshirtagency/brand/main/<file>
Fetch and inline the bytes. Do not hotlink a logo from a client-facing page.
