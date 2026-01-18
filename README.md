## 📊 Gestão de Demandas & SLA — Power BI + SharePoint

Projeto de Business Intelligence desenvolvido com foco em governança de dados, análise de SLAs e visualização estratégica, utilizando SharePoint como fonte de dados e Power BI (PBIP) como camada analítica.

---

## 🎯 Objetivo do Projeto

Demonstrar, na prática, a construção de uma solução de BI completa, contemplando:

- Integração com SharePoint Lists
- Modelagem analítica limpa e escalável
- Criação de KPIs de SLA e gestão de demandas
- Uso do formato PBIP para versionamento em Git
- Organização voltada a portfólio profissional

---

## 🧱 Arquitetura da Solução

- **SharePoint Online**
  - Lista `fDemandas`
- **Power BI – Power Query**
  - Extração, limpeza e tratamento
- **Modelo Dimensional**
  - Tabela fato + calendário
- **Medidas DAX**
  - Organizadas por pastas
- **Dashboard Executivo**

---

## 🗂️ Estrutura do Repositório

gestao-demandas-sla-powerbi/

├── GestaoDemandas.pbip/

├── Report/

└── SemanticModel/

├── docs/

├── imagens/

└── storytelling.md

├── README.md

└── .gitignore

---

## 📐 Modelagem de Dados

- Tabela Fato: fDemandas

- Dimensão Tempo: Calendario

- Modelo em estrela

- Relacionamentos unidirecionais

- Granularidade: demanda individual

📌 Colunas técnicas do SharePoint foram descartadas, mantendo apenas atributos analíticos.

---

## 📏 Indicadores (KPIs)

- Total de Demandas

- Demandas no Prazo

- Demandas Fora do Prazo

- SLA (%)

- Tempo Médio de Atendimento

- Demandas por Status

- Demandas por Responsável

As medidas DAX estão organizadas em pastas, seguindo as etapas do projeto.

---

## 📊 Dashboard

O dashboard foi estruturado com foco em:

- Visão executiva

- Clareza na leitura de SLAs

- Comparação entre demandas concluídas e pendentes

- Destaque visual para desvios de prazo

📷 Imagens do dashboard podem ser encontradas na pasta /imagens.

---

## 🧠 Storytelling Analítico

O relatório responde às seguintes perguntas de negócio:

- Estamos cumprindo os SLAs acordados?

- Onde estão os maiores gargalos?

- Quais demandas impactam negativamente o SLA?

- Como evolui o desempenho ao longo do tempo?

---

## 🛠️ Tecnologias Utilizadas

- Power BI Desktop (PBIP)

- SharePoint Online

- DAX

- Power Query (M)

- Git & GitHub

---

## 🚀 Diferenciais do Projeto

- Uso de PBIP (pronto para versionamento)

- Organização profissional de medidas

- Separação clara entre modelo, visual e documentação

- Projeto pensado como case real de BI corporativo

---

## 👤 Autor

Maurício Barros

Analista de Dados | BI | Power BI | SQL | IA Generativa

🔗 GitHub: https://github.com/opusvix

🔗 LinkedIn: [(https://www.linkedin.com/in/mauriciodasilvabarros/)]
