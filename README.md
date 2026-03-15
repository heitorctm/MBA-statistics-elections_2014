# Eleições 2014 — Análise Estatística de Candidatos a Deputado Federal

Projeto da disciplina de **Estatística Descritiva** do MBA em Ciência de Dados.

## Objetivo

Analisar o financiamento de campanhas e o resultado eleitoral dos candidatos a Deputado Federal nas eleições gerais de 2014, identificando padrões relacionados a gasto, votos e variáveis demográficas (gênero, raça e escolaridade).

## Dados

| Arquivo | Fonte | Descrição |
|---|---|---|
| `datasets/eleicoes.csv` | Professor | Dataset principal: gasto e votos por candidato |
| `datasets/extra/prestacao_final_2014/` | TSE | Despesas declaradas por nota fiscal |
| `datasets/extra/consulta_cand_2014/` | TSE | Cadastro oficial: situação eleitoral e dados demográficos |

Fonte externa: [dadosabertos.tse.jus.br](https://dadosabertos.tse.jus.br), Eleições Gerais 2014.

## Estrutura do Notebook

1. **Imports**
2. **Preparação e Enriquecimento** — join com dados do TSE e validação do dataset
3. **Análise Exploratória** — distribuição de gastos, análise por estado, partido, e variáveis qualitativas
4. **Síntese e Conclusões** — tabelas descritivas e padrões identificados

## Principais Achados

- Candidatos eleitos gastaram em média **77x mais** que os não eleitos
- Mulheres representam 29,6% das candidaturas mas concentram apenas 9,6% do gasto total
- Candidatos brancos com ensino superior capturam a maior parte dos recursos e das vagas

## Requisitos

```
pandas
matplotlib
scipy
numpy
```
