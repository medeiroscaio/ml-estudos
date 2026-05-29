# projeto-survey-2019

Análise exploratória do Stack Overflow Developer Survey com foco na pergunta central:
**"O que realmente determina quanto um desenvolvedor ganha?"**

## análises

**Parte 1 — exploração e limpeza**
- Remoção de duplicatas, nulos e outliers (método IQR sobre `ConvertedComp`)
- Análise por país — top 10 por salário mediano
- Análise por nível de educação
- Análise por linguagem de programação
- Análise por anos de experiência profissional

**Parte 2 — estatística e comparação temporal**
- Histograma de assimetria do `ConvertedComp` antes e depois da limpeza
- Correlação Spearman entre `YearsCodePro` e `ConvertedComp` (r = 0.44)
- Heatmap de correlação
- Comparação salarial 2019 vs 2021 — impacto do home office pós-pandemia

## datasets

`data2019.csv` e `data2021.csv` não estão incluídos (.gitignore).  
Download: https://survey.stackoverflow.co/
