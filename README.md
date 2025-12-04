<p align="center">
  <img src="assets/logo-vassouras.png" alt="Universidade de Vassouras" width="400"/>
</p>

<h3 align="center">
  Universidade de Vassouras  
</h3>

---

### 📚 Curso: **Engenharia de Software**  
### 🖥️ Disciplina: **Probabilidade e Estatística**  
### 👨‍🎓 Autor: **Matheus Beiruth**

---

# Statistical Analysis & Outlier Detection 📊

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Libraries](https://img.shields.io/badge/Pandas-NumPy-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📋 Project Overview
Este projeto implementa um pipeline de **Estatística Descritiva** em Python focado na caracterização da distribuição de dados e na detecção de anomalias (*outliers*). Utilizando o método do Intervalo Interquartil (IQR), o script calcula medidas de tendência central e dispersão, definindo limites estatísticos para validar a integridade do conjunto de dados.

O objetivo é demonstrar a aplicação prática de conceitos fundamentais de análise de dados para a tomada de decisão baseada em estatística.

## 🛠️ Tech Stack
* **Linguagem:** Python 3
* **Computação Numérica:** NumPy (cálculo de percentis e arrays)
* **Manipulação de Dados:** Pandas
* **Visualização de Dados:** Matplotlib & Seaborn (Boxplots e Histogramas)

## ⚙️ Metodologia
A análise segue um fluxo estruturado para garantir a robustez dos resultados:

1.  **Definição do Dataset:** Análise de um vetor de notas variando de 4 a 8.
2.  **Cálculo de Quartis:** Determinação de Q1 (25%), Q2 (Mediana) e Q3 (75%).
3.  **Cálculo do IQR:** Mensuração da dispersão central ($IQR = Q3 - Q1$).
4.  **Definição de Limites (Fences):**
    * *Lower Fence:* $Q1 - 1.5 \times IQR$
    * *Upper Fence:* $Q3 + 1.5 \times IQR$
5.  **Identificação de Outliers:** Filtragem de pontos de dados fora dos limites estabelecidos.
6.  **Visualização:** Geração de Boxplot para visualização de simetria e dispersão.

## 📊 Key Findings (Resultados)

| Medida | Valor Calculado |
| :--- | :--- |
| **1º Quartil (Q1)** | 5.0 |
| **Mediana (Q2)** | 6.0 |
| **3º Quartil (Q3)** | 7.0 |
| **Amplitude Interquartil (IQR)** | 2.0 |
| **Limite Inferior** | 2.0 |
| **Limite Superior** | 10.0 |

> **Conclusão da Análise:** Com base nos limites calculados (2.0 a 10.0), **nenhum outlier foi detectado** no conjunto de dados atual, indicando uma distribuição de notas consistente e sem anomalias extremas.

## 📈 Visualizações

O projeto gera automaticamente:
* **Boxplot:** Para validação visual da distribuição dos quartis e ausência de *outliers*.
* **Histograma:** Para análise da frequência e formato da distribuição dos dados.

## 🚀 How to Run

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/BeiruthDEV/estatistica-descritiva-outliers.git](https://github.com/BeiruthDEV/estatistica-descritiva-outliers.git)
    ```
2.  Instale as dependências necessárias:
    ```bash
    pip install numpy pandas matplotlib seaborn
    ```
3.  Execute o notebook `Atividade_2_P1.ipynb` em um ambiente Jupyter ou Google Colab.

---
*Desenvolvido por Matheus Beiruth como parte do portfólio de Análise de Dados.*
