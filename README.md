# Reservoir stratification and methylmercury: analysis visualizations

Working visualizations and data workbooks from the reservoir stratification / dissolved oxygen / methylmercury (MeHg) analysis
(Almaden, Calero, Guadalupe, Stevens Creek, Lake Almaden; Chesbro and Uvas for stratification).
Companion to the public-facing visualization site.

| File | What it shows |
|---|---|
| `index.html` | Landing page |
| `stratification-onset.html` | Year × day heatmap of surface–bottom ΔT with adjustable threshold; 3 °C crossing table |
| `mehg-thermocline.html` | MeHg in depth bins relative to the thermocline, colored by DO; where each day’s MeHg peak sat |
| `chl-vs-mehg.html` | Chlorophyll maximum vs metalimnetic MeHg peak depth, oxic vs anoxic |
| `oxic-vs-anoxic.html` | Composite DO / chlorophyll / MeHg profiles for oxic vs anoxic metalimnetic peaks |
| `sulfate.html` | Surface-minus-bottom sulfate drawdown vs bottom DO and MeHg; metalimnion oxic vs anoxic comparison |
| `reservoirs-by-year.html` | Summer deep and surface MeHg by year, colored by oxygen; hypolimnetic MeHg mass |
| `figures.html`, `fig-*.png` | Static report figures |
| `data-*.xlsx` | Result workbooks (stratification threshold, MeHg vs thermocline, follow-up analyses) |

All files are in one folder, so upload them all at once (**Add file → Upload files → choose your files → select all**).
Turn on GitHub Pages under **Settings → Pages** (branch `main`, folder `/ (root)`).

## Data and permissions
The pages and workbooks contain processed Valley Water monitoring data. Confirm approval before making the repository public;
delete the `data-*.xlsx` files if only the visualizations should be shared.

## Methods in brief
Thermocline = steepest temperature gradient; metalimnion = dT/dz ≥ 1 °C/m; stratification onset = surface (top 1 m) minus bottom ΔT ≥ 3 °C,
interpolated between profiles. MeHg samples are matched to same-day profiles; oxic peaks have DO ≥ 2 mg/L at the peak depth.
Hypolimnetic mass uses surveyed capacity tables with water level estimated from sonde depth.
