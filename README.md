# Ciencia de Dados – Avaliações

Repositório de notebooks usados em atividades semanais, prova e trabalho final da disciplina de Introdução a Ciência de Dados (ICMC/USP). Todo o conteúdo está em notebooks `.ipynb` e foi pensado para ser executado no Google Colab com dados armazenados no Drive.

## Estrutura rápida
- `atividades_semanais/`: listas 1–8 e revisão (tips, salários de jogadores, wine, company financials, PCA breast cancer, dados desbalanceados, WDBC, Titanic).
- `p1/PROVA1.ipynb`: prova prática com limpeza de dados imobiliários, imputação e normalização.
- `trabalho_dados/trabalho_olist.ipynb`: projeto completo com os 9 datasets públicos da Olist, EDA, engenharia de atributos logísticos, modelos (LogReg, RandomForest, XGBoost) e insights sobre satisfação e preferências regionais.

## Dependências
- Python 3 com `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `imbalanced-learn` e `xgboost` (apenas no trabalho Olist).
- Dados ficam referenciados via Google Drive (`drive.mount(...)` nos notebooks). Coloque os CSVs/arquivos nos caminhos esperados ou altere-os antes de rodar.

## Como executar
1) Abra o notebook no Colab ou Jupyter.  
2) Certifique-se de montar o Drive (Colab) ou ajustar os caminhos locais dos datasets.  
3) Instale dependências faltantes (`pip install -q pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost`).  
4) Execute as células em ordem.

## Notas
- Os notebooks usam importação padrão para exploração (estatísticas, histogramas, correlação), pré-processamento (limpeza, imputação, escala) e classificação (Logistic Regression, Random Forest, PCA, SMOTE/undersampling quando necessário).
- Não há dados versionados aqui, portanto é preciso fornecer os arquivos indicados nos próprios notebooks.
