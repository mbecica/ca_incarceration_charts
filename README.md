# ca_incarceration_charts

Charts exploring the data in [ca_incarceration_stats](https://github.com/mbecica/ca_incarceration_stats). All charts are self-contained HTML files using D3.js v7 (loaded from CDN), reading CSVs from `data/`. Open any file in a browser.

## Charts

### Population

| File | Description |
|---|---|
| `population.html` | California prison, parole, jail, probation populations over time |
| `population_grouped.html` | Same, grouped by facility vs community |
| `population_share.html` | Stacked bar of each group's share of the total justice-involved population, 2003–2024 |
| `population_rate.html` | Population rates per 100k California residents over time |
| `population_rate_narrow.html` | Same as above, narrower aspect ratio |
| `community_corrections_population.html` | Stacked area of community corrections (parole, probation, PRCS, MS, CRPP), 2011–2024 |
| `community_corrections_population_rate.html` | Same as above but per 100k California residents |

### Budget

| File | Description |
|---|---|
| `budget_total.html` | CDCR total budget with program breakdown (Adult Operations, Parole, Rehabilitation, Other), FY 1980–81 to 2024–25, 2024 dollars |
| `budget_pct.html` | CDCR budget as percentage of California General Fund |
| `budget_pct_breakdown.html` | Same with program-level breakdown |
| `community_corrections_funding.html` | Stacked area of state parole + county probation + SCO PRCS allocations, FY 2011–12 to 2023–24, 2024 dollars |
| `community_corrections_cost_per_person.html` | State parole vs combined county supervision per-person cost, 2024 dollars |
| `county_probation_cost_per_person.html` | 58-county spaghetti chart of probation cost per probationer, 2011–2024, 2024 dollars |

## Data

The `data/` directory holds CSVs consumed by the charts. Files prefixed with `ca_` are copied directly from the [ca_incarceration_stats](https://github.com/mbecica/ca_incarceration_stats) repo (refresh manually as needed). Files without that prefix are derived/aggregated for specific charts.

| File | Origin | Notes |
|---|---|---|
| `ca_statewide_prison_population.csv` | mirror of stats repo | population by year, 1920–2025 |
| `ca_statewide_corrections_budget.csv` | mirror of stats repo | CDCR budget by FY, 1980–81 to 2025–26 |
| `community_corrections_funding.csv` | derived | state parole + county probation summed across all 58 counties + SCO PRCS allocations, nominal and 2024 dollars |
| `community_corrections_cost_per_person.csv` | derived | state parole and combined county supervision per-person costs, 2024 dollars |
| `county_probation_cost_per_person.csv` | derived | per-county per-year probation cost per probationer, 2024 dollars |

## Reference documents

- `community_corrections_summary.md` — narrative summary with reconciled population, funding, and cost-per-person tables for 2011–2024, suitable for copy-paste into reports.
