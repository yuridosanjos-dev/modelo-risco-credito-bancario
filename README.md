# 📊 Modelo de Inteligência Artificial para Risco de Crédito Bancário

Este projeto simula uma solução real de engenharia de dados e Machine Learning voltada para o setor financeiro. O objetivo principal é identificar perfis de clientes propensos à inadimplência e calcular o retorno financeiro gerado pela implementação do modelo.

## 💰 Impacto no Negócio (ROI)
* **Prejuízo Evitado:** R$ 1.600.000,00 (Simulação baseada em uma carteira de testes travando 64 calotes em potencial).
* **Eficiência do Modelo:** 85.50% de acurácia geral.
* **Foco Comercial:** 91% de assertividade na identificação de bons pagadores, evitando o bloqueio de clientes lucrativos.

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Python** (Linguagem base)
* **Pandas & NumPy** (Manipulação e estruturação dos dados sintéticos)
* **Matplotlib & Seaborn** (Análise exploratória visual e gráficos de comportamento)
* **Scikit-Learn** (Algoritmo de Machine Learning: *Random Forest Classifier*)

## 📈 Lógica de Desenvolvimento
1. **Geração de Dados Sintéticos:** Criação de uma base de 1.000 clientes amarrando variáveis de Score (Serasa) e Renda Anual.
2. **Feature Engineering:** Criação da variável de proporção de comprometimento de renda em relação ao valor do empréstimo.
3. **Análise Visual (EDA):** Identificação de padrões de risco concentrados em faixas de baixa renda e baixo score.
4. **Treinamento de IA:** Divisão de dados (80/20) e treinamento do classificador com métricas de validação completas para apresentação técnica.
