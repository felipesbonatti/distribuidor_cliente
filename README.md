# 📊 Distribuição Inteligente de Clientes para Gerentes Bancários

[![GitHub last commit](https://img.shields.io/github/last-commit/felipesbonatti/distribuidor_cliente?style=flat-square)](https://github.com/felipesbonatti/distribuidor_cliente)
[![GitHub repo size](https://img.shields.io/github/repo-size/felipesbonatti/distribuidor_cliente?style=flat-square)](https://github.com/felipesbonatti/distribuidor_cliente)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Logo GitHub" width="100">
</p>

---

## 📌 Sobre o Projeto

Este repositório apresenta um **caso real de otimização na distribuição de clientes para gerentes e agências bancárias**, desenvolvido para garantir uma alocação eficiente, estratégica e alinhada com as regras de negócio. O projeto foi criado com o objetivo de automatizar a distribuição de clientes, priorizando critérios como **proximidade geográfica** e **rentabilidade**, enquanto mantém a coerência com o histórico de atendimento.

O sistema foi projetado para **melhorar a gestão de relacionamento com clientes** e **maximizar a performance dos gerentes**, contribuindo para a eficiência operacional e estratégica do negócio.

<p style="color: red; font-size: 14px;">
  <strong>Observação:</strong> Por questões de conformidade com a <strong>Lei Geral de Proteção de Dados (LGPD)</strong>, os nomes dos campos e informações sensíveis foram omitidos ou anonimizados neste repositório.
</p>

---

## 🎯 Objetivo

O principal objetivo deste projeto foi **criar um modelo de alocação de clientes** que:

- **Prioriza a proximidade geográfica** entre clientes e gerentes (utilizando chave localpara).
- **Foca na rentabilidade**, priorizando clientes com maior **MOB (Margem Operacional Bruta)**.
- **Mantém a coerência** com clientes já atendidos por determinados gerentes, garantindo continuidade no relacionamento.

---

## ⚙️ Solução Entregue

A solução desenvolvida inclui:

### 1. **Distribuição Inteligente de Clientes**
   - Alocação automática de clientes com base em **proximidade geográfica** e **estratégia de rentabilidade**.
   - Priorização de clientes com maior **MOB**, garantindo foco nos mais rentáveis.

### 2. **Integração com Bases Existentes**
   - Conexão com a base de dados de gerentes e clientes, garantindo **atualização em tempo real**.
   - Respeito às **regras de negócio** e **critérios financeiros** estabelecidos.

### 3. **Tabela Analítica Final**
   - Detalhamento da alocação de cada cliente por gerente.
   - Inclusão de **indicadores de rentabilidade** e **performance** para análise estratégica.

---

## 📊 Resultados

O modelo desenvolvido trouxe os seguintes benefícios:

- **Eficiência Operacional:** Redução do tempo necessário para alocação de clientes.
- **Otimização de Rentabilidade:** Foco em clientes com maior **MOB**, maximizando o retorno financeiro.
- **Melhoria no Relacionamento:** Manutenção da coerência no atendimento, fortalecendo o vínculo entre clientes e gerentes.

---

## 🛠️ Tecnologias Utilizadas

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</div>

- **Linguagem de Programação:** [Python](https://www.python.org/)
- **Bibliotecas:** Pandas, NumPy, Geopy (para cálculos geográficos)
- **Banco de Dados:** [SQLite](https://www.sqlite.org/index.html) ou outro SGBD (dependendo da implementação)
- **Ferramentas de Análise:** Jupyter Notebook, Excel (para visualização de dados)
- **Controle de Versão:** [Git](https://git-scm.com/)


