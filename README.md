# Bullying, Belonging, Teacher Support, and Life Satisfaction in PISA 2022 (Spain)

Secondary analysis of PISA 2022 Spain student data on bullying, school belonging, teacher support, and life satisfaction for a Psychology, Society & Education manuscript.

## Key results

- Higher bullying frequency is associated with lower student life satisfaction, adjusting for covariates.
- School belonging and perceived teacher support are positively associated with life satisfaction and attenuate bullying–wellbeing associations.
- Results are robust across multiple model specifications (alternative bullying indicators and interaction terms).

## Reproducibility

1. Download `CY08MSP_STU_QQQ.SAV` from the OECD PISA 2022 database (https://www.oecd.org/pisa/data/) and place it in `data/raw/`.
2. Run `R/01_load_pisa_spain.R`.
3. Run `R/02_build_scales.R`.
4. Run `R/03_models.R` to reproduce the main tables for the manuscript.
5. See `sessionInfo.txt` for details of the R version and package versions used.

## Data

This project uses the OECD PISA 2022 student file:

- File required: `CY08MSP_STU_QQQ.SAV`
- Source: OECD PISA 2022 database: https://www.oecd.org/pisa/data/

Instructions:
1. Download `CY08MSP_STU_QQQ.SAV` from the OECD PISA 2022 data portal.
2. Create the folder `data/raw/` if it does not exist.
3. Place `CY08MSP_STU_QQQ.SAV` in `data/raw/`.
4. Do NOT commit or upload the `.SAV` file to this repository (it is too large and subject to OECD terms of use).

## Notes for peer review

- This repository is configured for double‑blind peer review.
- Identifying information (e.g., author names, personal GitHub handles, and long‑term URLs) is not included in the manuscript text.
- A stable, non‑anonymised link to the full code repository will be provided after acceptance, in line with journal policy.
