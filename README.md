# Data Engineering Portfolio

A curated collection of end-to-end data engineering projects demonstrating practical experience designing and building data pipelines, real-time streaming solutions, cloud data platforms, analytics solutions, and CI/CD workflows using Azure, Microsoft Fabric, and Databricks.

---

## 🚀 Projects

### 🔹 Microsoft Fabric Sales Data Engineering & Power BI Analytics

**Tech:** Microsoft Fabric | PySpark | Lakehouse | Delta Lake | Medallion Architecture | Dimensional Modelling | Direct Lake | Power BI | DAX | Data Pipelines

🔗 https://github.com/stevening1/fabric-data-engineering-power-bi-analytics

Built an end-to-end sales analytics solution in Microsoft Fabric using a medallion architecture to transform raw sales data into analysis-ready datasets. Developed Bronze-to-Silver and Silver-to-Gold Spark notebook pipelines, implementing data cleansing, enrichment, and incremental upserts to maintain dimensional and fact tables in a star schema.

Created a Direct Lake semantic model and interactive Power BI report featuring executive sales performance, product performance, and customer insights. Developed DAX measures for revenue, year-over-year growth, year-to-date performance, customer and product contribution, and product rankings.

Automated the end-to-end workflow using a Fabric pipeline with file-arrival triggers, sequential notebook execution, semantic model refresh, failure handling, and email notifications. Implemented a separate conditional Lakehouse maintenance pipeline to assess file-size and file-count thresholds and run Delta table optimization and V-Order when required.

---

### 🔹 Azure Databricks Hospital Readmission Project

**Tech:** Azure Databricks | PySpark | Delta Lake | Unity Catalog | Lakeflow Jobs | AI/BI Dashboards | GitHub Actions | Databricks Asset Bundles

🔗 https://github.com/stevening1/azure-databricks-hospital-readmission-project

Developed an automated healthcare analytics pipeline using Azure Databricks to ingest and transform hospital data, identify trends and potential drivers of readmissions, and deliver analytical insights through AI/BI Dashboards. Implemented a medallion architecture with Unity Catalog and automated deployment workflows using GitHub Actions and Databricks Asset Bundles.

---

### 🔹 Azure & Microsoft Fabric Real-Time Weather Streaming Project

**Tech:** Python | PySpark | Databricks | Azure Functions | Azure Event Hubs | Microsoft Fabric Eventstream | Fabric Eventhouse | KQL | Power BI | Fabric Activator | Azure Key Vault

🔗 https://github.com/stevening1/azure_fabric_weather_streaming_project

Built an end-to-end real-time weather streaming solution that ingests live Johannesburg weather data from WeatherAPI.com and streams it through Azure Event Hubs into Microsoft Fabric Eventstream and Eventhouse for real-time analytics.

Developed ingestion solutions using both Databricks and Azure Functions and performed a cost comparison using Azure Cost Management. The solution also includes a Power BI weather dashboard and event-driven severe weather alerts using KQL and Fabric Activator.

Implemented security using Azure Key Vault, managed identities, RBAC, and least-privilege access principles.

---

### 🔹 Retail Data Engineering Project

**Tech:** Azure Data Factory | ADLS Gen2 | Databricks | Delta Lake | SQL Server | Synapse Analytics | Power BI

🔗 https://github.com/stevening1/retail-data-engineering-project

Designed a modern retail analytics pipeline that ingests data from an on-premises SQL Server database, transforms the data into analysis-ready datasets, and delivers insights into sales, customer, and product performance through Power BI.

---

### 🔹 Microsoft Fabric London Bike Real-Time Monitoring

**Tech:** Microsoft Fabric Eventstream | Fabric Eventhouse | KQL | Real-Time Dashboard | Fabric Activator | Microsoft Teams

🔗 https://github.com/stevening1/fabric-london-bike-realtime-monitoring

Developed a real-time bike availability monitoring solution using live London bicycle station data. Ingested JSON events through Fabric Eventstream into an Eventhouse KQL database and built an interactive real-time dashboard to analyse bike availability and empty docking spaces across neighbourhoods.

Implemented parameterised KQL queries, neighbourhood filtering, and automatic dashboard refresh. Configured Fabric Activator to trigger Microsoft Teams notifications when a neighbourhood has no bikes available, demonstrating event-driven alerting and operational monitoring.

---

### 🔹 COVID-19 Data Engineering Pipeline

**Tech:** Azure Data Factory | ADLS Gen2 | Databricks | Azure SQL | Power BI

🔗 https://github.com/stevening1/covid19-azure-data-factory-databricks-project

Built an end-to-end data engineering pipeline to ingest, transform, and visualize COVID-19 data across European countries, creating analysis-ready datasets to support analytics and machine learning use cases.

---

## 🛠️ Core Skills

### Data Engineering & Processing

* Azure Data Factory and Lakeflow Jobs — pipeline orchestration
* Databricks and PySpark — distributed data processing
* Python — data ingestion and application development
* KQL — querying and analysing real-time data
* Fabric Eventstream — low-code event ingestion and processing
* Spark notebooks and Fabric Data Pipelines — data transformation and orchestration
* Incremental data processing and Delta Lake MERGE operations

### Cloud Data Platforms

* Microsoft Fabric Lakehouse — cloud-based data engineering and analytics
* Azure Data Lake Storage Gen2 — cloud data lake architecture
* Delta Lake — reliable analytical data storage
* Azure Event Hubs — real-time event ingestion
* Microsoft Fabric Eventstream — streaming data pipelines
* Microsoft Fabric Eventhouse — real-time analytical data storage
* Azure SQL and SQL Server — relational data platforms
* Azure Synapse Analytics — analytical data warehousing
* Unity Catalog — data governance and access management

### Analytics & Visualisation

* Power BI — interactive dashboards and reporting
* DAX — analytical measures, time intelligence, rankings, and contribution analysis
* Direct Lake — Power BI semantic models over OneLake data
* Dimensional modelling — star schemas, fact tables, and dimension tables
* Databricks AI/BI Dashboards — analytical visualisation
* Microsoft Fabric Real-Time Dashboards — live data visualisation and monitoring
* Fabric Activator — event-driven alerts and automation
* Microsoft Teams integration — automated operational notifications

### DevOps, Security & Optimisation

* Git and GitHub — source control
* GitHub Actions — CI/CD automation
* Azure DevOps — development and deployment workflows
* Databricks Asset Bundles — Databricks deployment automation
* Azure Key Vault — secrets and credential management
* Managed Identities and RBAC — cloud identity and access management
* Delta table optimization and V-Order — Lakehouse maintenance
* Pipeline failure handling and automated notifications

---

## 🎯 Areas of Experience

* Batch and real-time data engineering
* Cloud-based data pipeline architecture
* ETL and ELT development
* Distributed data processing with Spark and PySpark
* Medallion architecture and Delta Lake
* Incremental data processing and upsert patterns
* Data lake and data warehouse solutions
* Dimensional modelling and analytical datasets
* Semantic modelling, DAX, and business intelligence
* Real-time streaming and event-driven architectures
* KQL-based analytics and time-sensitive event monitoring
* Event-driven alerting and automated notifications
* Cloud cost analysis and optimisation
* CI/CD and deployment automation
* Cloud security and least-privilege access
* Data platform maintenance and operational reliability
