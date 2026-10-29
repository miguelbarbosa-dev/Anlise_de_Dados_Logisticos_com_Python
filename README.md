# 📊 Análise de Dados com Pandas

Projeto prático de manipulação e limpeza de dados utilizando Python. O foco atual é a preparação de um dataset de produtos de supermercado para futuras análises.

> **Status do projeto:** Em desenvolvimento. Nesta etapa inicial, o foco é a exploração, tratamento de valores nulos e padronização de tipos de dados. Em breve, serão adicionados gráficos e extração de insights!
---

# ⚠️ Para usar e ver de maneira correta, você devera executar 1 e 2 Célula

---
## 🧰 Tecnologias utilizadas
- [Python 3.x](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/) — Manipulação de dados
- [NumPy](https://numpy.org/) — Operações numéricas
- [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/) — Visualização de dados (próximos passos)

---

## 📁 O que já foi feito (Notebook)
1. **Exploração Inicial:** Leitura do CSV (10.000 linhas) e verificação da estrutura.
2. **Tratamento de Nulos:** Identificação e remoção de linhas com dados faltantes (`dropna`).
3. **Limpeza e Padronização:** 
   - Conversão de datas (`validade`) para o formato `datetime`.
   - Limpeza da coluna `preco` (remoção de "R$", "preçopendente" e conversão para `Float64`).
   - Limpeza da coluna `estoque_unidades` (remoção do texto "un" e conversão para `Int64`).

## 🚀 Próximos Passos
- Análise Exploratória de Dados (EDA).
- Criação de gráficos para visualizar categorias, preços e estoques.
- Extração de insights de negócio.

---

## 💻 Como usar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git