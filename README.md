# IRS Domestic Content Safe Harbor — Component Trees

An interactive, single-file visualization of the IRS domestic content bonus credit safe harbor for clean energy tax credits (IRC §§ 45, 45Y, 48, 48E).

For each technology, the page draws the two compliance branches as a tree:

- **Steel / Iron Requirement** — structural steel and iron items, an absolute pass/fail test (100% U.S. manufacturing processes; these items never enter the percentage math).
- **Manufactured Products** — each Manufactured Product flowing down to its Manufactured Product Components, with the assigned cost percentages from the currently operative First Updated Elective Safe Harbor (Notice 2025-08).

## Coverage

| Technology | Variants | Percentages? |
|---|---|---|
| Solar PV — Ground-Mount | Tracking / Fixed, each with a "domestic c-Si cells & wafers" alternate | Yes (Notice 2025-08 §5.05) |
| Solar PV — Rooftop | MLPE / String, each with a domestic-wafer alternate | Yes (Notice 2025-08 §5.06) |
| Land-Based Wind | — | Yes (Notice 2025-08 §6.02) |
| Battery Energy Storage | Grid-Scale (>1 MWh) / Distributed (≤1 MWh) | Yes (Notice 2025-08 §7.02) |
| Offshore Wind | — | Classification only (Notice 2023-38 Table 2) |
| Hydropower / Pumped Storage | — | Classification only (Notice 2024-41 §3.02) |

Every percentage column sums to 100%; a total row on the page verifies this per variant. Offshore wind and hydropower have no assigned percentages — projects must use manufacturers' actual direct costs under Notice 2023-38 §3.03(2).

## Usage

Open `index.html` in any browser — no build step, no dependencies, works offline. Supports light/dark themes and phone widths.

## Sources

Official IRS notices (U.S. government works, public domain), available at irs.gov/pub/irs-drop:

- Notice 2023-38 (May 2023) — framework and Table 2 classifications
- Notice 2024-41 (May 2024) — New Elective Safe Harbor; hydropower classifications
- Notice 2025-08 (Jan 2025) — First Updated Elective Safe Harbor (current tables)

Data transcribed and verified September 2026. This is a research aid, not tax advice — confirm figures against the source notices before relying on them.
