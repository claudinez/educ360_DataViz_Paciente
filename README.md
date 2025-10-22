# educ360_DataViz_Paciente

🩺 README — Análise de Pacientes de uma Clínica
# 🩺 Análise de Pacientes de uma Clínica

Este projeto realiza uma **análise exploratória de dados (EDA)** sobre pacientes de uma clínica de saúde.  
O objetivo é compreender o comportamento dos dados de glicose, pressão arterial e distribuição etária e de gênero.

## 🎯 Objetivos do Projeto

1. **Ler o arquivo CSV** com informações dos pacientes.  
2. **Tratar valores nulos** de forma adequada.  
3. **Gerar visualizações com Matplotlib**, incluindo:
   - 📊 Gráfico de Barras — *Média de Glicose por Faixa Etária*  
   - 🥧 Gráfico de Pizza — *Proporção de Pacientes por Gênero*  
   - 📈 Gráfico de Linhas — *Evolução Média da Pressão Arterial por Mês*

## 🧠 Insights Esperados

- **Faixas etárias mais altas** tendem a apresentar **maior glicose média**.  
- A **distribuição de gênero** pode ser observada de forma clara no gráfico de pizza.  
- O gráfico de linha mostra possíveis **tendências mensais na pressão arterial média**.

## 🧩 Tecnologias Utilizadas

| Categoria | Biblioteca |
|-----------|------------|
| Manipulação de dados  | `pandas`, `numpy` |
| Visualização de dados | `matplotlib` |
| Ambiente de execução  | Google Colab / Jupyter Notebook |

## ⚙️ Estrutura do Projeto

📦 analise_pacientes_clinica
┣ 📄 pacientes_clinica.csv
┣ 📘 analise_pacientes.ipynb
┗ 📄 README.md
