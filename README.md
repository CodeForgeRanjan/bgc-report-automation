# 📊 BGV Report Automation Engine 🚀

This project automates high-volume Background Verification (BGV) workflows. It completely replaces slow, manual Excel work and heavy VBA Macros with a fast, secure local Python pipeline (**Jupyter Notebook**) and an interactive **Streamlit Cloud Web Application**.

---

## ⚡ How This Tool Evolved

* **The Old Way (Excel & VBA Macros):** Before this project, checking data, sorting files, and extracting info was done manually inside Excel using VBA Macros. This required a lot of copy-paste work and wasted a lot of time.
* **The Smart Local Way (Jupyter Notebook):** I moved the entire workflow to Python. Inside **`Report_Automation.ipynb`**, I wrote scripts using Regular Expressions (Regex) to clean messy data and automatically match city details with a Pincode master sheet.
* **The Ultimate Cloud Way (Streamlit App):** Finally, I upgraded this local engine into a full-scale **Multi-Utility Streamlit Cloud App** with a beautiful dashboard interface, making it incredibly easy for anyone to upload raw files and get cleaned results instantly.

---

## ⚙️ How to Run This Project Locally

The main automation script is saved in **`Report_Automation.ipynb`**. If you want to run this pipeline on your local computer, follow these simple steps:

👉 **Live Multi-Utility Automation Tool:** [r-ranjan-robtos.streamlit.app](https://r-ranjan-robtos.streamlit.app/)


1. **Open your Terminal / Command Prompt (cmd) and launch the Jupyter Server:**
   ```bash
   python -m jupyter notebook
