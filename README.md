Projeto de análise de dados em Python focado na identificação de padrões e redução do cancelamento de clientes (Churn Rate) utilizando Pandas e Plotly.

# 📊 Análise de Cancelamento de Clientes (Churn Analysis)

## 🎯 Objetivo do Projeto

Com uma taxa de cancelamento inicial superior a **56%**, o objetivo deste projeto é:

1. Tratar e organizar a base de dados de clientes.

2. Analisar os fatores de maior impacto na decisão de cancelamento.

3. Simular o impacto de decisões estratégicas na redução do *churn*.

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**

- **Pandas**: Limpeza, filtragem e manipulação de dados.

- **Plotly Express**: Visualização interativa e análise exploratória de gráficos.

- **Jupyter Notebook**: Ambiente interativo para execução do código.

## 📂 Estrutura do Repositório

```text
.

├── cancelamentos_sample.csv   # Amostra da base de dados dos clientes

├── analise_cancelamentos.ipynb # Notebook com o código Python e gráficos

└── README.md                  # Documentação do repositório

```

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**

   ```bash

   git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git

   cd NOME-DO-REPOSITORIO

   ```

2. **Instale as dependências necessárias:**

   ```bash

   pip install pandas plotly notebook

   ```

3. **Abra o Jupyter Notebook:**

   ```bash

   jupyter notebook

   ```

   Execute o arquivo `analise_cancelamentos.ipynb`.

## 📌 Principais Insights Encontrados

Após o tratamento e cruzamento dos dados com gráficos interativos, foram identificados 3 pontos críticos de cancelamento:

1. **Tipo de Contrato:** Clientes no plano **mensal** apresentam taxa de cancelamento próxima de 100%.

   - *Ação:* Criar incentivos e descontos para migração para planos anuais ou trienais.

2. **Atendimento ao Cliente:** Clientes que ligaram mais de **4 vezes** para o Call Center cancelaram o serviço.

   - *Ação:* Implementar alerta de prioridade no suporte ao atingir a 3ª ligação.

3. **Atraso no Pagamento:** Clientes com mais de **20 dias** de atraso no pagamento cancelaram 100% das vezes.

   - *Ação:* Criar régua de cobrança automática e ofertas de renegociação antes dos 10 dias de atraso.

## 📈 Resultados da Simulação

Ao filtrar a base de dados simulando a resolução dos 3 gargalos principais:

- A taxa de cancelamento foi reduzida de **56.7%** para aproximadamente **18%**.
