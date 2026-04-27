# Ivan Gruber

**Sports Data Engineer | Real-Time Analytics | Cloud Data Platforms**

I build production-style data systems for sports analytics: event ingestion, medallion lakehouse pipelines, streaming decision engines, ML-ready feature layers, and dashboards that turn raw game data into operational insight.

[Portfolio](https://ivanrivasgr.github.io) | [LinkedIn](https://linkedin.com/in/ivangruber) | [Email](mailto:ivanfgruber@gmail.com)

---

## Current Focus

I am building **Bullpen Signal**, a real-time vs batch decision engine for pitcher fatigue, bullpen readiness, and matchup leverage.

The project is designed to answer a practical architecture question: when does a manager need a fast provisional signal, when does the organization need canonical batch truth, and how do you reconcile the gap between both?

[Bullpen Signal](https://github.com/ivanrivasgr/bullpen-signal) | [CI/CD](https://github.com/ivanrivasgr/bullpen-signal/actions)

---

## Selected Projects

### Bullpen Signal

Dual-path baseball decision engine using deterministic MLB game replay, Redpanda/Kafka-style event streams, Flink jobs, Iceberg lakehouse tables, dbt incremental models, quality checks, lineage, observability, and a Streamlit serving layer.

**Why it matters:** demonstrates the boundary between streaming systems and batch truth in a high-pressure operational sports setting.

`Redpanda` `Flink` `Iceberg` `dbt` `Great Expectations` `OpenLineage` `Prometheus` `Grafana` `Streamlit`

[Repository](https://github.com/ivanrivasgr/bullpen-signal) | [GitHub Actions](https://github.com/ivanrivasgr/bullpen-signal/actions)

### BaseballIQ

End-to-end MLB analytics platform with Statcast-style data, Bronze/Silver/Gold modeling, pitcher CSW prediction, SHAP explainability, cached LLM scouting insights, and a polished Streamlit dashboard.

**Why it matters:** shows a complete analytics product, from data modeling and ML framing to user-facing decision support.

`Python` `DuckDB` `Parquet` `XGBoost` `SHAP` `Streamlit` `Plotly` `Pytest`

[Live Demo](https://baseballiq-aovcjbmgvuzznyck63ajbg.streamlit.app/) | [Repository](https://github.com/ivanrivasgr/baseballiq)

### Soccer Data Platform

Production-style sports data platform using Bronze/Silver/Gold architecture for GPS tracking data, validation, Parquet transformation, CI/CD, Airflow orchestration, and Terraform-backed AWS S3 lake design.

`Python` `Airflow` `Terraform` `AWS S3` `Parquet` `Pytest` `GitHub Actions` `Streamlit`

[Live Demo](https://soccer-data-platform-demo-2ysoonreyzjsuspa2kf6ve.streamlit.app/) | [Repository](https://github.com/ivanrivasgr/soccer-data-platform-demo)

### Sports Injury Risk Intelligence

ML pipeline for football injury risk using point-in-time correct features, leakage guards, CI coverage gates, confidence intervals, and out-of-distribution flags.

`Python` `Scikit-learn` `Great Expectations` `Delta Lake` `Pytest` `GitHub Actions`

[Live Demo](https://sportsinjuryriskintelligence-jxgxyr6kp5thzqfbhkyu8w.streamlit.app/) | [Repository](https://github.com/ivanrivasgr/Sports_Injury_Risk_Intelligence)

---

## Engineering Strengths

- Building data products around real operational decisions, not just dashboards.
- Designing batch, streaming, and reconciliation layers with clear tradeoffs.
- Working across ingestion, transformation, quality, orchestration, ML features, and serving.
- Translating sports domain complexity into testable data contracts and useful analytics interfaces.

---

## Stack

**Languages:** Python, SQL, Ruby  
**Data:** DuckDB, Parquet, Iceberg, Delta Lake, BigQuery, Redshift  
**Streaming & orchestration:** Redpanda, Kafka-style eventing, Apache Flink, Airflow, dbt, GitHub Actions  
**Cloud & infra:** GCP, AWS, Docker Compose, Terraform, MinIO, S3  
**Quality & observability:** Pytest, Great Expectations, OpenLineage, Prometheus, Grafana  
**Analytics & apps:** Streamlit, Plotly, Power BI, SHAP, scikit-learn, XGBoost  
**Sports data:** MLB Statcast, pybaseball, MLB StatsAPI, pitch-by-pitch tracking, GPS tracking data

---

## Background

I have 5+ years of experience designing and operating analytics pipelines across sports data, cloud ETL, BI automation, and client-facing data delivery.

At **Synergy Sports / Sportradar**, I worked with live MLB game data, pitch-by-pitch feeds, QA workflows, and structured datasets used downstream for analytics and broadcast reporting.

At **Vikua**, I delivered cloud analytics systems across multiple client environments, improving time-to-insight, reliability, and compute efficiency.

I am currently completing the **MIT MicroMasters in Statistics and Data Science** track, with a focus on statistical modeling and computation.

---

## Contact

[Portfolio](https://ivanrivasgr.github.io)  
[LinkedIn](https://linkedin.com/in/ivangruber)  
[Email](mailto:ivanfgruber@gmail.com)

> I care about data systems that hold up under pressure: live decisions, late corrections, measurable reliability, and interfaces that make complex information usable.
