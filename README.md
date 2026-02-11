# 📊 Projeto de Análise de Preços Globais de Smartphones - 2025

## 📌 Contexto
Este projeto realiza uma análise exploratória de dados (EDA) a partir de um dataset.<br>
fictício contendo informações sobre smartphones vendidos globalmente em 2025.
A base de dados foi obtida no **Kaggle** e contém variáveis relacionadas a preço,<br>
especificações técnicas, sistemas operacional, avaliações de usuários e mês de lancamento<br>
O foco do projeto  é transformar dados brutos em insights de negócio por meio de<br>
análise estatítica descritiva e visualizações gráficas.

## 🎯 Objetivo do Projeto
- Praticar manipulação e transformação de daods com Pandas
- Aplicar técnicas de Análises Exploratória de Dados (EDA)
- Investigar padrões e relações entre preço, hardware e avliação
- Gerar visualizações para apoiar interpretações analíticas
- Desenvolvover raciocínio orientado a pergunta de negócio


## 🗂️ Sobre o Conjunto de Dados
- 1000 registros
- 15 colunas
- Nenhum valor nulo
- Nenhum registro duplicado
## Principais Variáveis
- brand
- model
- price_usd
- ram_gb
- storage_gb
- camera_mp
- battery_mah
- display_size_inch
- charging_watt
- 5g_support
- os
- processor
- rating
- release_month
- year

Após validação, foi confirmado que os tipos de dados estvam corretos e a base<br>
estava íntegra para análise.


## 🛠️ Tecnologias Utilizadas
- **Python 3.11.9**
- **Pandas** - manipulação de e transfornação de dados
- **Matplolib** - visualização de dados


## 📌 Perguntas de Negócio Investigadas
Durante a análise, foram exploradas as seguintes questões:
- Quais marcas aparecem com mais frequência ?
- Quais são os modelos e marcas mais bem avaliados?
- Quais são os modelos e marcas menos avaliados?
- Quantas avaliaçõesnegativas cada modelo recebeu?
- Qual sistema operacional é o mais utilizado?
- Qual foi o faturamento total por mês?
- Quantos celulares foram lançados por mês?
- Como o suporte ao **5G** impacta preço e avaliação?


## 📊 Principais Análises Realizadas
### 📌 Participação por Marca
- Identificação da frequência de cada marca no conjunto de dados.

- Insight:
  Vivo, Google e OnePlus apresentam maior volume de modelos registrados.

### 📌 Avaliação Média por Modelo e Marca
- Cálculo da média de avaliações por modelo e por marca.

- Insight:
  Samsung e Realme apresentam as maiores médias de avaliação entre as marcas

### 📌 Avaliações Negativas
- Foram consideradas negativas as avaliações ≤3.9.

- Insight:
  Não houve concentração significativa de avaliações negativas em modelos específicos.

### 📌 Sistema Operacional
- Análise da distribuição percentual por sistema operacional.

- Insight:
  Android representa aproximadamente 89% dos dispositivos do dataset, indicando forte<br>
  concentração de mercado no exossistema Android.

### 📌 Faturamento Mensal
- Cálculo do faturamento total por mês com base na soma de price_usd.

- Insight:
  Abril apresentou o maior faturamento no período analisado.

### 📌 Volume de Lançamentos
- Análise de quantidade lançamentos por mês.

- Insight:
  Abril também foi o mês com maior número de lançamentos.

### 📌 Análise de Suporte ao 5G
- Comparação entre dispositivos com e sem suporte ao 5G.

- Rsultados:
  - Modelos com 5G representam 503 registros
  - Modelos sem 5G representam 497 registros
  - Diferença pequena no preço médio
  - Avaliação média semelhante entre os grupos
- Insigth:
  O suporte ao 5G não demonstrou impacto significativo na avaliação média, mas está<br>
  fortemente presente no volume de modelos lançados.


## 📈 Visualizações Desenvolvidas
- Gráficos de barras - quantidade de modelos por marca
- Gráfico de pizza - distribuição de sistemas operacionais
- Gráfico de linha - faturamento mensal
- Gráfico de barras - lançamentos por mês


## 🧠 Conclusões Estratégicas
- O mercado apresenta forte concentração no sistema Android
- Marcas como Samsung e Realme se destacam em avaliação média
- O preço não demonstrou relação direta com melhor avaliação
- O suporte ao 5G está amplamente distribuído, mas não impacta significativamente a<br>
  percepção de qualidade

