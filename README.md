# Awesome-Merchant-Risk-Platform

## Top Merchant Risk Platform Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**

*Focused on Merchant Risk, Fraud Prevention, Transaction Monitoring, Identity Risk & Real-Time Decisioning*

**Last updated: September 2026**



This repository tracks notable **SaaS/Hosted platforms** and **open-source projects** for **Merchant Risk Platforms**. These tools help merchants, marketplaces, fintechs, payment providers, and digital businesses detect and prevent payment fraud, account takeover, friendly fraud, chargebacks, bot abuse, identity fraud, transaction laundering, and other forms of financial and digital risk.



**Examples** include Riskified, Signifyd, Sardine, Sift, Forter, SEON, Unit21, Fraud.net, Feedzai, and Kount.



Modern merchant-risk platforms typically combine **device intelligence, behavioral analytics, transaction scoring, identity verification, velocity rules, IP intelligence, network intelligence, machine learning, graph analysis, behavioral biometrics, chargeback intelligence, account-takeover detection, bot detection, manual review, case management, and real-time approve/review/decline decisioning**.



**Open-source emphasis**: This section is heavily expanded with projects for **self-hosted fraud detection, real-time transaction scoring, AML/fraud monitoring, feature stores, rules engines, device fingerprinting, stream processing, graph analytics, case management, explainable ML, risk APIs, and fraud-model development**.



> **Important distinction:** There are very few mature open-source, drop-in replacements for Riskified, Signifyd, Sift, Forter, or Feedzai. Commercial platforms often rely on proprietary consortium data, device networks, behavioral datasets, merchant feedback loops, proprietary models, and large-scale infrastructure. The open-source ecosystem is therefore best viewed as a collection of **fraud/risk engines and building blocks for constructing a self-hosted merchant-risk platform**.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or repositories.



## Table of Contents



* [SaaS/Hosted Platforms](#saashosted-platforms)

* [Open-Source GitHub Projects](#open-source-github-projects)

* [Open-Source Fraud & Risk Engines](#open-source-fraud--risk-engines)

* [Fraud Detection & Machine Learning](#fraud-detection--machine-learning)

* [Feature Stores & Real-Time Risk Features](#feature-stores--real-time-risk-features)

* [Device Intelligence & Behavioral Signals](#device-intelligence--behavioral-signals)

* [Rules, Policy & Decision Engines](#rules-policy--decision-engines)

* [Graph Analytics & Entity Resolution](#graph-analytics--entity-resolution)

* [AML, Transaction Monitoring & Case Management](#aml-transaction-monitoring--case-management)

* [Streaming & Real-Time Infrastructure](#streaming--real-time-infrastructure)

* [Search, Analytics & Risk Operations](#search-analytics--risk-operations)

* [AI/LLM Infrastructure](#aillm-infrastructure)

* [Recommended Open-Source Merchant Risk Architecture](#recommended-open-source-merchant-risk-architecture)

* [Commercial → Open-Source Mapping](#commercial--open-source-mapping)

* [Open-Source Capability Matrix](#open-source-capability-matrix)

* [Best Open-Source Combinations](#best-open-source-combinations)

* [What Open Source Can and Cannot Replace](#what-open-source-can-and-cannot-replace)

* [How to Contribute](#how-to-contribute)

* [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



* **[Riskified](https://www.riskified.com/)**

  E-commerce risk-management platform providing automated decisions, chargeback protection, account protection, policy protection, and payment optimization using transaction, device, behavioral, and network data.



* **[Signifyd](https://www.signifyd.com/)**

  Commerce protection platform providing automated fraud decisions, chargeback protection, abuse prevention, and customer-experience optimization.



* **[Sardine](https://www.sardine.ai/)**

  Fraud prevention and compliance platform combining device intelligence, behavioral analytics, identity, transaction monitoring, and risk decisioning.



* **[Sift](https://sift.com/)**

  Digital trust and fraud-prevention platform covering payment fraud, account takeover, content abuse, payment abuse, and other stages of the customer journey.



* **[Forter](https://www.forter.com/)**

  Digital-commerce trust platform providing real-time identity-based decisioning, fraud prevention, account protection, and abuse prevention.



* **[SEON](https://seon.io/)**

  Fraud-prevention platform combining digital-footprint intelligence, device intelligence, IP/email/phone analysis, transaction monitoring, and risk scoring.



* **[Unit21](https://www.unit21.ai/)**

  No-code transaction-monitoring and fraud/AML platform supporting configurable rules, risk workflows, case management, and real-time monitoring.



* **[Fraud.net](https://www.fraud.net/)**

  AI-driven fraud-prevention platform providing real-time transaction risk scoring, behavioral intelligence, rules, analytics, and fraud operations.



* **[Feedzai](https://feedzai.com/)**

  Enterprise risk-operations platform focused on fraud prevention, financial crime, transaction monitoring, and AI-driven risk decisioning.



* **[Kount](https://kount.com/)**

  Digital-fraud prevention platform providing identity trust, transaction protection, account protection, and fraud decisioning.



* **[Ekata](https://ekata.com/)**

  Identity-verification and risk-intelligence platform providing identity attributes and risk signals for fraud prevention.



* **[Socure](https://www.socure.com/)**

  Digital identity-verification and fraud-prevention platform focused on identity risk, onboarding, account opening, and transaction-related risk.



* **[LexisNexis Risk Solutions](https://risk.lexisnexis.com/)**

  Broad risk-information ecosystem covering fraud prevention, identity, digital identity intelligence, transaction risk, and financial crime.



* **[TransUnion TruValidate](https://www.transunion.com/product/truvalidate-fraud-and-identity-solutions)**

  Fraud and identity platform combining identity intelligence, device signals, behavioral information, and transaction-risk controls.



* **[Experian Fraud & Identity](https://www.experian.com/business/solutions/fraud-and-identity)**

  Identity and fraud-risk technology supporting digital identity, transaction risk, authentication, and fraud prevention.



* **[DataVisor](https://www.datavisor.com/)**

  AI-driven fraud and risk platform using machine learning, anomaly detection, graph analysis, and risk intelligence.



* **[BioCatch](https://www.biocatch.com/)**

  Behavioral-biometrics platform analyzing user behavior for fraud and account-takeover detection.



* **[Arkose Labs](https://www.arkoselabs.com/)**

  Bot and fraud-prevention platform focused on automated abuse, account attacks, credential stuffing, and malicious automation.



* **[HUMAN](https://www.humansecurity.com/)**

  Digital-security platform covering bot management, fraud, account abuse, and malicious automation.



* **[Riskified Chargeback Guarantee](https://www.riskified.com/platform-riskified/)**

  Automated e-commerce transaction decisions and chargeback protection.



* **[Signifyd Commerce Protection](https://www.signifyd.com/products/)**

  Automated commerce-risk decisioning covering payment fraud and customer abuse.



* **[Sift Digital Trust & Safety](https://sift.com/platform/)**

  Risk decisioning across payment, account, content, and abuse use cases.



* **[Forter Trust Platform](https://www.forter.com/platform/)**

  Real-time trust decisions using identity and behavioral signals across digital commerce.



## Open-Source GitHub Projects



> The projects below are **not all complete merchant-risk platforms**. They are grouped according to their usefulness in constructing a self-hosted risk and fraud-prevention system.

>

> The strongest direct open-source options include **Jube, risk-triage, Financial Fraud Risk Engine, and Fraud Detection System**. Projects such as **Feast, FingerprintJS, Open Policy Agent, Apache Flink, Kafka, Redis, Neo4j, OpenSearch, MLflow, and SHAP** provide the infrastructure required to build a much larger production risk platform.



### Open-Source Fraud & Risk Engines



* **[Jube](https://github.com/jube-home/aml-fraud-transaction-monitoring)**

  Open-source AML and fraud-detection platform providing real-time transaction monitoring, rule-based detection, adaptive machine learning, risk scoring, velocity checks, aggregation, sanctions screening, workflow-driven case management, and audit trails.



  Jube is particularly relevant as one of the more complete open-source projects combining **fraud detection, AML monitoring, rules, ML, risk scoring, and case management**.



* **[risk-triage](https://github.com/opensyndicate/risk-triage)**

  Open-source payment-risk scoring and fraud-triage library providing transaction signals, weighted risk scoring, reason codes, and approve/review/block-style advisory decisions.



  It is intentionally a lightweight and explainable risk engine rather than a full commercial fraud platform.



* **[Financial Fraud Risk Engine](https://github.com/AmirhosseinHonardoust/Financial-Fraud-Risk-Engine)**

  End-to-end fraud-risk workflow demonstrating data pipelines, cost-sensitive ML, threshold optimization, batch scoring, SHAP explainability, reason codes, and an analyst dashboard.



  Useful primarily as a **reference implementation and development starting point**, rather than a production fraud network.



* **[Fraud Detection System](https://github.com/OlawumiSalaam/fraud-detection-system)**

  Open-source real-time fraud decisioning example combining a FastAPI API, feature engineering, LightGBM, MLflow, transaction scoring, decision thresholds, audit logging, and Streamlit visualization.



* **[FraudGuard](https://github.com/atifbashir-ju/FraudGuard)**

  Open-source credit-card fraud detection system providing an end-to-end ML pipeline, REST API, model evaluation, and interactive risk dashboard.



* **[Fraud Detection Platform](https://github.com/peralivet/fraud-detection-platform)**

  Production-oriented fraud ML project covering calibrated fraud scoring, cost-sensitive thresholds, risk bands, batch scoring, and analyst-oriented outputs.



### Fraud Detection & Machine Learning



* **[scikit-learn](https://github.com/scikit-learn/scikit-learn)**

  General-purpose machine-learning toolkit useful for transaction-fraud models, anomaly detection, classification, clustering, and preprocessing.



* **[XGBoost](https://github.com/dmlc/xgboost)**

  Gradient-boosting framework widely useful for structured transaction-risk models.



* **[LightGBM](https://github.com/microsoft/LightGBM)**

  Efficient gradient-boosting framework suitable for large-scale fraud-risk models and tabular transaction data.



* **[CatBoost](https://github.com/catboost/catboost)**

  Gradient-boosting framework particularly useful for categorical-heavy merchant, customer, device, and transaction features.



* **[PyTorch](https://github.com/pytorch/pytorch)**

  Deep-learning framework useful for behavioral modeling, sequence models, graph models, and advanced fraud detection.



* **[TensorFlow](https://github.com/tensorflow/tensorflow)**

  Machine-learning framework suitable for large-scale fraud modeling and anomaly detection.



* **[PyOD](https://github.com/yzhao062/pyod)**

  Open-source anomaly-detection toolkit supporting many algorithms useful for detecting unusual transactions, users, devices, and merchant behavior.



* **[River](https://github.com/online-ml/river)**

  Online machine-learning framework designed for streaming data and continuously updated models, useful for real-time fraud environments.



* **[Alibi Detect](https://github.com/SeldonIO/alibi-detect)**

  Open-source outlier, adversarial, drift, and distribution-shift detection library useful for fraud and model-monitoring systems.



* **[Evidently](https://github.com/evidentlyai/evidently)**

  Open-source ML observability toolkit useful for detecting data drift, prediction drift, model degradation, and feature anomalies.



* **[MLflow](https://github.com/mlflow/mlflow)**

  Open-source ML lifecycle platform for experiment tracking, model management, evaluation, and deployment workflows.



* **[Optuna](https://github.com/optuna/optuna)**

  Hyperparameter-optimization framework useful for tuning fraud models and decision thresholds.



* **[SHAP](https://github.com/shap/shap)**

  Explainable-AI toolkit useful for generating feature-attribution explanations for individual fraud-risk decisions.



* **[LIME](https://github.com/marcotcr/lime)**

  Explainability toolkit useful for local explanations of individual risk predictions.



### Feature Stores & Real-Time Risk Features



* **[Feast](https://github.com/feast-dev/feast)**

  Open-source feature store for managing offline and online ML features. Feast includes a fraud-detection reference architecture demonstrating real-time fraud prediction with point-in-time-correct training data and low-latency online features.



* **[Hopsworks](https://github.com/logicalclocks/hopsworks)**

  Open-source data and ML platform with feature-store capabilities suitable for fraud-model development.



* **[Feast Fraud Detection Example](https://docs.feast.dev/)**

  Reference implementation demonstrating real-time fraud prediction, feature computation, backfills, training datasets, and online inference.



* **[Redis](https://github.com/redis/redis)**

  Low-latency store useful for velocity counters, recent transaction windows, device state, session risk, and real-time feature retrieval.



* **[Dragonfly](https://github.com/dragonflydb/dragonfly)**

  High-performance Redis-compatible in-memory datastore useful for real-time risk features and counters.



* **[Apache Cassandra](https://github.com/apache/cassandra)**

  Distributed database suitable for high-volume transaction and behavioral-event workloads.



### Device Intelligence & Behavioral Signals



* **[FingerprintJS](https://github.com/fingerprintjs/fingerprintjs)**

  Open-source browser-fingerprinting library useful for generating browser/device signals that can become inputs to a merchant-risk engine.



* **[OpenReplay](https://github.com/openreplay/openreplay)**

  Open-source session-replay platform useful for investigating suspicious user journeys and behavioral anomalies.



* **[PostHog](https://github.com/PostHog/posthog)**

  Open-source product analytics platform useful for collecting behavioral events, sessions, funnels, and user activity that can feed fraud/risk analysis.



* **[Matomo](https://github.com/matomo-org/matomo)**

  Open-source analytics platform useful for self-hosted behavioral analytics and suspicious-session investigation.



* **[OpenTelemetry](https://github.com/open-telemetry/opentelemetry-collector)**

  Open-source observability framework useful for collecting application and transaction telemetry that can support operational risk monitoring.



> Browser fingerprinting is only one risk signal. A complete device-intelligence platform requires additional signals, reputation data, behavioral history, network intelligence, and model-based decisioning.



### Rules, Policy & Decision Engines



* **[Open Policy Agent](https://github.com/open-policy-agent/opa)**

  General-purpose policy engine useful for implementing transparent transaction-risk rules, merchant policies, limits, review conditions, and authorization decisions.



* **[Cedar](https://github.com/cedar-policy/cedar)**

  Open-source policy language and authorization engine useful for fine-grained risk and operational policies.



* **[Drools](https://github.com/apache/incubator-kie-drools)**

  Rule engine suitable for complex business rules, transaction policies, risk thresholds, and decision tables.



* **[Easy Rules](https://github.com/j-easy/easy-rules)**

  Lightweight Java rules engine useful for prototyping fraud decision logic.



* **[json-rules-engine](https://github.com/CacheControl/json-rules-engine)**

  JavaScript rules engine useful for configurable browser/server-side risk rules.



* **[NRules](https://github.com/NRules/NRules)**

  .NET rules engine useful for implementing configurable fraud and transaction decisioning.



* **[OPA](https://github.com/open-policy-agent/opa)** + **[Rego](https://www.openpolicyagent.org/)**

  Particularly useful for separating fraud/risk policies from application code.



### Graph Analytics & Entity Resolution



* **[Neo4j Community Edition](https://github.com/neo4j/neo4j)**

  Graph database useful for modeling relationships among customers, cards, devices, IP addresses, merchants, emails, shipping addresses, accounts, and transactions.



* **[NetworkX](https://github.com/networkx/networkx)**

  Python graph-analysis library useful for fraud rings, transaction networks, connected components, and relationship analysis.



* **[igraph](https://github.com/igraph/igraph)**

  High-performance graph-analysis library suitable for large-scale fraud-network analysis.



* **[Apache AGE](https://github.com/apache/age)**

  Graph database extension for PostgreSQL, useful for combining graph relationships with transactional data.



* **[DGL](https://github.com/dmlc/dgl)**

  Deep graph-learning framework useful for graph-based fraud detection and entity-risk modeling.



* **[PyTorch Geometric](https://github.com/pyg-team/pytorch_geometric)**

  Graph-neural-network framework suitable for fraud-ring detection, entity-risk scoring, and relationship modeling.



* **[Splink](https://github.com/moj-analytical-services/splink)**

  Probabilistic record-linkage framework useful for entity resolution across customer, account, merchant, device, and transaction datasets.



* **[dedupe](https://github.com/dedupeio/dedupe)**

  Open-source entity-resolution and record-linkage library useful for connecting potentially identical customer or merchant identities.



### AML, Transaction Monitoring & Case Management



* **[Jube](https://github.com/jube-home/aml-fraud-transaction-monitoring)**

  Particularly strong open-source option for combining fraud detection, AML transaction monitoring, risk scoring, rules, workflows, and case management.



* **[Mojaloop](https://github.com/mojaloop/mojaloop)**

  Open payment-interoperability ecosystem useful for payment transaction infrastructure and transaction-monitoring architectures.



* **[OpenSanctions](https://github.com/opensanctions/opensanctions)**

  Open-source/open-data ecosystem for sanctions, politically exposed persons, and other compliance datasets.



* **[OpenSanctions Dataset](https://www.opensanctions.org/)**

  Structured entity data useful as one component of AML/KYC and risk-screening workflows.



* **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**

  Search and analytics engine suitable for transaction investigation, case review, alert investigation, and risk operations.



* **[TheHive](https://github.com/TheHive-Project/TheHive)**

  Open-source security incident/case-management platform whose workflow concepts can be adapted to fraud-investigation case management.



* **[Cortex](https://github.com/TheHive-Project/Cortex)**

  Observable-analysis and automation engine useful for enriching suspicious entities and investigations.



* **[MISP](https://github.com/MISP/MISP)**

  Open-source threat-information sharing platform useful for sharing indicators and intelligence that may complement fraud-risk investigations.



### Streaming & Real-Time Infrastructure



* **[Apache Kafka](https://github.com/apache/kafka)**

  Distributed event-streaming backbone for transactions, authentication events, device events, chargebacks, login events, and fraud signals.



* **[Apache Flink](https://github.com/apache/flink)**

  Stream-processing engine suitable for real-time velocity checks, aggregations, anomaly detection, feature computation, and risk-event processing.



* **[Apache Spark](https://github.com/apache/spark)**

  Large-scale data-processing framework useful for offline fraud-model training and historical transaction analysis.



* **[Apache Pulsar](https://github.com/apache/pulsar)**

  Distributed event-streaming platform suitable for high-volume risk-event pipelines.



* **[NATS](https://github.com/nats-io/nats-server)**

  Lightweight messaging system useful for low-latency fraud-event distribution.



* **[RabbitMQ](https://github.com/rabbitmq/rabbitmq-server)**

  Message broker useful for asynchronous fraud workflows, case creation, notifications, and enrichment.



* **[Temporal](https://github.com/temporalio/temporal)**

  Durable workflow engine useful for manual-review workflows, fraud investigations, delayed decisions, chargeback workflows, and long-running risk processes.



### Search, Analytics & Risk Operations



* **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**

  Search and analytics engine useful for transaction investigation, risk events, alert search, and fraud operations.



* **[ClickHouse](https://github.com/ClickHouse/ClickHouse)**

  High-performance analytical database suitable for large transaction histories, risk analytics, merchant profiling, and fraud reporting.



* **[PostgreSQL](https://github.com/postgres/postgres)**

  Strong transactional database foundation for merchants, customers, transactions, risk decisions, cases, rules, and audit records.



* **[DuckDB](https://github.com/duckdb/duckdb)**

  Lightweight analytical database useful for fraud-data exploration and model development.



* **[Grafana](https://github.com/grafana/grafana)**

  Dashboards for transaction-risk KPIs, fraud rates, review queues, model performance, and operational monitoring.



* **[Metabase](https://github.com/metabase/metabase)**

  Self-hosted BI platform useful for merchant-risk reporting and fraud analytics.



* **[Apache Superset](https://github.com/apache/superset)**

  Open-source BI platform for risk and fraud dashboards.



### AI/LLM Infrastructure



* **[Ollama](https://github.com/ollama/ollama)**

  Local LLM runtime useful for fraud-investigation assistants, case summarization, analyst explanations, and suspicious-activity analysis.



* **[vLLM](https://github.com/vllm-project/vllm)**

  High-performance LLM inference engine for self-hosted risk-analysis services.



* **[LlamaIndex](https://github.com/run-llama/llama_index)**

  RAG framework useful for querying transaction histories, investigation notes, policies, and risk documentation.



* **[LangChain](https://github.com/langchain-ai/langchain)**

  Framework for building risk-analysis workflows and investigation assistants.



* **[LangGraph](https://github.com/langchain-ai/langgraph)**

  Useful for stateful fraud-investigation agents and human-in-the-loop workflows.



* **[Haystack](https://github.com/deepset-ai/haystack)**

  Open-source RAG and search framework useful for investigation knowledge bases.



* **[LiteLLM](https://github.com/BerriAI/litellm)**

  Unified LLM interface useful for connecting risk applications to multiple local or hosted models.



## Additional Strong Open-Source Options



* **[Jube](https://github.com/jube-home/aml-fraud-transaction-monitoring)** for an open-source AML and fraud-monitoring platform.

* **[risk-triage](https://github.com/opensyndicate/risk-triage)** for transparent transaction-risk scoring and fraud triage.

* **[Financial Fraud Risk Engine](https://github.com/AmirhosseinHonardoust/Financial-Fraud-Risk-Engine)** for cost-sensitive fraud scoring and explainability.

* **[Fraud Detection System](https://github.com/OlawumiSalaam/fraud-detection-system)** for a FastAPI/LightGBM real-time decisioning reference implementation.

* **[FraudGuard](https://github.com/atifbashir-ju/FraudGuard)** for an end-to-end credit-card fraud detection example.

* **[Feast](https://github.com/feast-dev/feast)** for online/offline fraud features and real-time model serving.

* **[FingerprintJS](https://github.com/fingerprintjs/fingerprintjs)** for browser/device signals.

* **[Open Policy Agent](https://github.com/open-policy-agent/opa)** for configurable risk and policy rules.

* **[Apache Flink](https://github.com/apache/flink)** for real-time transaction feature computation.

* **[Kafka](https://github.com/apache/kafka)** for fraud-event streaming.

* **[Redis](https://github.com/redis/redis)** for velocity counters and online features.

* **[Neo4j](https://github.com/neo4j/neo4j)** for fraud-network and entity-relationship analysis.

* **[Splink](https://github.com/moj-analytical-services/splink)** for customer/entity resolution.

* **[PyTorch Geometric](https://github.com/pyg-team/pytorch_geometric)** for graph-based fraud models.

* **[PyOD](https://github.com/yzhao062/pyod)** for anomaly detection.

* **[River](https://github.com/online-ml/river)** for online/streaming machine learning.

* **[Evidently](https://github.com/evidentlyai/evidently)** for model and data-drift monitoring.

* **[MLflow](https://github.com/mlflow/mlflow)** for fraud-model lifecycle management.

* **[OpenSearch](https://github.com/opensearch-project/OpenSearch)** for fraud investigation and risk operations.

* **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** for large-scale fraud analytics.

* **[OpenSanctions](https://github.com/opensanctions/opensanctions)** for sanctions/PEP data integration.

* **[Ollama](https://github.com/ollama/ollama)** for private AI investigation assistants.



**Frameworks for building custom systems**: Combine **Jube + Feast + FingerprintJS + Open Policy Agent + Kafka + Flink + Redis + PostgreSQL + Neo4j + OpenSearch + MLflow** to construct a self-hosted merchant-risk platform with real-time scoring, rules, behavioral signals, graph analysis, case investigation, and machine-learning capabilities.



## Recommended Open-Source Merchant Risk Architecture



```text

┌──────────────────────────────────────────────────────────────────────┐

│                         CUSTOMER / USER                              │

│                                                                      │

│  Web │ Mobile │ Checkout │ Login │ Signup │ Marketplace │ API        │

└──────────────────────────────┬───────────────────────────────────────┘

                               │

                               ▼

┌──────────────────────────────────────────────────────────────────────┐

│                     SIGNAL COLLECTION LAYER                          │

│                                                                      │

│ Device │ Browser │ IP │ Geo │ Account │ Payment │ Behavior │ Session │

│                                                                      │

│ FingerprintJS │ OpenTelemetry │ Application Events                  │

└──────────────────────────────┬───────────────────────────────────────┘

                               │

                               ▼

┌──────────────────────────────────────────────────────────────────────┐

│                       EVENT STREAM                                   │

│                                                                      │

│ Kafka │ Flink │ Pulsar │ NATS │ Redis                                │

└──────────────────────────────┬───────────────────────────────────────┘

                               │

                ┌──────────────┼────────────────┐

                ▼              ▼                ▼

        ┌──────────────┐ ┌─────────────┐ ┌──────────────┐

        │ Online       │ │ Historical  │ │ Entity /     │

        │ Features     │ │ Data        │ │ Graph        │

        │ Feast/Redis  │ │ PostgreSQL  │ │ Neo4j        │

        └──────┬───────┘ └──────┬──────┘ └──────┬───────┘

               │                │                │

               └────────────────┼────────────────┘

                                ▼

                    ┌────────────────────────┐

                    │     RISK ENGINE        │

                    │                        │

                    │ Rules + ML + Graph     │

                    │ Velocity + Anomaly     │

                    │ Device + Behavioral    │

                    └────────────┬───────────┘

                                 │

                                 ▼

                    ┌────────────────────────┐

                    │ DECISION ENGINE        │

                    │                        │

                    │ APPROVE                │

                    │ REVIEW                 │

                    │ CHALLENGE              │

                    │ DECLINE                │

                    └────────────┬───────────┘

                                 │

                 ┌───────────────┼────────────────┐

                 ▼               ▼                ▼

          ┌────────────┐  ┌─────────────┐  ┌──────────────┐

          │ Payment    │  │ Manual      │  │ Case         │

          │ Gateway    │  │ Review      │  │ Management   │

          └────────────┘  └─────────────┘  └──────────────┘

                                 │

                                 ▼

                       ┌───────────────────┐

                       │ Feedback Loop     │

                       │                   │

                       │ Chargebacks       │

                       │ Fraud Labels      │

                       │ Analyst Decisions │

                       └─────────┬─────────┘

                                 │

                                 ▼

                       ┌───────────────────┐

                       │ Model Training    │

                       │ MLflow + Python   │

                       └───────────────────┘

```



## Commercial → Open-Source Mapping



| Commercial Platform                | Open-Source Building-Block Strategy                                   |

| ---------------------------------- | --------------------------------------------------------------------- |

| **Riskified**                      | Jube + Feast + FingerprintJS + Flink + ML models + case management    |

| **Signifyd**                       | Risk engine + transaction features + rules + ML + chargeback feedback |

| **Sardine**                        | FingerprintJS + Feast + Jube + Flink + behavioral analytics           |

| **Sift**                           | Kafka + Feast + ML + graph analytics + OpenSearch + decision engine   |

| **Forter**                         | Device/identity signals + graph engine + ML + real-time decisioning   |

| **SEON**                           | FingerprintJS + IP/device/email/phone signals + rules + ML            |

| **Unit21**                         | Jube + OPA + PostgreSQL + workflow/case management                    |

| **Fraud.net**                      | Kafka + Flink + Feast + MLflow + ML models + risk API                 |

| **Feedzai**                        | Kafka + Flink + Feast + ML + OPA + graph analytics                    |

| **Kount**                          | FingerprintJS + graph analysis + ML + rules + transaction decisioning |

| **Ekata-style identity risk**      | Entity resolution + graph analytics + identity signals + ML           |

| **BioCatch-style behavioral risk** | Event collection + sequence models + anomaly detection                |

| **Arkose-style abuse prevention**  | Behavioral signals + rate limiting + challenge workflows + ML         |

| **Custom Merchant Risk Platform**  | Jube + Feast + Kafka + Flink + Redis + Neo4j + OpenSearch             |



> These mappings are **architectural equivalents, not drop-in replacements**. Commercial risk platforms often possess proprietary global data networks, device graphs, consortium intelligence, merchant feedback, chargeback data, proprietary models, and operational infrastructure that cannot be recreated simply by installing open-source components.



## Open-Source Merchant Risk Capability Matrix



| Capability               | Jube | Risk-Triage | Feast | FingerprintJS | OPA | Flink | Neo4j | OpenSearch |

| ------------------------ | ---: | ----------: | ----: | ------------: | --: | ----: | ----: | ---------: |

| Transaction Risk Scoring |    ✅ |           ✅ |    ⚠️ |             ❌ |  ⚠️ |    ⚠️ |    ⚠️ |          ❌ |

| Fraud Rules              |    ✅ |           ✅ |     ❌ |             ❌ |   ✅ |    ⚠️ |     ❌ |         ⚠️ |

| Machine Learning         |    ✅ |          ⚠️ |    ⚠️ |             ❌ |   ❌ |    ⚠️ |    ⚠️ |          ❌ |

| Real-Time Features       |    ✅ |          ⚠️ |     ✅ |            ⚠️ |  ⚠️ |     ✅ |    ⚠️ |         ⚠️ |

| Velocity Checks          |    ✅ |           ✅ |    ⚠️ |             ❌ |  ⚠️ |     ✅ |     ❌ |         ⚠️ |

| Device Signals           |   ⚠️ |          ⚠️ |    ⚠️ |             ✅ |   ❌ |    ⚠️ |    ⚠️ |          ❌ |

| Behavioral Analytics     |   ⚠️ |          ⚠️ |    ⚠️ |            ⚠️ |   ❌ |     ✅ |    ⚠️ |         ⚠️ |

| Graph Fraud Detection    |   ⚠️ |           ❌ |     ❌ |             ❌ |   ❌ |    ⚠️ |     ✅ |         ⚠️ |

| Case Management          |    ✅ |           ❌ |     ❌ |             ❌ |   ❌ |     ❌ |     ❌ |         ⚠️ |

| AML Monitoring           |    ✅ |           ❌ |     ❌ |             ❌ |   ❌ |    ⚠️ |    ⚠️ |         ⚠️ |

| Sanctions Screening      |    ✅ |           ❌ |     ❌ |             ❌ |  ⚠️ |    ⚠️ |     ❌ |         ⚠️ |

| Explainability           |    ✅ |           ✅ |     ❌ |             ❌ |  ⚠️ |    ⚠️ |    ⚠️ |         ⚠️ |

| Audit Trail              |    ✅ |          ⚠️ |    ⚠️ |             ❌ |  ⚠️ |     ✅ |    ⚠️ |          ✅ |

| Self-Hosted              |    ✅ |           ✅ |     ✅ |             ✅ |   ✅ |     ✅ |     ✅ |          ✅ |



> `⚠️` indicates that the capability requires customization, another component, or external data.



## Best Open-Source Combinations



### Open Transaction Fraud Engine



```text

Jube

 +

PostgreSQL

 +

Redis

 +

Kafka

 +

Flink

```



Useful for:



* Transaction monitoring

* Velocity rules

* Risk scoring

* Fraud alerts

* Real-time decisioning

* Audit trails



### Modern ML-Based Merchant Risk Platform



```text

Kafka

   ↓

Flink

   ↓

Feast

   ↓

ML Model

   ↓

Risk Engine

   ↓

OPA

   ↓

APPROVE / REVIEW / CHALLENGE / DECLINE

```



Useful for:



* High-volume payments

* Real-time scoring

* Online feature retrieval

* ML-driven risk decisions

* Configurable policies



### Device + Behavioral Risk



```text

Browser / Mobile

       ↓

FingerprintJS

       ↓

Behavioral Events

       ↓

Kafka

       ↓

Redis / Feast

       ↓

Risk Model

       ↓

Decision Engine

```



Potential signals include:



* Device identity

* New device

* Device reuse

* Browser characteristics

* Session velocity

* Login velocity

* IP/geo mismatch

* Behavioral anomalies

* Account age

* Transaction history



### Graph-Based Fraud Detection



```text

Customer

   │

   ├── Email

   ├── Phone

   ├── Device

   ├── IP

   ├── Card

   ├── Address

   ├── Merchant

   └── Transaction

          │

          ▼

       Neo4j

          │

          ▼

  Connected Entity Analysis

          │

          ▼

     Fraud Ring Score

```



Useful for identifying:



* Shared devices

* Shared IP addresses

* Synthetic identities

* Account clusters

* Card-sharing patterns

* Address reuse

* Merchant/customer networks

* Fraud rings



### Merchant Risk Operations



```text

Transaction

     ↓

Risk Score

     ↓

┌─────────────────────────────┐

│                             │

│ APPROVE                     │

│                             │

│ CHALLENGE                   │

│                             │

│ MANUAL REVIEW               │

│                             │

│ DECLINE                     │

│                             │

└──────────────┬──────────────┘

               ↓

          Case Queue

               ↓

        Analyst Review

               ↓

      Decision + Reason

               ↓

         Feedback Label

               ↓

        Model Retraining

```



## Key Open-Source Components by Function



| Function                          | Recommended Projects        |

| --------------------------------- | --------------------------- |

| Complete fraud/AML engine         | Jube                        |

| Transaction-risk scoring          | risk-triage                 |

| Fraud ML reference implementation | Financial Fraud Risk Engine |

| Real-time fraud API               | Fraud Detection System      |

| Feature store                     | Feast                       |

| Device fingerprinting             | FingerprintJS               |

| Rules engine                      | OPA / Drools                |

| Streaming                         | Kafka / Flink               |

| Online features                   | Redis / Feast               |

| Graph fraud                       | Neo4j / PyTorch Geometric   |

| Entity resolution                 | Splink / dedupe             |

| Anomaly detection                 | PyOD                        |

| Online ML                         | River                       |

| Model monitoring                  | Evidently                   |

| Model lifecycle                   | MLflow                      |

| Explainability                    | SHAP                        |

| AML / transaction monitoring      | Jube                        |

| Sanctions data                    | OpenSanctions               |

| Search/investigation              | OpenSearch                  |

| Analytics                         | ClickHouse                  |

| Dashboards                        | Grafana / Metabase          |

| Workflow                          | Temporal                    |

| Local AI                          | Ollama                      |

| Risk-policy engine                | OPA                         |

| Identity/access                   | Keycloak / Authentik        |



## Real-Time Merchant Risk Flow



```text

                         TRANSACTION

                              │

                              ▼

                    ┌─────────────────┐

                    │ Signal Capture  │

                    └────────┬────────┘

                             │

         ┌───────────────────┼────────────────────┐

         ▼                   ▼                    ▼

      Device              Customer             Payment

      Signals             History              Signals

         │                   │                    │

         └───────────────────┼────────────────────┘

                             ▼

                          Kafka

                             │

                             ▼

                          Flink

                             │

              ┌──────────────┼──────────────┐

              ▼              ▼              ▼

            Redis          Feast          Neo4j

              │              │              │

              └──────────────┼──────────────┘

                             ▼

                    ┌─────────────────┐

                    │ Risk Model      │

                    │ ML / Rules      │

                    │ Graph Score     │

                    └────────┬────────┘

                             │

                             ▼

                    ┌─────────────────┐

                    │ Decision Engine │

                    └────────┬────────┘

                             │

             ┌───────────────┼────────────────┐

             ▼               ▼                ▼

          APPROVE          REVIEW           DECLINE

             │               │                │

             │               ▼                │

             │        Analyst / Case          │

             │        Management              │

             │               │                │

             └───────────────┼────────────────┘

                             ▼

                       Outcome Data

                             │

                             ▼

                     Model Feedback

```



## Fraud Model Development Pipeline



```text

Historical Transactions

          ↓

Fraud / Chargeback Labels

          ↓

Data Cleaning

          ↓

Feature Engineering

          ↓

Point-in-Time Correct Features

          ↓

Train / Validation / Test

          ↓

Model Training

          ↓

Calibration

          ↓

Threshold Optimization

          ↓

Explainability

          ↓

Shadow Deployment

          ↓

A/B / Champion-Challenger

          ↓

Production

          ↓

Drift Monitoring

          ↓

Retraining

```



## Risk Signals



A self-hosted merchant-risk engine can combine:



### Transaction



* Amount

* Currency

* Merchant category

* Payment method

* Transaction frequency

* Historical spending

* Refund history

* Chargeback history



### Customer



* Account age

* Login history

* Purchase history

* Failed-payment history

* Previous disputes

* Email reputation

* Phone reputation



### Device



* Device ID

* Browser fingerprint

* Device age

* Device reuse

* Emulator indicators

* Root/jailbreak indicators

* Session characteristics



### Network



* IP address

* ASN

* Proxy indicators

* VPN indicators

* Geographic consistency

* IP velocity



### Behavioral



* Mouse/touch behavior

* Typing patterns

* Navigation patterns

* Session duration

* Checkout velocity

* Bot-like activity



### Relationship



* Shared device

* Shared IP

* Shared email

* Shared phone

* Shared payment instrument

* Shared shipping address

* Shared merchant relationships



## What Open Source Can Replace



Open-source software can provide much of the **technical infrastructure** surrounding merchant-risk systems, including:



* Transaction-risk scoring

* Fraud rules

* Velocity checks

* Anomaly detection

* Machine-learning models

* Feature stores

* Real-time feature retrieval

* Device/browser signals

* Behavioral-event collection

* Graph analysis

* Entity resolution

* Risk APIs

* Decision engines

* Case-management workflows

* Investigation search

* Model monitoring

* Explainability

* Risk dashboards

* Transaction streaming

* Fraud-model training

* AML transaction monitoring

* Sanctions-data integration

* Audit logging



## What Open Source Cannot Automatically Replace



Open-source software alone does **not** automatically provide:



* Global merchant fraud consortium data

* Global card/device reputation networks

* Proprietary device graphs

* Proprietary identity graphs

* Billions of historical transaction labels

* Proprietary chargeback datasets

* Network-wide fraud intelligence

* Card-network risk intelligence

* Commercial IP reputation databases

* Commercial email/phone reputation databases

* Guaranteed fraud-loss protection

* Chargeback guarantees

* Global fraud-decisioning infrastructure

* Vendor-operated manual review teams

* Proprietary behavioral-biometric networks

* Enterprise fraud SLAs



This is a major difference between open-source systems and platforms such as Riskified, Signifyd, Sift, Forter, or Feedzai.



A practical architecture therefore looks like:



```text

Open-Source Risk Engine

        +

Merchant's Own Transaction Data

        +

Merchant Fraud / Chargeback Feedback

        +

Optional External Intelligence

        +

ML Models

        +

Rules

        +

Graph Analytics

        +

Human Review

```



## Recommended Technology Stack



### Core Risk Engine



```text

Jube

/

Custom Python Risk Engine

```



### Feature Store



```text

Feast

+

Redis

```



### Streaming



```text

Kafka

+

Flink

```



### Device Intelligence



```text

FingerprintJS

+

Application Behavioral Events

```



### Machine Learning



```text

LightGBM

+

XGBoost

+

CatBoost

+

PyTorch

```



### Graph Intelligence



```text

Neo4j

+

PyTorch Geometric

+

NetworkX

```



### Decision Policies



```text

Open Policy Agent

/

Drools

```



### Model Management



```text

MLflow

+

Evidently

+

SHAP

```



### Investigation



```text

OpenSearch

+

PostgreSQL

+

Grafana

```



### AI Assistant



```text

Ollama

+

LlamaIndex

+

LangGraph

```



## Example Self-Hosted Merchant Risk Stack



```text

┌──────────────────────────────────────────────────────────────┐

│                    MERCHANT / CHECKOUT                       │

└───────────────────────────┬──────────────────────────────────┘

                            │

                            ▼

┌──────────────────────────────────────────────────────────────┐

│                   SIGNAL COLLECTION                          │

│                                                              │

│ FingerprintJS │ Behavioral Events │ Payment │ Account        │

└───────────────────────────┬──────────────────────────────────┘

                            │

                            ▼

┌──────────────────────────────────────────────────────────────┐

│                 KAFKA / FLINK                                 │

└───────────────────────────┬──────────────────────────────────┘

                            │

              ┌─────────────┼─────────────┐

              ▼             ▼             ▼

           Redis          Feast         Neo4j

              │             │             │

              └─────────────┼─────────────┘

                            ▼

                 ┌───────────────────┐

                 │    Jube / ML      │

                 │                   │

                 │ Rules             │

                 │ ML                │

                 │ Velocity          │

                 │ Graph             │

                 │ Anomaly           │

                 └─────────┬─────────┘

                           │

                           ▼

                 ┌───────────────────┐

                 │       OPA         │

                 │ Decision Policies │

                 └─────────┬─────────┘

                           │

                 ┌─────────┼─────────┐

                 ▼         ▼         ▼

              APPROVE    REVIEW    DECLINE

                           │

                           ▼

                    Case Management

                           │

                           ▼

                    Feedback Labels

                           │

                           ▼

                 MLflow / Retraining

```



## Open-Source Security & Governance



A production merchant-risk platform should provide:



```text

Encryption

+

TLS

+

RBAC

+

SSO

+

MFA

+

Secrets Management

+

Immutable Audit Logs

+

Model Versioning

+

Decision Versioning

+

Rule Versioning

+

Data Retention

+

PII Controls

+

Access Logging

+

Human Review

```



Potential components include:



* **[Keycloak](https://github.com/keycloak/keycloak)** — identity and SSO.

* **[Authentik](https://github.com/goauthentik/authentik)** — identity management.

* **[Open Policy Agent](https://github.com/open-policy-agent/opa)** — policy enforcement.

* **[OpenBao](https://github.com/openbao/openbao)** — secrets management.

* **[PostgreSQL](https://github.com/postgres/postgres)** — transactional risk data.

* **[OpenSearch](https://github.com/opensearch-project/OpenSearch)** — investigation and audit search.

* **[OpenTelemetry](https://github.com/open-telemetry/opentelemetry-collector)** — telemetry and observability.



## Open-Source Maturity



| Category                          | Maturity |

| --------------------------------- | -------: |

| Fraud ML libraries                |    ⭐⭐⭐⭐⭐ |

| Rules engines                     |    ⭐⭐⭐⭐⭐ |

| Streaming infrastructure          |    ⭐⭐⭐⭐⭐ |

| Feature stores                    |     ⭐⭐⭐⭐ |

| Anomaly detection                 |    ⭐⭐⭐⭐⭐ |

| Device fingerprinting             |     ⭐⭐⭐⭐ |

| Graph databases                   |    ⭐⭐⭐⭐⭐ |

| Entity resolution                 |     ⭐⭐⭐⭐ |

| Fraud research projects           |     ⭐⭐⭐⭐ |

| Real-time fraud engines           |      ⭐⭐⭐ |

| AML transaction monitoring        |      ⭐⭐⭐ |

| Fraud case management             |      ⭐⭐⭐ |

| Merchant-risk platforms           |       ⭐⭐ |

| Open-source Riskified replacement |       ⭐⭐ |

| Open-source Sift replacement      |       ⭐⭐ |

| Open-source Forter replacement    |       ⭐⭐ |

| Open-source Feedzai replacement   |       ⭐⭐ |



## Best Open-Source Shortlist



### Best Complete Open-Source Fraud/AML Platform



**[Jube](https://github.com/jube-home/aml-fraud-transaction-monitoring)**



Strong candidate when the requirement includes transaction monitoring, fraud detection, ML risk scoring, rules, workflows, and case management in one open-source project.



### Best Lightweight Risk-Scoring Engine



**[risk-triage](https://github.com/opensyndicate/risk-triage)**



Useful for transparent, testable transaction-risk scoring and reason codes.



### Best Feature Store



**[Feast](https://github.com/feast-dev/feast)**



Useful for building low-latency online fraud features and point-in-time-correct training datasets.



### Best Device Signal Building Block



**[FingerprintJS](https://github.com/fingerprintjs/fingerprintjs)**



Useful for collecting browser/device signals that can become inputs to a broader risk engine.



### Best Rules/Policy Engine



**[Open Policy Agent](https://github.com/open-policy-agent/opa)**



Useful for transparent, version-controlled risk policies.



### Best Graph Foundation



**[Neo4j](https://github.com/neo4j/neo4j)**



Useful for connecting customers, devices, IPs, cards, addresses, merchants, and transactions.



### Best Real-Time Processing



**[Apache Flink](https://github.com/apache/flink)**



Useful for real-time velocity calculations, aggregations, behavioral features, and streaming fraud detection.



### Best Fraud Model Stack



```text

LightGBM

+

XGBoost

+

CatBoost

+

PyTorch

+

SHAP

+

MLflow

+

Evidently

```



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: project name, official/repository link, 1–2 sentence description, and whether it is SaaS, hosted, open-source, fraud engine, ML library, feature store, rules engine, graph platform, or infrastructure.

4. For open-source projects, include the actual GitHub repository whenever available.

5. Do not describe a generic ML library as a complete merchant-risk platform.

6. Clearly distinguish **production systems**, **research projects**, **reference implementations**, and **building blocks**.

7. Mention important licensing, data, model, privacy, and maturity limitations where relevant.

8. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



* This is a **community-curated** list — not exhaustive and not an endorsement.

* Commercial fraud platforms may possess proprietary transaction networks, device graphs, behavioral datasets, chargeback histories, consortium intelligence, and models that are unavailable in open-source software.

* Most open-source projects listed here are **fraud engines, ML libraries, feature stores, rules engines, graph databases, device-signal libraries, transaction-monitoring systems, or infrastructure components**, rather than complete replacements for Riskified, Signifyd, Sift, Forter, Feedzai, or Kount.

* Fraud models can generate both false positives and false negatives. A risk score should not be treated as proof of fraud.

* Automated decisions involving customers can have significant consequences and should be monitored for accuracy, unintended bias, data-quality problems, and inappropriate denial or escalation.

* Payment fraud systems should comply with applicable privacy, consumer-protection, financial-services, payment-network, data-protection, and security requirements.

* Personal and financial data should be minimized, protected, retained only as necessary, and processed according to applicable law.

* Open-source availability does not automatically mean that a project, model, dataset, or dependency is suitable for commercial production use.

* Always verify current project status, license, model license, dependencies, data sources, security posture, and operational maturity before deployment.



---



**Made for merchants, marketplaces, fintechs, PSPs, payment teams, fraud analysts, risk engineers, AML teams, data scientists, and open-source developers.**

Let's make merchant risk management more **transparent, explainable, self-hosted, programmable, data-driven, and interoperable**.
