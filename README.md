# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML).


## 🎯 Ciclo do Projeto

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)


## 🚀 Passo a Passo

### 1. Seleção do Dataset

-   Extração de Dataset: Através da pasta `datasets` deste repositório. Foi extraído um dataset para treinamento/teste de modelo de ML.
-   Upload do dataset realizado no SageMaker Canvas.

### 2. Construção/Treinamento

-   No SageMaker Canvas, foi importado o `dataset-500-curso-sagemaker-canvas-dio.csv`
-   Foram configuradas as variáveis de entrada e saída de acordo com os dados, utilizando o ID do Produto como PK e a QUANTIDADE_ESTOQUE como target para análise.
-   Foi utilizada a schedule holiday que verifica os feriados no Brasil, para aperfeiçoamento da build.

### 3. Análise

-   Após o treinamento, foram examinadas as métricas do modelo.
-   A característica de "feriados no Brasil" influenciou as previsões.

### 4. Prever

-   Modelo treinado para fazer previsões de estoque.
-   Exportados os resultados e analisadas as previsões geradas.

## Conclusão

Neste projeto podemos perceber a facilidade de geração de modelos para ML utilizando o AWS SageMaker Canvas, foram feitas configurações simples com base no dataset que então foi treinado através de IA generativa, gerando resultados satisfatórios.
