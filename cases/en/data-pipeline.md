# Case: Data Pipeline Modernization & Data-Driven Culture

<div align="right">
  <kbd>
    <span>🇺🇸</span> 
    <strong>Reading in English</strong>
  </kbd>
  <a href="../pt/data-pipeline.md">
    <kbd>
      <span>🇧🇷</span> 
      <span style="color: #666;">Ler em Português</span>
    </kbd>
  </a>
  <a href="../es/data-pipeline.md">
    <kbd>
      <span>🇪🇸</span> 
      <span style="color: #666;">Leer en Español</span>
    </kbd>
  </a>
</div>

---

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-the-challenge">The Challenge</a> •
  <a href="#-strategy-and-solution">Strategy</a> •
  <a href="#-results-and-impact">Results</a> •
  <a href="#-lessons-learned">Lessons Learned</a>
</p>

---

### 🎯 Overview
- **Context:** Yampa, a Brazilian SaaS startup providing financial control for SMBs, expanding into a complete management ecosystem.
- **My Role:** Product Growth Manager & Data Strategist.
- **Timeline:** 6 months.
- **Stack/Tools:** SQL, Metabase (Open Source), n8n, Looker Studio, Google Cloud/Data Lake.

---

### 🔍 The Challenge
We identified a critical issue regarding data integrity and, consequently, the reliability of information provided via dashboards. The company rarely used data for strategic decision-making due to numerical discrepancies between departments.
> "The lack of trust in data hindered scaling; growth metrics did not align with the audited financial reality."

---

### 🔧 Strategy and Solution
To resolve the trust and infrastructure bottleneck, the strategy was divided into four pillars:

1. **Audit & Mapping:** Conducted a full mapping of existing data, identifying technical debt in databases, query routines, and processing bottlenecks.
2. **Business Rules Workshops:** Facilitated workshops with all departments (Marketing, Product, Finance, Sales, and CS) to define unified metric concepts and align expectations, prioritizing the refactoring backlog.
3. **Technical Refactoring:** Led the complete refactoring process of queries, views, and tables. Since a full ETL pipeline overhaul was unfeasible at the time, we focused on the sanity of the consumption layer.
4. **Centralization & Infrastructure:** Restructured 100% of the company's dashboards, migrating to a new BI tool (Metabase) to ensure a single "source of truth."

---

### 📈 Results and Impact
The results brought not only precision but also cost savings and agility to the startup:

- **Reliability:** Achieved **97% alignment** of critical data (MRR, ARR, Churn, CAC, LTV) compared to financial team audits.
- **Financial Efficiency:** Centralized 100% of dashboards in Metabase (Open Source), generating **immediate savings** on previous software licensing fees.
- **Operational Agility:** Reduced data update lead time from **3 to 2 days**.
- **Data Culture:** 100% of strategic Growth and Product decisions are now based on the new centralized dashboards.

---

### 💡 Lessons Learned
- **Scalable Prioritization:** The importance of focusing on the visualization layer and business rules when back-end ETL pipelines cannot be immediately changed.
- **Holistic Vision:** Gained a deep understanding of how recurring revenue indicators impact different areas of the company in unique ways.
- **Alternative Stack:** Confirmed the technical and financial viability of using Open Source tools (Metabase) integrated with automation flows (n8n) for growth-stage companies.

---
<p align="center">
  <br>
  <a href="../../README.en.md">
    <img src="https://img.shields.io/badge/%E2%AC%85%20BACK%20TO%20MAIN%20PROFILE%20%E2%AC%85-black?style=for-the-badge&logo=github&logoColor=white" width="400">
  </a>
</p>
