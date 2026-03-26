# 🏥 VidaPlena Clínicas S.A. — Dashboard de Análise de Dados

Projeto de Business Intelligence desenvolvido para simular um ambiente real de análise de dados no setor de saúde.

O objetivo é demonstrar como dados podem ser utilizados para gerar insights estratégicos sobre operação, clientes, finanças e experiência do paciente.

---

## 🎯 Objetivo

Construir um dashboard completo e realista que permita:

- Analisar a operação de atendimentos médicos  
- Avaliar a performance financeira  
- Entender o comportamento dos pacientes  
- Identificar ineficiências operacionais  
- Medir a qualidade do atendimento  

---

## 🧱 Modelagem de Dados

O projeto foi desenvolvido utilizando um modelo relacional com as seguintes tabelas:

- `pacientes`
- `medicos`
- `unidades`
- `agendamentos`
- `faturamento`
- `avaliacoes`

### 🔗 Relacionamentos

- Pacientes → Agendamentos  
- Médicos → Agendamentos  
- Unidades → Agendamentos  
- Agendamentos → Faturamento  
- Agendamentos → Avaliações  

---

## 📊 Estrutura do Dashboard

O dashboard foi dividido em 5 páginas principais:

### 🟪 1. Visão Geral
- Receita total  
- Ticket médio  
- Total de atendimentos  
- Taxa de ocupação  
- Nota média dos pacientes  
- Evolução temporal  

---

### 🟦 2. Operação
- Volume de atendimentos  
- Produtividade médica  
- Tempo médio de espera  
- Duração das consultas  
- Performance por unidade e médico  

---

### 🟩 3. Clientes
- Novos vs recorrentes  
- Taxa de retenção  
- Churn  
- Perfil dos pacientes  
- Distribuição por convênio e região  

---

### 🟥 4. Financeiro
- Receita faturada vs recebida  
- Receita perdida  
- Taxa de recebimento  
- Impacto de glosas  
- Análise por convênio e ticket médio  

---

### 🟨 5. Experiência do Paciente
- Nota média  
- Distribuição de avaliações  
- % de avaliações positivas/negativas  
- Impacto do tempo de espera  
- Performance por médico e unidade  

---

## 📈 Principais Métricas

- Receita Total  
- Ticket Médio  
- Taxa de Ocupação  
- Retenção de Pacientes  
- Churn  
- Receita Perdida  
- SLA de Atendimento  
- Nota Média (1 a 5 estrelas)  

---

## 💡 Principais Insights

- A operação apresenta volume estável de atendimentos, com boa taxa de ocupação  
- Existe concentração geográfica de atendimentos, principalmente na região Sudeste  
- A base de pacientes é majoritariamente recorrente, indicando fidelização  
- Foram identificadas perdas financeiras relevantes associadas a glosas  
- O tempo de espera impacta diretamente a experiência do paciente  

---

## ⚠️ Oportunidades de Melhoria

- Redução de glosas e melhoria no processo de faturamento  
- Otimização da capacidade das unidades  
- Redução do tempo de espera  
- Expansão geográfica da operação  
- Padronização da performance entre médicos  

---

## 🛠️ Tecnologias Utilizadas

- Power BI  
- DAX  
- Modelagem de Dados  
- Excel / CSV  

---

## 🚀 Sobre o Projeto

Este projeto foi desenvolvido com foco em simular um cenário corporativo real, indo além da criação de dashboards visuais.

A proposta é demonstrar como a análise de dados pode apoiar decisões estratégicas, identificar oportunidades de melhoria e gerar valor para o negócio.

---

## 👨‍💻 Autor
cleiton Hentges


---
