# Recoding Rules

## SadOrHopeless
- Keep only valid values (1 and 2)
- Remove missing or invalid values
- Recode:
  - 1 → 1 (Yes)
  - 2 → 0 (No)

## BMIPCT
- Remove missing values
- Use cleaned data for mean analysis

## Joint Dataset
- Keep only rows where:
  - SadOrHopeless is valid
  - BMIPCT is not missing