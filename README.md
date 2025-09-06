# 📦 Data Analysis using AI Tools | Supply Chain Domain  

This project is inspired by **Codebasics** and demonstrates how modern AI tools can be integrated into a **supply chain workflow** to automate data collection, storage, and analysis.  

The goal is to **streamline data pipelines** (emails → cloud database → AI analysis) and uncover valuable insights without writing complex code.  

---

## 🔍 Problem Statement  
In the **supply chain domain**, organizations handle massive volumes of scattered data:  
- Customer orders via emails  
- Invoices and billing information  
- Shipment and delivery records  

The main challenges are:  
1. Collecting this data from multiple sources.  
2. Storing it securely in one place.  
3. Analyzing it quickly to improve decision-making.  

---

## ⚙️ Workflow Overview  

![Workflow] <!-- Replace with actual path of your image -->  

1. **Data Collection (Gmail → CSV)**  
   - Supply chain data (orders, emails, etc.) is fetched directly from Gmail.  

2. **Automation with n8n**  
   - **n8n** acts as the automation engine, sending incoming data from Gmail to the pipeline automatically.  
   - Eliminates repetitive manual tasks.  

3. **Cloud Storage (Postgres + Supabase)**  
   - Data is stored in **Postgres**.  
   - **Supabase** provides cloud-hosted infrastructure, ensuring scalability and secure access.  

4. **AI-Powered Analysis with Quadratic**  
   - **Quadratic** (AI spreadsheet tool) is used to query and analyze the supply chain data.  
   - Insights are generated using natural language prompts—no SQL or formulas required!  

---

## 🛠️ Tech Stack  
- **n8n** → Workflow automation  
- **Postgres** → Relational database  
- **Supabase** → Cloud database hosting  
- **Quadratic** → AI-powered data analysis  

---

## ✨ Key Learnings  
- How to integrate **AI tools** into traditional supply chain analytics.  
- Benefits of **automating repetitive workflows** using n8n.  
- Why cloud solutions like **Supabase** make scaling easier.  
- How AI spreadsheets (Quadratic) can simplify complex analysis.  

---

## 🙌 Acknowledgement  
This project is part of a learning journey with **[Codebasics](https://codebasics.io/)**.  

---

## 🔗 Additional Links  

- 📄 **LinkedIn Post** → [[Click here](https://www.linkedin.com/posts/ujjalmondal_dataanalytics-ai-supplychain-activity-7370066499123916800-zhZV?utm_source=share&utm_medium=member_desktop&rcm=ACoAADdvak8B0Zwmdf3JbEXWL7tzIaAem94O4pQ)]  
- 🎥 **YouTube Video Presentation** → [[click here](https://www.youtube.com/watch?v=335_8gUfu8U)]  
- 📧 **Contact Email** → [ujjalmondal.business@gmail.com]  

---

## 📌 Next Steps  
- Enhance data cleaning steps before loading into Supabase.  
- Explore advanced Quadratic use cases (trend analysis, forecasting).  
- Extend the workflow to include real-time dashboards. # Data-Analysis-using-AI-Tools-Quadratic-N8N-Supply-Chain


Thank You!
