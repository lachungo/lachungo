<div align="center">

# Louis Achungo

### Principal SQL Server Architect · Senior SQL Server DBA · Database Reliability Engineer

**SQL Server Performance Engineering · Azure SQL & AWS RDS · HA/DR · Observability · AI-Driven Database Automation**

[Portfolio](https://sql-it-techsolutions.com/) ·
[LinkedIn](https://www.linkedin.com/in/louis-achungo/) ·
[Email](mailto:achungolm@gmail.com)

</div>

---

## Engineering Profile

I am a **Principal SQL Server Architect and Senior SQL Server DBA with 25 years of experience** designing, administering, optimizing, and modernizing enterprise database platforms across on-premises, Azure, AWS, and hybrid environments.

My work focuses on turning complex database operations into **reliable, observable, automated, and evidence-driven engineering systems**.

### Core Specialties

- SQL Server Architecture, Administration, and Performance Engineering
- Query Store Tuning, Plan Stability, and Parameter-Sensitivity Analysis
- Always On Availability Groups, HA/DR, and Business Continuity
- Azure SQL Database, Azure SQL Managed Instance, and AWS RDS
- Extended Events, Execution-Plan Analysis, and Root-Cause Analysis Investigation
- VLDB Index Maintenance (Rebuild & Reorg) Orchestration and Resumable Operations
- Database Observability, SRE practices, and Operational Automation
- AI-assisted database assessment and diagnostic engineering
- AI-Driven Database Automation, Diagnostic Reasoning, and Evidence-Backed Root-Cause Analysis

---

## Flagship Engineering Projects

| Project | Engineering Focus |
|---|---|
| **[Agentic AI RCA Toolkit for SQL Server](https://github.com/lachungo/agentic-ai-rca-toolkit)** | SQL Server flight recorder correlating CPU, blocking, I/O, memory, TempDB, transaction-log, and connectivity evidence. Preserves strict lineage between an execution, its runtime parameters, matching actual execution plan, findings, and root-cause classification. |
| **[SQL Server VLDB Index Maintenance Framework](https://github.com/lachungo/sql-server-vldb-index-maintenance-framework)** | Queue-based maintenance orchestration for multi-terabyte SQL Server estates, including AG-aware execution, resumable maintenance windows, storage guardrails, observability, and recovery workflows. |
| **[Agentic AI DBA Assessment Toolkit](https://github.com/lachungo/SQL-Server-Agentic-AI-DBA-Assessment-Toolkit)** | Automated SQL Server health, security, configuration, availability, and performance assessments with technical and executive reporting. |
| **[SQL Server Observability and DBA SRE Toolkit](https://github.com/lachungo/SQL-Server-Observability-and-DBA-SRE-Toolkit)** | Enterprise monitoring, alerting, Always On observability, root-cause analysis, and operational intelligence. |
| **[SQL Server CPU Saturation RCA](https://github.com/lachungo/sql-server-cpu-saturation-rca)** | Evidence-driven CPU troubleshooting using scheduler pressure, waits, workload correlation, query activity, and performance diagnostics. |
| **[SQL Server Engineering Portfolio](https://github.com/lachungo/sql-server-portfolio)** | Central portfolio of SQL Server architecture, automation, performance engineering, observability, and cloud database projects. |

---

## Selected Engineering Impact

- Improved representative SQL Server workloads by **97.6% and 99.7%** through parameter-sensitivity analysis, plan reuse, and controlled performance validation.
- Reduced representative TempDB allocation by **96.9%** during stored-procedure optimization.
- Engineered a Query Store plan-stability approach using multi-metric comparison, last-known-good plan analysis, Automatic Plan Correction awareness, validation, rollback, and audit controls.
- Designed a SQL Server flight recorder that correlates evidence across **seven performance domains** instead of treating independent monitoring alerts as root causes.
- Built resumable, window-aware, and storage-aware maintenance orchestration for multi-terabyte SQL Server environments.
- Investigated large-scale SQL connectivity, session, workload, and replication architectures across enterprise environments.

---

## SQL Server Flight Recorder Architecture

The Agentic AI RCA Toolkit investigates seven correlated evidence domains: 

| Evidence domain | Investigation focus |
|---|---|
| CPU and scheduler pressure | Runnable workload, worker pressure, CPU-intensive executions |
| Blocking and waits | Blocker chains, wait duration, impacted sessions |
| I/O and storage latency | Read/write latency, physical activity, file pressure |
| Memory grants and spills | Grant pressure, cardinality issues, runtime spills |
| TempDB pressure | Allocation activity, spills, contention, file utilization |
| Transaction-log pressure | Log utilization, growth, reuse waits, long transactions |
| Connectivity pressure | Failed connections, latency, resets, and session evidence |

The investigation preserves the evidence chain:

> **Incident window → captured execution → runtime parameters → matching execution plan → plan findings → causal classification**

**Roadmap:** An MCP-based AI agent layer, now in development, will interpret this evidence, reason across performance domains, explain root causes, and recommend corrective actions.

---

## Technology Focus

`SQL Server 2016–2022` · `T-SQL` · `Query Store` · `Extended Events`  
`Always On Availability Groups` · `Azure SQL` · `AWS RDS`  
`Execution Plans` · `Performance Tuning` · `HA/DR` · `Database Reliability`  
`PowerShell` · `GitHub Actions` · `AI-Driven Automation`

---

## Certifications

- Microsoft Certified: Azure Database Administrator Associate — **DP-300**
- Microsoft Certified: Azure Fundamentals — **AZ-900**
- AWS Certified Cloud Practitioner — **CLF-C02**
- Microsoft Certified IT Professional — SQL Server DBA
- Microsoft Certified Solutions Expert — SQL Server
- Microsoft Certified Solutions Associate — SQL Server
- Microsoft Certified Database Administrator — SQL Server

---

## Professional Links

- **Portfolio:** [sql-it-techsolutions.com](https://sql-it-techsolutions.com/)
- **LinkedIn:** [linkedin.com/in/louis-achungo](https://www.linkedin.com/in/louis-achungo/)
- **GitHub:** [github.com/lachungo](https://github.com/lachungo)
- **Email:** [achungolm@gmail.com](mailto:achungolm@gmail.com)

---

<div align="center">

### Monitoring shows that something happened.  
### Engineering explains what happened, why it mattered, and what evidence supports the conclusion.

</div>
