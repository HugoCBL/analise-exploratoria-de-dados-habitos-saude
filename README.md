# 📊 **Análise Exploratória de Dados: Hábitos de Saúde e Estilo de Vida**

## 📌 **Introdução**
Este projeto consiste em uma **Análise Exploratória de Dados (EDA)** realizada com a **linguagem R** no dataset *"Dados de Saúde e Hábitos de Vida"*.  
O **objetivo principal** é investigar como fatores do **estilo de vida** — como **tabagismo**, **nível de atividade física** e **horas de sono** — se relacionam com indicadores de saúde, como **IMC** e **pressão arterial**.

---

## 🔍 **Metodologia e Análise**
A análise seguiu um processo estruturado de **limpeza** e **exploração de dados**, documentado no notebook R (`.ipynb`):

- 🩺 **Tratamento de Valores Ausentes:** Valores **NAs** tratados por imputação — **mediana** para variáveis numéricas e **moda** para variáveis categóricas.  
- ⚙ **Padronização de Dados:** Padronização de variáveis como `Sexo` e `Historico_Doenca`, correção de inconsistências em `Horas_Sono` e `Consumo_Alcool_semanal_ml`.  
- 🧮 **Engenharia de Variáveis:** Criação da variável **IMC** a partir de **peso** e **altura**.

---

## 💡 **Principais Insights**
A análise revelou **insights relevantes** sobre hábitos e saúde:

- 🚬 **Tabagismo:** Fumantes apresentam, em média, **pressão arterial mais alta**, sugerindo relação com risco cardiovascular.  
- 🏃 **Atividade Física:** Relação **inversa** entre nível de atividade e IMC — sedentários tendem a ter **IMC mais elevado**.  
- 🎂 **Idade:** A proporção de pessoas com **histórico de doenças** aumenta com a idade.  
- 😴 **Sono e Pressão Arterial:** Ausência de correlação linear forte entre horas de sono e pressão sistólica, indicando influência de outros fatores.

---

## 📂 **Estrutura do Repositório**
- `analise_exploratoria_de_dados_habitos_saude.ipynb` → Notebook em R com o **código completo**.  
- `dados_saude_habitos.csv` → Dataset **original**.  
- `dados_saude_habitos_tratado.csv` → Dataset **tratado**.  
- `relatorio_interpretativo.pdf` → Relatório completo com **metodologia, análises e conclusões**.

---

## 🖥 **Como Rodar o Projeto**
Para reproduzir a análise, utilize um ambiente que suporte **notebooks R**, como **Google Colab** ou **RStudio**:

1. **Clone** este repositório.  
2. Abra o notebook `analise_exploratoria_de_dados_habitos_saude.ipynb`.  
3. Certifique-se de que o arquivo `dados_saude_habitos.csv` esteja no **mesmo diretório** do notebook.  
4. Execute as células em ordem para **replicar a análise**.
