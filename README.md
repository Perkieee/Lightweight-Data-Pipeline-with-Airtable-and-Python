# Lightweight Data Pipeline with Airtable and Python  

##  Overview  
This project demonstrates how to connect **Airtable** with a **Python environment** to build a simple ETL-like pipeline.  

The pipeline performs the following steps:  
1. **Extract**: Fetch customer records from Airtable.  
2. **Transform**: Use Python and Pandas to engineer a new feature (`Is High Value`) that flags high-value customers based on income and spending score.  
3. **Load**: Write the transformed data back into Airtable, updating a checkbox field (`High Value`).  

This project shows how to integrate cloud-based tools like Airtable with Python for lightweight, automated data workflows.  

---

## ⚙️ Tech Stack  
- **Python 3.9+**  
- **Airtable** (Free Tier)  
- **Libraries**:  
  - [pyairtable](https://github.com/gtalarico/pyairtable)  
  - [pandas](https://pandas.pydata.org/)  
  - [python-dotenv](https://pypi.org/project/python-dotenv/)  

---

## Getting Started  

### 1. Clone the repository  
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
