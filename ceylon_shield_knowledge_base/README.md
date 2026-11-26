# Ceylon Shield Insurance PLC — Knowledge Base

© 2026 Noob Dev (Pvt) Ltd. For students of the Certified AI & Agentic Engineering Professional 3.0 program only. Do not share or upload to public repositories.

Ceylon Shield Insurance PLC is a **fictional company** created for this project.

## Folder Structure

| Folder | Contents |
|---|---|
| 00_company | Company overview, branches, contact channels |
| 01_motor | Motor policy terms and premium rates |
| 02_health | Health policy terms (2025 and 2026 editions) and premium rates |
| 03_life | Life plans and premium rates |
| 04_home | Home policy terms |
| 05_travel | Travel policy terms and premium rates |
| 06_claims | Claims procedures, document checklist, settlement timelines |
| 07_customer_service | FAQ, complaints, cancellations, payments |
| 08_internal | Internal staff-only documents |

## Document Metadata

Every document starts with a YAML front-matter block:

| Field | Meaning |
|---|---|
| doc_id | Unique document ID |
| title | Document title |
| product | motor, health, life, home, travel or general |
| doc_type | policy_terms, premium_table, claims_procedure, faq, etc. |
| version | Document version |
| effective_date | Date the document became valid |
| status | `active` or `superseded` |
| audience | `public` or `internal` |
