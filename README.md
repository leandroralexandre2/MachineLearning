🍷 Wine Quality Prediction using RandomForestClassifier
# MachineLearning
Este repositório contém um projeto de Machine Learning que utiliza o algoritmo Random Forest para prever a qualidade de vinhos com base em diversas variáveis químicas do famoso Wine Dataset do Scikit-learn.

🔍 Descrição do Projeto

O objetivo deste projeto é construir um modelo preditivo que classifique a qualidade de vinhos em diferentes categorias, a partir de um conjunto de dados que inclui variáveis como teor alcoólico, acidez, fenóis, entre outras. O modelo foi desenvolvido utilizando a biblioteca Scikit-learn, com o algoritmo RandomForestClassifier, amplamente conhecido pela sua eficiência em tarefas de classificação.

📂 Estrutura do Projeto

wine_quality_rf.py: Script principal que contém todo o pipeline de Machine Learning.
data/: Diretório para armazenar o dataset de vinhos.
notebooks/: Notebooks Jupyter utilizados para análises exploratórias e visualizações dos dados.
README.md: Este arquivo explicativo.

🔧 Tecnologias Utilizadas

- Python 3.8+
- Scikit-learn para a implementação do modelo.
- Pandas e NumPy para manipulação de dados.
- Matplotlib e Seaborn para visualizações gráficas.
- RandomForestClassifier para a criação do modelo de classificação.

🚀 Como Executar o Projeto

1. Clone este repositório:

 git clone https://github.com/leandroralexandre2/wine-quality-prediction.git


2. Instale as dependências:

git clone https://github.com/seu-usuario/wine-quality-prediction.git
pip install -r requirements.txt

3. Execute o script principal para treinar o modelo:

python wine_quality_rf.py


📊 Resultados

Acurácia nos dados de teste: 100%

Acurácia média na validação cruzada: 97.21%

O modelo foi avaliado usando uma matriz de confusão e validação cruzada, obtendo ótimos resultados para as previsões de qualidade do vinho.

📈 Visualizações
Incluímos gráficos gerados durante o processo de análise de dados, como a matriz de confusão e gráficos de dispersão, para ajudar a entender melhor os padrões no dataset.

Sinta-se à vontade para contribuir com melhorias ou sugestões para este projeto!!!

