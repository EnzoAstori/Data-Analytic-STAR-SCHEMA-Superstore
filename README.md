# 📊 Análise de Vendas — Superstore (2014–2017)

## 📌 Visão Geral do Projeto

Este projeto apresenta uma **análise exploratória de dados (EDA)** do dataset fictício **Superstore**, abrangendo o período de 2014 a 2017.

O modelo foi estruturado em **Star Schema**, garantindo organização, escalabilidade e performance analítica.

### 🏗️ Modelagem de Dados

**Tabelas Dimensão:**
- `DIM-Clients`
- `DIM-Products`
- `DIM-Orders`
- `DIM-Sales`

**Tabela Fato:**
- `FAC-Superstore`

O modelo permite análises temporais, por categoria, produto, cliente e logística.

---

# ❓ Perguntas de Negócio Respondidas

- Qual o panorama geral do negócio?
- Como evoluíram as vendas ao longo dos anos?
- Qual modo de envio predomina?
- Quais categorias geram mais receita e lucro?
- Qual o impacto dos descontos na lucratividade?
- Quais produtos apresentam desempenho crítico?
- Quais ações estratégicas podem otimizar resultados?

---

# 📈 Principais Métricas

| Métrica            | Valor        |
|--------------------|-------------|
| 💰 Receita Total   | **$2,30 Mi** |
| 📈 Lucro Total     | **$286,4 Mil** |
| 📦 Itens Vendidos  | **38 Mil** |
| 🎯 Descontos Totais | **$1,56 Mil** |

---

# 📊 Análises Realizadas

## 1️⃣ Panorama Geral

- Crescimento consistente ano após ano.
- Modelo de negócio sustentável com lucro positivo acumulado.
- Alta dependência de vendas em determinadas categorias.

---

## 2️⃣ Evolução das Vendas (2014 → 2017)

| Ano  | Receita |
|------|---------|
| 2014 | $0,15 Mi |
| 2015 | Crescimento |
| 2016 | Crescimento |
| 2017 | $0,45 Mi |

📌 **Insight:**  
O crescimento foi contínuo e acelerado, indicando maturidade operacional e aumento de demanda.

---

## 3️⃣ Vendas por Modo de Envio

- 🚚 **Standard Class** → Modalidade dominante (maior volume)
- ⚡ First Class → Nicho estratégico
- 🚀 Same Day → Entregas premium

📌 **Insight:**  
A empresa prioriza eficiência logística de custo moderado (Standard Class), maximizando margem.

---

## 4️⃣ Desempenho por Categoria

| Categoria         | Destaques              | Análise |
|------------------|------------------------|----------|
| 🖥 Technology     | Phones, Copiers        | Líder em receita e lucro |
| 🗂 Office Supplies| Binders, Paper         | Alto volume e estabilidade |
| 🪑 Furniture      | Tables, Bookcases      | Margens inconsistentes |

📌 **Insight Estratégico:**  
- **Technology** é o motor financeiro da operação.  
- **Office Supplies** garante fluxo constante.  
- **Furniture** exige revisão estratégica.

---

## 5️⃣ Impacto dos Descontos na Lucratividade

Exemplo crítico identificado:

> 🪑 Mesa com 45% de desconto → Prejuízo de **-$383**

### Padrões Observados:

- ❌ Furniture com descontos >30% tende a operar no vermelho.
- ⚖️ Technology mantém margem mesmo com descontos moderados.
- 📉 Descontos agressivos impactam diretamente a lucratividade.

📌 **Insight:**  
Política de descontos precisa ser segmentada por categoria.

---

# 🚨 Produtos com Desempenho Crítico

- Itens de Furniture com alta taxa de desconto.
- Produtos com volume baixo e margem negativa.
- Dependência excessiva de poucos produtos de Technology.

---

# 🎯 Recomendações Estratégicas

### 1️⃣ Revisão da Política de Descontos
- Limitar descontos de Furniture a ≤20–25%.
- Criar regra dinâmica baseada em margem mínima.

### 2️⃣ Fortalecer Technology
- Expandir mix de produtos premium.
- Investir em marketing direcionado.

### 3️⃣ Otimização de Portfólio
- Descontinuar produtos com prejuízo recorrente.
- Foco em produtos com alta margem + alta demanda.

### 4️⃣ Estratégia Logística
- Manter Standard Class como principal.
- Oferecer upgrade pago para Same Day.

---

# 📌 Conclusão Executiva

O negócio apresenta:

✅ Crescimento consistente  
✅ Lucro positivo acumulado  
✅ Forte performance em Technology  
⚠️ Fragilidade na categoria Furniture  
⚠️ Descontos impactando margens  

A empresa possui base sólida, mas pode aumentar significativamente sua rentabilidade com ajustes estratégicos na política de descontos e no portfólio.

---

# 🛠️ Tecnologias Utilizadas

- Power BI
- Modelagem Star Schema
- DAX
- Análise Exploratória de Dados (EDA)

---

# 👨‍💻 Autor

**Enzo Rubim Astori**  
Estudante de Engenharia da Computação  
Foco em Data Analytics e Business Intelligence

---
