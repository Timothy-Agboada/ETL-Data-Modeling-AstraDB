# ETL-Data-Modeling-AstraDB
ETL pipeline with Apache Cassandra (AstraDB) for data ingestion, transformation, and analytics.


# ETL Pipeline with Apache Cassandra (AstraDB)

## 📌 Project Overview
This project demonstrates a **large-scale ETL pipeline** using Apache Cassandra (AstraDB) for **data ingestion, transformation, and analytics**. The dataset consists of user activity logs from a web application.

## 🚀 Features
✅ **Extract** data from AstraDB Collections API
✅ **Transform** data by removing duplicates & aggregating user activity
✅ **Load** processed data into AstraDB for fast querying
✅ **Automated scheduling** using Google Colab
✅ **Data visualization** with Matplotlib

## 📂 Project Structure
📦 ETL-Data-Modeling-AstraDB
┣ 📂 data
┃ ┣ 📜 user_activity.csv
┣ 📜 etl_pipeline.py
┣ 📜 requirements.txt
┣ 📜 README.md


## 🛠️ Technologies Used
- **Apache Cassandra (AstraDB)**
- **Python (Pandas, NumPy, Matplotlib)**
- **Google Colab**
- **GitHub**

## 🎯 How to Run
1️⃣ Clone the repo:
   git clone https://github.com/your-username/ETL-Data-Modeling-AstraDB.git
   cd ETL-Data-Modeling-AstraDB

2️⃣ Install dependencies:
    pip install -r requirements.txt

3️⃣ Run the ETL script:
    python etl_pipeline.py
