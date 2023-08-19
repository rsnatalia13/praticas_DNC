# Análise de Dados e Predição de Valores de Propriedades Residenciais nos EUA

Este repositório contém um projeto desenvolvido como parte de uma aula prática do curso de Formação em Dados. O projeto envolve a análise de um dataset contendo informações sobre propriedades residenciais nos EUA, com o objetivo de compreender as relações entre diferentes variáveis e desenvolver um modelo de predição de valores das propriedades.

## Dataset

O dataset utilizado neste projeto contém as seguintes informações sobre as propriedades:

- Renda média da população na área em que a propriedade está localizada;
- Idade média das casas na região em questão;
- Número médio de cômodos das casas da região em questão;
- Número médio de quartos das casas da região em questão;
- População total da área;
- Preço das propriedades.

## Etapas do Projeto

### Exploração e Limpeza dos Dados

Inicialmente, realizamos uma exploração detalhada dos dados, identificando valores ausentes ou inconsistentes. Utilizamos técnicas estatísticas, como média e desvio padrão, para compreender a distribuição dos dados.

### Análise de Correlações

Utilizando a biblioteca Seaborn, plotamos gráficos de distribuição e dispersão para analisar possíveis correlações lineares entre as variáveis. Posteriormente, criamos um mapa de calor para visualizar as correlações entre todos os dados descritivos e o preço das propriedades. Isso nos permitiu identificar quais variáveis têm maior impacto nos preços das propriedades.

### Desenvolvimento do Modelo de Regressão Linear

Para realizar a predição dos valores das propriedades, implementamos um modelo simples de regressão linear utilizando a biblioteca scikit-learn. Utilizamos o coeficiente de determinação R² como métrica de avaliação do desempenho do modelo. Além disso, plotamos um gráfico de linhas para comparar os valores reais das propriedades com os valores previstos pelo modelo.

