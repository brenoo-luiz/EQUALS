# 📊 Dashboard Interativo de Análise de Vendas
Este projeto foi desenvolvido como parte do **CASE PS 25.1 Estágio BI** da empresa fictícia **Lumen Store**, com o objetivo de aplicar técnicas de análise de dados e criar um dashboard interativo para responder a perguntas estratégicas de negócio.

---

## 🎯 Objetivo

Desenvolver uma solução completa de Business Intelligence utilizando Python para analisar os dados de vendas de uma empresa. A entrega inclui:
- Tratamento e limpeza de dados;
- Criação de métricas e KPIs;
- Visualizações interativas através de um dashboard.

---

## 🛠 Tecnologias Utilizadas

- **Python 3.10+**
- **Pandas** – Manipulação e análise de dados
- **NumPy** – Operações numéricas
- **Plotly** – Criação de gráficos interativos
- **JupyterDash** – Construção do dashboard interativo em ambiente Jupyter
- **Jupyter Notebook** – Execução dos notebooks
- **VS Code** – Ambiente de desenvolvimento
- **Virtualenv** – Gerenciamento de ambiente virtual

---

## 📁 Estrutura do Projeto

```
📦 projeto-lumenstore/
├── dashboard_lumenstore.ipynb      # Dashboard interativo com visualizações
├── limpeza.ipynb                   # Notebook de limpeza e tratamento de dados
├── processamento.ipynb             # Notebook com criação de métricas e KPIs
├── dados_completos.csv             # Arquivo com os dados já tratados
├── requirements.txt                # Lista de dependências do projeto
└── README.md                       # Este arquivo
```

---

## 🔎 Ordem de Execução e Análise

Siga os passos abaixo **na ordem indicada** para garantir o funcionamento correto do projeto:

### 1. Pré-requisitos

- Ter o **Python 3.10+** instalado
- Ter o **VS Code com a extensão Jupyter** habilitada
- Ter o **Git** instalado (opcional, caso deseje clonar o repositório)

### 2. Clonar o repositório

```bash
git clone <URL_DO_REPOSITORIO>
cd projeto-lumenstore
```

### 3. Criar e ativar o ambiente virtual

```bash
python -m venv venv
source venv/bin/activate    # Linux/Mac
venv\Scripts\activate       # Windows
```

### 4. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 5. Executar os Notebooks

#### 🧹 Etapa 1 – Limpeza dos Dados

- Abra o notebook `limpeza.ipynb`
- Execute todas as células
- Esta etapa realiza:
  - Renomeação de colunas
  - Conversão de datas
  - Tratamento de duplicatas e valores ausentes
  - Criação de colunas auxiliares como:
    - `Mes_Ano`, `Faturamento Total`, `Desconto Aplicado`, `Ticket Médio`

#### ⚙️ Etapa 2 – Processamento e Cálculo de Métricas

- Abra o notebook `processamento.ipynb`
- Execute todas as células
- Métricas geradas:
  - Faturamento por mês, canal, filial
  - Top 5 produtos por família
  - Ticket médio por canal e por filial
  - Curva ABC
  - Participação no faturamento
  - Comparação entre períodos

#### 📊 Etapa 3 – Visualização Interativa

- Abra o notebook `dashboard_lumenstore.ipynb`
- Execute todas as células
- O dashboard será iniciado automaticamente no navegador
- Permite seleção de filtros e visualizações dinâmicas

---

## 📊 Gráficos e Métricas Disponíveis no Dashboard

1. **Curva ABC por Família de Produtos**  
2. **Faturamento Mensal**  
3. **Participação das Filiais no Faturamento**  
4. **Ticket Médio por Canal de Venda (SAH)**  
5. **Top 5 Produtos Mais Vendidos por Família**  
6. **Evolução Temporal das Vendas**  
7. **Ticket Médio por Filial**  
8. **Distribuição de Vendas por Categoria de Produto**  
9. **Comparação de Vendas entre Períodos**  

Todos os gráficos são interativos e reagem dinamicamente conforme os filtros aplicados.

---

## 🧾 Requisitos

Um arquivo `requirements.txt` está incluso com todas as dependências. Para gerar novamente:

```bash
pip freeze > requirements.txt
```

---

## 🔗 Contato

Caso tenha dúvidas, sugestões ou queira colaborar com melhorias, sinta-se à vontade para entrar em contato.

📧 **breno.luiz.contato@email.com**  
📍 **Engenharia de Controle e Automação | Ciência de Dados | BI | Python**

---