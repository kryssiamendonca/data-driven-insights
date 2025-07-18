# Data Driven Insights - Análise de Vendas

Este projeto realiza uma análise exploratória do dataset de vendas `sales_data_sample.csv`, utilizando Python, Pandas e visualizações com Seaborn e Matplotlib.

## Objetivos:

- Entender o comportamento das vendas por unidade e por mês
- Identificar as unidades com maior volume de pedidos
- Classificar vendas em categorias para facilitar tomada de decisão
- Gerar visualizações que facilitem a interpretação dos dados

## Estrutura do Projeto

- `data_driven_insights.ipynb`: notebook com a análise completa
- `sales_data_sample.csv`: base de dados (anonimizada)
- `imagens/`: gráficos e visualizações gerados durante a análise

## Ferramentas Utilizadas

- Python 3
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Google Colab (para análise e integração com Google Drive)

## Como usar

1. Faça o clone do repositório
2. Abra o notebook no Google Colab
3. Conecte seu Google Drive para acessar o dataset
4. Execute as células na ordem para reproduzir a análise

## Possíveis melhorias futuras

- Tornar os gráficos interativos com Plotly
- Implementar limpeza automática de dados
- Criar dashboard com KPIs em ferramentas como Power BI ou Dash

---

**Explicação do notebook**

O notebook data_driven_insights.ipynb é uma análise exploratória de um dataset de vendas (sales_data_sample.csv) que carreguei no meu Google Drive pessoal.

**Como funciona:**

**Carregamento dos dados**: lê o CSV e exibe as primeiras linhas para conhecer a base.

**Análise inicial**: mostra tipos de dados, estatísticas básicas, e valores ausentes para entender qualidade e estrutura.

**Transformação de dados**: converte colunas para formatos corretos (ex: datas), cria colunas auxiliares como MES_ANO.

**Agrupamentos e métricas**: calcula total de vendas, número de pedidos por unidade e mês, identifica unidades com maior volume.

**Visualizações**: gera gráficos (barras, distribuições) para mostrar tendências e destacar insights importantes.

**Classificações com if/else**: segmenta vendas em categorias (Alta, Média, Baixa) para facilitar a análise e priorização.

**Salvamento de gráficos**: exporta imagens para o Google Drive, facilitando uso no GitHub ou relatórios.

## O motivo é criar um fluxo de análise organizado, que permita extrair informações úteis para tomada de decisão, apresentando dados limpos, visuais claros e insights acionáveis.

---

## Autora
      Kryssia Mendonça - https://github.com/kryssiamendonca
