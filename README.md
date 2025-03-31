📝 README
📌 Visão Geral
Este projeto demonstra a aplicação de regressão polinomial para prever valores de aluguel com base em características de imóveis. Desenvolvido como parte do Módulo 34 do curso EBAC, o trabalho explora diferentes graus de polinômios e compara seus desempenhos.

🎯 Objetivos
Implementar modelos de regressão polinomial com diferentes graus

Comparar o desempenho entre modelos com polynomial features de grau 2 e 4

Visualizar os resultados das previsões

Explicar conceitos de regularização (Ridge, Lasso e Elastic Net)

📂 Estrutura do Projeto
Copy
aluguel-regressao/
│
├── dados/
│   └── ALUGUEL_MOD12.csv          # Dataset original
│
├── notebooks/
│   └── regressao_aluguel.ipynb    # Jupyter notebook com a análise completa
│
├── graficos/                      # Pasta para armazenar visualizações
│   ├── regressao_degree2.png
│   └── regressao_degree4.png
│
└── README.md                      # Este arquivo
🔧 Requisitos
Python 3.8+

Bibliotecas:

pandas

numpy

matplotlib

scikit-learn

jupyter (para o notebook)

🚀 Como Executar
Clone o repositório

Crie e ative um ambiente virtual:

bash
Copy
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows
Instale as dependências:

bash
Copy
pip install -r requirements.txt
Execute o Jupyter Notebook:

bash
Copy
jupyter notebook
Abra o notebook regressao_aluguel.ipynb
