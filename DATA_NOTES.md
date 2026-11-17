# Data notes

## Structure

The `Tableau_Data` analytical table contains 600 rows and four columns: `Country`, `Year`, `Indicator`, and `Value`.

## Coverage in the supplied workbook

- Countries: 15
- Observed years: 2021, 2023, 2024, 2025
- Indicators: 10
- Country–year–indicator combinations: 600
- Duplicate combinations detected in the original four-column table: 0

## Repository-copy cleaning log

| Issue | Action | Records |
|---|---|---:|
| `Framce` country label | Corrected to `France` | 10 |
| Colon (`:`) in `Value` | Replaced with blank / unavailable | 47 |

The cleaned table contains 47 blank `Value` cells. These are unavailable observations, not zeros. No imputation or interpolation was performed.

## Provenance still to document

The supplied workbook alone does not establish the full bibliographic provenance needed for a research data release. Before DOI publication, add:

- the exact source dataset/publication and stable URL or DOI;
- date of retrieval or download;
- source-specific indicator names and definitions;
- measurement units and denominator/population, where applicable;
- source licence and permission to redistribute;
- any suppression or non-disclosure rules behind unavailable values.

Do not infer these details from indicator labels alone.
