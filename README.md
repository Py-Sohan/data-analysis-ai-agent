# 🤖 Data Analysis AI Agent – NVIDIA Nemotron + Streamlit

This project is an interactive AI-powered data analysis assistant built with **Streamlit** and **NVIDIA's Nemotron Ultra 253B** model. It allows users to upload a CSV file and chat directly with their data using natural language. The agent intelligently understands queries, generates appropriate **pandas** or **matplotlib** code, executes it, and returns either a plot or a table — along with smart reasoning.
![image](https://github.com/user-attachments/assets/65d9bca1-e395-40e0-8e43-1ff376d28cfd)


---

## 🎯 Features

✅ Upload your **CSV file**  
✅ Ask natural-language questions about the data  
✅ Smartly detects whether the query needs a **plot** or **table**  
✅ Generates **clean Python code** using pandas and matplotlib  
✅ Displays insightful explanations with reasoning trails  
✅ Powered by **NVIDIA Nemotron Ultra 253B**  
✅ Live plotting and error-handling  
✅ Clean, streaming chat experience with expandable sections

---

## 🧠 How It Works

### 📌 Query Understanding
- Uses an LLM-based classifier to determine if the query requires a visualization.
  
### 🛠 Code Generation
- If the query involves **visuals**, it generates `pandas + matplotlib` code.
- Otherwise, it uses **pandas** only for data queries.
- All code is executed safely and returns results as:
  - 📈 Plot (with live `pyplot`)
  - 📋 DataFrame / Series
  - ⚠️ Error message (if something goes wrong)

### 🧩 Reasoning Engine
- After generating the output, the LLM explains the results using a prompt curated based on the type of output (plot, table, or error).
- Streams internal LLM "thinking" inside a collapsible `<details>` block for transparency.

---

## 🎥 Watch Live Video

👉 [**Watch Dashboard Walkthrough**]([https://drive.google.com/file/d/1TgxPBLaSIYxg4jRXc153UJjvIojMB57e/view?usp=drive_link](https://drive.google.com/file/d/1Qh-KNOhIL2kSk6kc--zsJq4xcIWqhNPg/view?usp=drive_link)
![image](https://github.com/user-attachments/assets/90718893-2ec0-4e20-af40-7c54b3905b58)

