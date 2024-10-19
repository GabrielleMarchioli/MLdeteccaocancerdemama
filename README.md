# Machine Learning para a Detecção do Câncer de Mama

A utilização de Machine Learning para a detecção do câncer de mama vem crescendo, contribuindo para diagnósticos mais rápidos e precisos. Este projeto visa desenvolver um modelo de Machine Learning capaz de classificar tumores como benignos ou malignos utilizando o conjunto de dados Wisconsin.

## Contexto

De acordo com a Sociedade Brasileira de Mastologia, uma em cada 12 mulheres terá um tumor nas mamas até os 90 anos. O câncer de mama é a principal causa de morte entre as mulheres em diversos países. A detecção precoce é fundamental, pois quanto mais cedo o câncer é identificado, maiores são as chances de sucesso no tratamento. 

Com o intuito de reforçar a importância da prevenção e do diagnóstico precoce, a campanha Outubro Rosa é realizada anualmente.

## Objetivo do Projeto

Desenvolver um modelo de Machine Learning para classificar tumores mamários como benignos ou malignos, contribuindo para a conscientização sobre a importância da detecção precoce.

## Dados

Os dados utilizados neste projeto são provenientes do [Repositório de Machine Learning da UCI](https://archive.ics.uci.edu/ml/datasets/Breast+cancer+wisconsin+(diagnostic)). O conjunto de dados contém 569 entradas e 32 colunas, coletadas através de biópsias. A variável alvo classifica os tumores como:

- **M**: Maligno
- **B**: Benigno

Os dados estão disponíveis [neste link direto](https://www.dropbox.com/s/z8nw6pfumdw3bb9/breast-cancer-wisconsin.csv?raw=1).

## Estrutura do Código

1. **Importação dos Dados**: O arquivo CSV é carregado em um DataFrame usando a biblioteca Pandas.
2. **Análise Exploratória**: Analisamos a estrutura do conjunto de dados, estatísticas descritivas e a distribuição das variáveis.
3. **Preparação dos Dados**: Os dados são padronizados e a variável alvo é convertida de categórica para numérica usando Label Encoding.
4. **Modelo de Machine Learning**: Um modelo de Random Forest é utilizado para classificar os dados.
5. **Avaliação do Modelo**: A acurácia do modelo é avaliada, e são apresentadas métricas como precisão, recall e a matriz de confusão.

## Resultados

- **Acurácia do Modelo**: 96.49%
- **Métricas Adicionais**:
  - Precisão: [valores da precisão]
  - Recall: [valores do recall]
  - F1-Score: [valores do f1-score]

A matriz de confusão revelou que o modelo teve um bom desempenho em ambas as classes, lidando bem com os tumores benignos e malignos.

## Conclusão

O modelo desenvolvido demonstra ser eficaz na detecção do câncer de mama. No entanto, é importante considerar que cada caso é único e uma alta acurácia não garante a eficácia em aplicações críticas como a detecção de câncer.
