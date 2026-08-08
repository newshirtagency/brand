New Shirt Agency - Client Logo Library
======================================
Canonical client brand marks for automated report rendering.

Naming: clients/<slug>-<light|dark>.png
  -light  for LIGHT report headers (paper #FFFFFF / tint #EFEDF4)
  -dark   for DARK report headers  (ink #0A0C12) - the weekly client report, per D-2026-08-06-49

Every file is a transparent PNG rendered at 2x its display box (124px tall; Somma is
width-constrained at 680px wide). Fetch it, then embed as a data URI. Do not hotlink from a
client-facing page.

CDN (fetch these):
  https://cdn.jsdelivr.net/gh/newshirtagency/brand@main/clients/<slug>-<variant>.png

Slugs and the client each belongs to:
  somma, dave-koz, friends-at-sea, redwood   ->  BW    (Bridgeway Entertainment)
  two-rock, divided-by-13                    ->  TR13  (Two-Rock and Divided by 13)
  frankie-valli                              ->  FV    (Frankie Valli and the Four Seasons)

Choosing a variant: match the ground you are rendering on, not the client's website. A mark
built for a light header is invisible on ink and the reverse is equally true. If you cannot
tell which ground you are rendering on, that is a bug - resolve it before picking a file.

Dark variants are derived, not redrawn. Single-colour line art is recoloured flat to
Bright #FFFDF7. Knockout marks (the Divided by 13 disc, where the glyph is cut out of a
filled shape) are luminance-inverted, because recolouring one flat collapses it into a solid
blob. Friends at Sea keeps its blue triangle and navy figure and brightens only the wordmark.
Redwood is luminance-lifted with saturation restored. Somma's gold already carries on ink and
is byte-identical in both variants.

A missing slug is a REPORTED FAILURE. Never fall back to a wordmark silently - a report that
quietly drops a client's mark looks identical to one that never had it.

Pending: summer-horns (Dave Koz and Friends Summer Horns). Artwork exists and is held by John;
it is not published here because no Summer Horns report page exists yet. Its mark is yellow
#FFE500 on red #F10043 - it reads well on ink and very poorly on the light tint, so it needs a
deliberate treatment before it goes on a light header.

Provenance: supplied by the client or the brand's own site, processed 2026-08-08.
Masters and per-brand colour specs: NSA SharePoint, 06_Clients/<Brand>/report-branding.md.
