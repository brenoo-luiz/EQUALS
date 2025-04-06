# 📊 Dashboard Interativo de Análise de Vendas

Este projeto foi desenvolvido como parte do **CASE PS 25.1 Estágio BI** da empresa **Lumen Store**, com o objetivo de aplicar técnicas de análise de dados e visualização interativa. Através de um dashboard construído com **Python** e **JupyterDash**, é possível explorar indicadores de vendas por canal, filial, produto e período, facilitando a tomada de decisão com base em dados reais.

---

## 🎯 Objetivo

Analisar de forma automatizada os dados de vendas de uma empresa fictícia, respondendo às perguntas do case proposto, por meio de um dashboard interativo que oferece visões estratégicas sobre o desempenho comercial.

---

## ⚙️ Tecnologias Utilizadas

- **Python 3.10+**
- **Pandas** – Manipulação de dados
- **Plotly** – Visualização de gráficos interativos
- **JupyterDash** – Criação de dashboards interativos em notebooks
- **NumPy** – Operações numéricas
- **Jupyter Notebook** – Ambiente de desenvolvimento e visualização

---

## 🧹 Etapas de Tratamento e Limpeza dos Dados

- Renomeação e padronização dos nomes das colunas.
- Conversão de datas para datetime e extração de informações temporais (ano, mês, dia).
- Remoção de valores duplicados.
- Tratamento de valores ausentes.
- Criação de colunas auxiliares, como:
  - Mês/Ano formatado.
  - Faturamento total (valor monetário total + desconto).
  - Cálculo de métricas como ticket médio, margem de lucro, entre outras.

---

## 📊 Gráficos e Análises Implementadas

O dashboard interativo permite navegar entre as seguintes visualizações:

1. **Curva ABC por Família de Produtos**  
   Classifica as famílias que mais geram faturamento com base no conceito de Pareto.

2. **Faturamento Mensal**  
   Exibe a evolução do faturamento por mês e ano, permitindo visualizar sazonalidades.

3. **Participação das Filiais no Faturamento**  
   Compara o faturamento acumulado entre diferentes filiais.

4. **Ticket Médio por Canal de Venda (SAH)**  
   Calcula o ticket médio (faturamento médio por pedido) para cada canal de venda.

5. **Top 5 Produtos Mais Vendidos por Família**  
   Exibe os cinco produtos com maior volume de vendas dentro de cada família de produtos.

6. **Evolução Temporal das Vendas**  
   Permite analisar tendências gerais e picos de vendas ao longo do tempo.

7. **Ticket Médio por Filial**  
   Mostra a média de faturamento por pedido em cada filial.

8. **Distribuição de Vendas por Categoria de Produto**  
   Visualiza a distribuição percentual do faturamento entre categorias de produto.

9. **Comparação de Vendas entre Períodos**  
   Permite comparar o desempenho de vendas entre dois intervalos de tempo selecionados.

---

## 🛠 Como visualizar o projeto no VS Code

Se você deseja executar o projeto e visualizar as análises, siga os passos abaixo:

1. **Clone o repositório** (se ainda não tiver feito):
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```
2. **Acesse o diretório do projeto:**
   ```bash
   cd nome_do_projeto
   ```
3. **Crie e ative um ambiente virtual (recomendado):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate  # Windows
   ```
4. **Instale as dependências necessárias:**
   ```bash
   pip install -r requirements.txt
   ```
5. **Abra o VS Code e execute os notebooks Jupyter:**
   - No terminal do VS Code, execute:
     ```bash
     code .
     ```
   - Abra a pasta dos notebooks.
   - Execute as células para visualizar os gráficos e análises.

## 🔗 Contato
Caso tenha dúvidas ou sugestões, fique à vontade para entrar em contato!

🚀 _Projeto em desenvolvimento!_
