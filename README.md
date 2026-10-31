# Projeto de Análise de Dados - Empresa de Telecomunicações (ConnectaTel)

## 🎯 Objetivo do Projeto
Este projeto tem como objetivo realizar a limpeza, tratamento, análise exploratória (EDA) e segmentação de dados de clientes e interações de uma empresa de telecomunicações, identificando padrões de comportamento, consumo e tendências de *churn*.

## 📂 Datasets Utilizados
* **`users.json` / Base de Utilizadores:** Contém informações demográficas, datas de registo, cidade e dados de cancelamento (*churn*).
* **`usage.csv` / Base de Utilização:** Regista as interações diárias dos clientes (chamadas e mensagens, com respetivas durações e comprimentos).

## 🛠️ Etapas da Análise
1. **Inspeção Inicial:** Importação e verificação de dimensões, tipos de dados e inconsistências.
2. **Tratamento de Dados Anómalos:** Identificação e tratamento de valores sentinela (ex: idade `-999`), datas futuras inválidas (2026) e valores ausentes.
3. **Análise de Dados Ausentes (MAR):** Estudo estatístico e justificação do padrão *Missing At Random* nas métricas de interação.
4. **Análise Exploratória e Visualização (EDA):** Gráficos de distribuição demográfica, faixas etárias e níveis de uso (segmentação por chamadas e mensagens).
5. **Conclusões e Recomendações de Negócio:** Insights executivos sobre *heavy users* e estratégias de retenção da base.

## 🚀 Como Executar o Notebook
1. Certifique-se de que tem o Python instalado juntamente com as bibliotecas necessárias (`pandas`, `numpy`, `matplotlib`, `seaborn`).
2. Clone este repositório para o seu computador:
   ```bash
   git clone [https://github.com/AlineHard/Projeto-An-lise-de-uma-empresa-de-telecomunica-es.git](https://github.com/AlineHard/Projeto-An-lise-de-uma-empresa-de-telecomunica-es.git)
