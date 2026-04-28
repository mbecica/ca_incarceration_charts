# California Community Corrections, 2011 → 2024

Reference document compiling population, funding, and cost-per-person figures for California's community corrections system over the period 2011–2024 (calendar years for population; FY 2011–12 to FY 2023–24 for funding). Numbers reconciled across calculation choices.

---

## Programs covered

- **State parole** — CDCR Division of Adult Parole Operations (DAPO). State-run.
- **Probation** — felony + misdemeanor probation. County-run.
- **Post-Release Community Supervision (PRCS)** — created Oct 2011 by AB 109 for people released from state prison for non-serious / non-violent / non-sex offenses. County-run.
- **Mandatory Supervision (MS)** — created Oct 2011 by AB 109 for the community-supervision portion of split sentences. County-run.
- **Community Reentry Program Participants (CRPP)** — CDCR community placements (Alternative Custody Program, Female/Male Community Reentry, Medical Reprieve, Community Participant Mother). State-run. Began mid-2016.

---

## Population (December snapshots)

| Group | 2011 | 2024 | Change |
|---|---:|---:|---:|
| Parole | 105,500 | 34,660 | **−67.1%** |
| Probation (felony + misdemeanor) | 297,917 | 151,849 | **−49.0%** |
| &nbsp;&nbsp;– felony | 247,770 | 122,689 | −50.5% |
| &nbsp;&nbsp;– misdemeanor | 50,147 | 29,160 | −41.9% |
| PRCS | 12,339 *(estimate)* | 37,000 | (see note) |
| Mandatory supervision | ~0 *(program starting)* | 7,800 | net new |
| CRPP | 0 *(did not exist)* | 1,007 | net new |

**Bundle totals (Dec snapshots):**

| Bundle | 2011 | 2024 | Change |
|---|---:|---:|---:|
| Parole + probation | 403,417 | 186,509 | **−53.8%** |
| All five programs | 415,756 | 232,316 | **−44.1%** |
| Probation + PRCS + MS *(county supervision)* | 310,256 | 196,649 | **−36.6%** |

**Note on PRCS 2011 baseline:** the 2011 PRCS value of 12,339 in our dataset is a Gemini-produced estimate flagged as "source unverified." First verified value is 2013 at 39,057 (CPOC California Probation Summary). 2013 → 2024 change is **−5.3%**. AB 109 took effect Oct 2011, so any 2011 figure reflects only ~2.5 months of program operation.

---

## Funding (FY 2011–12 → FY 2023–24, all in 2024 dollars)

| Stream | FY 2011–12 | FY 2023–24 | Real change |
|---|---:|---:|---:|
| State parole (CDCR DAPO + Board of Parole Hearings) | $1,040M | $790M | **−24.1%** |
| County probation, summed across all 58 counties *(funds probation, PRCS, and MS together)* | $1,641M | $2,363M | **+44.0%** |
| **Combined parole + county supervision** | **$2,681M** | **$3,153M** | **+17.6%** |
| County public protection (police + jail + courts + fire + probation), all 58 counties — *for context, not community-corrections-specific* | $23.40B | $31.34B | +33.9% |
| SCO PRCS county allocations *(supplemental state→county payments)* | n/a *(not yet established)* | $9.3M | first year FY 2017–18 ($15.4M); peaked FY 2018–19 at $28.2M |

In nominal dollars, the combined parole + county supervision total rose from $1.94B → $3.10B (+60.1%); county probation alone from $1.19B → $2.33B (+96.1%); county public protection from $16.92B → $30.86B (+82.4%).

### What the combined total covers and what's missing

The combined parole + county supervision figure captures funding for **four of the five programs**: state parole, probation, PRCS, and mandatory supervision. PRCS and MS share the county probation budget (no separate funding line) so they fold in cleanly without double-counting.

**CRPP is not in the combined total.** CRPP participants remain in CDCR custody (placed in community programs like Alternative Custody, Female/Male Community Reentry, etc.), so their costs are bundled into CDCR's adult institution operations budget rather than parole. There is no separable CRPP funding figure in publicly available data. Population is small (~1,000 in 2024), so the omission is small — but it's a real data gap.

**SCO PRCS county allocations are excluded from the combined total** to avoid double-counting: those payments flow into county probation departments and are already captured in the SCO county probation expenditure totals. They are listed separately above for transparency.

---

## Cost per person (2024 dollars)

Pairs FY budget with December population at fiscal-year-end (FY 2011–12 → Dec 2012; FY 2023–24 → Dec 2024).

| | FY 2011–12 | FY 2023–24 | Change |
|---|---:|---:|---:|
| **State parole** ($/person) | $17,048 | $22,783 | **+33.6%** |
| &nbsp;&nbsp;Budget (2024 $) | $1,040M | $790M | −24.1% |
| &nbsp;&nbsp;Population | 61,000 | 34,660 | −43.2% |
| **County supervision** ($/person) | $5,074 | $12,017 | **+136.8%** |
| &nbsp;&nbsp;Budget (2024 $) | $1,641M | $2,363M | +44.0% |
| &nbsp;&nbsp;Population (probation + PRCS + MS) | 323,493 | 196,649 | −39.2% |

County supervision per-person cost is calculated as `county probation budget ÷ (probation + PRCS + MS population)`, treating counties as a single supervision system since PRCS and MS do not have separate funding lines and are administered by county probation departments.

### What's driving the per-person increases

- **State parole**: budget shrank 24% but population shrank 43% — population fell faster than the budget.
- **County supervision**: budget grew 44% in real terms while population fell 39% — both effects pushed cost-per-person up. (Different mechanism from parole.)

---

## Reconciling earlier numbers

Two prior cost-per-person figures were reported in conversation but used different denominators. Use the chart-3 framing (above) as canonical:

| Calculation | Numerator | Denominator | FY 2011–12 | FY 2023–24 | Status |
|---|---|---|---:|---:|---|
| Quick first pass | County probation budget (real) | Probation pop only | ~$5,500 | ~$15,500 | superseded |
| Canonical | County probation budget (real) | Probation + PRCS + MS | $5,074 | $12,017 | use this |

The probation-only denominator overstates per-person cost because the county probation budget also funds PRCS and MS supervision.

---

## Sources

- CDCR Monthly Report of Population (Tpop1d series); CDCR Data Points; LAO visualizations — for parole, prison, CRPP populations.
- California Department of Justice, OpenJustice — for probation populations (Yuba 2016 and 2017 manually interpolated due to apparent coding error in source).
- CPOC California Probation Summary; LAO Figure 1 (PRCS 4849) — for PRCS and mandatory supervision populations.
- Governor's Budget chapter 5210 (ebudget.ca.gov) — for CDCR adult parole and Board of Parole Hearings expenditures.
- California State Controller's Office, ByTheNumbers, datasets `uctr-c2j8` (counties) and `ju3w-4gxp` (cities, for San Francisco) — for county probation expenditures (built from `EXP_PUBLIC_PROTECTION` subcategory_2 = `Probation_*` for FY 2003–2016 and from `GEN/SR/DEBT/CAPPROJ/PERM_PROBATION` form_tables for FY 2017–2024).
- BLS CPI-U fiscal-year averages — for inflation adjustment to 2024 dollars (CPI 2024 = 314.2).
- SCO Post-Release Community Supervision payments xlsx files — for SCO PRCS county allocations.

Underlying data: [`ca_incarceration_stats`](https://github.com/mbecica/ca_incarceration_stats) repository.
