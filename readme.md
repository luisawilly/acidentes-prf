# Análise de Acidentes Rodoviários - PRF

Análise de dados de acidentes em rodovias federais brasileiras usando dados oficiais da Polícia Rodoviária Federal.

## Sobre o Projeto

Dashboard e análise exploratória para identificar padrões de acidentes rodoviários no primeiro semestre de 2025.

**Tecnologias:** Python (Pandas) + Power BI

## Principais Números

- **279.900** acidentes analisados
- **13.800** óbitos
- **31.700** feridos graves
- **53%** dos acidentes não geraram feridos

## Estrutura do Projeto

```
acidentes-prf-sample/
├── dashboard/
│   └── dashboard.pbix
├── data/
│   ├── processed/
│   │   └── acidentes_limpos_1_sample.csv
│   └── raw/
│       └── sample.csv
├── design/
│   ├── frame-0.png
│   └── frame-1.png
├── notebook/
│   └── limpeza-acidentes-1
└── README.md
```

## Como Usar

1. **Notebook:** Execute `notebook/limpeza-acidentes-1` para ver a análise
2. **Dashboard:** Abra `dashboard/dashboard.pbix` no Power BI

## Tratamento de Dados

- Conversão de coordenadas para formato decimal
- Cálculo de idades a partir do ano de nascimento
- Limpeza de valores nulos
- Criação de categorias de gravidade (Fatal, Grave, Leve, Sem Feridos)

## Principais Insights

- Abril e maio concentram mais acidentes
- Região Sudeste tem maior número de ocorrências
- Padrões claros de horários de pico

## Observação

Este repositório contém uma **amostra de 1000 registros**. A análise completa foi feita com a base integral da PRF (279k registros).

## Contato

- Email: dados.awilly@gmail.com
- LinkedIn: [luis-awilly](https://www.linkedin.com/in/luis-awilly/)
- GitHub: [luisawilly](https://github.com/luisawilly)