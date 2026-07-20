<h1 align="center">Kim Ji Hoon</h1>
<p align="center"><b>Senior Data Engineer</b> · Data Platform · Workflow Orchestration · GitOps</p>

<p align="center">
  <a href="https://github.com/kjh0623">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=17&duration=3200&pause=900&center=true&vCenter=true&width=600&lines=Running+Airflow+3+on+Kubernetes+with+3%2C600+DAGs;Apache+Airflow+upstream+contributor;Building+reliable%2C+observable+data+platforms;From+DAG+to+dashboard" alt="typing" />
  </a>
</p>

---

### 👋 About

Senior Data Engineer with 12 years of experience. From batch and pipeline orchestration (Apache Airflow)
to query engines (Trino), transformation (dbt), and the **Kubernetes + GitOps** platform that runs it all,
I design and reliably operate every stage that data flows through. I currently run an **Airflow 3 platform
with 3,600 DAGs** on Kubernetes.

- 🛠️ **Data platform ownership** — operating the Airflow / Trino / dbt stack across multiple clusters (dev · stag · prd)
- 🔀 **Orchestration at scale** — Kubernetes-based Airflow 3.x, Git-bundle DAGs, custom image pipelines
- 🚀 **GitOps first** — declarative delivery with ArgoCD; every change goes Git → review → sync
- 🔎 **Root-cause driven** — digging down to the transaction and session level to find the real cause, and contributing upstream when needed
- 🔐 **Governed access** — data access control built on OPA / Ranger / OIDC

---

### 🔭 Open Source

> 🎯 Running a 3,600-DAG production platform, I trace the bugs and race conditions I hit down to their root cause and contribute the fixes directly upstream (**Apache Airflow**, **Trino**).

**Apache Airflow**

| | Contribution | Status |
|---|---|---|
| [apache/airflow#69845](https://github.com/apache/airflow/pull/69845) | Fix DAG import errors being dropped during parsing | 🟢 under review |
| [apache/airflow#70002](https://github.com/apache/airflow/pull/70002) | Fix `dag_tag` UniqueViolation race with HA dag processors | 🟢 under review |
| [apache/airflow#70003](https://github.com/apache/airflow/pull/70003) | Add `pin_symlink_on_refresh` to `LocalDagBundle` for git-sync checkouts | 🟢 under review |
| [apache/airflow#70056](https://github.com/apache/airflow/issues/70056) | Report: scheduler silently skips queued DagRuns with unresolvable pinned versions | 🐛 reported |
| [apache/airflow#70057](https://github.com/apache/airflow/pull/70057) | Don't fail requests with a bare 500 on transient JWT refresh errors | 🟢 under review |
| [apache/airflow#70058](https://github.com/apache/airflow/pull/70058) | Add `refresh_on_initialize` option to `GitDagBundle` | 🟢 under review |

**Trino**

| | Contribution | Status |
|---|---|---|
| [trinodb/trino#28630](https://github.com/trinodb/trino/issues/28630) | "SHOW COLUMNS only returns the first row" — root-caused to the client's batch payload handling (not a server bug); the analysis closed the issue | ✅ root-caused & closed |
| [trinodb/trino#28602](https://github.com/trinodb/trino/issues/28602) | OPA access control: on partial-permission denial for `SELECT *`, the error message leaks every column name — discussing the fix (semantic analyzer) with maintainers, PR in preparation | 💬 in discussion |

---

### 🌱 What I work on

| Area | Details |
|------|---------|
| **Pipeline orchestration** | Apache Airflow 3.x on Kubernetes — Git-bundle DAGs, custom images (dbt/ClickHouse/Impala venvs), multi-env (dev · stag · prd) |
| **Query & analytics** | Trino coordinators/workers, OPA-based access policies, group sync automation |
| **Transformation** | dbt (core + ClickHouse / Impala adapters) |
| **Platform / GitOps** | ArgoCD-managed EKS & on-prem clusters, declarative manifests, selective sync & rollout |
| **Reliability** | multi-replica DAG-processor race conditions, transaction-safety, TLS & auth-proxy hardening |

---

### 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-437291?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL%20%2F%20HiveQL-336791?style=flat-square)
![Shell](https://img.shields.io/badge/Shell%20Script-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Pipeline & Streaming**

![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Apache NiFi](https://img.shields.io/badge/Apache%20NiFi-728E9B?style=flat-square&logo=apachenifi&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache%20Iceberg-2C5BFF?style=flat-square)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Fluentd](https://img.shields.io/badge/Fluentd-0E83C8?style=flat-square&logo=fluentd&logoColor=white)

**Data Platform**

![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=flat-square&logo=apachehadoop&logoColor=black)
![Hive](https://img.shields.io/badge/Hive-FDEE21?style=flat-square&logo=apachehive&logoColor=black)
![Impala](https://img.shields.io/badge/Impala-1A73E8?style=flat-square)
![Kudu](https://img.shields.io/badge/Kudu-00A1E0?style=flat-square)
![HBase](https://img.shields.io/badge/HBase-BE0102?style=flat-square)
![Trino](https://img.shields.io/badge/Trino-DD00A1?style=flat-square&logo=trino&logoColor=white)
![Kyuubi](https://img.shields.io/badge/Kyuubi-1B9E85?style=flat-square)
![Gravitino](https://img.shields.io/badge/Gravitino-4C71F0?style=flat-square)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Druid](https://img.shields.io/badge/Druid-29F1FB?style=flat-square&logo=apachedruid&logoColor=black)
![Cloudera](https://img.shields.io/badge/Cloudera%20CDP%2FCDH-F96702?style=flat-square&logo=cloudera&logoColor=white)

**Infra & DevOps**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Kustomize](https://img.shields.io/badge/Kustomize-326CE5?style=flat-square)
![GitLab CI/CD](https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Harbor](https://img.shields.io/badge/Harbor-60B932?style=flat-square&logo=harbor&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO%20%2F%20S3-C72E49?style=flat-square&logo=minio&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

**Observability & Security**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Thanos](https://img.shields.io/badge/Thanos-6D41FF?style=flat-square)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F5A800?style=flat-square)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white)
![OPA](https://img.shields.io/badge/Open%20Policy%20Agent-7D9199?style=flat-square&logo=openpolicyagent&logoColor=white)
![OIDC](https://img.shields.io/badge/OIDC-F78C40?style=flat-square)
![Ranger](https://img.shields.io/badge/Apache%20Ranger-1B4F72?style=flat-square)

**Backend & DB**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot%2FBatch-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-C74634?style=flat-square)
![MSSQL](https://img.shields.io/badge/MSSQL-A91D22?style=flat-square)
![Tibero](https://img.shields.io/badge/Tibero-005EB8?style=flat-square)

---

### 📊 GitHub

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kjh0623/kjh0623/output/github-snake-dark.svg" />
  <img width="100%" src="https://raw.githubusercontent.com/kjh0623/kjh0623/output/github-snake.svg" alt="snake" />
</picture>

---

### 📫 Connect

<p align="center">
  <a href="mailto:gktxk@naver.com">
    <img src="https://img.shields.io/badge/Email-gktxk%40naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white" alt="email" />
  </a>
  <a href="https://www.linkedin.com/in/%EC%A7%80%ED%9B%88-%EA%B9%80-logankim/">
    <img src="https://img.shields.io/badge/LinkedIn-Kim%20Ji%20Hoon-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" />
  </a>
  <a href="https://github.com/kjh0623?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-kjh0623-181717?style=for-the-badge&logo=github&logoColor=white" alt="github" />
  </a>
</p>
