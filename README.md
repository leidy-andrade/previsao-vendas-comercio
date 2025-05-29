
# 📊 Previsão de Vendas em Comércio Local

Este projeto tem como objetivo prever o valor total de vendas diárias de um pequeno comércio, com base em dados históricos simulados de 6 meses. Utilizei modelos de séries temporais com a biblioteca Prophet, do Facebook, para prever as vendas dos próximos 30 dias.

## 🧠 Objetivos do Projeto

- Analisar padrões históricos de vendas
- Visualizar tendências e sazonalidades
- Prever as vendas para os próximos 30 dias
- Criar visualizações úteis para tomada de decisão

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- Pandas
- Seaborn & Matplotlib
- Prophet (Facebook)
- Jupyter Notebook

---

## 📁 Estrutura do Projeto

```
previsao-vendas-comercio/
├── data/
│   ├── vendas_comercio_local.xlsx     # Base de dados simulada
│   └── previsao_30_dias.xlsx                    # Previsão gerada
├── images/
│   ├── grafico_vendas_diarias.png              # Gráfico de vendas por dia
│   └── grafico_boxplot_dia_semana.png          # Boxplot por dia da semana
├── notebook/
│   └── Previsão de vendas - comércio.ipynb         # Notebook com código principal
├── README.md
```

---

## 📈 Principais Resultados

### ✅ Vendas Diárias
Gráfico mostrando o comportamento de vendas ao longo do tempo.

### ✅ Comportamento por Dia da Semana
Boxplot com os dias mais fortes de vendas.

### ✅ Previsão para os Próximos 30 Dias
Gráfico com a linha de previsão e faixa de confiança.

---

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/leidy-andrade/previsao-vendas-comercio.git
   ```

2. Instale as dependências:
   ```bash
   pip install pandas matplotlib seaborn prophet
   ```

3. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook notebook/previsao_vendas_comercio.ipynb
   ```

---

## 👩‍💻 Autor

Desenvolvido por Leidiane (https://github.com/leidy-andrade)  
Estudante de Ciência de Dados e Análise de Negócios.
