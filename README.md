# Marketing Bancário 💰💲

## Introdução
Este projeto visa analisar dados relacionados a campanhas de marketing bancário, focando na compreensão das características dos clientes que influenciam suas decisões de depósito. O modelo é projetado para aprender com os dados existentes, permitindo prever o público-alvo e identificar fatores que impactam a adesão a depósitos a prazo.

## 📊 Variáveis Trabalhadas
- **Age**: Idade do cliente.
- **Job**: Tipo de trabalho do cliente.
- **Marital**: Estado civil do cliente.
- **Education**: Nível de educação do cliente.
- **Default**: Indicador se o cliente está com crédito inadimplente.
- **Balance**: Saldo médio anual do cliente em euros.
- **Housing**: Indicador se o cliente possui empréstimo habitacional.
- **Loan**: Indicador se o cliente possui empréstimo pessoal.
- **Day**: Último dia de contato do mês.
- **Month**: Último mês de contato do ano.
- **Duration**: Duração do último contato, em segundos.
- **Campaign**: Número de contatos realizados durante esta campanha para este cliente, incluindo o último contato.
- **Pdays**: Dias desde que o cliente foi contatado pela última vez em uma campanha anterior (-1 indica que não foi contatado anteriormente).
- **Previous**: Número de contatos realizados antes desta campanha para este cliente.
- **Poutcome**: Resultado da campanha de marketing anterior.

### Variável Alvo
- **Depositou (y)**: O cliente subscreveu a um depósito a prazo?

## 📂 Fonte dos Dados
- **Bank Marketing Classification Dataset**:  
  Disponível no Kaggle: [Bank Marketing Dataset](https://www.kaggle.com/datasets/adilashrafi/bank-marketing-classification-task)

## 💻 Linguagem Utilizada
- **Python**

## 📚 Bibliotecas Utilizadas

- **Tratamento de Dados**:
  - `pandas`: Para manipulação e análise de dados.
  - `numpy`: Para operações matemáticas e numéricas.

- **Visualização de Dados**:
  - `seaborn`: Para criação de gráficos estatísticos.
  - `matplotlib`: Para visualização de dados.

- **Modelagem**:
  - `DecisionTreeClassifier`: Para modelagem de classificação.
  - `train_test_split`: Para dividir os dados em conjuntos de treino e teste.
  - `metrics`: Para avaliação do modelo.
  - `accuracy_score`, `classification_report`: Para métricas de desempenho do modelo.


## Link do Projeto.
<div align="left">  
<a href="https://github.com/felipefagion/MLearning/blob/main/ProjetoMl.ipynb" target="_blank"><img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"</a>

## Link do com Vídeo Dashboard Interativo .
<div align="left">  
<a href="https://github.com/felipefagion/MLearning/blob/main/dash_boardmarket.gif" target="_blank"><img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"</a>

