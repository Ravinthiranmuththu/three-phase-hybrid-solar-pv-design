# Three-Phase Hybrid Solar PV + Battery Storage | Engineering Portfolio

**Design and Cost Estimation of a 9.90 kWp Three-Phase Hybrid Solar PV System with 20.48 kWh Battery Storage**

**Project type:** Preliminary commercial rooftop solar engineering case study (Sri Lanka)  
**Status:** Portfolio / preliminary design — **NOT FOR CONSTRUCTION**  
**Author:** Muththukumar Ravinthiran | BSc Electrical and Information Engineering, University of Ruhuna

## Project overview

This portfolio study develops a preliminary electrical design for a commercial three-phase hybrid photovoltaic system with lithium battery energy storage. It demonstrates PV string calculations, battery energy analysis, preliminary cable and protection engineering, bill of quantities preparation, and CAD single-line drafting. This is a **hypothetical site**, not a surveyed or installed system.

## Preliminary design basis

| Item | Design basis |
| --- | --- |
| Grid | 400/230 V, 3-phase, 4-wire, 50 Hz |
| PV array | 20 × 495 W LONGi modules = **9.90 kWp** |
| PV strings | 2 strings × 10 modules (one string per MPPT; provisional) |
| Inverter | Deye SUN-10K-SG04LP3-EU, 10 kW three-phase hybrid (provisional model) |
| Battery | 4 × Deye SE-F5, 5.12 kWh = **20.48 kWh nominal** |
| Critical load | 3 kW assumed |
| Battery backup | ~5.02 h theoretical at 80% DoD, 92% conversion efficiency and constant 3 kW load; excludes other losses and operating limits |

**Compatibility caution:** The selected PV module's nominal operating current (12.95 A) is close to the inverter's cited MPPT2 current limit (13 A). This is a *nominal screening check only*; exact module variant, module datasheet, inverter manual, temperature/irradiance conditions and manufacturer approval must be verified before procurement or installation. Battery BMS and parallel-operation details also require written confirmation.

## Repository contents

- [`drawings/Hybrid_Solar_SLD_RevE.dxf`](drawings/Hybrid_Solar_SLD_RevE.dxf) — editable preliminary SLD, opens in LibreCAD.
- [`calculations/Solar_Engineering_Workbook_RevC.xlsx`](calculations/Solar_Engineering_Workbook_RevC.xlsx) — calculation, cable/protection and costing workbook; **earlier revision** and subject to the revision differences below.
- [`docs/DESIGN_STATUS.md`](docs/DESIGN_STATUS.md) — design assumptions, discrepancies, outstanding checks and limitations.
- [`docs/GITHUB_UPLOAD_GUIDE.md`](docs/GITHUB_UPLOAD_GUIDE.md) — upload and display instructions.

## Workflow

1. Define commercial rooftop and electrical assumptions.
2. Select preliminary PV, inverter and battery equipment.
3. Calculate string voltage/current, nominal AC current, battery energy and candidate cable voltage drops.
4. Document candidate isolation, overcurrent, surge and earthing requirements.
5. Draft editable single-line diagram in DXF format.
6. Prepare preliminary BOQ and quotation fields; distinguish advertised prices from formal quotations.
7. Record unresolved design approval gates.

## Key calculations

- PV DC nameplate: `20 × 495 W = 9,900 Wp`.
- Three-phase nominal output current at 400 V, unity PF: `10,000 / (sqrt(3) × 400) = 14.43 A`.
- Battery nominal energy: `4 × 5.12 kWh = 20.48 kWh`.
- Illustrative battery backup: `20.48 × 0.80 × 0.92 / 3 = 5.02 h`.

These simplified examples do not substitute for full equipment, conductor, fault-level or protection coordination checks.

## Open the drawing

Install [LibreCAD](https://librecad.org/), choose **File → Open**, select `drawings/Hybrid_Solar_SLD_RevE.dxf`, and use **Auto Zoom**. The DXF contains editable CAD entities; it is not a raster image.

## Engineering limitations

**This is not a commissioned installation, certified design, verified quotation, utility-approved interconnection or construction-ready SLD.** Site data, manufacturer approvals, protective-device coordination, final cable sizing, earthing, structural roof assessment and local interconnection approval remain outstanding. The drawing and workbook have **different revision levels**; do not assume every circuit tag or provisional value matches between them. See `docs/DESIGN_STATUS.md`.

## References to validate against

- [Deye official website](https://www.deyeinverter.com/) — exact inverter and battery datasheets / installation manuals.
- [LONGi official website](https://www.longi.com/) — exact module datasheet and warranty.
- [PUCSL](https://www.pucsl.gov.lk/) — Sri Lankan rooftop PV/BESS interconnection guidance.
- [LibreCAD](https://librecad.org/) — DXF editing.

This repository is shared for engineering learning and portfolio demonstration only.
