# 📦 Análise de Embarque Portuário - Power BI + MySQL

Este projeto apresenta uma análise visual dos embarques portuários com base no dataset **Port Shipment Dataset**, disponibilizado no Kaggle. Através do uso de **MySQL** para armazenamento e do **Power BI** para visualização, foi possível construir um dashboard informativo que apresenta os principais insights sobre os dados de embarque.

---

## 🔗 Fonte dos Dados

- [Kaggle - Port Shipment Dataset](https://www.kaggle.com/datasets/mikoajfish99/port-of-los-angeles)

---

## 🧰 Tecnologias Utilizadas

- **MySQL** – Armazenamento dos dados
- **Power BI** – Conexão, transformação e visualização dos dados
- **Power Query** – Para tratamento e cálculo de colunas como peso total e volume

---

## ⚙️ Etapas do Projeto

1. **Download do Dataset** no Kaggle.
2. **Importação para o MySQL**:
   - Criação de um novo schema
   - Criação de tabela com base nas colunas do CSV
   - Importação dos dados para a nova tabela

3. **Conexão Power BI + MySQL**:
   - Utilizado o conector nativo do Power BI
   - Aplicado filtro e transformação de dados via Power Query

4. **Criação do Dashboard**:
   - Cálculo de métricas como: valor total embarcado, peso total, produtos mais caros/pedidos, embarques por país e por dia
   - Visualizações: gráficos de linha, barras, pizza, KPIs e tabelas

---

## 📊 Dashboard Final

O dashboard apresenta os seguintes insights:

- **Valor total do embarque** e **peso total** embarcado
- **Produtos mais caros** e **mais pedidos**
- **Quantidade de embarques por dia**
- **Total de embarques por país**
- **Valor total por país**

![image](https://github.com/user-attachments/assets/684842e6-1a76-44b3-8742-c8f8031ed761)

