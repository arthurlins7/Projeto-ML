# Predição e Análise de Sífilis Congênita com Machine Learning

## Descrição do Projeto
Este projeto aplica técnicas de aprendizado de máquina para investigar fatores clínicos e sociodemográficos associados a casos de sífilis congênita no Brasil, com base no dataset *"Clinical and sociodemographic data on congenital syphilis cases"* (2013-2021). O objetivo é criar modelos preditivos que possam auxiliar na identificação de fatores de risco e propor intervenções preventivas para saúde pública.

As tarefas principais incluem:
- Pré-processamento e análise exploratória de dados.
- Construção de modelos de classificação para prever o resultado do exame VDRL.
- Construção de modelos de regressão para analisar a relação com a idade dos pacientes.
- Interpretação dos resultados para fornecer insights sobre prevenção e políticas públicas.

---

## Estrutura do Repositório
```plaintext
├── data/                      # Arquivos do dataset e scripts de manipulação.
├── notebooks/                 # Notebooks Jupyter com análises e modelos.
│   ├── exploration.ipynb      # Análise exploratória e pré-processamento.
│   ├── classification.ipynb   # Modelos de classificação.
│   ├── regression.ipynb       # Modelos de regressão.
├── src/                       # Scripts Python para modularizar o código.
│   ├── preprocess.py          # Funções para limpeza e transformação de dados.
│   ├── models.py              # Implementação de modelos.
│   ├── evaluation.py          # Métricas de avaliação.
├── results/                   # Relatórios gerados e gráficos.
├── README.md                  # Documentação do projeto.
└── requirements.txt           # Dependências do projeto.

