# Governance

These repositories belong to the **Data & AI** organisation. Ownership and access are managed as code in the `swapfiets-terraform` repository, not in the GitHub UI.

## Teams

- **Data & AI Platform** — shared infrastructure and cross-platform engineering.
  - **Data Platform** — ELT, pipelines, Snowflake.
  - **AI Platform** — agents, LLMs.
- **Data Products** — dbt reporting, BI, analytics.
- **Data Science** — ML models.

Each repository is owned by one of these teams (see its CODEOWNERS). Team membership, repository access, and settings are defined in Terraform; changes go through a pull request there.

## Decisions

Cross-cutting standards (repository hygiene, branch protection, templates, shared workflows) are proposed and reviewed by the Data & AI Platform team. Team-specific conventions live in each team's own documentation.
