<h1 align="center">Hi, I'm Aniket Gurubaxani 👋</h1>
<h3 align="center">Data Engineer · Databricks · PySpark · SQL · Python · AWS</h3>

<p align="center">
  <a href="mailto:aniketgurubaxani@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/aniketgurubaxani/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://credentials.databricks.com/d9a02cf6-6106-46f7-88b4-bf304b06eaf6"><img src="https://img.shields.io/badge/Databricks%20Certified-Data%20Engineer%20Associate-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks Certified Data Engineer Associate"/></a>
</p>

---

### 🧑‍💻 About me

- 🛠️ Data Engineer with **2 years of experience** building and supporting ETL pipelines for **pharmaceutical commercial and compliance data**.
- ☁️ Hands-on with **Databricks, PySpark, SQL, Python and AWS** (S3, EC2, RDS/Aurora PostgreSQL, Redshift): incremental loads, legacy-to-cloud migrations, data remediation and production support.
- 🧬 Domain knowledge in field force alignment, multichannel marketing (MCM), HCP/HCO, transparency / healthcare spend, event data (Cvent) and MDM.
- 📈 Previously an analyst on e-commerce customer and product data, using cohort analysis, search optimization and Power BI dashboards.
- 🤝 Open to collaborating on data engineering and analytics projects.

---

### 🛠️ Tech Stack

**Languages**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

**Big Data & Platforms**

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square&logo=delta&logoColor=white)
![Hive](https://img.shields.io/badge/Hive-FDEE21?style=flat-square&logo=apachehive&logoColor=black)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)

**Cloud & Databases**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Visualization & Tools**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### 🚀 Projects

#### 🔄 Field Force Alignment Migration: Legacy PostgreSQL → Databricks
`Databricks` `PySpark` `Python` `AWS S3` `EC2` `Redshift` `Aurora PostgreSQL`

- Built a two-stage pipeline that replaced a legacy direct-Postgres extract for **17 tables (~12M rows)**: a parallel **PySpark export** to versioned S3 folders, then a **Python loader on EC2** into RDS/Redshift. The existing scheduler and downstream jobs did not need to change.
- Built **watermark-based incremental loading** with seed, delta and full-snapshot modes plus a lookback for late-arriving data. Each export writes its manifest last, so partial exports are never loaded and failed runs recover on their own.
- Made the pipeline **config-driven**: new tables are added by editing a control file, ad-hoc re-exports run from a request file, and Redshift column widths are tracked automatically.
- Compared legacy and new data for **19 entities**, column by column, and built **15 old-to-new ID mapping tables** to fix IDs across the base, integration and reporting layers.

#### 🧪 Pharma Commercial & Compliance Data Operations
`SQL` `Python` `AWS S3` `ETL`

- Ran data operations across **200+ tables and ~20 vendor feeds** (MCM, Transparency, HCP/HCO, Events/Cvent), with tables ranging from **1K to 10M+ records**.
- Designed an **end-to-end pipeline from raw ingestion to reporting**: vendor files land in S3, then go through transformation and validation before downstream extracts are delivered.
- Built SQL/Python **validation and reconciliation** across data layers and resolved **100+ data quality and production issues** through root-cause analysis.
- Delivered a major **Cvent business-grain change** across all data layers and checked its effect on event and attendee reporting.

#### 🛒 E-commerce Customer & Product Analytics
`SQL` `Python` `Hive` `Spark` `BigQuery` `Power BI`

- Used **cohort and behavioral analysis** to improve customer retention by **16%** and product performance by **12%**.
- Used keyword analysis to optimize search, raising **CTR by 20%** and **organic traffic by 25%**.
- Built **Power BI dashboards** and ran **Python sentiment analysis** on customer feedback to give product and marketing teams insights they could act on.

---

### 📈 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=AniketGurubaxani&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AniketGurubaxani&layout=compact&hide_border=true" alt="Top languages"/>
</p>

---

<p align="center"><i>"Without data, you're just another person with an opinion." — W. Edwards Deming</i></p>
