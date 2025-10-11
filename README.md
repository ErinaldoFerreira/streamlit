# 📊 Dashboard de Vendas — Streamlit

Este projeto é um **dashboard interativo de vendas** desenvolvido em **Python** com **Streamlit** e **Pandas**.
Ele permite visualizar métricas de receita, quantidade vendida, evolução ao longo do tempo e produtos mais vendidos — tudo a partir de um arquivo CSV.

---

## 🚀 Demonstração

O app exibe:

* Filtros de **categoria** e **período de tempo**
* Indicadores (KPIs) de **receita total** e **quantidade vendida**
* Gráficos interativos:

  * Receita ao longo do tempo
  * Top produtos por receita
* Tabela de dados filtrados
* Opção para **baixar o CSV filtrado**

---

## 🧩 Tecnologias utilizadas

* [Python 3.10+](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [Streamlit](https://streamlit.io/)

---

## 📂 Estrutura do projeto

```
.
├── sales_data.csv        # Dados de exemplo
├── demo.py               # Código principal do dashboard
└── README.md             # Documentação do projeto
```

---

## ⚙️ Instalação e execução

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/ErinaldoFerreira/streamlit.git
cd streamlit
```

### 2️⃣ Crie um ambiente virtual (opcional, mas recomendado)

```bash
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate   # macOS / Linux
```

### 3️⃣ Instale as dependências

```bash
pip install streamlit pandas
```

### 4️⃣ Execute o aplicativo

```bash
streamlit run demo.py
```

Ou, se o comando `streamlit` não for reconhecido:

```bash
python -m streamlit run demo.py
```

---

## 📈 Exemplo de uso

1. Carregue o arquivo `sales_data.csv` (já incluído ou substitua pelo seu).
2. Use o menu lateral para:

   * Selecionar categorias de produtos
   * Definir o intervalo de datas
3. Veja os KPIs, gráficos e tabela atualizados automaticamente.
4. Faça o download do CSV filtrado clicando em **"Baixar CSV filtrado"**.

---

## 📸 Captura de tela (opcional)

*(adicione aqui uma imagem do dashboard)*

```markdown
![Dashboard de Vendas](screenshot.png)
```

---

## 💡 Observação

* O arquivo `sales_data.csv` deve conter, no mínimo, as seguintes colunas:

  * `Date_Sold`
  * `Category`
  * `Product_Name`
  * `Quantity_Sold`
  * `Total_Sales`

---

## 🧑‍💻 Autor

**Erinaldo Ferreira**
📧 [erinaldopaladino@gmail.com]
🌐 [https://github.com/ErinaldoFerreira](https://github.com/ErinaldoFerreira)


