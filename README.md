Campaign Marketing Automation Workflow (CMAW)

Automated case analysis, metrics extraction, and multi-source data analysis for e-commerce marketing using n8n, Google Sheets, and SQL-like transformation logic.

🚀 Overview

CMAW (Campaign Marketing Automation Workflow) is an end-to-end automation system designed for e-commerce and digital marketing analysts.

It performs two major tasks:

1️⃣ Case → Analytical Questions & Metrics (Automated Requirement Extraction)

A user submits a free-text marketing case (e.g., campaign brief, client scenario, e-commerce analysis request).
The workflow will automatically:

✔️ Identify key analytical questions
✔️ Identify corresponding measurable metrics
✔️ Generate a structured JSON output
✔️ Produce a formatted, human-readable analysis summary
✔️ Send the result to your Gmail inbox

All powered by n8n + OpenAI Agent.

2️⃣ Multi-Sheet Data Loading & Analysis

The workflow reads two Google Sheets datasets:

Sheet Name	Content	Used For
site_data	date, sessions, orders, sales, category	Sales Volume & Web Traffic analysis
keyword_data	keyword, search volume, date	Keyword Search Volume & demand trend

An optional second AI Agent can then generate SQL-like analysis code based on the extracted metrics, such as:

Seasonality trends

Demand fluctuations

Search volume patterns

Traffic → conversion movement

Category-level performance
