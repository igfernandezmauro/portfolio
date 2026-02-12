---
layout: default
title: Ignacio Fernandez Mauro's Portfolio
---

# Ignacio Fernandez Mauro
## Data Engineer | Analytics Engineer | Data & Systems Builder

I design and build data systems end-to-end, from ingestion and modeling to analytics and decision-making layers.

My background spans software development, data engineering, and analytics. I focus on building reliable data pipelines, well-modeled storage systems, and practical analytics that drive real-world feedback loops.

My projects range from exploratory data analytics to fully serverless AWS data platforms with event-driven modeling and API layers.

## Tools & Technologies
### Data Engineering
- AWS Lambda
- Amazon DynamoDB
- Amazon S3
- API Gateway
- EventBridge Scheduler
- Python
- Event-driven architecture
- Change detection via hashing
- Incremental state modeling

### Data Analytics
- SQL
- Python (Pandas, NumPy)
- Tableau
- Excel
- Exploratory data analysis
- Statistical reasoning

### Software Development
- REST APIs
- HTML / JavaScript
- Git
- Object-oriented programming
- Data modeling

---

## Data Engineering Projects

### 1. Magic: the Gathering Commander Tracker (AWS Serverless Data Platform)
**Tools:** AWS Lambda · API Gateway · DynamoDB · S3 · JavaScript · React (UI) · Serverless REST APIs

**Summary:**
Built an autonomous system that syncs deck data from _Archidekt_, stores snapshots and diffs over time, tracks user-logged play events, and serves analytics via REST APIs. The UI allows game logging on mobile, time-zone converted timestamps, and a smart deck picker that balances freshness and randomness.

**Key contributions:**
- Event log design and DynamoDB modeling
- Serverless cloud architecture (Lambda + S3 + DynamoDB)
- API design with stage deployments and CORS
- Frontend UI for asynchronous data updates
- UX considerations for mobile data input

**[View project →](projects/data-engineering/mtg-commander-tracker.html)**

---

## Data Analytics Projects

### 1. Content Performance Analysis with Databricks
**Tools:** Databricks · Spark · Python · Statsmodels · Matplotlib

**Summary:**  
Exploratory and statistical analysis of content performance data using Databricks, focused on understanding which variables are associated with higher view counts. The project combines data preparation, exploratory data analysis, and multiple linear regression (OLS) to evaluate relationships between exposure and engagement metrics.

**Key contributions:**
- Cleaned and prepared structured performance data in Databricks
- Conducted exploratory data analysis to understand distributions and correlations
- Built and interpreted an OLS regression model using Statsmodels
- Evaluated model fit and statistical significance of explanatory variables
- Interpreted results and limitations from an analytical perspective

**[View project →](projects/data-analytics/cross-platform-engagement.html)**

---

### 2. Spotify Track Popularity Analysis
**Tools:** SQL · Excel · Tableau

**Summary:**  
End-to-end data analysis project completed as the final assignment for a professional data analytics certification. The project analyzes Spotify track data to explore how audio characteristics relate to track popularity, using SQL for data extraction, Excel for data preparation, and Tableau for visualization.

**Key contributions:**
- Queried and filtered Spotify track data using SQL
- Cleaned and organized datasets in Excel
- Performed exploratory and descriptive analysis of audio features
- Built Tableau dashboards to visualize popularity patterns and comparisons
- Communicated findings through clear, business-friendly visualizations

**[View project →](projects/data-analytics/spotify-popularity-features.html)**

---

## Analytical Approach

Projects in this portfolio follow a consistent analytics workflow:

1. **Understand the dataset and question** - clarify scope, assumptions, and limits  
2. **Prepare the data** - clean, validate, and structure for analysis  
3. **Explore relationships** - apply descriptive analysis or statistical models  
4. **Communicate insights** - present findings clearly using visuals and narrative  

---

## Current Focus
- Designing event-driven data architectures in AWS
- Modeling state vs immutable event tables in DynamoDB
- Building feedback loops between systems and analytics
- Expanding into scalable aggregation patterns
