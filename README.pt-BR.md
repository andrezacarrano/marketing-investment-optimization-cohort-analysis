# 📈 Otimização de Investimento em Marketing: Estudo de Caso Y.Afisha

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)](https://pandas.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 📋 Sumário
- [Objetivo do Projeto](#-objetivo-do-projeto)
- [Resultados](#-resultados)
- [Ferramentas Utilizadas](#-ferramentas-utilizadas)
- [O que Aprendi](#-o-que-aprendi-evidências-técnicas)
- [Melhorias Futuras](#-melhorias-futuras)
- [Como Executar](#-como-executar)

## 🎯 Objetivo do Projeto
Otimização das despesas de marketing da plataforma **Y.Afisha** através da análise de logs de servidor, dados de pedidos e estatísticas de custos. O foco central é determinar a eficiência dos diferentes canais de marketing, analisar o comportamento de retenção de usuários e calcular métricas de rentabilidade (**LTV** e **ROMI**) para fundamentar decisões estratégicas de alocação de orçamento.

## 📊 Resultados
- **Métricas de Engajamento**: Cálculo de DAU, WAU e MAU, identificando os períodos de maior atividade e a duração média das sessões de uso.
- **Análise de Conversão**: Mapeamento do tempo de conversão (de registro a cliente), identificando as coortes com maior velocidade de fechamento.
- **Rentabilidade por Canal**: Identificação dos canais de marketing com o melhor ROMI (Retorno sobre Investimento em Marketing) e o menor CAC.
- **Recomendação Estratégica**: Formulação de proposta de redistribuição de orçamento focada nos canais que apresentam retorno positivo (LTV > CAC) e maior retenção ao longo do tempo.

## 🛠️ Ferramentas Utilizadas
- **Linguagem**: Python
- **Bibliotecas**:
  - Pandas (Processamento de dados)
  - Matplotlib e Seaborn (Visualização)
  - NumPy (Cálculos matemáticos)
- **Metodologias**: Análise de Coortes, Cálculo de LTV, CAC e ROMI (Retorno sobre Investimento)
- **Ambiente**: VS Code / Jupyter Notebook

## 📚 O que Aprendi (Evidências Técnicas)
- **Estruturação de Análise de Coortes**: Agrupamento de usuários por data de primeira compra para monitorar o comportamento ao longo do tempo.
- **Cálculo de Métricas de Negócio (KPIs)**: Implementação de lógica para calcular LTV (Lifetime Value) acumulado e CAC por origem de anúncio.
- **Análise de Funil e Retenção**: Avaliação da frequência de retorno dos usuários e identificação de pontos de atrito no processo de compra.
- **Visualização de Dados Financeiros**: Criação de mapas de calor (heatmaps) para visualização de coortes e gráficos de barras empilhadas para distribuição de custos e receitas.

## 🚀 Melhorias Futuras
- **Modelagem Preditiva de LTV**: Utilização de algoritmos de regressão para prever o valor futuro de novos clientes com base nas primeiras interações.
- **Segmentação Avançada**: Análise do comportamento de compra cruzado entre diferentes dispositivos (Desktop vs. Mobile) para personalização de anúncios.
- **Automação de Dashboards**: Integração dos resultados em uma ferramenta de BI (Tableau ou Power BI) para monitoramento em tempo real.

## ▶️ Como Executar
1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/marketing-optimization-yafisha.git
   cd marketing-optimization-yafisha
   ```

2. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Execute o notebook**:
   Abra o arquivo `marketing-investment-optimization-cohort-analysis.ipynb` no Jupyter Notebook ou VS Code e execute as células em ordem.

## 📞 Contato
Para dúvidas ou sugestões, entre em contato via [email@example.com](mailto:email@example.com) ou abra uma issue no repositório.

---
*Este projeto faz parte do curso de Análise de Dados da TripleTen.*
