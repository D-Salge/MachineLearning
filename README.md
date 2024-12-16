# MachineLearning

Este projeto tem como objetivo criar um modelo preditivo de **Score de Crédito** utilizando técnicas de aprendizado de máquina e análise exploratória de dados (EDA).

## Estrutura do Projeto

- **dados_credito.xlsx**: Arquivo contendo os dados utilizados no projeto, com informações sobre clientes e seus atributos financeiros e pessoais.
- **ScoreCredito.py**: Script principal em Python, contendo todo o pipeline de análise exploratória, tratamento de dados, normalização, treinamento do modelo e previsão.
- **ScoreCreditoML.ipynb**: Notebook Jupyter com a mesma lógica do script, detalhando visualizações e análises intermediárias.

## Funcionalidades Implementadas

1. **Análise Exploratória dos Dados (EDA)**:
   - Inspeção de dados ausentes.
   - Detecção e tratamento de outliers.
   - Estatísticas descritivas e visualização de distribuições.
   - Gráficos de dispersão e heatmap de correlações.

2. **Pré-processamento de Dados**:
   - Tratamento de valores ausentes (substituição pela mediana).
   - Codificação de variáveis categóricas (Label Encoding).
   - Normalização dos dados numéricos (MinMaxScaler).

3. **Treinamento do Modelo**:
   - Separação dos dados em conjuntos de treino e teste.
   - Modelo de Regressão Linear para prever o score de crédito.
   - Métrica R² para avaliação do modelo.

4. **Predição**:
   - Entrada manual de dados para predição do score de crédito.

## Tecnologias Utilizadas

- **Python**: Linguagem principal.
- **Pandas**: Manipulação de dados.
- **Matplotlib e Seaborn**: Visualização de dados.
- **Scikit-learn**: Modelos de machine learning e ferramentas de pré-processamento.
- **Jupyter Notebook**: Para análises iterativas.

## Como Usar

1. Certifique-se de ter o Python instalado (>= 3.8).
2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
   *(Você precisará gerar este arquivo caso ainda não exista.)*
3. Coloque o arquivo `dados_credito.xlsx` na mesma pasta do script ou notebook.
4. Execute o script `ScoreCredito.py`:
   ```bash
   python ScoreCredito.py
   ```
   Ou abra o `ScoreCreditoML.ipynb` em um ambiente Jupyter para explorar as análises interativamente.

## Resultados

Os resultados incluem:
- Visualizações que destacam padrões nos dados.
- Modelo treinado para prever o score de crédito.
- R² do modelo como métrica de avaliação.
- Predições com base em novos dados fornecidos manualmente.

## Melhorias Futuras

- Testar outros modelos de machine learning para melhorar a métrica de avaliação.
- Implementar cross-validation para validar a performance do modelo.
- Explorar a implementação de hiperparâmetros automatizados (Grid Search ou Random Search).
- Criar uma interface gráfica para facilitar a entrada de novos dados e exibição dos resultados.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Autor

**Daniel Salge**  
[GitHub](https://github.com/D-Salge) | [LinkedIn](https://www.linkedin.com/in/danielsalge/)

---

Este projeto foi desenvolvido para fins de estudo e experimentação em Machine Learning.
