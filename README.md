📊 Análise de Receita de Planos de Telecom (Megaline)
🚀 Visão Geral

Neste projeto, realizei uma análise de dados para a empresa fictícia Megaline, com o objetivo de identificar qual plano pré-pago — Surf ou Ultimate — gera mais receita.

A análise combina exploração de dados, modelagem de receita e testes estatísticos para apoiar decisões de negócio baseadas em dados.

🎯 Problema de Negócio

A equipe comercial precisava decidir qual plano promover mais nas campanhas de marketing.

A pergunta central foi:

👉 Qual plano gera mais receita para a empresa?

🧠 Abordagem Analítica

O projeto foi estruturado em etapas claras:

🔹 1. Preparação dos Dados
Limpeza e tratamento de valores ausentes
Conversão de tipos de dados
Padronização dos datasets

🔹 2. Feature Engineering
Cálculo de uso mensal por usuário:
📞 Minutos de chamadas
💬 Mensagens enviadas
🌐 Dados móveis utilizados
Agregação por usuário e por mês

🔹 3. Análise Exploratória (EDA)
Comparação de comportamento entre os planos
Distribuições de uso
Identificação de padrões e outliers

🔹 4. Modelagem de Receita
Implementação das regras de cobrança de cada plano
Cálculo da receita mensal por usuário
Comparação direta entre planos

🔹 5. Testes Estatísticos
Teste de hipótese para validar diferenças de receita
Avaliação de significância estatística

📈 Principais Resultados
Diferenças claras no comportamento de consumo entre os planos
Usuários de planos distintos apresentam perfis de uso diferentes
A receita média varia de forma relevante entre os planos

💡 Impacto de Negócio
Suporte direto à decisão de marketing
Otimização potencial de receita
Demonstração do uso de dados para decisões estratégicas

🛠️ Tecnologias e Ferramentas
Python
Pandas
NumPy
Matplotlib / Seaborn
SciPy (testes estatísticos)
Jupyter Notebook

📂 Estrutura do Projeto
├── sprint4.ipynb   # Análise completa
├── README.md       # Documentação