# Insurance-Data-Pipeline-ETL-Visualization

## 📌 Project Overview
This project focuses on building an **ETL pipeline** to process and analyze insurance premium data. The workflow involves **Extracting, Transforming, and Loading (ETL)** data from a structured dataset, performing **data validation**, and generating insightful visualizations to explore trends in claims, premiums, and discounts.

## 🚀 Features
- **ETL Pipeline**: Extract, clean, and transform insurance data for analysis.
- **Data Validation**: Ensure data integrity and handle missing values.
- **Data Analysis & Visualization**: Identify trends in claims severity, premium adjustments, and discount distributions.

## 🛠 Technologies Used
- **Python** (Pandas, NumPy) - Data processing & transformation.
- **Matplotlib & Seaborn** - Data visualization.
- **SQLite** - Optional database storage.
- **Jupyter Notebook/Google Colab** - Running and testing the ETL pipeline.

## 📂 Project Structure
```
Insurance_ETL_Visualization/
│-- data/
│   ├── insurance_data.csv  # Raw dataset
│-- notebooks/
│   ├── insurance_etl.ipynb  # Jupyter Notebook for ETL and visualization
│-- src/
│   ├── etl.py  # ETL script
│   ├── visualization.py  # Data visualization script
│-- README.md
```

## 📥 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Insurance_ETL_Visualization.git
   cd Insurance_ETL_Visualization
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 📊 How to Run
1. Place the dataset (`insurance_data.csv`) inside the `data/` folder.
2. Run the ETL script:
   ```bash
   python src/etl.py
   ```
3. Run the visualization script:
   ```bash
   python src/visualization.py
   ```
4. Alternatively, open `insurance_etl.ipynb` in Jupyter Notebook or Google Colab to run step-by-step.

## 📈 Key Insights
- **Claims Severity Distribution**: Understanding the frequency of different severity levels.
- **Total Claims by Region**: Identifying high-claim areas.
- **Premium Adjustment Trends**: Observing how insurance premiums vary by policy type.

## 🔍 Future Improvements
- Integrate **Apache Airflow** for automated ETL workflows.
- Store processed data in a **SQL database** for efficient querying.
- Implement **interactive dashboards** using **Plotly or Power BI**.

## 📩 Contact
For any questions or collaboration opportunities, feel free to reach out:
📧 Email: truong.nt239260@sis.hust.edu.vn  
🔗 LinkedIn: [www.linkedin.com/in/ngotruong](https://www.linkedin.com/in/ngotruong)  
🐙 GitHub: [https://github.com/PatrickDoCS](https://github.com/PatrickDoCS)  

---
💡 **"Turning raw data into meaningful insights."**

