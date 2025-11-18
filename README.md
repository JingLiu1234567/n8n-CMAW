# Campaign Marketing Automation Workflow (CMAW)

Automated case analysis, metrics extraction, multi-sheet data processing, SQL-driven insights, and visual analytics for e-commerce marketing — powered by n8n, Google Sheets, and OpenAI.

## 🚀 Overview
CMAW (Campaign Marketing Automation Workflow) is an end-to-end automation system designed for e-commerce and digital marketing analysts.

The workflow performs **three major tasks**:

---

## 1️⃣ Case → Analytical Questions & Metrics (Automated Requirement Extraction)

A user submits a free-text marketing case (e.g., campaign brief, client scenario, e-commerce analysis request).

The workflow automatically:
- ✔️ Identifies key analytical questions  
- ✔️ Maps them to measurable metrics  
- ✔️ Generates a structured JSON output  
- ✔️ Produces a formatted, human-readable summary  
- ✔️ Sends the result to your Gmail inbox  

This step is powered by **n8n + OpenAI Agent**.

---

## 2️⃣ Multi-Sheet Data Loading & SQL-Based Analysis

The workflow reads two Google Sheets datasets:

| Sheet Name     | Content                                   | Used For |
|----------------|-------------------------------------------|----------|
| site_data      | date, sessions, orders, sales, category   | Sales Volume & Web Traffic |
| keyword_data   | keyword, search volume, date              | Keyword Search Volume |

Using these datasets, a second AI Agent (or SQL node) can automatically:
- Generate SQL-like queries  
- Aggregate metrics (monthly/seasonal)  
- Join datasets on date  
- Produce analytical tables for further visualization  

---

## 3️⃣ Visual Analytics (Charts & Trend Lines)

Based on the SQL output, the workflow can generate:
- 📈 Seasonal sales trends  
- 📉 Demand fluctuations  
- 🔎 Keyword search trends  
- 📊 Traffic → conversion movement  
- 🏷️ Category-level performance charts  

These charts can be displayed inside n8n, exported, or sent via email.

---
