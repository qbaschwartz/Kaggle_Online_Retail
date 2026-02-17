# DECISIONS

## Decision 1 — Dataset
- Choice: Kaggle "Online Retail"
- Why:
  - Contains a timestamp (InvoiceDate) and a user identifier (CustomerID) → monthly retention is feasible
  - Realistic transactional data that is easy to explain to stakeholders
  - Quick to start with (lower complexity for the first portfolio iteration)

## Decision 2 — SQL Environment
- Choice: DuckDB locally (start), later Postgres (Docker) + dbt
- Why:
  - DuckDB runs instantly → no environment setup blocker
  - Great for fast SQL practice and exporting clean tables to Power BI
  - Clear upgrade path that signals AE skills (tests/docs/lineage later)
