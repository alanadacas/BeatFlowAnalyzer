# 🎵 Beat Flow Analyzer
Este projeto tem como objetivo criar um modelo preditivo para classificar músicas em duas categorias: "agitada" ou "lenta", com base em características de áudio do dataset "Spotify Tracks Dataset". O critério de classificação é a coluna valence, que mede a positividade musical da faixa.

## 🎯 Objetivo
- Desenvolver um modelo de machine learning para classificar músicas como "agitadas" (valence > 0.5) ou "lentas" (valence ≤ 0.5).
- Utilizar técnicas de pré-processamento e engenharia de features para melhorar a performance do modelo.

## 📊 Dataset
O dataset contém 114.000 faixas do Spotify, com 21 colunas, incluindo:

- Características de áudio (danceability, energy, loudness, etc.).
- Metadados (artistas, nome da faixa, gênero, etc.).
- A coluna valence foi transformada em target para a classificação.

## 🔧 Pré-processamento
- Feature Engineering: Seleção das colunas relevantes para o modelo.
- Codificação de Variáveis Categóricas: Uso do LabelEncoder para transformar colunas como artists, album_name, track_genre e target em valores numéricos.
- Análise de Correlação: Visualização da matriz de correlação para entender as relações entre as features.

## 🚀 Próximos Passos
- Dividir o dataset em conjuntos de treino e teste.
- Treinar e avaliar diferentes algoritmos de classificação (como Random Forest, SVM, etc.).
- Otimizar hiperparâmetros e validar o modelo final.

## 📂 Estrutura do Projeto
- Notebook: PredictMusicStyle.ipynb contém todo o código e análises.
- Dataset: dataset.csv (não incluído no repositório, mas disponível no Kaggle).

## 💡 Tecnologias Utilizadas
- Python
- Pandas, Matplotlib, Seaborn, Scikit-learn

## 👨‍💻 Como Executar
- Clone o repositório.
- Baixe o dataset do Kaggle e coloque-o na pasta do projeto.
- Execute o notebook PredictMusicStyle.ipynb para reproduzir as análises e o modelo.
