<!-- Dishant Modh — GitHub Profile README -->

<!-- ═══════════════ HEADER BANNER ═══════════════ -->
<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0891b2,100:00E0FF&height=220&section=header&text=Dishant%20Modh&fontSize=62&fontColor=ffffff&fontAlignY=36&animation=fadeIn&desc=Site%20Reliability%20%E2%80%A2%20Database%20Reliability%20%E2%80%A2%20Cloud%20Infrastructure&descSize=18&descAlignY=58" alt="Dishant Modh banner" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00E0FF&center=true&vCenter=true&width=850&lines=Site+Reliability+Engineer+%7C+Database+Reliability+Engineer;PostgreSQL+%7C+Aurora+%7C+MongoDB+%7C+Cassandra+%7C+Snowflake;Terraform+%7C+AWS+%7C+Multi-Region+Disaster+Recovery;Building+Reliable%2C+Scalable+%26+Self-Healing+Platforms;5%2B+Years+Running+Production+Databases+at+Scale" alt="Typing SVG" />
</p>

<p align="center">
  <a href="mailto:dishantmodh7@gmail.com"><img src="https://img.shields.io/badge/Email-dishantmodh7%40gmail.com-00E0FF?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/dishant-modh-3334071a3/"><img src="https://img.shields.io/badge/LinkedIn-Dishant%20Modh-00E0FF?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://dishantmodh.com"><img src="https://img.shields.io/badge/Website-dishantmodh.com-00E0FF?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://twitter.com/DishantModh"><img src="https://img.shields.io/badge/X-@DishantModh-00E0FF?style=for-the-badge&logo=x&logoColor=white"></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=dhmodh&style=for-the-badge&color=00E0FF&label=PROFILE+VIEWS"/>
  <img src="https://img.shields.io/github/followers/dhmodh?style=for-the-badge&color=00E0FF"/>
  <img src="https://img.shields.io/github/stars/dhmodh?style=for-the-badge&color=00E0FF"/>
  <img src="https://img.shields.io/badge/Based%20in-Bengaluru%2C%20India-00E0FF?style=for-the-badge&logo=googlemaps&logoColor=white"/>
</p>

---

## 👨‍💻 About Me

I'm an **SRE & Database Reliability Engineer** with **5+ years** owning database infrastructure across distributed, cloud-native systems — from a healthcare-tech SaaS platform to enterprise-scale multi-region deployments.

> *I don't just keep databases running — I make them **faster, cheaper, scalable and resilient.***

<table>
<tr>
<td>⚡ <b>Highly Available</b></td>
<td>🔄 <b>Self-Healing</b></td>
<td>📈 <b>Performance Optimized</b></td>
</tr>
<tr>
<td>☁️ <b>Cloud Native</b></td>
<td>🤖 <b>Automation First</b></td>
<td>🌍 <b>DR Ready</b></td>
</tr>
</table>

---

## 🏆 Engineering Impact

<table align="center">
<tr>
<td align="center" width="33%">
<h3>⏱️ 8 min → &lt; 60 sec</h3>
<sub><b>RTO</b> via Aurora Global + AWS DMS</sub>
</td>
<td align="center" width="33%">
<h3>💰 $1.2M+</h3>
<sub><b>Annualized AWS savings</b></sub>
</td>
<td align="center" width="33%">
<h3>⚡ 1.8s → 0.9s</h3>
<sub><b>P95 latency</b> · 40+ queries tuned</sub>
</td>
</tr>
<tr>
<td align="center">
<h3>🔭 45 → 31 min</h3>
<sub><b>MTTR</b> with Datadog + Grafana</sub>
</td>
<td align="center">
<h3>🤖 91% precision</h3>
<sub>ML anomaly detection · 87% recall</sub>
</td>
<td align="center">
<h3>🚚 4+ TB · 0 breaches</h3>
<sub>6 zero-downtime migrations to AWS</sub>
</td>
</tr>
</table>

---

## 🌍 Architecture I Build: Multi-Region DR

```mermaid
flowchart LR
    APP([Applications]) --> P

    subgraph R1["Primary Region"]
        P[(Aurora Global<br/>Primary Cluster)]
        PM[Datadog / Grafana]
    end

    subgraph R2["Secondary Region"]
        S[(Aurora Global<br/>Secondary Cluster)]
    end

    subgraph R3["Migration / Sync"]
        DMS[AWS DMS]
    end

    P -- "Storage-level replication" --> S
    P -. "CDC" .-> DMS
    DMS -.-> X[(Target / Heterogeneous DB)]
    PM -. "Alerts" .-> ONCALL{{On-call SRE}}
    S -. "Managed failover  RTO < 60s" .-> APP

    classDef db fill:#0e7490,stroke:#00E0FF,color:#fff;
    class P,S,X db;
```

---

## 🗄️ Database Expertise

```txt
PostgreSQL 14/15   ████████████████████  Expert
Aurora (PG/MySQL)  ████████████████████  Expert
MySQL 8            ████████████████░░░░  Advanced
MongoDB            ████████████████░░░░  Advanced
Cassandra          ██████████████░░░░░░  Advanced
Snowflake          ████████████░░░░░░░░  Proficient
Oracle             ████████████░░░░░░░░  Proficient
```

<details>
<summary><b>🔬 What I specialize in (click to expand)</b></summary>
<br>

| Area | Focus |
|---|---|
| 🐘 **PostgreSQL** | Query & index tuning · autovacuum tuning · partitioning · replication & HA |
| 🌍 **Reliability** | Multi-region DR · failover design · PITR backups · capacity planning |
| 🚚 **Migrations** | Zero-downtime moves to RDS/Aurora with AWS DMS |
| 🍃 **NoSQL** | MongoDB aggregation optimization · Cassandra data modeling |
| 🤖 **Automation** | Terraform modules · CI/CD validation · Python/Bash DBA tooling |
| 🚨 **Operations** | P0/P1 incident response · post-mortems · runbooks |

</details>

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,postgres,mysql,mongodb,cassandra,snowflake,terraform,docker,kubernetes,python,go,bash,linux,git,githubactions,jenkins,prometheus,grafana,ansible&perline=10&theme=dark" />
</p>

<details>
<summary><b>☁️ Cloud, IaC, Observability & Languages (click to expand)</b></summary>
<br>

| Category | Tools |
|---|---|
| **AWS** | RDS · Aurora · EC2 · DMS · Lambda · S3 · IAM · CloudWatch · VPC |
| **IaC & CI/CD** | Terraform · GitHub Actions · Jenkins · Octopus Deploy · Docker · Ansible |
| **Observability** | Datadog · Grafana · Prometheus · Loki · Alertmanager |
| **Languages** | Python · SQL · Bash · Go · PowerShell |

</details>

---

## 💼 Experience

### 🏢 GlobalLogic *(Client: Hitachi)* — SRE / DBA
📍 Bengaluru  ·  📅 Feb 2024 – Present

> Managing enterprise-scale distributed database workloads across **3 AWS regions**.

- 🌍 Run PostgreSQL, Aurora, MySQL, MongoDB, Cassandra & Snowflake clusters at **99.95%+ uptime**
- 🔄 Built multi-region DR architecture on **Aurora Global Database + AWS DMS**
- ⚙️ Automated RDS provisioning & patching with **Terraform + GitHub Actions**
- 💰 Delivered **$1.2M annualized AWS savings** through infrastructure optimization
- 📊 Rolled out a centralized observability stack on **Datadog + Grafana**
- ⚡ Cut MongoDB & Cassandra query latency from **820ms → 450ms**
- 👥 Mentored junior SREs on PostgreSQL tuning & incident management

### 🏥 HHAeXchange — Database Administrator
📍 Ahmedabad  ·  📅 Dec 2021 – Feb 2024

> Healthcare-tech SaaS platform serving **500K+ caregivers** with **120+ production databases**.

- 🐘 Administered PostgreSQL, MySQL, Cassandra & Oracle at **99.99% uptime**
- ⚡ Optimized **40+ slow PostgreSQL queries** using `EXPLAIN ANALYZE`
- 🚚 Executed **6 zero-downtime migrations** to AWS RDS/Aurora
- 🤖 Automated DBA operations with Python & Bash
- 🚨 Primary on-call DBA for P0/P1 incidents and post-mortems
- 🔧 Built Terraform modules & CI/CD validation pipelines

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [ml-dba](https://github.com/dhmodh/ml-dba)
ML anomaly detection platform built on PostgreSQL metrics.
**`91% precision`**

</td>
<td width="50%" valign="top">

### 🐘 [patroni-ha-cluster](https://github.com/dhmodh/patroni-ha-cluster)
Self-healing PostgreSQL HA cluster with Patroni + Terraform.
**`< 5s failover`**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧰 [postgres-dba-toolkit](https://github.com/dhmodh/postgres-dba-toolkit)
PostgreSQL monitoring & diagnostics toolkit.
**`Production-ready`**

</td>
<td width="50%" valign="top">

### 🏗️ [terraform-rds-modules](https://github.com/dhmodh/terraform-rds-modules)
Reusable Terraform modules for RDS provisioning.
**`Eliminated config drift`**

</td>
</tr>
</table>

---

## 🏅 Certifications

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Solutions%20Architect%20Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-SI%20Associate-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Microsoft-Azure%20Fundamentals%20AZ--900-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-Foundations-181717?style=for-the-badge&logo=github&logoColor=white"/>
</p>

---

## 🌱 Currently Working On

| | Focus |
|---|---|
| 🔌 | **PgBouncer** + PgBouncer Exporter integration |
| 📦 | **pgBackRest / Barman** PITR backup automation |
| 🤖 | **LSTM-based** anomaly detection for PostgreSQL |
| ☸️ | **Kubernetes-native** PostgreSQL operations |
| 📡 | Advanced observability pipelines |

---

## 📊 GitHub Analytics

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=dhmodh&show_icons=true&theme=tokyonight&border_color=00E0FF&border_radius=10&hide=stars&hide_title=false" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dhmodh&layout=compact&theme=tokyonight&border_color=00E0FF&border_radius=10&hide_border=false" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=dhmodh&theme=tokyonight&ring=00E0FF&fire=00E0FF&currStreakLabel=00E0FF&border=00E0FF&hide_border=false" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=dhmodh&theme=react-dark&color=00E0FF&line=00E0FF&point=ffffff&area_color=0d1117&hide_border=true" />
</p>

---

## 🤝 Let's Connect

<p align="center">
  Open to conversations about <b>database reliability, DR design, PostgreSQL performance and cloud cost optimization.</b>
</p>

<p align="center">
  <a href="mailto:dishantmodh7@gmail.com"><img src="https://img.shields.io/badge/Gmail-00E0FF?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/dishant-modh-3334071a3/"><img src="https://img.shields.io/badge/LinkedIn-00E0FF?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://dishantmodh.com"><img src="https://img.shields.io/badge/Portfolio-00E0FF?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
  <a href="https://twitter.com/DishantModh"><img src="https://img.shields.io/badge/X-00E0FF?style=for-the-badge&logo=x&logoColor=white"/></a>
  <a href="https://github.com/dhmodh"><img src="https://img.shields.io/badge/GitHub-00E0FF?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<p align="center">
  <i>"Automate. Optimize. Scale. Deliver Reliably."</i>
</p>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00E0FF,50:0891b2,100:0d1117&height=120&section=footer" alt="footer" />
</p>
