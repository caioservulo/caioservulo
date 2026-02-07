# Case: Modernización de Pipeline de Datos y Cultura Data-Driven

<div align="right">
    <kbd>
      <span>🇪🇸</span> 
      <strong>Leyendo en Español</strong>
  </kbd>
  <a href="../en/data-pipeline.md">
    <kbd>
      <span>🇺🇸</span> 
      <span style="color: #666;">Read in English</span>
    </kbd>
  </a>
 <a href="../pt/data-pipeline.md">
    <kbd>
      <span>🇧🇷</span> 
      <span style="color: #666;">Ler em Português</span>
    </kbd>
  </a>
</div>

---

<p align="center">
  <a href="#-visión-general">Visión General</a> •
  <a href="#-el-desafío">El Desafío</a> •
  <a href="#-estrategia-y-solución">Estrategia</a> •
  <a href="#-resultados-e-impacto">Resultados</a> •
  <a href="#-aprendizajes">Aprendizajes</a>
</p>

---

### 🎯 Visión General
- **Contexto:** Yampa, una startup brasileña de SaaS de control financiero para PyMEs en expansión hacia un ecosistema completo de gestión.
- **Mi Rol:** Product Growth Manager & Data Strategist.
- **Timeline:** 6 meses.
- **Stack/Herramientas:** SQL, Metabase (Open Source), n8n, Looker Studio, Google Cloud/Data Lake.

---

### 🔍 El Desafío
Identificamos un problema crítico en la integridad de los datos y, en consecuencia, en la confiabilidad de la información proporcionada a través de los dashboards. La empresa utilizaba poco los datos para la toma de decisiones estratégicas debido a la divergencia de números entre las áreas.
> "La falta de confianza en los datos impedía el escalamiento; las métricas de crecimiento no coincidían con la realidad financiera auditada."

---

### 🔧 Estrategia y Solución
Para resolver el cuello de botella de confianza e infraestructura, la estrategia se dividió en cuatro frentes:

1. **Audit & Mapping:** Realicé el mapeo completo de los datos existentes, identificando deuda técnica en bases de datos, rutinas de consulta y cuellos de botella de procesamiento.
2. **Workshop de Reglas de Negocio:** Facilité workshops con todas las áreas (Marketing, Producto, Finanzas, Ventas y CS) para definir conceptos unificados de métricas y alinear expectativas, priorizando el backlog de refactorización.
3. **Refactorización Técnica:** Liderazgo del proceso de refactorización completa de consultas, vistas y tablas. Como la revisión total del flujo de ETL era inviable en ese momento, nos enfocamos en la integridad de la capa de consumo.
4. **Centralización e Infraestructura:** Reestructuramos el 100% de los dashboards de la empresa, migrando a una nueva herramienta de BI (Metabase), garantizando una única "fuente de la verdad".

---

### 📈 Resultados e Impacto
Los resultados trajeron no solo precisión, sino también ahorro y agilidad para la startup:

- **Confiabilidad:** Aumento al **97% en la adherencia** de datos críticos (MRR, ARR, Churn, CAC, LTV) en comparación con las auditorías del equipo financiero.
- **Eficiencia Financiera:** Centralización del 100% de los dashboards en Metabase (Open Source), generando un **ahorro inmediato** en el licenciamiento de herramientas anteriores.
- **Agilidad Operativa:** Reducción del tiempo de espera para la actualización de datos de **3 a 2 días**.
- **Cultura de Datos:** El 100% de las decisiones estratégicas de Growth y Producto pasaron a basarse en los nuevos dashboards centralizados.

---

### 💡 Aprendizajes
- **Priorización a Escala:** La importancia de enfocarse en la capa de visualización y reglas de negocio cuando el pipeline de ETL de back-end no puede ser modificado inmediatamente.
- **Visión Holística:** Entendimiento profundo de cómo los indicadores de ingresos recurrentes impactan de manera diferente a cada área de la empresa.
- **Stack Alternativa:** La viabilidad técnica y financiera de utilizar herramientas Open Source (Metabase) integradas a flujos de automatización (n8n) para empresas en etapa de growth.

---
<p align="center">
  <br>
  <a href="../../README.es.md">
    <img src="https://img.shields.io/badge/%E2%AC%85%20VOLVER%20AL%20PERFIL%20PRINCIPAL%20%E2%AC%85-black?style=for-the-badge&logo=github&logoColor=white" width="400">
  </a>
