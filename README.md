# 📊 Dashboard de Salários na Área de Dados

Este projeto é um **dashboard interativo** desenvolvido com [Streamlit](https://streamlit.io/), [Pandas](https://pandas.pydata.org/) e [Plotly](https://plotly.com/), com o objetivo de explorar e analisar salários na área de dados ao longo dos anos.

A aplicação permite filtrar informações por **ano**, **senioridade**, **tipo de contrato** e **tamanho da empresa**, exibindo KPIs, gráficos interativos e tabelas dinâmicas.

---

## 🚀 Funcionalidades

- **Filtros interativos** para refinar os dados:
  - Ano
  - Senioridade
  - Tipo de contrato
  - Tamanho da empresa
- **KPIs principais**:
  - Salário médio anual
  - Salário máximo anual
  - Total de registros
  - Cargo mais frequente
- **Visualizações interativas**:
  - **Top 10 cargos** por salário médio
  - **Distribuição de salários** por faixa
  - **Proporção de tipos de trabalho** (remoto, híbrido, presencial)
  - **Mapa de calor** com salário médio de Cientistas de Dados por país
- **Tabela detalhada** com os dados filtrados

---



---

## 📂 Estrutura do Projeto

```plaintext
📦 dashboard-salarios
 ┣ 📜 app.py                 # Código principal da aplicação
 ┣ 📜 requirements.txt       # Dependências do projeto
 ┗ 📜 README.md               # Documentação
```
🛠️ Tecnologias Utilizadas
Python 3.11+

Pandas 2.2.3

Streamlit 1.44.1

Plotly 5.24.1

📦 Instalação e Execução
1️⃣ Clone o repositório
```
git clone https://github.com/seu-usuario/dashboard-salarios.git
cd dashboard-salarios
```
2️⃣ Crie um ambiente virtual (opcional, mas recomendado)
```
python -m venv venv
source venv/bin/activate    # Linux/Mac
venv\Scripts\activate       # Windows
```
3️⃣ Instale as dependências
```
pip install -r requirements.txt
```
4️⃣ Execute o projeto
```
streamlit run app.py
```
📊 Fonte dos Dados
O conjunto de dados foi carregado diretamente de um arquivo CSV hospedado no GitHub:
```
https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv
```

