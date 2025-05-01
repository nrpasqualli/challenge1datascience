# 📊 Análise de Vendas - Alura Store

Este projeto tem como objetivo analisar os dados de vendas de quatro lojas da **Alura Store**, utilizando Python e bibliotecas como **Pandas** e **Matplotlib**. A análise inclui métricas de faturamento, categorias de produtos mais vendidos, avaliações de clientes e custos de frete.

---

## 🗂️ Dados Utilizados

Os dados foram obtidos diretamente do GitHub da Alura:

- [`loja_1.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv)
- [`loja_2.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv)
- [`loja_3.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv)
- [`loja_4.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv)

Cada arquivo contém informações como:

- Produto
- Categoria do produto
- Preço
- Frete
- Data da compra
- Vendedor
- Local da compra
- Avaliação
- Tipo de pagamento
- Coordenadas (latitude e longitude)

---

## ✅ Etapas da Análise

### 1. 📈 Faturamento por Loja

Foi calculado o faturamento total de cada unidade da Alura Store. Os valores foram apresentados numericamente e visualizados em um gráfico de barras.

### 2. 🛍️ Vendas por Categoria

Contabilizamos o número de vendas por categoria de produto em cada loja. Também foram gerados gráficos de pizza para visualização percentual.

### 3. 🌟 Média de Avaliações

Analisamos a média de avaliação dos clientes para cada loja, com base na coluna `Avaliação da compra`.

### 4. 📦 Produtos Mais e Menos Vendidos

Realizamos uma contagem agregada por categoria e loja, comparando o desempenho de cada tipo de produto entre as lojas. O resultado foi exibido em um gráfico de barras horizontal.

### 5. 🚚 Custo Médio de Frete

Calculamos o valor médio do frete pago pelos clientes em cada loja.

---

## 📊 Exemplos de Visualizações

- Faturamento por loja (gráfico de barras)
- Distribuição das vendas por categoria (gráficos de pizza)
- Comparação de categorias entre lojas (gráfico de barras horizontal)

---

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Pandas
- Matplotlib
- Jupyter Notebook (recomendado para execução)

---

## 📌 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Instale as dependências:
   ```bash
   pip install pandas matplotlib
   ```
3. Execute o notebook ou script `.py`.

---

