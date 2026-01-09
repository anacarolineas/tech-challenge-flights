## Previsão de Atrasos de Voos com Machine Learning

### 📌 Descrição do Projeto

Este projeto tem como objetivo prever atrasos de voos utilizando algoritmos de Machine Learning supervisionado, a partir de dados históricos de voos. A previsão de atrasos é um problema relevante para o planejamento operacional de companhias aéreas e para a melhoria da experiência dos passageiros.

### 🎯 Objetivo

Construir, treinar e comparar modelos de Machine Learning capazes de classificar voos como atrasados ou não atrasados, avaliando desempenho, custo computacional e aplicabilidade prática.

### 🗂️ Dados Utilizados

Os dados incluem informações operacionais dos voos, como:

- Horário programado
- Aeroporto de origem e destino
- Companhia aérea
- Variáveis temporais (hora do dia, dia da semana, etc.)
- Histórico de atrasos

A variável alvo é:
- Atraso do voo (atrasado / não atrasado)

### 🧠 Modelos Utilizados

Foram avaliados dois modelos principais:

**Random Forest**

- Utilizado como baseline robusto 
- Boa capacidade de generalização
- Menor custo de processamento
- Facilita a interpretação da importância das variáveis

**XGBoost**

- Modelo baseado em Gradient Boosting
- Melhor desempenho preditivo
- Redução de falsos negativos (atrasos não detectados)
- Mais adequado para uso em cenários operacionais