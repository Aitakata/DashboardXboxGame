# 🎮 Dashboard de Vendas Xbox com Excel

## 📋 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio **"Criando um Dashboard de Vendas do Xbox com Excel"** da plataforma DIO.

O objetivo do desafio foi transformar dados brutos em informações estratégicas por meio da construção de um dashboard interativo no Microsoft Excel, permitindo uma análise visual eficiente do desempenho das vendas de assinaturas do Xbox Game Pass.

---

## 🎯 Objetivos

- Organizar e tratar dados de vendas.
- Aplicar conceitos de análise de dados no Excel.
- Criar indicadores visuais para apoio à tomada de decisão.
- Desenvolver um dashboard intuitivo e de fácil interpretação.
- Utilizar segmentações de dados (Slicers) para navegação dinâmica.

---

## 📊 Base de Dados

A base utilizada contém informações sobre assinaturas do Xbox Game Pass, incluindo:

- ID do assinante
- Nome do cliente
- Tipo de plano
- Data de início da assinatura
- Renovação automática
- Valor da assinatura
- Tipo da assinatura
- EA Play Season Pass
- Minecraft Season Pass
- Cupons de desconto
- Valor total da compra

Fonte dos dados: disponibilizada pela DIO para fins educacionais. 【1-937630】

---

## 📈 Indicadores Desenvolvidos

O dashboard responde às seguintes perguntas de negócio:

### 1. Qual o faturamento total das vendas de planos anuais?

Análise consolidada do faturamento gerado por assinaturas anuais.

### 2. Qual o faturamento das vendas anuais considerando renovação automática?

| Renovação Automática | Faturamento |
|---------------------|-------------|
| Não | R$ 217,00 |
| Sim | R$ 1.537,00 |
| **Total** | **R$ 1.754,00** |

Dados obtidos na aba de cálculos da planilha. 【1-937630】

### 3. Total de vendas do EA Play Season Pass

- Total vendido: **R$ 600,00**

【1-937630】

### 4. Total de vendas do Minecraft Season Pass

- Total vendido: **R$ 940,00**

【1-937630】

---

## 🖥️ Dashboard
<img width="1175" height="877" alt="image" src="https://github.com/user-attachments/assets/231f8b42-238d-45bb-8869-e7334a67c1ca" />


O dashboard foi desenvolvido utilizando:

- Tabelas Dinâmicas
- Segmentação de Dados (Slicers)
- Cartões de KPI
- Formatação condicional
- Design visual baseado na identidade Xbox
- Consolidação de métricas e indicadores

Principais métricas exibidas:

✅ Total de assinaturas EA Play  
<img width="437" height="157" alt="image" src="https://github.com/user-attachments/assets/999c423c-56e4-4235-92ae-a9392f25ca19" />

✅ Total de assinaturas Minecraft Season Pass  
<img width="432" height="157" alt="image" src="https://github.com/user-attachments/assets/6f7b0d64-eba5-4c69-abb0-28d0ef2ff8c0" />

✅ Faturamento de assinaturas anuais  
✅ Análise por renovação automática

---

## 📂 Estrutura do Repositório

```text
📦 dashboard-vendas-xbox
┣ 📜 README.md
┣ 📊 Dashboard.xlsx
┣ 📷 imagens
┃ ┗ dashboard.png
