# Optimization of Fleet Allocation using Decision Support System (DSS)

## 📌 Project Overview
This project aims to optimize transport fleet allocation based on **zone costs** and **fleet availability status**. The system is developed to assist in real-time decision-making for logistics distribution, ensuring efficient resource management and cost reduction.

> **Note:** This project is currently **On-Progress**. The current repository focuses on the data testing module and the core system allocation logic.

## 🚀 Key Features (Current Progress)
* **Data Preprocessing:** Cleaning and transformation of operational data spanning a 2-month period.
* **Cost Analysis:** Calculation of inter-zone cost references (`zone_cost_ref`) to establish baseline distribution expenses.
* **Allocation Algorithm:** Implementation of the `run_dss_demo_direct` function to match available fleets (Ready/On-Trip status) with distribution demands.
* **Top-K Recommendation:** The system provides prioritized fleet recommendations based on the lowest cost-weight criteria.

## 🛠️ Tech Stack
* **Language:** Python
* **Key Libraries:** * `Pandas` & `NumPy`: Data manipulation and numerical processing.
    * `XGBoost`: Implemented for future demand forecasting.
    * `Matplotlib` / `Seaborn`: Data visualization.
* **Environment:** Jupyter Notebook / Google Colab.

## 📊 Logic Flow
The system operates through the following workflow:
1. **Input Reference:** Integration of zone-based cost reference data.
2. **Status Check:** Real-time verification of fleet availability (categorizing units as *Ready* or *On-Trip*).
3. **DSS Logic Calculation:** Evaluating candidates based on predefined optimization criteria.
4. **Optimization Output:** Generating a prioritized list of the most optimal fleet units for assignment.

## 📂 Repository Structure
* `Testing Forecasting and Assigment Problem 2 Months.ipynb`: Main research notebook containing data testing and DSS logic.
* `requirements.txt`: List of Python dependencies required to run the project.
