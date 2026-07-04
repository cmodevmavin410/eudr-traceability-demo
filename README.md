# EUDR Farm-to-Export Traceability — Interactive Demo

An interactive, click-through demo of a **deforestation-free supply chain** under the
**EU Deforestation Regulation (EUDR)** — from a smallholder farmer's self-audit all the way
to EU export and full trace-back.

**▶ Live demo:** https://cmodevmavin410.github.io/eudr-traceability-demo/

---

## What it shows

The demo walks through a single platform built from two connected modules:

- 🟢 **Compliance** — plot mapping, GeoJSON export, deforestation check, and Due Diligence Statement (DDS)
- 🔵 **Marketplace** — farmer self-audit, product listing, and selling

### The 7-step flow

1. **Farmer self-audit** — declare against the three core EUDR conditions
2. **Map the plot** — draw the boundary on a real map; area is computed in hectares & rai
3. **Generate GeoJSON** — export a standards-compliant geolocation file (downloadable)
4. **Deforestation check** — screen the plot against the 31 Dec 2020 EUDR cut-off *(simulated)*
5. **Issue a Due Diligence Statement (DDS)** — generate the certificate with a scannable QR
6. **List for sale** — the verified product becomes sellable on the marketplace
7. **Full trace-back** — follow the product from EU export all the way to the original plot

The map, GeoJSON export, and QR code are **fully functional**. The satellite deforestation
check is **simulated** for the demo.

## Tech

- HTML + vanilla JavaScript (no build step)
- [Leaflet](https://leafletjs.com/) for interactive mapping
- Geodesic polygon area calculation
- GeoJSON generation & download
- QR code generation

## Disclaimer

This is an **independent portfolio project** by **Adisak Kueanun**, built with **fictitious
sample data**. It contains no source code, data, branding, or assets from any employer or
commercial product. The EUDR compliance workflow modelled here is based on publicly available
EU regulatory requirements.
