# Flooring Container & Pallet Load Calculator

Free, single-file, client-side calculator for flooring exporters and importers:
enter your carton dimensions and weight, get cartons-per-container for **20GP** and
**40HQ**, floor-loaded or palletized, with load weight, volume fill and payload usage.

**Live tool: https://shuchandecor.github.io**

## Why

Flooring is a dense cargo — 8 mm SPC runs ~12 kg/m², so containers routinely hit the
payload limit before the volume limit. Most generic cubic-volume calculators get this
wrong for flooring. This one shows both limits side by side.

## Features

- 20GP and 40HQ side by side
- Floor-loaded or palletized (110×110 cm industrial pallet, ~1.8 m stack)
- Payload cap warning when weight, not volume, is the constraint
- Everything computed in the browser — no tracking, no backend, no signup

## Use it

Open https://shuchandecor.github.io, type your carton spec from the packing list,
press Calculate. Estimates for planning only — confirm final loading with your
freight forwarder.

## Maintained by

[SHUCHAN FLOORING](https://shuchanflooring.com) — SPC & laminate flooring factory in
Changzhou, China. We also maintain a [landed-cost calculator](https://shuchanflooring.com/landed-cost-calculator)
on our site.

MIT licensed. PRs welcome.
