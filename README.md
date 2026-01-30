# Ocean-Data-Sources
A description of data ocean data sources, high level exploration, and how to access them


| Dataset name | Provider / Source | Description | Temporal coverage | Accessible | Paywall | Link | Notes |
|--------------|-------------------|-------------|-------------------|------------|---------|------|-------|
| ERA5 | ECMWF / Copernicus Climate Change Service (C3S) | Global atmospheric and ocean surface reanalysis providing consistent climate variables | 1940–present (hourly) | ✅ | ❌ | [...](https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels?tab=overview) | Ocean variables include $H_s$, $T_p$, and u/v wind components; note ocean and wind resolutions differ |

## Brief Exploration
- **ERA5:** `era5.ipynb`

## Data Source Notes

### ERA5 
ERA5 is a comprehensive reanalysis dataset spannning 1940-present at an hourly resolution. Updates to the dataset occur daily a latency of 5 days. An article titled [*The ERA5 global reanalysis*](https://rmets.onlinelibrary.wiley.com/doi/10.1002/qj.3803) describes the dataset. Note, that key variables of atmospheric wind and ocean waves relevant for oceanographic/ forecasting exist on different grid resolutions. ocean waves wave data has a resolution of $0.5^\circ \times 0.5^\circ$, while atmospheric variables such as `u10` and `v10` (10m wind) have a $0.25^\circ \times 0.25^\circ$ resolution.

