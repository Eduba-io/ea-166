# Homecare Application Inc. Landing Page

Intended URL path: /for/homecare-application-inc

## What this page does

A single bespoke landing page built for the Homecare Application Inc. conversation at eMerge Americas 2026 (booth SS29). It carries the fit-analysis pitch body in a healthcare-native visual system drawn from `Brand Pack/brand-pack.json`: navy primary, sky-blue secondary, green accent, Source Sans 3 throughout. Eduba branding only appears once, in the footer, per the disclosure rules in `eduba-conference-sprint/templates/company-output-template.md` sections 9 to 13.

## Booth flow

1. Matt opens the page on his phone during the booth conversation.
2. Hero headline states the read. Lede frames the three home-care app pain points.
3. Pitch body carries the Feeld reference, the 60/30/10 layering frame, and the Ethics Engine citation with real anchor links.
4. CTA block routes to Matt's Calendly at https://calendly.com/thecro-eduba/30min.

## Files

- `index.html`: single static page, semantic HTML
- `styles.css`: all styles. No JavaScript, no external JS
- One webfont is loaded (Source Sans 3) because the brand pack names it explicitly as both heading and body family

## Notes for the agency-side handoff

- No pricing for any past Eduba engagement appears on the page. "Scoped sprint" replaces the prior dollar figure.
- All URLs are real anchors with `target="_blank" rel="noopener"`.
- Ethics Engine is introduced with its one-sentence bio and both canonical links in a single sentence.
- No logo file was available for Homecare Application Inc. at build time. The page uses a neutral mark built from the brand tokens plus a text wordmark. Swap in an official logo whenever it becomes available.
- The page is English only. Brand pack did not flag a bilingual market.
