# Case: Modernização de Pipeline de Dados e Cultura Data-Driven

<div align="right">
  <kbd>
    <span>🇧🇷</span> 
    <strong>Lendo em Português</strong>
  </kbd>
  <a href="../en/data-pipeline.md">
    <kbd>
      <span>🇺🇸</span> 
      <span style="color: #666;">Read in English</span>
    </kbd>
  </a>
  <a href=../es/data-pipeline.md">
    <kbd>
      <span>🇪🇸</span> 
      <span style="color: #666;">Leer en Español</span>
    </kbd>
  </a>
</div>

---

<p align="center">
  <a href="#-visão-geral">Visão Geral</a> •
  <a href="#-o-desafio">O Desafio</a> •
  <a href="#-estratégia-e-solução">Estratégia</a> •
  <a href="#-resultados-e-impacto">Resultados</a> •
  <a href="#-aprendizados">Aprendizados</a>
</p>

---

### 🎯 Visão Geral
- **Contexto:** Yampa, uma startup brasileira de SaaS de controle financeiro para PMEs em expansão para um ecossistema completo de gestão.
- **Meu Papel:** Product Growth Manager & Data Strategist.
- **Timeline:** 6 meses.
- **Stack/Ferramentas:** SQL, Metabase (Open Source), n8n, Looker Studio, Google Cloud/Data Lake.

---

### 🔍 O Desafio
Identificamos um problema crítico na integridade dos dados e, consequentemente, na confiabilidade das informações fornecidas via dashboards. A empresa utilizava pouco os dados para tomada de decisões estratégicas devido à divergência de números entre as áreas.
> "A falta de confiança nos dados impedia a escala; as métricas de crescimento não batiam com a realidade financeira auditada."

---

### 🔧 Estratégia e Solução
Para resolver o gargalo de confiança e infraestrutura, a estratégia foi dividida em quatro frentes:

1. **Audit & Mapping:** Realizei o mapeamento completo dos dados existentes, identificando débitos técnicos em bancos de dados, rotinas de consulta e gargalos de processamento.
2. **Workshop de Regras de Negócio:** Facilitei workshops com todas as áreas (Marketing, Produto, Financeiro, Vendas e CS) para definir conceitos unificados de métricas e alinhar expectativas, priorizando o backlog de refatoração.
3. **Refatoração Técnica:** Liderança do processo de refatoração completa de consultas, views e tabelas. Como a revisão total do fluxo de ETL era inviável no momento, focamos na sanidade da camada de consumo.
4. **Centralização e Infraestrutura:** Reestruturamos 100% dos dashboards da empresa, migrando para uma nova ferramenta de BI (Metabase), garantindo uma única "fonte da verdade".

---

### 📈 Resultados e Impacto
Os resultados trouxeram não apenas precisão, mas economia e agilidade para a startup:

- **Confiabilidade:** Aumento para **97% na aderência** de dados críticos (MRR, ARR, Churn, CAC, LTV) em comparação com as auditorias do time financeiro.
- **Eficiência Financeira:** Centralização de 100% dos dashboards em Metabase (Open Source), gerando **saving imediato** com licenciamento de ferramentas anteriores.
- **Agilidade Operacional:** Redução do tempo de espera por atualização de dados de **3 para 2 dias**.
- **Cultura de Dados:** 100% das decisões estratégicas de Growth e Produto passaram a ser baseadas nos novos dashboards centralizados.

---

### 💡 Aprendizados
- **Priorização em Escala:** A importância de focar na camada de visualização e regras de negócio quando o pipeline de ETL de back-end não pode ser alterado imediatamente.
- **Visão Holística:** Entendimento profundo de como indicadores de receita recorrente impactam diferentemente cada área da empresa.
- **Stack Alternativa:** A viabilidade técnica e financeira de utilizar ferramentas Open Source (Metabase) integradas a fluxos de automação (n8n) para empresas em estágio de growth.

---
<p align="center">
  <br>
  <a href="../../README.md">
    <img src="https://img.shields.io/badge/%E2%AC%85%20VOLTAR%20AO%20PERFIL%20PRINCIPAL%20%E2%AC%85-black?style=for-the-badge&logo=github&logoColor=white" width="400">
  </a>
</p>
