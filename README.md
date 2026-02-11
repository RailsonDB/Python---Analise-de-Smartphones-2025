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




## 📈 Visualizações Gráficas
Foram criados gráficos como:
- Gráficos de barras com a quantidade de aparelhos por marca
- Gráfico de pizza com distribuição dos sistemas operacionais
- Gráfico de linha com faturamento mensal
- Gráfico de lançamento por mês


## Insighs Encontrados
- Android domina o mercado
- Marcas com Samsung e Realme se destacam
- Modelos com 5G lidera em volume
- Preço médio não necessariamente define melhor avaliação

