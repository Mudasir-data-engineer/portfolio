# Mudasir Shafiq - Data Engineering Portfolio

Portfolio of production-oriented data engineering, analytics, cloud, AI automation, and platform projects by **Mudasir Shafiq**, a Paris-based Lead Data Engineer.

**Live portfolio:** [mudasir-data-engineer.github.io/portfolio](https://mudasir-data-engineer.github.io/portfolio/)

## Portfolio overview

The website brings together:

- 12 end-to-end data engineering and platform case studies
- 5 AI agent and workflow automation case studies
- 11 analytics, dashboard, and reporting examples
- English and French Lead Data Engineer CVs
- Skills, professional profile, certifications, and contact links

Each project is supported by a downloadable PDF case study describing the business problem, architecture, implementation, technology choices, controls, and outcome.

## Featured projects

| Project | Focus | Selected technologies |
| --- | --- | --- |
| Growlytic Marketing Intelligence | Multi-tenant AI marketing intelligence, live advertising metrics, grounded reporting, integrations, and billing | PostgreSQL, Meta and Google APIs, Claude, Gemini, Vercel |
| GrowMore Reporting Platform | Tenant-isolated commerce analytics and automated reporting | Python, dlt, dbt, PostgreSQL, FastAPI, Next.js |
| Collabs+ Community SaaS | Modular community platform with auditable roles, bookings, messaging, and credits | FastAPI, PostgreSQL, SQLAlchemy, Alembic, RBAC |
| Zisonix Commerce Platform | Bilingual commerce experience with database-enforced pricing and secure administration | Next.js, Supabase, PostgreSQL, RLS |
| Zisonix Marketplace Data Pipeline | Cross-marketplace ingestion, entity resolution, deduplication, and image curation | Python, Amazon, eBay, Cdiscount, data-quality rules |
| Karbonomics Impact Engine | Traceable product carbon-footprint proof of concept with deterministic calculations | Python, SQLite, ETL, lineage, automated testing |
| Livestock Intelligence | Streaming time-series pipeline and predictive livestock analytics | Kafka, Airflow, BigQuery, scikit-learn |
| Synthetic Data Engine | Configurable, validated synthetic datasets with idempotent publishing | Python, validation rules, Google Sheets |

The portfolio also includes digital agency analytics, advertising performance, delivery-route optimization, sports catalogue scraping, AI support and lead-qualification agents, and Power BI, GA4, BigQuery, and marketing reports.

## Technical coverage

- **Data engineering:** Python, SQL, Airflow, Kafka, Spark, dbt, ETL/ELT, streaming, Data Vault 2.0
- **Data platforms:** PostgreSQL, BigQuery, Snowflake, Redshift, Databricks, Redis, pgvector
- **Cloud and infrastructure:** AWS, GCP, Azure, S3, Lambda, Step Functions, Terraform, Docker, Kubernetes, Vercel, Cloudflare R2
- **Applications and APIs:** FastAPI, REST, Pydantic, JWT, RBAC, Next.js, TypeScript, Node.js
- **Analytics and AI:** Power BI, Tableau, Grafana, GA4, scikit-learn, OpenAI, Claude, Gemini
- **Quality and governance:** validation, lineage, audit history, versioned reference data, unit normalization, tenant isolation, CI/CD, and production monitoring

## Repository structure

```text
portfolio/
|-- index.html                     # Single-page portfolio website
|-- case-studies/                  # Project case studies and analytical reports
|-- resume/
|   |-- Data Engr_CV_Eng.pdf       # English Lead Data Engineer CV
|   `-- Data Engr_CV_Fr.pdf        # French Lead Data Engineer CV
|-- assets/                        # Static site assets
|-- .github/workflows/
|   `-- deploy-pages.yml           # GitHub Pages deployment workflow
`-- README.md
```

## Run locally

This is a static website with no build step. Clone the repository and serve its root directory with any local HTTP server. For example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

Changes pushed to the `main` branch are deployed to GitHub Pages through the workflow in `.github/workflows/deploy-pages.yml`.

## Contact

- [LinkedIn](https://www.linkedin.com/in/mudasir-data-engineer/)
- [GitHub](https://github.com/Mudasir-data-engineer)
- [Portfolio](https://mudasir-data-engineer.github.io/portfolio/)
- Email: [chmudasir.fr@gmail.com](mailto:chmudasir.fr@gmail.com)
