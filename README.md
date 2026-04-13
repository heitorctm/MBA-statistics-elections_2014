# Brazilian Elections 2014: Statistical Analysis of Federal Deputy Candidates

Project for the **Descriptive Statistics** course of the MBA in Data Science.

## Objective

Analyze campaign financing and electoral results of Federal Deputy candidates in the 2014 general elections, identifying patterns related to spending, votes, and demographic variables (gender, race, and education).

## Data

| File | Source | Description |
|---|---|---|
| `datasets/eleicoes.csv` | Professor | Main dataset: spending and votes per candidate |
| `datasets/extra/prestacao_final_2014/` | TSE | Declared expenses by invoice |
| `datasets/extra/consulta_cand_2014/` | TSE | Official registry: electoral status and demographic data |

External source: [dadosabertos.tse.jus.br](https://dadosabertos.tse.jus.br), 2014 General Elections.

## Notebook Structure

1. **Imports**
2. **Preparation and Enrichment** — join with TSE data and dataset validation
3. **Exploratory Analysis** — spending distribution, analysis by state, party, and qualitative variables
4. **Summary and Conclusions** — descriptive tables and identified patterns

## Key Findings

- Elected candidates spent on average **77x more** than non-elected ones
- Women represent 29.6% of candidacies but account for only 9.6% of total spending
- White candidates with higher education capture the largest share of resources and seats

## Requirements

```
pandas
matplotlib
scipy
numpy
```
