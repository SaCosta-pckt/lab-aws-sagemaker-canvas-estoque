# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

### 1. Escolha da IA para Geração do Dataset

Para a realização deste projeto de previsão de estoque, o primeiro passo foi a escolha de uma inteligência artificial adequada para gerar um dataset simulado. Optou-se por uma IA especializada em geração de dados sintéticos, capaz de replicar padrões realistas de vendas, sazonalidade e promoções, baseando-se em dados históricos de mercado.

A escolha da IA levou em consideração sua capacidade de gerar dados variados e realistas, garantindo um conjunto de dados robusto e representativo das condições reais de mercado. Isso incluiu a simulação de diferentes cenários, como variações sazonais e a influência de eventos promocionais, permitindo a criação de um dataset diversificado e desafiador para o modelo de previsão de estoque.

### 2. Construção e Treinamento do Modelo

Após a geração do dataset, o próximo passo foi importar esses dados para o Amazon SageMaker Canvas. O processo começou com a seleção do arquivo de dados gerado pela IA, que foi então carregado na plataforma para análise e treinamento.

#### Configuração de Variáveis:
Uma vez que o dataset foi importado, as variáveis de entrada (features) e saída (target) foram configuradas. As variáveis de entrada incluíam aspectos como datas, quantidades vendidas e preços de produtos, enquanto a variável de saída foi definida como a quantidade de estoque a ser prevista.

#### Treinamento do Modelo:
Com as variáveis configuradas, o treinamento do modelo foi iniciado. O SageMaker Canvas aplicou uma série de algoritmos de machine learning para identificar o melhor modelo para o conjunto de dados. Este processo de treinamento variou em duração, dependendo do tamanho e complexidade do dataset, mas foi otimizado para proporcionar um balanceamento adequado entre precisão e eficiência.

### 3. Análise dos Resultados

#### Avaliação das Métricas de Performance:
Após o término do treinamento, foram examinadas as métricas de performance do modelo. As métricas analisadas incluíram o erro médio absoluto (MAE), o erro quadrático médio (MSE), entre outras. Essas métricas foram cruciais para avaliar a precisão das previsões e a adequação do modelo aos dados.

#### Análise das Características Influentes:
O SageMaker Canvas também ofereceu uma análise das variáveis mais influentes nas previsões. Esta análise permitiu identificar quais fatores tiveram maior impacto nas previsões de estoque, como períodos sazonais ou variações de preço, proporcionando insights valiosos sobre o comportamento do modelo.

#### Ajustes e Re-treinamento:
Com base nas análises das métricas e características influentes, foram realizados ajustes nas variáveis de entrada e, se necessário, nos parâmetros do modelo. Novos treinamentos foram realizados para melhorar o desempenho do modelo, garantindo uma maior precisão nas previsões.

### 4. Previsão e Conclusões

#### Previsões de Estoque:
Com o modelo treinado e ajustado, foram realizadas previsões de estoque utilizando novos dados ou dados de validação. As previsões foram geradas para diferentes períodos e condições, visando simular situações reais de mercado.
