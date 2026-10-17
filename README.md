# BigQuery Enterprise AI Agent with Gemini Enterprise

A hands-on implementation of a **BigQuery Data Agent** built inside Google Cloud's **Gemini Enterprise** platform. This agent connects directly to enterprise BigQuery datasets to perform schema inspection, natural language data exploration, and automated SQL metrics analysis.

---

## 📌 Features & Implementation
* **BigQuery Agent Integration**: Deployed a dedicated data agent integrated into Gemini Enterprise to inspect structured data assets seamlessly.
* **Schema Inspection**: Natural language querying of table structures (e.g., retrieving column types, modes, and descriptions for `installation_requests` inside `pool_data`).
* **Automated Data Analytics**: Translates plain-English business analytics prompts into executable BigQuery queries for rapid data synthesis and aggregated calculations.
* **Grounded Insights**: Delivers structured schema tables and precise field definitions straight from BigQuery metadata.

---

## 🛠️ Google Cloud Tools & Architecture
* **Google Cloud Platform (GCP)**
* **Gemini Enterprise** (Agent Workspace)
* **BigQuery Data Agent**
* **Google BigQuery** (`pool_data` dataset)

---

## 📊 Demonstrated Query & Output

### 1. Schema Discovery Query
**Prompt:** `What is the schema of the installation_requests table?`

**Agent Response:**
| Column Name | Data Type | Mode | Description |
| :--- | :--- | :--- | :--- |
| `width_m` | FLOAT | NULLABLE | Width of the pool in meters |
| `length_m` | FLOAT | NULLABLE | Length of the pool in meters |
| `max_depth_m` | FLOAT | NULLABLE | Maximum depth of the pool in meters |
| `include_hot_tub` | BOOLEAN | NULLABLE | Whether a hot tub is included in the request |
| `include_waterfall` | BOOLEAN | NULLABLE | Whether a waterfall feature is included in the request |
| `install_zip` | INTEGER | NULLABLE | ZIP code where the pool will be installed |
| `customer_phone` | STRING | NULLABLE | Contact phone number of the customer |

---


<img width="1461" height="837" alt="Screenshot 2026-10-17 at 10 16 03 PM" src="https://github.com/user-attachments/assets/3d7e1760-7fda-42c1-bd56-518e02ddd883" />

<img width="1452" height="794" alt="Screenshot 2026-10-17 at 10 16 13 PM" src="https://github.com/user-attachments/assets/c14f8d8e-3090-45c0-9b4c-41c86b2b1950" />


