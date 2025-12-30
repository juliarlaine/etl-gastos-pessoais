# ETL de Gastos Pessoais

Este projeto foi desenvolvido como parte do **Santander Bootcamp 2025** e tem como objetivo demonstrar, de forma prática, o fluxo ETL (Extração, Transformação e Carregamento) utilizando Python e Pandas.

## 📌 Descrição do Projeto
O pipeline realiza a leitura de um arquivo CSV contendo dados de gastos pessoais, transforma esses dados por meio de agregações simples e, por fim, salva um novo arquivo com o resumo dos gastos por categoria.

## 🔄 Pipeline ETL
- **Extração**: leitura de dados a partir de um arquivo CSV local
- **Transformação**: conversão de tipos, agrupamento e ordenação dos gastos por categoria
- **Carregamento**: persistência dos dados transformados em um novo arquivo CSV

## 🗂️ Estrutura do Repositório
etl-gastos-pessoais/
├── data/
│ ├── gastos.csv
│ └── resumo_gastos.csv (gerado pelo pipeline)
├── notebook_python.ipynb
├── requirements.txt
└── README.md

## 🛠️ Tecnologias Utilizadas
- Python
- Pandas
- Jupyter Notebook

## ▶️ Como Executar
1. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

2. Execute o notebook notebook_python.ipynb célula por célula.