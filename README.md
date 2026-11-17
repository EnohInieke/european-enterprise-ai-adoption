# Human–AI Communication in Europe

Research dataset and Tableau visualisation examining enterprise AI adoption and AI-related indicators across European countries.

## Public visualisation

[View the interactive Tableau Public dashboard](https://public.tableau.com/app/profile/enoh.johninieke/viz/HUMANAICOMMUNICATIONINEUROPE/Dashboard1).

## Dataset overview

The cleaned analytical table contains **600 records**, covering **15 countries**, **4 observed years**, and **10 indicators**.

- Countries: Austria, Belgium, Denmark, Finland, France, Germany, Ireland, Italy, Luxembourg, Netherlands, Poland, Portugal, Romania, Spain, Sweden
- Observed years: 2021, 2023, 2024, 2025
- Indicators: AI Adoption, AI Marketing/Sales, Autonomous Movement, Image Recognition, Image/Video/Audio Generation, Language Generation, Machine Learning, Speech Recognition, Text Mining, Workflow/Decision Support

The analytical table uses four fields:

| Field | Description |
|---|---|
| `Country` | Country name |
| `Year` | Observation year |
| `Indicator` | AI adoption or AI-related indicator |
| `Value` | Numeric value where reported; blank where unavailable in the supplied source workbook |

The years represented in the supplied data are 2021, 2023, 2024 and 2025. The dataset does not contain observations for 2022; no values have been interpolated or imputed for that year.

## Files

- `data/tableau_data.csv` — cleaned analytical table for reuse and analysis.
- `data/Human_AI_Communication_Europe_Cleaned.xlsx` — cleaned workbook. The original workbook's other worksheets are retained; the `Tableau_Data` worksheet contains the corrections described below.
- `methodology/DATA_NOTES.md` — data structure, cleaning log and outstanding provenance notes.
- `tableau/README.md` — notes on the published visualisation and packaged workbook refresh.

## Cleaning applied to this repository copy

Two transformations were made to the repository copy of the `Tableau_Data` worksheet:

1. Corrected the country label `Framce` to `France` in 10 records.
2. Replaced the colon (`:`) placeholder with an empty cell in 47 records, following the project owner's instruction that these entries represent unavailable values.

No other values were intentionally changed. The uploaded source workbook has been left unchanged.

## Data provenance and interpretation

The exact source publication(s), extraction date, indicator definitions, units, and any source-specific confidentiality or suppression rules must be documented before this repository is treated as a final citable data release. An empty value in this repository means the supplied workbook marked the observation as unavailable; it must not be interpreted as zero.

The dataset is observational and contains only the years listed above. Comparisons across years should account for the missing 2022 observation and any changes in source definitions or coverage.

## Reproducibility and release status

This is a prepared repository copy. Before creating a DOI-bearing release:

- complete and verify the source citations and indicator definitions;
- confirm that redistribution is permitted by the original data source's licence/terms;
- refresh the Tableau data extract using the cleaned data and re-export the packaged `.twbx` workbook;
- verify that the refreshed workbook and the CSV contain matching records.

## Author

Enoh Inieke  
ORCID: [0009-0004-2328-8796](https://orcid.org/0009-0004-2328-8796)
