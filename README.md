# Weekly Report Automation Agent

This project demonstrates an **automated weekly report generation system**.  
It replaces manual data analysis by reading Excel files, extracting KPIs, generating charts, and outputting structured business summaries.  
The system has already been deployed internally as an **Agent workflow**, enabling analysts to interact with it through natural language dialogue.

---

## Features
- Upload Excel product analysis data
- Automatically generate KPI trends and structured weekly reports
- Visualize key business metrics (e.g., call volume trends, customer rankings)
- Export structured Excel reports and chart images
- Integrated with an Agent workflow for interactive analysis

---

## Repository Structure
- `notebooks/`: Main Jupyter Notebook (`weekly_report_demo.ipynb`)
- `sample_data/`: Example input data (`.xlsx`)
- `output_examples/`: Example generated weekly reports (e.g., Week16.xlsx)
- `requirements.txt`: Dependencies
- `LICENSE`: Open-source license (MIT)

---

## Usage
1. Clone this repo:
   ```bash
   git clone https://github.com/JaniJiang/weekly-report-agent.git
   cd weekly-report-agent
