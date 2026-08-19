# Data Scientist Resume Skill

> Resume for data science, machine learning, and AI engineering roles.

## When to Use

- Applying to Data Scientist, ML Engineer, AI Engineer positions
- Research scientist roles at tech companies
- Analytics and business intelligence positions
- When the posting mentions Python, ML, statistics, or data pipelines

## Framework

### Data Scientist Resume Structure

1. **Header** — Name, email, LinkedIn, GitHub, Google Scholar (if publications)
2. **Summary** (optional) — Specialization + years + key impact
3. **Technical Skills** — Languages, ML frameworks, tools, domains
4. **Experience** — Reverse chronological with model/metric-focused bullets
5. **Education** — Degree, research focus, thesis (if relevant)
6. **Publications** — If applicable (ML/NLP/CV conferences)
7. **Projects** — Kaggle, open-source, personal projects

### Skills Section Format

```
TECHNICAL SKILLS
Languages:       Python, R, SQL, Scala
ML/DL:           PyTorch, TensorFlow, scikit-learn, XGBoost, Hugging Face
Data:            Pandas, NumPy, Spark, Dask, Polars
MLOps:           MLflow, Kubeflow, Airflow, Weights & Biases
Cloud:           AWS SageMaker, GCP Vertex AI, Azure ML
Visualization:   Matplotlib, Plotly, Tableau, Looker
Statistics:      Bayesian inference, A/B testing, causal inference, time series
Domains:         NLP, Computer Vision, Recommender Systems, Forecasting
```

### How to Present Model Results

```
FORMAT:
[Action] + [Model/Technique] + [Dataset/Scale] + [Performance Metric] + [Business Impact]

EXAMPLES:
• Developed XGBoost model on 50M+ user dataset, achieving 0.92 AUC
  and reducing churn by 18% ($3.2M annual revenue saved)

• Built transformer-based NLP pipeline processing 100K documents/day,
  achieving 94.5% F1-score and reducing manual review time by 70%

• Implemented collaborative filtering recommendation engine serving
  2M daily users, improving click-through rate by 23% and average
  order value by $12
```

## Templates

### Data Scientist Template

```
[FULL NAME]
[Email] | [Phone] | [LinkedIn] | [GitHub] | [Google Scholar]

SUMMARY
Data scientist with [X] years applying machine learning to [domain].
Proven track record of deploying models that drive [business metric].
Expertise in [specialization 1] and [specialization 2].

TECHNICAL SKILLS
Languages:       Python, R, SQL, [Other]
ML/DL:           [Frameworks and libraries]
Data Eng:        [ETL tools, databases, big data frameworks]
MLOps:           [Experiment tracking, deployment, monitoring]
Cloud:           [Cloud platforms and services]

EXPERIENCE

[Company] — Data Scientist                          [MM/YYYY] – Present

Model Development:
• Developed [model type] for [use case], achieving [metric] on [dataset
  size]. Model deployed to production serving [X] predictions/day.
• Built end-to-end ML pipeline: [data source] → [feature engineering]
  → [model training] → [deployment], reducing model iteration time
  from [X] weeks to [Y] days.
• Designed and analyzed [X] A/B tests, establishing statistical
  framework adopted by [team/org] for experiment-driven decisions.

Business Impact:
• [Model/analysis] led to [specific business decision], resulting in
  [quantified business outcome — revenue, cost, efficiency].
• Automated [manual process] using [ML approach], saving [X]
  analyst-hours per month.
• Created [dashboard/model] used by [X] stakeholders for [purpose],
  improving decision-making speed by [X]%.

[Previous Company] — Junior Data Scientist          [MM/YYYY] – [MM/YYYY]
• [Achievement with model metrics]
• [Achievement with business impact]

EDUCATION
[Master's/PhD] in [Statistics/CS/Math/related] — [University] — [Year]
  Thesis: "[Title]" — Advisor: [Name]
  Focus: [ML specialization area]

[Bachelor's] in [Field] — [University] — [Year]

PUBLICATIONS (if applicable)
[1] [Last name, Initials]. (Year). [Title]. [Conference/Journal].

PROJECTS & COMPETITIONS
• [Kaggle Competition]: [Medal/Percentile] — [Brief approach description]
• [Open Source Project]: [Description] — [Stars/contributors]
• [Personal Project]: [Description] — [Link]
```

### ML Engineer Template

```
[FULL NAME]
[Email] | [GitHub] | [LinkedIn]

SUMMARY
ML engineer with [X] years building production machine learning systems.
Specialized in [NLP/CV/RecSys/Forecasting] with experience deploying
models at [X]M+ request/day scale. Strong software engineering fundamentals.

TECHNICAL SKILLS
Languages:       Python, Go, Java, SQL, Rust
ML Frameworks:   PyTorch, TensorFlow, ONNX, TensorRT
MLOps:           MLflow, Kubeflow, SageMaker, BentoML, Triton
Infra:           Kubernetes, Docker, Terraform, gRPC, Redis
Data:            Spark, Kafka, Flink, Airflow, dbt
Monitoring:      Prometheus, Grafana, Evidently, Great Expectations

EXPERIENCE

[Company] — ML Engineer                             [MM/YYYY] – Present

Production ML Systems:
• Designed and deployed [model type] serving [X]M predictions/day with
  p99 latency of [X]ms and 99.9% availability.
• Built feature store serving [X] features to [Y] models, reducing
  feature engineering duplication across [X] teams.
• Implemented A/B testing framework for ML models, enabling safe
  rollouts and reducing production incidents by [X]%.

MLOps & Infrastructure:
• Created automated model training pipeline with [tools], reducing
  model refresh cycle from monthly to daily.
• Designed model monitoring system detecting [X]% of model degradation
  within [Y] hours, enabling proactive model retraining.
• Optimized model inference reducing cost by [X]% through [technique —
  quantization, distillation, batching, caching].

[Previous Company] — Data Scientist                 [MM/YYYY] – [MM/YYYY]
• [Achievement focused on production deployment]
• [Achievement focused on system design]

EDUCATION
[Degree] in [CS/EE/Stats] — [University] — [Year]

PUBLICATIONS & PATENTS (if applicable)
[1] [Citation]
```

## Examples

### Before & After: Model Description

**Before (too vague):**
```
- Built machine learning model for customer churn
- Used Python and scikit-learn
- Improved accuracy
```

**After (data science standard):**
```
• Developed gradient-boosted ensemble model (XGBoost + LightGBM) to
  predict customer churn on 3.2M subscriber dataset with 147 engineered
  features. Achieved 0.91 AUC-ROC (vs. 0.72 baseline) with 87% precision
  at 70% recall threshold.

• Deployed model via REST API (FastAPI + Docker) on AWS ECS, serving
  real-time predictions with 45ms p95 latency. Model flags at-risk
  customers 30 days before churn, enabling proactive retention campaigns
  that reduced churn rate from 8.2% to 5.1% ($4.1M annual revenue impact).
```

### Before & After: Data Pipeline

**Before:**
```
- Created data pipeline for analysis
```

**After:**
```
• Built Apache Spark pipeline processing 2TB of daily clickstream data
  from Kafka topics, transforming raw events into 200+ ML features stored
  in Delta Lake. Pipeline runs on 20-node EMR cluster with 99.7% success
  rate and 45-minute SLA, replacing manual SQL queries that took 6+ hours.
```

### Dataset Description Proven Patterns

```
✓ GOOD: "3.2M user records, 147 features spanning 18 months of behavioral,
         transactional, and demographic data with 4.3% positive class rate"

✗ BAD:  "Large dataset with many features"

✓ GOOD: "150K labeled images (1024×1024) across 200 categories,
         80/10/10 train/val/test split, collected from [source]"

✗ BAD:  "Image classification dataset"
```

## Common Mistakes

1. **Listing "Python, Machine Learning" as skills** — Be specific about libraries and techniques
2. **No model performance metrics** — Always include AUC, F1, precision/recall, or RMSE
3. **Missing business impact** — "Improved model accuracy" means nothing without context
4. **Confusing data science with data analysis** — Show you can build and deploy models
5. **No mention of data scale** — How many records? How much data? What latency?
6. **Forgetting data engineering** — ETL, feature engineering, and data quality matter
7. **Listing Kaggle without results** — Include your percentile or medal
8. **Overclaiming AI expertise** — "Expert in deep learning" when you ran one tutorial

---

## 中文版本

### 适用场景

- 申请数据科学家、机器学习工程师、AI工程师岗位
- 科技公司的研究科学家职位
- 数据分析和商业智能岗位

### 中文数据科学简历要点

- **量化指标**：AUC、F1、准确率、召回率必须写清楚
- **业务影响**：技术指标要转化为业务价值（收入、成本、效率）
- **数据规模**：必须说明数据量级（行数、特征数、数据量）
- **部署经验**：国内很看重模型上线能力，不仅仅是实验

### 国内大厂数据科学面试重点

- 特征工程能力
- 模型优化和调参经验
- 线上AB测试经验
- 大规模数据处理经验
- 业务理解和指标设计
