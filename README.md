# Checkpoint 01 2SEM-SERS - Analise de Dados de Energia
Análise de dados de energia (datasets e API pública) utilizando Orange Data Mining, Python e Pandas, para o Checkpoint 01 do 2º Semestre da disciplina de Soluções em Energias Renováveis e Sustentáveis do 1º do curso Ciência da Computação da FIAP

## Integrantes

| Nome completo | RM |
| --- | --- |
| Augusto de Souza Avila | 570839 |
| Davi Simoncelo | 571738 |
| João Pedro Sousa | 573962 |
| Matheus Evangelista | 568593 |
| Murilo Lima de Carvalho | 570156 |

---

## Descrição

A análise é feita primeiramente em 6 datasets públicos relacionados à energia disponíveis no UC Irvine Machine Learning Repository e Kaggle, com situações-problema hipotéticas para a análise, dividida em 2 etapas. Na etapa A, é utilizado o Orange Data Mining para carregar, inspecionar, selecionar atributos, verificar a qualidade dos dados, gerar uma amostra e exportar o conjunto preparado. Na etapa B, é utilizado o Python / Pandas para carregar o arquivo preparado, organizar os atributos, calcular valores de referência, criar novos DataFrames por filtros, contar registros, calcular percentuais e interpretar os resultados.

Depois é feita a consulta e análise de dados obtidos diretamente de uma API pública do Portal de Dados Abertos do Operador Nacional do Sistema Elétrico (ONS), com o conjunto de dados selecionado sendo o de Carga de Energia Verificada, filtrado para somente dados da área SP — São Paulo, no período de 01/08/2025 a 07/08/2025. Nessa análise, é usado o Pandas, com auxílio do Matplotlib e Seaborn para a criação de gráfico. É feita a requisição, a construção, a inspeção do dataframe e a organização dos dados. São utilizados indicadores para a análise sobre o comportamento dos dados e dos padrões de consumo. É feita a visualização dos dados em gráficos, o relatório técnico com auxílio de inteligência artificial, a validação crítica desse relatório e o relatório final sobre o conjunto de dados.

Toda a construção da análise está no formato de 2 Jupyter Notebooks, com relatórios e insights.

---

## Fontes

### Dataset 1 — Appliances Energy Prediction (UCI)

Fonte: https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction

Situação:

A empresa de eficiência energética está analisando o comportamento de uma residência de baixo consumo. A equipe deseja identificar períodos de consumo elevado dos eletrodomésticos e observar quais condições de temperatura e umidade estavam presentes nesses momentos.

### Dataset 2 — Steel Industry Energy Consumption (UCI)

Fonte: https://archive.ics.uci.edu/dataset/851/steel+industry+energy+consumption

Situação:

A equipe de gestão de energia de uma indústria siderúrgica deseja localizar situações de consumo elevado e verificar se esses períodos coincidem com condições de carga elevada ou valores menos favoráveis de fator de potência.

### Dataset 3 — Power Consumption of Tetouan City (UCI)

Fonte: https://archive.ics.uci.edu/dataset/849/power+consumption+of+tetouan+city

Situação:

Uma equipe responsável pelo planejamento da distribuição de energia em Tétouan deseja identificar qual das três zonas apresenta o maior pico de consumo e observar as condições ambientais registradas nos momentos de maior demanda.

### Dataset 4 — Solar Power Generation Data (Kaggle)

Fonte: https://www.kaggle.com/datasets/anikannal/solar-power-generation-data

Situação:

Uma equipe de operação de uma usina fotovoltaica deseja localizar períodos de alta geração e identificar quais inversores aparecem com maior frequência nesses momentos. Nesta atividade, o foco inicial será o arquivo de geração da planta, sem realizar junção com o arquivo de sensores.

### Dataset 5 — Wind & Solar Energy Production (Kaggle)

Fonte: https://www.kaggle.com/datasets/ahmeduzaki/wind-and-solar-energy-production-dataset

Situação:

Um operador de um portfólio de fontes renováveis deseja comparar a ocorrência de períodos de alta produção solar e alta produção eólica. Como as duas fontes possuem escalas próprias, cada uma deverá ser comparada com o seu próprio valor máximo.

### Dataset 6 — Individual Household Electric Power Consumption (UCI)

Fonte: https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

Situação:

Uma residência possui monitoramento elétrico detalhado e deseja identificar episódios de demanda elevada que também apresentem corrente acima do comportamento médio. O dataset é o mesmo utilizado como referência em aula, mas o critério de análise será diferente.

### API

API pública de **Carga Verificada do ONS**:

- Portal: https://dados.ons.org.br/
- Conjunto de dados: https://dados.ons.org.br/dataset/carga-energia-verificada

Nesta análise foi utilizado os dados da área **SP — São Paulo**, no período de **01/08/2025 a 07/08/2025**.

---