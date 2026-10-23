# Design Status and Verification Register

## Deliverable revisions

| Deliverable | Revision | State |
| --- | --- | --- |
| Editable electrical SLD | E | Preliminary drawing; NOT FOR CONSTRUCTION |
| Electrical calculations / BOQ workbook | C | Preliminary; not synchronized to Rev E at the individual device-tag level |

**Revision mismatch:** This package intentionally preserves the latest available files, but it is **not a coordinated issued-for-design set**. Reconcile all tags, cable schedules, ratings and quantities before using it beyond a portfolio exercise.

## Technical hold points

| ID | Verification required | Status |
| --- | --- | --- |
| H01 | Confirm exact LONGi 495 W module SKU, electrical/temperature ratings and availability | OPEN |
| H02 | Confirm inverter full model code, firmware, MPPT current and voltage constraints and PV string acceptance | OPEN |
| H03 | Confirm Deye SE-F5 four-unit parallel arrangement, BMS communication, cable/busbar and protection details | OPEN |
| H04 | Measure site cable routes, ambient conditions, grouping, installation method and cable ampacity | OPEN |
| H05 | Obtain prospective short-circuit current, fault-loop impedance, earthing system and protection coordination | OPEN |
| H06 | Verify AC RCD/RCBO suitability, neutral switching, grid/backup arrangement and anti-islanding | OPEN |
| H07 | Confirm PV/battery DC isolation, overcurrent, SPD and earthing/lightning design against current standards | OPEN |
| H08 | Confirm structural roof capacity, mounting layout, shading and PV yield | OPEN |
| H09 | Obtain formal supplier quotations including taxes, validity and availability | OPEN |
| H10 | Obtain utility and relevant regulatory interconnection approval | OPEN |

## Scope boundaries

- No physical installation, site survey, laboratory test or commissioning is claimed.
- Device symbols and protection labels in the DXF are **illustrative**, not final certified selections.
- Cable cross sections and lengths are candidate assumptions; no ampacity or fault-withstand certification is implied.
- Advertised prices, if present in source workbooks, are not formal quotations.
- Avoid interpreting the SLD's simplified battery busbars as an approved manufacturer's wiring schematic.

## For future engineering development

Reconcile the Rev C workbook and Rev E drawing into a single revision, add verified datasheets and supplier quotations, then undertake protection coordination and full site-specific checks with a qualified engineer.
