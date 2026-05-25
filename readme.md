# Projeto da 2ª Unidade - DCA3606 - Inteligência Artificial

Repositório destinado ao projeto prático da 2ª unidade da disciplina de **Inteligência Artificial (DCA3606)** do Departamento de Engenharia de Computação e Automação (DCA) da **UFRN**.

## Objetivo do Projeto
O objetivo deste trabalho é aplicar o pipeline completo de Machine Learning (pré-processamento, exploração e modelagem) utilizando técnicas de aprendizagem **Supervisionada** e **Não Supervisionada** em dois conjuntos de dados reais.

## Datasets Utilizados
O projeto aborda dois problemas distintos:
1. **Classificação (Condição Climática):** Previsão de categorias meteorológicas a partir de dados de telemetria ambiental.
2. **Regressão (Consumo Energético):** Previsão contínua da demanda de energia baseada em variáveis físicas.

## Técnicas e Algoritmos Aplicados

### Pré-processamento e Redução de Dimensionalidade
* Tratamento de valores faltantes e anomalias
* Padronização de dados (`StandardScaler`)

### Aprendizagem Não Supervisionada (Clustering)
* PCA (Análise de Componentes Principais)
* K-Means
* DBSCAN

### Aprendizagem Supervisionada
Para ambos os datasets (adaptando para Classificação e Regressão), foram avaliados 6 modelos:
1. Regressão Logística / Regressão Linear
2. Árvores de Decisão (*Decision Trees*)
3. Random Forest
4. XGBoost
5. Máquinas de Vetores de Suporte (*SVM / SVC / SVR*)
6. Redes Neurais Artificiais (*MLP Classifier / Regressor*)

## Organização do repositório
```
assets/
datasets/
nao_supervisionado.ipynb
supervisionado_classificacao.ipynb
regressao.ipynb
readme.md
requirements.txt
```

## Bibliotecas e Requisitos
O projeto foi desenvolvido em Python (Jupyter Notebook). Para executar os notebooks localmente, instale as seguintes dependências:

```bash
pip install -r requirements.txt
```

