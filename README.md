# Simulação de Monte Carlo para Previsão de Preços de Ações

Este projeto utiliza a **Simulação de Monte Carlo** para prever preços futuros de ações com base em dados históricos. O foco é na ação da **Banco do Brasil (BBAS3.SA)**, mas o modelo pode ser adaptado para qualquer ativo.

---

## Objetivo

O objetivo deste projeto é:
1. Demonstrar a aplicação da Simulação de Monte Carlo no mercado financeiro.
2. Prever preços futuros de ações com base em dados históricos.
3. Visualizar a distribuição de probabilidade dos preços finais.

---

## Metodologia

O modelo utilizado é o **Movimento Browniano Geométrico (GBM)**, que simula a evolução dos preços considerando:
- **Retorno médio (μ)**: Média dos retornos históricos.
- **Volatilidade (σ)**: Desvio padrão dos retornos históricos.
- **Preço atual (S0)**: Último preço histórico da ação.

A simulação gera múltiplas trajetórias de preços, permitindo visualizar a incerteza e a variabilidade inerentes ao mercado financeiro.

---

## Como Usar

### Pré-requisitos

Certifique-se de ter as seguintes bibliotecas instaladas:

```bash
pip install numpy pandas matplotlib yfinance