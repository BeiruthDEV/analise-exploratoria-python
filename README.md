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

# Atividade-2-P1-Probabilidade-e-Estat-stica

## 📊 Análise Estatística com Python – Quartis, IQR e Outliers

Este projeto aplica estatística descritiva em Python para calcular quartis, intervalo interquartil (IQR), limites superior e inferior e identificar outliers em um conjunto de dados. Além disso, são utilizadas visualizações gráficas para interpretar melhor os resultados.

## 🚀 Tecnologias utilizadas

Python 3

NumPy
 – manipulação numérica

Pandas
 – apoio na análise

Matplotlib
 – visualizações

Seaborn
 – gráficos estatísticos

## 🔢 Conjunto de Dados

As notas analisadas foram:

```bash
[4, 4, 5, 5, 5, 5, 6, 6, 6, 6, 6, 6, 7, 7, 7, 7, 8, 8]
```

## 📌 Etapas da Análise

Amplitude → diferença entre o maior e o menor valor.

Quartis (Q1, Q2, Q3) → obtidos com numpy.percentile.

IQR (Intervalo Interquartil) → IQR = Q3 - Q1.

Limites para Outliers:

Limite inferior = Q1 - 1.5 × IQR

Limite superior = Q3 + 1.5 × IQR

Identificação de Outliers → valores fora do intervalo.

Visualizações:

Boxplot → exibe quartis e outliers.

Histograma → mostra a distribuição dos dados.

## 📈 Resultados

Q1 (1º quartil): 5.0

Q2 (mediana): 6.0

Q3 (3º quartil): 7.0

IQR: 2.0

Limite inferior: 2.0

Limite superior: 10.0

Outliers: Nenhum

## 📊 Visualizações
Boxplot

Mostra a mediana, quartis e possíveis outliers.

Histograma

Mostra a distribuição das frequências das notas.

(as imagens são geradas automaticamente no notebook)

## 📝 Conclusão

Este projeto demonstrou como aplicar conceitos básicos de estatística descritiva com Python, identificando medidas de posição e dispersão.
As visualizações ajudaram a confirmar a ausência de outliers e a compreender a distribuição dos dados.

## 📂 Estrutura do Projeto
```bash
📦 analise-estatistica
 ┣ 📜 Atividade_2_P1.ipynb   # Notebook principal
 ┣ 📜 README.md              # Documentação do projeto
```



## 👤 Autor

Nome: Matheus Beiruth

Contato: matheusbeiruth10@gmail.com
