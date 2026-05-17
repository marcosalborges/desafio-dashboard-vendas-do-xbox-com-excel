# desafio-dashboard-vendas-do-xbox-com-excel
Projeto do desafio DIO: Dashboard de Vendas do Xbox com Excel — análise anual, mensal e trimestral de assinaturas e season passes.

# 🎮 Xbox Game Pass Subscriptions Sales Dashboard

## 📊 Visão Geral
Este projeto foi desenvolvido como parte do desafio **"Criando um Dashboard de Vendas do Xbox com Excel"**, do módulo **"Análise de Dados com Excel e Copilot"** proposto pela **Digital Innovation One (DIO)**.  

O objetivo é transformar dados brutos de vendas de assinaturas do **Xbox Game Pass** em informações visuais claras e úteis.  
O foco principal é permitir uma **análise eficaz do desempenho de vendas** e apoiar a **tomada de decisões baseadas em dados**.

O dashboard apresenta uma visão consolidada das vendas de planos anuais, mensais e trimestrais, além de dados específicos sobre os produtos **EA Play Season Pass** e **Minecraft Season Pass**.

---

## 🧩 Estrutura do Projeto
O repositório contém:
- **Dashboard principal (Excel)**: desenvolvido para exibir métricas de vendas e comparativos entre tipos de assinatura.
- **Base de dados 2024**: registros de vendas e assinaturas do Xbox Game Pass.
- **Documentação**: explicações sobre o processo de análise e construção do dashboard.

Além disso, utilizamos o **Método ABCD** para organizar o Workbook em abas, garantindo clareza e eficiência no desenvolvimento:

- **Assets**: Paletas de cores, imagens (ícones e logos) e elementos visuais para deixar o dashboard mais agradável e padronizado.  
- **Bases**: Aba destinada a armazenar a base de dados utilizada para obter as informações desejadas.  
- **Cálculos**: Espaço reservado para realizar os cálculos e preparar os dados que serão exibidos no dashboard.  
- **Dashboard**: Aba final de visualização, onde as informações são apresentadas de forma clara, rápida e contextualizada. Essa é a única aba exibida ao usuário final, enquanto as demais permanecem ocultas para manter a experiência limpa e objetiva.


---

## 💡 Perguntas de Negócio
O projeto responde às seguintes perguntas:

1. **Faturamento total anual**  
   Qual o faturamento total de vendas de planos anuais, considerando todas as assinaturas agregadas?

2. **Faturamento por auto renovação**  
   Qual o faturamento total e vendas de planos anuais, separados entre assinaturas com e sem auto renovação?

3. **Vendas EA Play Season Pass**  
   Qual o total de vendas do EA Play Season Pass?

4. **Vendas Minecraft Season Pass**  
   Qual o total de vendas do Minecraft Season Pass?

Essas métricas são apresentadas em três visões distintas:
- **Annual**
- **Monthly**
- **Quarterly**

---

## 🧠 Dados Utilizados
Os dados utilizados são referentes ao **ano de 2024**, com o período de cálculo entre **01/01/2024 e 31/12/2024**.  
A atualização dos dados ocorre em **25/12/2024 às 09:00:00**.

As principais variáveis incluem:

| Variável          | Descrição                           |
|-------------------|-------------------------------------|
| Tipo de Assinatura | Annual, Monthly, Quarterly          |
| Produto           | EA Play Season Pass, Minecraft Pass |
| Auto Renovação    | Sim / Não                           |
| Valor Total (R$)  | Faturamento agregado por categoria  |

---

## 🖥️ Visualizações
O dashboard foi construído com foco em **clareza e comparação visual**.  
Cada aba apresenta:
- **Totais de vendas por produto** (EA Play e Minecraft)
- **Comparativo de auto renovação** (Sim vs Não)
- **Filtros interativos** para selecionar o tipo de assinatura
