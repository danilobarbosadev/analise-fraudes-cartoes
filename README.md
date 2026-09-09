# Investigação de Fraudes em Transações de Cartão

Projeto de análise de dados desenvolvido em Python com o objetivo de investigar padrões suspeitos em transações contestadas e construir uma regra de apoio à decisão de ressarcimento.

> Os dados utilizados neste projeto são sintéticos e foram gerados exclusivamente para fins de estudo e portfólio.

## Objetivo

Identificar comportamentos potencialmente fraudulentos por meio da análise temporal, comportamental e do histórico transacional dos clientes.

## Principais etapas

- Limpeza e padronização dos dados
- Cruzamento de diferentes bases
- Análise exploratória das contestações
- Investigação de padrões temporais e comportamentais
- Segmentação por horário, região, estabelecimento e modalidade de fraude
- Comparação do valor contestado com o histórico do cliente
- Aplicação de P90 e P99
- Desenvolvimento de uma regra de decisão para ressarcimento

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- ipywidgets
- Google Colab

## Principais resultados

A análise identificou concentrações relevantes de contestações em determinados períodos, horários, estabelecimentos e adquirentes.

Também foi desenvolvida uma regra híbrida de ressarcimento baseada no histórico transacional de cada cliente.

No resultado final:

- **118 casos analisados**
- **117 casos classificados para ressarcimento**
- **1 caso sem histórico suficiente para decisão automática**
- **R$ 119.794,02 em potencial de ressarcimento**
- **99,15% dos clientes analisados classificados para ressarcimento**

## Projeto completo

O notebook contém todo o processo de preparação dos dados, análises, visualizações, hipóteses investigadas e construção da regra final.

➡️ [Acessar o notebook](investigacao_fraude_cartoes.ipynb)

---

Projeto desenvolvido como parte da evolução dos meus estudos e prática em **Python e Análise de Dados**.
