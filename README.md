# 📊 Cancelamento de Clientes - Análise de Churn com Python

Este projeto tem como objetivo analisar uma base de dados com mais de 800 mil registros de clientes, buscando identificar os principais fatores que influenciam o cancelamento (churn) de serviços e propor ações estratégicas para reduzir essa taxa.

---

## 🎯 Objetivos

- Entender o perfil dos clientes que mais cancelam.
- Identificar padrões e variáveis críticas associadas ao churn.
- Gerar insights com propostas de ações para retenção.
- Simular o impacto de ações estratégicas na taxa de cancelamento.

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- Pandas
- Plotly (para gráficos interativos)
- Jupyter Notebook

---

## ▶️ Como Executar

Para rodar este projeto em sua máquina, siga os passos abaixo:

1.  **Clone o repositório:**
    Abra seu terminal ou prompt de comando e execute:
    ```bash
    git clone [https://github.com/caiovinigomes/Analise-Cancelamento-Clientes](https://github.com/caiovinigomes/Analise-Cancelamento-Clientes)
    ```

2.  **Navegue até o diretório do projeto:**
    ```bash
    cd Analise-Cancelamento-Clientes
    ```

3.  **Instale as dependências:**
    Certifique-se de ter `pip` instalado. Em seguida, execute:
    ```bash
    pip install pandas plotly jupyter kaleido
    ```
    (Isso instalará todas as bibliotecas necessárias para o projeto).

4.  **Abra o Jupyter Notebook:**
    ```bash
    jupyter notebook main.ipynb
    ```
    Seu navegador padrão deve abrir com o Jupyter Notebook.

5.  **Execute as células:**
    Dentro do `main.ipynb`, execute todas as células em sequência para replicar a análise e gerar os gráficos.

---

## 🔎 Etapas da Análise

1. **Importação e leitura da base de dados**
2. **Tratamento de valores nulos e limpeza inicial**
3. **Análise exploratória das variáveis**
4. **Visualização de padrões com gráficos interativos**
5. **Geração de insights estratégicos**
6. **Simulação de ações e comparação do impacto**
7. **Conclusões e próximos passos**

---

## 📈 Resultados

Foi identificada uma taxa inicial de cancelamento de aproximadamente **56%** (valor real gerado no código). Após simulação de ações estratégicas — como incentivo a planos anuais, melhoria no atendimento e ações de recuperação de inadimplência — a taxa caiu para **18%**, evidenciando um potencial relevante de retenção.

---

## 💡 Principais Insights

- Clientes com **plano mensal** têm taxa de cancelamento muito maior.
- Mais de **4 ligações ao call center** indicam alto risco de churn.
- **Atrasos acima de 20 dias** no pagamento são fortemente associados ao cancelamento.

---

## 🔁 Próximos Passos

- Criar um modelo preditivo de churn (Machine Learning).
- Integrar com dashboards em tempo real (Power BI ou Dash).
- Automatizar alertas para equipes de atendimento e cobrança.

---

## 📂 Arquivos

- `main.ipynb`: Notebook com todo o processo de análise.
- `cancelamentos.csv`: Base de dados.
- `grafico_taxa_cancelamento.png`: Gráfico com o impacto das ações.

---

## ✨ Autor

**Caio Vinicius**  
[LinkedIn](https://www.linkedin.com/in/caiovinicius-gomes/)

---